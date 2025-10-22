# 🔐 Kubernetes Security Project — Local DevSecOps Implementation

## 📖 Overview
This project demonstrates how to implement **end-to-end Kubernetes security** locally using WSL2 and KinD (Kubernetes in Docker).

The goal was to replicate real-world DevSecOps practices — enforcing policies, scanning workloads, and hardening clusters — without using cloud platforms like AWS, Azure, or GCP.

---

## 🧰 Tools Used
- **Kubernetes (KinD on WSL2)**
- **Kyverno** – Policy enforcement
- **OPA Gatekeeper** – Policy-as-Code
- **Kubescape** – CIS & NSA compliance scanner
- **Docker** – Cluster runtime
- **YAML** – Configuration

---

## 🧪 Key Implementations
- Restricted privileged containers using Kyverno.
- Added admission control policies using OPA Gatekeeper.
- Scanned the cluster for CIS Benchmark compliance using Kubescape.
- Resolved Kyverno & Gatekeeper conflicts via namespace exclusions.

---

## 📂 Project Structure
Kubernetes-Security/
├── manifests/ → YAML configurations (Kyverno, Gatekeeper)
├── reports/ → Scan and Pod reports
├── README.md → Project documentation
└── LICENSE

---

## 🏁 Outcome
✅ Deployed a fully secure Kubernetes cluster locally.  
✅ Enforced runtime security policies.  
✅ Implemented policy-as-code controls.  
✅ Completed CIS & NSA compliance scans.

---

## ✍️ Author
**Harshit Sharma**  
*DevSecOps Engineer | Kubernetes | Cloud Security Enthusiast*  
[LinkedIn Profile](https://linkedin.com/in/harshit-sharma)

---

## 🪔 Shubh Deepawali Message
> “As we celebrate the festival of lights, may the values of Lord Rama — dharma, truth, and integrity — guide us in life and technology alike.  
> Building secure systems begins with building strong values.”  

#DevSecOps #Kubernetes #CloudSecurity #Kyverno #OPA #Kubescape #DevOps #SecurityEngineering
