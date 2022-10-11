---
# Getting Started with k8s with KinD
---

Create a local kubernetes cluster using 
 [KinD](https://kind.sigs.k8s.io)

```
kind create cluster --name <clusterName>

kind get clusters

kubectl cluster-info
```

Delete a KinD cluster
```
kind delete cluster
```

K8s FUC (Frequently Used Commands)
```
kubectl get namespace
kubectl config current-context
kubectl apply -f <file_name> -n <namespace>
kubectl get pods -n <namespace>
kubectl get svc -n <namespace>
kubectl port-forward svc/<service_name>  servicePort:externalPort -n <namespace> 

```

