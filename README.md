🏠 Homelab
---

### Introduction
---

This repo contains all the configurations and documentation related to my homelab setup.

As a DevOps student, my goal is to learn by doing—and my homelab is where the magic happens. It’s my sandbox for testing, breaking, fixing, and improving. I use it to explore technologies like Kubernetes, automation tools, containerization, monitoring stacks, and more. By self-hosting applications and managing the full lifecycle—from deployment to maintenance—I gain real-world experience with backup strategies, security, scalability, and operational reliability.

This is more than just a lab—it’s my personal playground and learning portfolio.

<br>

🏗 Homelab Setup Progress
---
<br>

This section documents the main steps I took while building my homelab using Raspberry Pi, Kubernetes (K3s), Flux, and GitOps.

<br>

1️⃣ Raspberry Pi + K3s Setup
	•	Flashed Raspberry Pi OS (64-bit Lite) + update + upgrade
	•	Configured ethernet for static ip + SSH access
 	•	Setup k3s without helm / with etcd 

2️⃣ GitOps Bootstrap (FluxCD)
	•	Generated personal access token for GitHub.
	•	Bootstrapped Flux
 	•	Fixed coredns issues inside the cluster for proper external resolution.

3️⃣ Deploy Linkding
	•	Started with simple linkding deployment to test everything (1 replica)
	•	Added a PVC for storage and data redundancy 
	•	Verified deployments with internal port-forwarding and cluster IPs.
 	•	Secured linkding by removing root access

4️⃣ Cloudflare 
	•	Registered cloudflare domain
	•	Created Cloudflare tunnel + service for public access.

5️⃣ Current & Next Steps
	•	✅ Kubernetes cluster fully functional.
	•	✅ Flux GitOps pipeline running.
	•	✅ Internal services deployed & tested.
	•	✅ Setup Cloudflare Tunnel.
	•	🔜 Expand with more services (Nextcloud, Mealie, monitoring stack).
	•	🔜 CI/CD pipelines for future projects.


 
