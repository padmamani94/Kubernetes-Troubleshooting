# Service Not Reachable

## Problem
Application cannot be accessed through the Service.

## Troubleshooting

kubectl get svc  
kubectl describe svc <service-name>  
kubectl get endpoints  

## Solution
- Verify selector labels
- Check targetPort
- Verify pod status
