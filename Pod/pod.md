# POD stand for (Proof of Delivery)

# POD Creation Methods
There are 2 basic methods of creating the POD
1. Command line method
2. File method

## 1.Command Line Method

Run this command 
```
kubectl run web-server --image=nginx  
```
#### View pods through this command

Run the following command for view the pod
```
kubectl get pods  
```
#### 2. File Method

 [File Method](./pod.yml)

Run the command
```
kubectl apply -f pod.yml  
```
For view the pod

```
kubectl get pods  
```
For view more details

```
kubectl get pods -o wide  
```
For delete the file

```
kubectl delete -f pod.yml  
```
For delete the pod

```
kubectl delete pod web-server  
```
