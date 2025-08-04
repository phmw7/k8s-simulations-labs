# Simulate CrashLoopBackOff

Runs a pod that exits immediately, causing repeated restarts.

## Steps
1. Apply:
   ```bash
   kubectl apply -f pod.yaml
   ```
2. Observe CrashLoopBackOff:
   ```bash
   kubectl get pods
   kubectl describe pod crash
   ```
3. Cleanup:
   ```bash
   kubectl delete -f pod.yaml
   ```