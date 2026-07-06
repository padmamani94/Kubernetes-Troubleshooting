# Pod Pending

## Problem
The pod remains in the Pending state.

## Causes
- Insufficient resources
- Node selector mismatch
- Persistent Volume unavailable

## Troubleshooting

kubectl describe pod <pod-name>  
kubectl get nodes  

## Solution
- Increase cluster resources
- Check scheduling constraints
- Verify Persistent Volumes
