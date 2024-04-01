<h1 align="center">Hi 👋, I'm Muhammad Amjad</h1>
<h3 align="center">DevOps and Cloud Enthusiast</h3>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=maamjad&label=Profile%20views&color=0e75b6&style=flat" alt="maamjad" /> </p>
<h3 align="left">This Repo is for Kubernetes:</h3>
<a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>

# This repository is all about kubernetes.
In this repository we will cover the following topics of kubernetes :

1. Pod
2. Namespace
3. Taint
4. Replication Controller
5. Replica Set
6. Deployment
7. Init Container 
8. Multi Container
9. RBAC
10. ConfigMap
11. Secrets
12. Labels
13. Pod Limit
14. Resource Quota
15. Limit Range
    
## Kubernetes Deployment Strategies:
1. Rolling Deployment
2. Recreate 
3. Blue Green 

## Kubernetes Service
1. ClusterIP
2. NodePort
3. LoadBalancer

## Kubernetes Storage
1. PV
2. PVC

### Kubernetes Basic Commands

#### It is used to view the number of nodes
```
kubectl get nodes 
```
#### It is used to view the number of pods
```
kubectl get pods 
```
#### It is used to view the number of pods with details
```
kubectl get pods -o wide 
```
#### It is used to view the namespaces
```
kubectl get namespace 
```
#### It is used to view the deatils of the master node
```
kubectl describe node master  
```
#### It is used to view the deatils of the worker node
```
kubectl describe node worker 
```
#### It is used to create the pod
```
kubectl run web-server --image=nginx
```
