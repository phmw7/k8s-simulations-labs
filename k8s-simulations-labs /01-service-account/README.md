# ServiceAccount with Cluster-Wide Pod Listing Permissions

This task creates a ServiceAccount with permissions to list pods across all namespaces.

## Steps
1. Apply the YAML files:
   ```bash
   kubectl apply -f service-account.yaml
   kubectl apply -f clusterrole-binding.yaml
   ```
2. Use the ServiceAccount with a pod to test permissions.
3. Cleanup:
   ```bash
   kubectl delete -f .
   ```