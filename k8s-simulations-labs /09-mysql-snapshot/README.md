# MySQL Pod Snapshot (Simulation)

Simulates MySQL volume snapshot using CSI.

## Steps
1. Deploy MySQL with PVC.
2. Create a VolumeSnapshot.
3. Restore from snapshot.

> NOTE: Requires CSI driver and snapshot CRDs