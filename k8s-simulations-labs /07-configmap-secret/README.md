# ConfigMap and Secret Usage

Mounts config data and secrets into a pod.

## Steps
1. Apply:
   ```bash
   kubectl apply -f .
   ```
2. Verify data in pod at `/etc/config` and `/etc/secret`
3. Cleanup:
   ```bash
   kubectl delete -f .
   ```