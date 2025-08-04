# Ingress Resource

Creates a sample Ingress to route traffic to a service.

## Steps
1. Enable ingress addon in Minikube:
   ```bash
   minikube addons enable ingress
   ```
2. Apply manifests:
   ```bash
   kubectl apply -f .
   ```
3. Test via:
   ```bash
   minikube service ingress-nginx-controller -n ingress-nginx --url
   ```