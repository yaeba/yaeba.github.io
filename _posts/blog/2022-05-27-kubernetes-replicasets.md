---
title: "Kubernetes: ReplicaSets"
excerpt: "Controller of a stable set of replica Pods running at any given time"
toc: true
tags: kubernetes
header:
  overlay_image: /assets/images/kubernetes.png
  overlay_filter: 0.5
  caption: "Photo credit: [**WallpaperAccess**](https://wallpaperaccess.com/kubernetes)"
---

## Useful links

- [https://kubernetes.io/docs/concepts/workloads/controllers/&#8203;replicationcontroller](https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller){:target="\_blank"}
- [https://kubernetes.io/docs/concepts/workloads/controllers/&#8203;replicaset/](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/){:target="\_blank"}
- Also check out my previous post on [Kubernetes: Pods](../kubernetes-pods/){:target="\_blank"}

## Concepts

Both ReplicationController and ReplicaSet are to be used to ensure a **specified** number of pod replicas are up and running at any given time.

- ReplicaSet is actually the **successor** of ReplicationController and they both serve identical purpose
- Having said that, it's almost always recommended to use **Deployment** over managing ReplicationController/ReplicaSet, as the former provides a couple of more useful features on top
- ReplicaSet requires us to define a **PodTemplate**, which it uses to create new pod(s) when needed
- It is also necessary to specify a **selector**, which defines the target (pod) it is maintaining
- ReplicaSet offers a richer way to specify label selector ([set-based](https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/#set-based-requirement)) over ReplicationController

## Notes

### Declarative manifest

- Simple example of ReplicaSet yaml definition
  ```yaml
  apiVersion: apps/v1
  kind: ReplicaSet
  metadata:
  name: nginx-rs
  labels:
    rskey1: rsvalue1
  spec:
    replicas: 3 # number of replica pods
    selector:
      matchLabels:
        podlabel: podvalue # selector
    template: # pod template (just like what we would define in pod yaml)
      metadata:
        labels:
          podlabel: podvalue # label of pod
      spec:
        containers:
          - name: nginx
            image: nginx:1.14.2
  ```

### Imperative commands

- `k get rs <replica-set-name> -o wide`
- Update number of replicas\
  `k scale rs <replica-set-name> --replicas=<num>`
- Determine ReplicaSet (owner) of a pod\
  `k get pods <pod-name> -o yaml | grep -A 5 owner`
- Delete ReplicaSet and all its pods\
  `k delete rs <replica-set-name>`
- Delete ReplicaSet only\
  `k delete rs <replica-set-name> --cascade=false`
