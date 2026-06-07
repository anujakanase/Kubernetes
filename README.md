# ☸️ Kubernetes 

This repository contains my hands-on Kubernetes practice, real-world examples, and deployment manifests created while learning Kubernetes and DevOps.

The goal of this repository is to build a strong understanding of Kubernetes concepts through practical implementation rather than theory alone.

---

## 🚀 Topics Covered

### Core Kubernetes Objects

* Pods
* ReplicaSets
* Deployments
* Services
* Namespaces
* Labels & Selectors

### Configuration Management

* ConfigMaps
* Secrets

### Storage

* Persistent Volumes (PV)
* Persistent Volume Claims (PVC)
* Storage Classes

### Workload Management

* StatefulSets
* DaemonSets
* Jobs
* CronJobs

### Networking

* ClusterIP Services
* NodePort Services
* LoadBalancer Services
* Ingress

### Scaling & Availability

* Horizontal Pod Autoscaler (HPA)
* Rolling Updates
* Rollbacks

### Security

* Service Accounts
* RBAC (Role-Based Access Control)

### Monitoring & Troubleshooting

* Logs
* Events
* Port Forwarding
* Resource Inspection

---

## 🛠 Prerequisites

Before using these manifests, ensure you have:

* Docker
* Kubernetes Cluster
* kubectl
* Kind / Minikube (for local practice)

Verify installation:

```bash
kubectl version
kubectl get nodes
```

---

## 📌 Common Commands

### Create Resources

```bash
kubectl apply -f deployment.yaml
```

### View Resources

```bash
kubectl get pods
kubectl get deployments
kubectl get services
```

### Describe Resources

```bash
kubectl describe pod <pod-name>
```

### View Logs

```bash
kubectl logs <pod-name>
```

### Execute Inside Container

```bash
kubectl exec -it <pod-name> -- sh
```

### Delete Resources

```bash
kubectl delete -f deployment.yaml
```

---

## 🧪 Practice Projects

This repository includes practical Kubernetes deployments such as:

* Nginx Application Deployment
* Apache Application Deployment
* Persistent Storage Examples
* Ingress Configuration Examples
* Scaling Demonstrations

---

## 🎯 Learning Objectives

Through this repository I am learning:

* Kubernetes Architecture
* Application Deployment
* Service Discovery
* Storage Management
* Networking Concepts
* Scaling Strategies
* Troubleshooting Production Issues
* DevOps Best Practices

---

## 📖 Useful References

* Kubernetes Official Documentation
* CNCF Documentation
* Kubernetes Cheat Sheet
* Kubectl Reference

---

