# Kubernetes Enterprise Capstone  
**Secure, Observable, GitOps-Driven Microservices Platform**

---

## Overview

This capstone project simulates a **real-world enterprise Kubernetes environment** where students design, deploy, secure, and operate a production-grade microservices platform.

The project is intentionally structured to align with CNCF Kubernetes certifications in the following order:

1. **CKA – Certified Kubernetes Administrator (first)**
2. **CKAD – Certified Kubernetes Application Developer (second)**
3. **CKS – Certified Kubernetes Security Specialist (advanced)**

This sequencing mirrors how Kubernetes is adopted in industry:  
**platform first → applications next → security by design.**

---

## Objectives

By completing this capstone, students will:

- Understand Kubernetes cluster architecture and operations
- Deploy and manage containerized applications
- Implement CI/CD and GitOps workflows
- Apply Kubernetes security best practices
- Build observability using Prometheus and Grafana
- Troubleshoot and operate a production-like Kubernetes platform

---

## High-Level Architecture

The platform consists of:

- Kubernetes Cluster (EKS / kind / k3s)
- Multiple microservices (frontend, backend, worker)
- Ingress controller (NGINX)
- CI/CD pipeline (GitHub Actions or Jenkins)
- GitOps deployment using ArgoCD
- Kubernetes security controls
- Observability stack (Prometheus + Grafana)

---

## Certification Alignment

This capstone maps directly to CNCF certification objectives:

| Area | CKA | CKAD | CKS |
|-----|-----|------|-----|
Cluster architecture & operations | ✅ |  |  |
Namespaces & quotas | ✅ |  |  |
Scheduling & resources | ✅ |  |  |
Troubleshooting | ✅ |  |  |
Application deployment |  | ✅ |  |
ConfigMaps & Secrets |  | ✅ | ✅ |
Scaling & probes | ✅ | ✅ |  |
CI/CD & GitOps |  | ✅ |  |
RBAC |  |  | ✅ |
NetworkPolicy |  |  | ✅ |
Pod Security |  |  | ✅ |
Image scanning |  |  | ✅ |
Monitoring & observability | ✅ |  |  |

---

## 12-Week Project Plan (CKA → CKAD → CKS)

### Weeks 1–2: Kubernetes Foundations (CKA Focus)
**Focus**
- Kubernetes architecture
- kubectl fundamentals
- Nodes and namespaces
- Basic scheduling concepts

**Deliverables**
- Working Kubernetes cluster
- Namespaced environments
- Basic deployments

---

### Weeks 3–4: Cluster Operations & Troubleshooting (CKA Heavy)
**Focus**
- Resource requests and limits
- Scheduling, taints, and tolerations
- Horizontal Pod Autoscaler
- Debugging failing workloads

**Deliverables**
- Scalable workloads
- Resource isolation
- Troubleshooting report

🧠 **CKA Exam Readiness Phase**

---

### Weeks 5–6: Application Deployment (CKA → CKAD Bridge)
**Focus**
- Deployments and Services
- ConfigMaps and Secrets
- Liveness & readiness probes
- Rolling updates

**Deliverables**
- Stable application deployments
- Zero-downtime updates
- Configuration management

🧠 **CKA Exam Target: End of Week 6**

---

### Weeks 7–8: Application Patterns & CI/CD (CKAD Focus)
**Focus**
- Helm charts
- Multi-container pods
- CI pipelines
- Deployment strategies

**Deliverables**
- Helm-based application packaging
- Automated CI pipeline
- Application release workflows

---

### Weeks 9–10: GitOps & Application Security (CKAD Heavy)
**Focus**
- GitOps using ArgoCD
- Secrets management
- Image scanning (Trivy)
- Deployment validation

**Deliverables**
- GitOps-driven deployments
- Secure application configurations
- CKAD-aligned workflow

🧠 **CKAD Exam Target: End of Week 10**

---

### Weeks 11–12: Kubernetes Security & Observability (CKS Foundation)
**Focus**
- RBAC with least privilege
- ServiceAccounts
- NetworkPolicies
- Pod Security Standards
- Prometheus & Grafana
- Incident simulation

**Deliverables**
- Secure cluster configuration
- Monitoring dashboards
- Final architecture demo

---

## Repository Structure

```text
k8s-enterprise-capstone/
├── docs/
│   ├── architecture.md
│   ├── security-model.md
│   └── observability.md
├── services/
│   ├── frontend/
│   ├── backend/
│   └── worker/
├── k8s/
│   ├── base/
│   ├── overlays/
│   ├── rbac/
│   ├── network-policies/
│   └── pod-security/
├── helm/
├── ci/
├── gitops/
│   └── argocd/
├── monitoring/
│   ├── prometheus/
│   └── grafana/
└── labs/
    ├── week01-02/
    ├── week03-04/
    ├── week05-06/
    ├── week07-08/
    ├── week09-10/
    └── week11-12/
