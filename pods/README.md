# Pod Example ☸️

This folder contains a basic Kubernetes Pod manifest created as part of my learning journey.

## 📌 Overview

- Creates a Pod named `nginx-pod`
- Runs an Nginx container
- Exposes container port 80
- Demonstrates the declarative approach using YAML

## 🚀 How to Deploy

kubectl apply -f pod.yaml

## 🔍 Verify

kubectl get pods

## 🧹 Delete

kubectl delete -f pod.yaml
