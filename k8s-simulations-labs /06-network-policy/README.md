# Network Policy Simulation

Restricts access to a pod to only same-namespace traffic.

## Steps
1. Apply network policy:
   ```bash
   kubectl apply -f .
   ```
2. Use test pods in other namespaces to verify blocked access.
3. Cleanup:
   ```bash
   kubectl delete -f .
   ```