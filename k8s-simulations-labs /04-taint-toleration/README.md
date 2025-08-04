# Taint a Node and Use Toleration

Simulates scheduling a pod on a tainted node.

## Steps
1. Taint the node:
   ```bash
   kubectl taint nodes $(kubectl get nodes -o name | head -1 | cut -d/ -f2) key=value:NoSchedule
   ```
2. Apply the pod:
   ```bash
   kubectl apply -f pod.yaml
   ```
3. Cleanup:
   ```bash
   kubectl delete -f pod.yaml
   kubectl taint nodes $(kubectl get nodes -o name | head -1 | cut -d/ -f2) key:NoSchedule-
   ```