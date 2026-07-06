# Node NotReady

## Problem
The node is not available for scheduling.

## Troubleshooting

kubectl get nodes  
kubectl describe node <node-name>

## Solution
- Restart kubelet
- Check node resources
- Verify network connectivity
