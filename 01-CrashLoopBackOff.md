## CrashLoopBackOff

# Problem
The pod starts but repeatedly crashes.

# Causes
- Application error
- Incorrect configuration
- Missing environment variables
- Database connection failure

# Troubleshooting

kubectl get pods
kubectl describe pod <pod-name>
kubectl logs <pod-name>
kubectl logs <pod-name> --previous

# Solution
- Check application logs
- Verify ConfigMaps and Secrets
- Fix application errors
- Restart the deployment
