# Kubectl Cheat Sheet

## Pods

kubectl get pods  
kubectl describe pod <pod-name>  
kubectl logs <pod-name>  
kubectl exec -it <pod-name> -- /bin/bash

## Deployments

kubectl get deployments    
kubectl rollout restart deployment <deployment-name>    
kubectl rollout status deployment <deployment-name>

## Services

kubectl get svc    
kubectl describe svc <service-name>


## Nodes

kubectl get nodes  
kubectl describe node <node-name>
