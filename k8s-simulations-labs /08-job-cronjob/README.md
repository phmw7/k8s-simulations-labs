# Job and CronJob

Runs a one-time and recurring task.

## Steps
1. Apply job:
   ```bash
   kubectl apply -f job.yaml
   ```
2. Apply cronjob:
   ```bash
   kubectl apply -f cronjob.yaml
   ```
3. Cleanup:
   ```bash
   kubectl delete -f .
   ```