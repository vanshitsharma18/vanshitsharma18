
<!-- ══════════════════════════════════════════════════════════════ -->
<!--                    VANSHIT SHARMA · GITHUB PROFILE            -->
<!-- ══════════════════════════════════════════════════════════════ -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=C8FF00&background=00000000&center=true&vCenter=true&multiline=true&width=620&height=90&lines=Vanshit+Sharma+%2F+DevOps+%26+Cloud+Engineer;Terraform+%7C+Kubernetes+%7C+GCP+%7C+AWS;Building+infrastructure+that+scales.)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vanshit--sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanshit-sharma/)
[![Gmail](https://img.shields.io/badge/Gmail-vanshitsharma2006-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vanshitsharma2006@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vanshitsharma18-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18)
[![Location](https://img.shields.io/badge/📍_New_Delhi-India-C8FF00?style=for-the-badge&logoColor=black)](https://github.com/vanshitsharma18)

</div>

<br/>

---

## `$ cat profile.yaml`

```yaml
# ──────────────────────────────────────────────────────────────────
# vanshit-sharma / profile.yaml
# ──────────────────────────────────────────────────────────────────

apiVersion: engineer/v1
kind: DevOpsEngineer

metadata:
  name: Vanshit Sharma
  location: New Delhi, India
  status: open-to-opportunities        # 🟢 actively looking

spec:
  role:
    - Junior DevOps Engineer
    - Cloud Engineer (GCP Certified)

  education:
    degree: B.Tech · Computer Science Engineering
    institute: Manav Rachna International Institute of Research and Studies
    duration: 2023 → 2027

  specializations:
    - Infrastructure as Code          # Terraform & Terragrunt
    - GitOps & CI/CD Automation       # GitHub Actions + ArgoCD on GKE Autopilot
    - DevSecOps                       # Trivy CVE scanning, IAM least-privilege, DLQ
    - Multi-Environment Cloud Infra   # GCP · AWS · Alibaba Cloud
    - Observability                   # Prometheus · Grafana · Alertmanager · Loki

  impact:
    deployment_time_reduction: "82%   (45 min → 8 min)"
    concurrent_requests_handled: 10_000
    infrastructure_cost_reduction: "~70% vs EC2-equivalent"
    config_drift_incidents: 0
    unauthorized_deployments: 0

  publication:
    title: "Serverless Notification System (AWS)"
    venue: Com-IT CON 2025 International Conference
    status: published ✅
```

---

## `$ terraform plan` — Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                  VANSHIT'S CI/CD ARCHITECTURE                   │
├────────────────┬────────────────┬───────────────────────────────┤
│   SOURCE       │   CI PIPELINE  │   CD + INFRA                  │
│  ─────────     │  ────────────  │  ───────────                  │
│  Git Push      │  GitHub        │  ArgoCD (GitOps)              │
│  PR Review     │  Actions       │  GKE Autopilot                │
│  Merge         │  ↓             │  Helm Charts                  │
│                │  Build Image   │  Terraform IaC                │
│                │  Trivy Scan ◀─── Block HIGH/CRITICAL CVEs      │
│                │  Push to       │  Terragrunt (DRY)             │
│                │  Artifact Reg  │  Remote State (GCS)           │
│                │  Unit Tests    │  WIF (keyless auth)           │
├────────────────┴────────────────┴───────────────────────────────┤
│   OBSERVABILITY: Prometheus · Grafana · Alertmanager · Loki     │
│   SECURITY:      IAP · IAM Least-Privilege · Trivy · WIF        │
└─────────────────────────────────────────────────────────────────┘
```

---

## `$ kubectl get skills --all-namespaces`

#### ☁️ Cloud Platforms
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Alibaba Cloud](https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=flat-square&logo=alibabacloud&logoColor=white)

#### 🐳 Containers & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GKE Autopilot](https://img.shields.io/badge/GKE_Autopilot-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

#### ⚙️ CI/CD & GitOps
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

#### 🏗️ Infrastructure as Code
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)

#### 📊 Monitoring, Observability & Security
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy_(DevSecOps)-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)
![GCloud Monitoring](https://img.shields.io/badge/Cloud_Monitoring-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

#### 💻 Languages & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## `$ terraform apply` — Projects

### 🏗️ GCP Incident Management Platform · Multi-Environment IaC

> `Terraform` · `Terragrunt` · `Cloud Run` · `Firestore` · `IAP` · `WIF` · `GitHub Actions` · `GCS`

Architected **multi-environment (dev/stage/prod)** GCP infrastructure using Terraform + Terragrunt across **7 reusable DRY modules** — provisioning Cloud Run services, Firestore, VPC, and a Google-managed HTTPS load balancer from a single codebase.

| What | How |
|---|---|
| **Keyless GCP auth** | Workload Identity Federation — eliminated all long-lived credentials |
| **Zero-trust access** | Identity-Aware Proxy (IAP) for OAuth 2.0 access control |
| **State management** | Remote state in GCS with state locking + IAM least-privilege per environment |
| **Reusability** | 7 Terraform modules, 3 identical environments from 1 codebase |

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18)

---

### 🚀 GitOps Kubernetes Deployment Pipeline · GKE Autopilot

> `GitHub Actions` · `GKE Autopilot` · `ArgoCD` · `Helm` · `Prometheus` · `Grafana` · `Trivy` · `Docker`

End-to-end GitOps platform — GitHub Actions handles CI, ArgoCD drives CD with declarative Git reconciliation. Trivy blocks vulnerabilities before they reach staging.

| Metric | Before | After |
|---|---|---|
| Deployment cycle | 45 min | **8 min** *(82% faster)* |
| Config drift incidents | 4 / sprint | **0** |
| Pre-deploy CVE blocking | None | **100% HIGH/CRITICAL** |
| Prometheus alert rules | — | **8 custom rules** across envs |
| p95 latency under load | — | **sub-200ms** (GKE Autopilot auto-scale) |

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/todo-app-deployment)

---

### ⚡ Serverless Notification System · AWS Event-Driven Architecture

> `Terraform` · `AWS Lambda` · `API Gateway` · `SNS` · `SQS` · `DynamoDB` · `IAM`

Fully Terraform-provisioned event-driven fan-out system on AWS. Architecture and IaC design **published at Com-IT CON 2025 International Conference**.

| Metric | Result |
|---|---|
| Concurrent requests | **10,000 at < 200ms avg latency** |
| Message loss | **Zero** — Dead Letter Queues on every failure path |
| Cost vs EC2-equivalent | **~70% reduction** via managed auto-scaling |
| Infra setup | **One command** — `terraform apply` |

- IAM least-privilege applied **per Lambda function** via Terraform resource blocks — eliminated over-permissioned service accounts
- DLQ integration catches every failure scenario; zero messages ever lost

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/serverless-notification-system)

---

### 🛒 CloudCart · Container-Native E-Commerce Pipeline

> `Node.js` · `Express` · `MongoDB` · `Docker` · `NGINX` · `Docker Compose` · `GitHub Actions` · `Linux`

Production-grade containerized platform with full dev/prod environment parity.

| Metric | Before | After |
|---|---|---|
| Docker image size | Baseline | **~40% smaller** (multi-stage builds) |
| Dev onboarding time | 60 min | **< 5 min** |
| Request throughput | Baseline | **~2× improvement** (k6, 500 concurrent users) |
| Environment-specific bugs | Present | **100% eliminated** |

- NGINX reverse proxy with upstream load balancing + Docker Compose service dependency graph
- Reproducible builds — deployable on any Linux host with `docker compose up`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshitsharma18/Ecommerce-web)

---

## `$ cat experience.log`

```
[Jun 2025 → Jul 2025]  NextGenya Solutions, Noida
Role     : DevOps & Automation Intern
Stack    : Azure DevOps · ServiceNow · CI/CD · REST APIs · Flow Designer

✔  Integrated Azure DevOps CI/CD pipelines for ServiceNow change requests
   → -30% manual release coordination | 0 unauthorized deployments

✔  Built REST APIs to sync deployment & incident data across tooling
   → ~25% faster incident response | ~15% fewer repetitive ops tasks
```

---

## `$ cat certifications.json`

```json
{
  "certifications": [
    {
      "name": "Associate Cloud Engineer",
      "issuer": "Google Cloud Platform",
      "status": "✅ Certified",
      "badge": "GCP"
    },
    {
      "name": "Certified Cloud Practitioner (CLF-C02)",
      "issuer": "Amazon Web Services",
      "status": "✅ Certified",
      "badge": "AWS"
    },
    {
      "name": "Cloud Certified Developer",
      "issuer": "Alibaba Cloud",
      "status": "✅ Certified",
      "badge": "ALI"
    },
    {
      "name": "Terraform Associate",
      "issuer": "HashiCorp",
      "status": "⏳ In Progress",
      "badge": "HCP"
    }
  ]
}
```

---

## `$ cat publications.md`

📄 **Serverless Notification System (AWS)**
*Presented & Published — Com-IT CON 2025 International Conference*

> Designed and implemented an event-driven fan-out notification architecture using AWS Lambda, SNS, SQS, and DynamoDB — fully provisioned with Terraform IaC for reproducible, one-command deployments. Demonstrated ~70% cost reduction vs. equivalent EC2-based architecture.

---

## `$ neofetch --stats`

<div align="center">

![Vanshit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=vanshitsharma18&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true&bg_color=030303&title_color=C8FF00&icon_color=C8FF00&text_color=a0a0a0)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vanshitsharma18&layout=compact&theme=chartreuse-dark&hide_border=true&langs_count=8&bg_color=030303&title_color=C8FF00&text_color=a0a0a0)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=vanshitsharma18&theme=chartreuse-dark&hide_border=true&background=030303&ring=C8FF00&fire=C8FF00&currStreakLabel=C8FF00)

</div>

---

## `$ make contact`

```makefile
.PHONY: email linkedin github call

email:
	@open "mailto:vanshitsharma2006@gmail.com"
	# → vanshitsharma2006@gmail.com

linkedin:
	@open "https://linkedin.com/in/vanshit-sharma"
	# → linkedin.com/in/vanshit-sharma

github:
	@open "https://github.com/vanshitsharma18"
	# → github.com/vanshitsharma18

call:
	@echo "+91 8595434717"
```

---

<div align="center">

```
╔════════════════════════════════════════════════════════════╗
║                                                            ║
║   Infrastructure as Code. GitOps by default.              ║
║   Security baked in — not bolted on.                       ║
║                                                            ║
║   $ terraform apply --target=opportunities                 ║
║   Apply complete! Resources: 1 job_offer added.            ║
║                                                            ║
╚════════════════════════════════════════════════════════════╝
```

![Profile Views](https://komarev.com/ghpvc/?username=vanshitsharma18&color=C8FF00&style=flat-square&label=profile+views)

</div>
