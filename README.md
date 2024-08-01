# K8s Examples

In this repository, I will be sharing some examples of Kubernetes.

Stay tuned!

**Preparating the environment**

Start the Minikube cluster with the following commands:
```bash
minikube start

# or, if you want to start a cluster with 3 nodes
minikube start --nodes 3
```

Lets check the status of the cluster:
```bash
kubectl get nodes
```

Lets check the status of the pods:
```bash
kubectl get pods --all-namespaces
```

With `-o wide` you can see more information about the pods, including the node where the pod is running:
```bash
kubectl get pods -o wide
```
