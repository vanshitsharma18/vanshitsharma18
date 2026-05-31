<div align="center">

# Vanshit Sharma

### Junior DevOps Engineer · Cloud Engineer · GCP Certified

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vanshit--sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanshit-sharma/)
[![Gmail](https://img.shields.io/badge/Gmail-vanshitsharma2006-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vanshitsharma2006@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vanshitsharma18-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18)

</div>

---

## About Me

DevOps and Cloud Engineer with hands-on experience designing **CI/CD pipelines**, **Kubernetes-based deployments**, and **cloud-native architectures on GCP and AWS**.

- 🏅 **Certified Google Cloud Associate Cloud Engineer**
- ⚙️ Building GitOps pipelines with **GitHub Actions + ArgoCD on GKE Autopilot**
- 🔒 Practising **DevSecOps** — Trivy container scanning, IAM least-privilege, DLQ error handling
- 🏗️ Provisioning infrastructure with **Terraform IaC** across AWS and GCP
- 📊 Implementing full observability stacks — **Prometheus, Grafana, Alertmanager, Loki**
- 📄 Published research: *Serverless Notification System (AWS)* — **Com-It CON 2025**

---

## Tech Stack

#### Cloud Platforms
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

#### Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

#### CI/CD & GitOps
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-F05032?style=flat-square&logo=git&logoColor=white)

#### Infrastructure as Code
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)

#### Monitoring & Security
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy_(DevSecOps)-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)

#### Languages & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

#### OS & Version Control
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Featured Projects

### 🔷 GitOps Kubernetes Deployment Pipeline
> `GitHub Actions` · `GKE Autopilot` · `ArgoCD` · `Helm` · `Prometheus` · `Grafana` · `Trivy` · `Docker`

End-to-end GitOps platform deployed on **GKE Autopilot** with full DevSecOps pipeline.

| Metric | Result |
|---|---|
| Deployment cycle | 45 min → **8 min (82% reduction)** |
| Configuration drift incidents | 4/sprint → **0** |
| Prometheus alert rules | **8 custom rules** across dev/staging |
| CVE blocking | **100% pre-deploy** container security coverage |

- Architected GitHub Actions (CI) + ArgoCD (CD) pipeline on GKE Autopilot, eliminating cluster node management overhead
- Integrated **Trivy** as a CI quality gate — automatically blocks HIGH/CRITICAL CVEs before staging
- Deployed Prometheus + Grafana observability stack; GKE Autopilot auto-scales to maintain **sub-200ms p95 latency**

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/todo-app-deployment)

---

### 🔷 Serverless Notification System (AWS)
> `Terraform` · `AWS Lambda` · `API Gateway` · `SNS` · `SQS` · `DynamoDB` · `IAM`

Event-driven fan-out notification system fully provisioned with **Terraform IaC**.  
📄 *Published at Com-It CON 2025 International Conference*

| Metric | Result |
|---|---|
| Concurrent requests handled | **10,000 at <200ms avg latency** |
| Message loss | **Zero** (DLQ for all failure scenarios) |
| Cost vs EC2-equivalent | **~70% reduction** |
| Infrastructure setup | One-command via Terraform |

- Provisioned complete AWS infrastructure (Lambda, API Gateway, SNS, SQS, DynamoDB, IAM) using Terraform — eliminated all manual console deployments
- Applied IAM least-privilege policies per Lambda function via Terraform resource blocks
- Dead-letter queue (DLQ) implementation ensures zero message loss across all failure scenarios

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/serverless-notification-system)

---

### 🔷 CloudCart — Container-Native E-Commerce Deployment Pipeline
> `Node.js` · `Express` · `MongoDB` · `Docker` · `NGINX` · `Docker Compose` · `GitHub Actions` · `Linux`

Production-grade containerized e-commerce platform with full dev/prod parity.

| Metric | Result |
|---|---|
| Docker image size | Reduced **~40%** (multi-stage builds) |
| Developer onboarding | 60 min → **under 5 min** |
| Request throughput | **~2×** improvement (k6, 500 concurrent users) |
| Environment bugs | **100% eliminated** across dev/staging/prod |

- Multi-stage Docker builds + NGINX reverse proxy with upstream load balancing
- Docker Compose orchestration with service dependency graph (App → MongoDB → NGINX)
- Structured for CI/CD readiness — reproducible builds deployable on any Linux host

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/Ecommerce-web)

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| 🏅 Google Cloud Associate Cloud Engineer | Google Cloud | ✅ Certified |
| 🏅 AWS Certified Cloud Practitioner (CLF-C02) | AWS | ✅ Certified |
| 🏅 Alibaba Cloud Certified Developer | Alibaba Cloud | ✅ Certified |
| 🔄 HashiCorp Terraform Associate | HashiCorp | In Progress |

---

## Research & Publications

📄 **Serverless Notification System (AWS)**  
*Presented at Com-It CON 2025 International Conference*
> Event-driven architecture using AWS Lambda, SNS, SQS, and DynamoDB with Terraform IaC for reproducible infrastructure provisioning.

---

## Education

🎓 **B.Tech — Computer Science Engineering**  
Manav Rachna International Institute of Research and Studies · 2023 – 2027

---

## GitHub Stats

<div align="center">

![Vanshit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=vanshitsharma18&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vanshitsharma18&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=vanshitsharma18&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Building scalable, automated, and production-ready infrastructure — one pipeline at a time.*

</div>
