# Kubernetes Simulations Lab

This repository contains 10 hands-on Kubernetes simulation tasks designed to help you prepare for the Certified Kubernetes Administrator (CKA) exam and showcase real-world skills in your portfolio.

## 📋 Task List

| Task | Title | Description |
|------|-------|-------------|
| 01 | ServiceAccount | Create a ServiceAccount with cluster-wide pod listing permissions |
| 02 | Deployment Upgrade | Upgrade a Deployment and add version annotations |
| 03 | PersistentVolume | Create a PersistentVolume and bind it to a pod using a PVC |
| 04 | Taint & Toleration | Taint a node and use tolerations to schedule a pod |
| 05 | Ingress Resource | Expose a web app using an Ingress controller |
| 06 | Network Policy | Restrict traffic between pods using a NetworkPolicy |
| 07 | ConfigMap & Secret | Inject config and secrets into a running pod |
| 08 | Job & CronJob | Run one-time and scheduled background tasks |
| 09 | MySQL Snapshot (Simulated) | Simulate a CSI snapshot of a MySQL pod's PVC |
| 10 | CrashLoopBackOff | Simulate a pod crash and observe recovery behavior |

## 🔧 Usage

You can apply each task using `kubectl apply -f .` from inside each task folder.

Tested with:
- Minikube v1.32+
- kubectl v1.29+

## 📂 Structure

Each task folder contains:
- `README.md` — steps and explanations
- YAML manifests for all Kubernetes resources

---

Built for hands-on practice, learning, and certification prep.
