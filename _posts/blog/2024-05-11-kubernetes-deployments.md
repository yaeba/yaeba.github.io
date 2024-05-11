---
title: "Kubernetes: Deployments"
excerpt: "Ensuring reliable and up-to-date application deployment"
toc: true
tags: kubernetes
header:
  overlay_image: /assets/images/kubernetes.png
  overlay_filter: 0.5
  caption: "Photo credit: [**WallpaperAccess**](https://wallpaperaccess.com/kubernetes)"
---

## Useful links

- [https://kubernetes.io/docs/concepts/workloads/controllers/&#8203;deployment/](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/){:target="\_blank"}
- [Kubernetes: Pods](../kubernetes-pods/){:target="\_blank"}
- [Kubernetes: ReplicaSets](../kubernetes-replicasets/){:target="\_blank"}

## Concepts

- **Deployments** manage the deployment and scaling of a set of Pods and provide declarative updates to applications.
- A Deployment is described as **a set of identical Pods** with no unique identities. A Deployment runs multiple replicas of your application and automatically replaces any instances that fail or become unresponsive.
- In essence, Deployments are **higher-level concepts** that manage ReplicaSets and provide additional features like **rolling updates and rollbacks**.
- As such, it's recommended to use Deployment instead of directly managing ReplicaSets because it provides additional useful features.
- Deployments manage **stateless** applications, while StatefulSets manage **stateful** applications

## Notes

### Declarative manifest

- Simple example of Deployment yaml definition, you will find this very similar to ReplicaSet
  ```yaml
  apiVersion: apps/v1
  kind: Deployment
  metadata:
    name: nginx-deployment
    labels:
      app: nginx
  spec:
    strategy: # how to replace old pods with new ones
      type: RollingUpdate # default strategy
      rollingUpdate:
        maxUnavailable: 1
        maxSurge: 1
    replicas: 3 # number of replica pods
    selector:
      matchLabels:
        app: nginx # selector
    template: # pod template (just like what we would define in pod yaml)
      metadata:
        labels:
          app: nginx # label of pod
      spec:
        containers:
        - name: nginx
          image: nginx:1.14.2
  ```

### Imperative commands

- Get deployment details\
  `k get deploy <deployment-name> -o wide`
- Update Deployment replicas\
  `k scale deployment <deployment-name> --replicas=<num>`
- Rollback to an earlier Deployment revision\
  `k rollout undo deploy <deployment-name>`
- View the rollout history of a Deployment\
  `k rollout history deploy <deployment-name>`
- Determine Deployment (owner) of a pod\
  `k get pods <pod-name> -o yaml | grep -A 5 owner`
- Delete Deployment and all its pods\
  `k delete deploy <deployment-name>`
- Delete Deployment only\
  `k delete deploy <deployment-name> --cascade=orphan`
