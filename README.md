# 🏠 Homelab

## Introduction

This repository contains all the configurations and documentation related to my personal homelab setup.

As a DevOps student, my goal is to **learn by doing** — and my homelab is where I experiment, test, break, fix, and improve my skills.  
Here I explore and practice technologies such as:

- Kubernetes (K3s)
- GitOps (FluxCD)
- Containerization (Docker)
- Infrastructure as Code
- Monitoring and Observability
- Networking & DNS
- Backup and Disaster Recovery

By self-hosting applications and managing the full deployment lifecycle, I gain real-world experience with:

- Security
- Scalability
- High availability
- Troubleshooting
- Automation

This is my **learning lab** and evolving **DevOps playground**.

---

## 🏗 Homelab Setup Progress

Documenting the key steps as I built and improved my homelab environment:

### 1️⃣ Raspberry Pi + K3s Cluster Setup

- Flashed Raspberry Pi OS (64-bit Lite), updated & upgraded.
- Configured static IP + SSH access for remote management.
- Installed **K3s** (lightweight Kubernetes) with embedded etcd.

### 2️⃣ GitOps Bootstrap with FluxCD

- Generated GitHub personal access token.
- Bootstrapped FluxCD with `flux bootstrap github`.
- Resolved CoreDNS issues for external DNS resolution inside the cluster.

### 3️⃣ First Application Deployment: Linkding

- Deployed **Linkding** (bookmark manager) to validate cluster deployment.
- Configured Persistent Volume Claims for data storage.
- Verified deployment with port-forwarding & ClusterIP.
- Hardened the deployment by removing root access.

### 4️⃣ External Access via Cloudflare

- Registered domain with Cloudflare.
- Set up Cloudflare Tunnel for secure public access to internal services.

### 5️⃣ Current Status & Next Steps

- ✅ K3s Kubernetes cluster operational.
- ✅ FluxCD GitOps fully running.
- ✅ Internal services deployed and functional.
- ✅ Cloudflare Tunnel working.
- 🔜 Expand services: Nextcloud, Mealie, monitoring stack.
- 🔜 Build CI/CD pipelines for automated deployments.

---

## ⚠️ Disclaimer

This homelab is purely for personal learning and experimentation.  
Any sensitive data, credentials or secrets are for test purposes only.
