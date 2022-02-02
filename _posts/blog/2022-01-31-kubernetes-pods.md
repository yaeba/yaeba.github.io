---
title: "Kubernetes: Pods"
excerpt: "Collection of containers that can run on a host"
toc: true
tags: kubernetes
header:
  overlay_image: /assets/images/kubernetes.png
  overlay_filter: 0.5
  caption: "Photo credit: [**WallpaperAccess**](https://wallpaperaccess.com/kubernetes)"
---

## Useful links

- [https://kubernetes.io/docs/concepts/workloads/pods/](https://kubernetes.io/docs/concepts/workloads/pods/){:target="\_blank"}
- [https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/](https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/){:target="\_blank"}
- [https://kubernetes.io/docs/concepts/workloads/pods/init-containers/](https://kubernetes.io/docs/concepts/workloads/pods/init-containers/){:target="\_blank"}
- [https://kubernetes.io/docs/reference/kubernetes-api/workload-resources/pod-v1/](https://kubernetes.io/docs/reference/kubernetes-api/workload-resources/pod-v1/){:target="\_blank"}

## Concepts

- Pod is the smallest deployable units of computing we create and deploy in Kubernetes
- A pod can contain one or more containers
- In terms of Docker concepts, a Pod is similar to a group of Docker containers with shared namespaces and shared filesystem volumes
- Normally we use other workload resources (controllers) to create and manage pods for us. Some examples are `ReplicaSet`, `Deployment`, `StatefulSet` and `DaemonSet`
- Some of the useful stuffs to specify in a pod are security context, volumes, environment variables and resources (request & limit) per container
- A pod may have one or more `init containers`, which are run before the actual app containers are started
  - `init containers` are supposed to run to completion and they run sequentially
- We can specify a `restartPolicy` that applies to all containers in the pod - possible values are `Always`, `OnFailure` and `Never`.
  - Should a container exit with and need to be restarted, kubelet restarts it with an exponential back-off delay (10s, 20s, 40s, …, 5mins)
- `imagePullPolicy` can be set to either `Always`, `IfNotPresent` or `Never` at the container-level

## Notes

### Declarative manifest

- Simple example of Pod yaml definition
  ```yaml
  apiVersion: v1
  kind: Pod
  metadata:
    name: nginx
    labels:
      key1: value1
  spec:
    restartPolicy: Always
    initContainers: []
    containers:
      - name: nginx
        image: nginx:1.14.2
        imagePullPolicy: Always
        command: []
        args: []
        ports:
          - containerPort: 80
        env:
          - name: KEY
            value: value
  ```

### Imperative commands

- `k get pods <pod-name> -o wide`
- get images\
  `k get pods <pod-name> -o jsonpath='{.spec.containers[*].image}'`
- `k describe pods <pod-name>`
- create a nginx pod with label, expose port 80 on container and create a ClusterIP service targeting exposed port\
  `k run nginx --image=nginx -l name=nginx --port 80 --expose`
- run a bash shell in a temporary pod in k8s\
  `k run <pod-name> --image=busybox --restart=Never -it --rm -- /bin/sh`
- `k edit pods <pod-name>`
- `k set image pods <pod-name> <container>=<image>`
- create a ClusterIP service for an existing pod, listens on port 80 and connects to containers on port 8080 \
  `k expose pod <pod-name> --name <service-name> --port=80 --target-port=8080`
- stream the logs of a container in a pod\
  `k logs <pod-name> -c <container> -f`
- `k exec <pod-name> -c <container> -- printenv`
- open a bash shell in a pod with running container\
  `k exec -it <pod-name> -c <container> -- /bin/bash`
- `k delete pods <pod-name>`
- `k delete pods --all`
- forcibly and immediately deletes the Pod from the API server store (etcd)\
  `k delete pods --force --grace-period=0`

## Further reading

### Immutable fields

A pod's specification is mostly unchangeable once it is created.

To change certain fields in the pod specification, it must be deleted, recreated and rescheduled.

We can only use `k patch`, `k apply` and `k edit` to update fields like

- `spec.containers[*].image`
- `spec.initContainers[*].image`
- `spec.activeDeadlineSeconds`
- `spec.tolerations`

To update other fields, such as `spec.containers[*].command`, `spec.restartPolicy` etc, quickest way is to do\
`k replace --force -f <new-pod>`\
This will delete the pod before creating an updated one.

A better solution is to employ controller (such as `Deployment`) to manage the destruction and creation for us.

### Pod phase

The phase of a Pod is a simple, high-level summary of where the Pod is in its lifecycle.

These are the possible values of pod phase

- `Pending`: pod has been accepted by the system, container(s) have not been started. This includes bounding to node and pulling image
- `Failed`: all containers in the pod have terminated, and >= 1 container has terminated in a failure
- `Running`: pod has been bounded to a node, all containers have started and >= 1 container is still running (or restarting)
- `Succeeded`: all containers terminated with exit code of 0, and no restart is required
- `Unknown`: the state of the pod could not be obtained

### Pod condition

Every pod has the list of conditions

1. `PodScheduled`: the Pod has been scheduled to a node
2. `ContainersReady`: all containers in the Pod are ready
3. `Initialized`: all init containers have completed successfully
4. `Ready`: the Pod is able to serve requests and **should** be added to the load balancing pools of all matching Services

For example, an nginx pod in "Running" phase may have all the conditions set to true

```yaml
status:
  phase: "Running"
  conditions:
    - type: PodScheduled
      status: "True"
    - type: ContainersReady
      status: "True"
    - type: Initialized
      status: "True"
    - type: Ready
      status: "True"
```
