## This folder contains a basic Deployment manifest created as part of my Kubernetes learning journey.

## 📌 Overview
Creates a Deployment named nginx-deployment  
Manages multiple replicas of a Pod running an Nginx container  
Demonstrates how Kubernetes ensures desired state and automatic Pod management

## 🚀 How to Deploy
```yaml
kubectl apply -f deployment.yaml
```

## 🔍 Verify
```yaml
kubectl get deployments
kubectl get pods
```

## 📈 Scale Deployment
```yaml
kubectl scale deployment nginx-deployment --replicas=5
```

## 🧹 Delete
```yaml
kubectl delete -f deployment.yaml
```
