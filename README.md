# 🚀 Kubernetes Minikube Project

## 🧩 Objective
Deploy and manage an application in Kubernetes using **Minikube**, **kubectl**, and **Docker**.

## 🧰 Tools Used
- Minikube
- kubectl
- Docker

## 🧱 Steps Followed
1. Installed Minikube and started a local cluster
2. Created `deployment.yaml` for Nginx app
3. Created `service.yaml` to expose the app via NodePort
4. Verified pods and services
5. Scaled the deployment
6. Accessed app using `kubectl port-forward`

## 📸 Screenshots
(Add screenshots here)

## 🧠 Commands Summary
```bash
minikube start --driver=docker
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get svc
kubectl port-forward service/myapp-service 8080:80
