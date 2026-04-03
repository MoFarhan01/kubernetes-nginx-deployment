# Kubernetes Nginx Deployment

This project demonstrates deploying a containerized Nginx application on a Kubernetes cluster using kubectl and exposing it via service.

## Architecture
- Kubernetes local cluster (Docker Desktop)
- Nginx container deployment
- NodePort service exposure
- Port-forward access

## Deployment
```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

```
## Create Service

```bash
kubectl apply -f service.yaml
```
## Verify Resources
# Check pods:
```bash
kubectl get pods
```
#Check service:
```bash
kubectl get svc
```
