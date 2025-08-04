# Deployment Upgrade with Version Annotations

Simulates upgrading an application version via rolling update.

## Steps
1. Apply the deployment:
   ```bash
   kubectl apply -f deployment.yaml
   ```
2. Upgrade image tag and annotate:
   ```bash
   kubectl set image deployment/nginx nginx=nginx:1.25
   kubectl annotate deployment nginx version=1.25
   ```
3. Cleanup:
   ```bash
   kubectl delete -f deployment.yaml
   ```