## This folder contains a basic StatefulSet manifest created as part of my Kubernetes learning journey.

## 📌 Overview
Creates a StatefulSet named mysql-statefulset  
Runs MySQL containers to demonstrate a stateful application  
Demonstrates how StatefulSets provide stable Pod identity and ordered deployment  

## 🚀 How to Deploy
```yaml
kubectl apply -f statefulset.yaml
```

## 🔍 Verify
```yaml
kubectl get statefulsets
kubectl get pods
```

## 🧹 Delete
```yaml
kubectl delete -f statefulset.yaml
```
