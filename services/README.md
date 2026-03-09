### This folder contains Kubernetes Service manifests created as part of my Kubernetes learning journey.

### 🚀 How to Deploy
kubectl apply -f <service-file>.yaml

### 🔍 Verify
kubectl get services

### 🧹 Delete
kubectl delete -f <service-file>.yaml

### ⚠️ Important Note  
The Service selector must match the Pod label.  
If the labels do not match, Service won’t connect to the Pod.

### Example:
#### Pod
labels:
  app: nginx

#### Service
selector:
  app: nginx
