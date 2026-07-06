# ImagePullBackOff

# Problem
Kubernetes cannot pull the container image.

# Causes
- Incorrect image name
- Invalid image tag
- Private registry authentication failure

# Troubleshooting

kubectl describe pod <pod-name>

# Solution
- Verify image name
- Verify image tag
- Configure imagePullSecrets
