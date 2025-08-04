# PersistentVolume and PersistentVolumeClaim

Creates a 1Gi volume and mounts it into a pod using a PVC.

## Steps
1. Apply:
   ```bash
   kubectl apply -f pv.yaml
   kubectl apply -f pvc.yaml
   kubectl apply -f pod.yaml
   ```
2. Verify volume is mounted.
3. Cleanup:
   ```bash
   kubectl delete -f .
   ```