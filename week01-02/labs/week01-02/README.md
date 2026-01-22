# Week 1–2 – Kubernetes Foundations (CKA Focus)

## 🎯 Objective
This phase establishes **core Kubernetes fundamentals** required for the CKA exam and for operating real-world clusters.
Everything in later weeks (CKAD, CKS, GitOps, Security) assumes mastery of these concepts.

---

## 📘 Topics Covered
- Kubernetes architecture (control plane & worker nodes)
- kubectl fundamentals
- Nodes, namespaces, and contexts
- Basic scheduling concepts
- Deployments and Services

---

## 📦 Environment Options
You may use:
- kind (recommended)
- minikube
- EKS / GKE / AKS

All labs assume kubectl access to a working cluster.

---

## 🧪 Labs Breakdown

### Lab 01 – Cluster Setup & kubectl Basics
- Create Kubernetes cluster
- Verify nodes and system pods
- Inspect control plane components
- Practice kubectl commands

### Lab 02 – Namespaces & Contexts
- Create dev / staging / prod namespaces
- Work with kubectl contexts
- Deploy resources into namespaces

### Lab 03 – Basic Deployments & Services
- Create Deployments
- Expose applications using Services
- Test connectivity
- Intro to node scheduling

---

## 📂 Deliverables
By the end of Week 2, you must submit:
- Running Kubernetes cluster
- Namespaces applied from YAML
- Sample application Deployment & Service
- Notes explaining architecture & namespace usage
- Troubleshooting observations

---

## 🎓 CKA Exam Mapping
- Cluster architecture
- kubectl operations
- Workloads & Services
- Scheduling basics
- Troubleshooting

---

## ✅ Completion Criteria
You are ready to move to Week 3–4 if you can:
- Deploy workloads without copy-paste
- Debug Pods using kubectl describe/logs
- Explain why namespaces matter
- Modify manifests confidently
