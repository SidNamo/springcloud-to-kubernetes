# sc-to-k8s

## 📌 Project Description

This project focuses on **migrating an existing open-source Spring Cloud–based system
to a Kubernetes (K8s) environment**.

The original source code was taken from a publicly available open-source repository
(not authored by me).  
This repository contains **migration work, configuration changes, and Kubernetes-related setup**
applied on top of the original Spring Cloud architecture.

The purpose of this project is to practice and document:
- Spring Cloud architecture understanding
- Kubernetes-based deployment patterns
- Configuration and infrastructure migration

---

## 🎯 Purpose

- Learn how Spring Cloud components map to Kubernetes concepts
- Replace or adapt Spring Cloud infrastructure components for K8s
- Practice containerization and deployment orchestration
- Document a real-world migration workflow

---

## 🛠 Tech Stack

- **Language**: Java
- **Framework**: Spring Cloud
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Configuration**: YAML (K8s manifests)
- **Environment**: Local / Test cluster

---

## 📂 Project Structure

```text
.
├─ services/           # Spring Cloud microservices
├─ docker/             # Docker-related files
├─ k8s/                # Kubernetes manifests
├─ config/             # Configuration overrides
└─ README.md
```

---

## ▶️ How to Run (High-Level)

1. Build Docker images for each service
2. Prepare Kubernetes cluster (local or remote)
3. Apply Kubernetes manifests
4. Verify service discovery and inter-service communication

> Detailed commands depend on the target cluster and environment.

---

## 🔐 Security & Privacy

- No production credentials are included
- No API keys, secrets, or certificates are stored
- Configuration values are for local or test environments only

---

## ⚖️ Open Source Notice

- This project is based on **existing open-source code**
- Original authorship belongs to the respective open-source contributors
- This repository is **for learning and migration practice purposes**
- License terms of the original project should be respected

---

## 📎 Notes

- Not intended for production use
- Infrastructure-focused learning project
- Kept public for reference and study purposes

---

## 📄 License

Follow the license of the original open-source project.
