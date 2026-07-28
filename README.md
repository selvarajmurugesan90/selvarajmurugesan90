<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Selvaraj%20Murugesan&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Senior%20DevSecOps%20and%20Cloud%20Engineer&descAlignY=55&descSize=18" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&width=800&height=120&lines=14%2B+Years+in+Cloud+and+Kubernetes+Engineering;GitOps+-+DevSecOps+-+AI+and+LLM+Infrastructure;Open+Source+Author+-+Klarity+v1.0.0)](https://github.com/selvarajmurugesan90)

<p align="center">
  <a href="https://www.linkedin.com/in/selvarajmurugesan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:selvarajmurugesan90@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://medium.com/@selvarajmurugesan90"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://github.com/selvarajmurugesan90/klarity"><img src="https://img.shields.io/badge/Klarity-Open%20Source-orange?style=for-the-badge&logo=kubernetes&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=selvarajmurugesan90&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS"/>
</p>

</div>

---

## About Me

Senior DevSecOps and Cloud Engineer with **14+ years of experience** managing cloud and on-premise environments across AWS, Azure, GCP, and OCI. Specializing in Kubernetes ecosystems, CI/CD automation, GitOps practices, and AI/LLM infrastructure — including MLOps pipelines, RAG-based applications, and multi-agent AI systems. Leveraging Generative AI tools such as **Claude Code** to accelerate development, automate infrastructure, and improve engineering productivity.

| Domain | Expertise |
|--------|-----------|
| **Kubernetes & Cloud** | EKS, AKS, GKE, OpenShift, ROSA, K3s, On-Prem — production cluster management, security hardening, scaling |
| **GitOps & CI/CD** | ArgoCD (App of Apps), Helm umbrella charts, Jenkins, Bamboo, GitLab CI, AWS CodePipeline |
| **AI / LLM Infrastructure** | LangGraph, LibreChat, Langfuse, NVIDIA NeMo Guardrails, ToolHive, MCP Servers, RAG pipelines with pgvector |
| **DevSecOps** | Trivy, OWASP ZAP, SonarQube, Prisma Cloud, Vault, Sealed Secrets, External Secrets Operator, cert-manager — author of [ops-engineering-skills](https://github.com/selvarajmurugesan90/ops-engineering-skills), an open-source AI agent skills library (296 skills, 22 domains) for DevOps, DevSecOps, and cloud engineering |
| **Observability** | Prometheus, VictoriaMetrics, Grafana, ELK Stack, FluentBit, Istio service mesh |
| **IaC** | Modular Terraform across AWS, Azure, GCP, OCI — Ansible for configuration management |
| **Open Source** | Author of [Klarity](https://github.com/selvarajmurugesan90/klarity) — enterprise Kubernetes observability for GitOps teams, and [ops-engineering-skills](https://github.com/selvarajmurugesan90/ops-engineering-skills) — a 296-skill, 22-domain AI agent skills library for DevOps, DevSecOps, and cloud engineering |

---

## Featured Project — Klarity

<div align="center">

[![Klarity](https://img.shields.io/badge/selvarajmurugesan90%2Fklarity-Enterprise%20Kubernetes%20Observability-0f172a?style=for-the-badge&logo=kubernetes&logoColor=60a5fa&labelColor=0f172a&color=1e3a5f)](https://github.com/selvarajmurugesan90/klarity)

</div>

<br/>

> **"Observe everything. Change nothing."**
>
> Klarity is an open-source, enterprise-grade Kubernetes observability dashboard built for teams that follow GitOps practices. Most dashboards let you edit resources directly — Klarity deliberately does not. In a proper GitOps workflow, your cluster's source of truth lives in Git, not a web form. Clicking "edit" in a dashboard bypasses your entire review, audit, and pipeline process.

<div align="center">

[![GitHub Stars](https://img.shields.io/badge/Stars-github-gold?style=flat-square&logo=github)](https://github.com/selvarajmurugesan90/klarity/stargazers)
[![Release](https://img.shields.io/badge/Release-v1.0.0-green?style=flat-square)](https://github.com/selvarajmurugesan90/klarity/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=flat-square)](https://github.com/selvarajmurugesan90/klarity/blob/main/LICENSE)
[![Go](https://img.shields.io/badge/Go-1.22-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/selvarajmurugesan90/klarity)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/selvarajmurugesan90/klarity)
[![Docker](https://img.shields.io/badge/Docker-GHCR-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/selvarajmurugesan90/klarity/pkgs/container/klarity)
[![Helm](https://img.shields.io/badge/Helm-Chart-0F1689?style=flat-square&logo=helm&logoColor=white)](https://selvarajmurugesan90.github.io/klarity)

</div>

**Key Capabilities:**

- Live CPU/Memory metrics at node and pod level with real-time visualizations and gauges
- Auto-discovers **62+ resource types** including CRDs — zero configuration required
- Web terminal (kubectl exec), live log streaming with severity filtering, and browser-based port forwarding
- Automatic GitOps integration — detects ArgoCD and Flux CD out of the box, zero config
- Global search across 10 resource types simultaneously with `Ctrl+K`
- Multi-auth: internal users (bcrypt + JWT), Kubernetes service account tokens, and OIDC
- Role-based access control: admin, editor, and viewer with account lockout protection
- Audit log with 2000-event ring buffer, cluster health reports, and warning event badges
- Single self-contained binary — Go backend + React frontend compiled into one Docker image

**Install with Helm:**

```bash
helm repo add klarity https://selvarajmurugesan90.github.io/klarity
helm repo update
helm upgrade --install klarity klarity/klarity --namespace klarity --create-namespace
```

<div align="center">

**[GitHub](https://github.com/selvarajmurugesan90/klarity)** &nbsp;·&nbsp; **[Website](https://selvarajmurugesan90.github.io/klarity)** &nbsp;·&nbsp; **[Read the Article](https://medium.com/@selvarajmurugesan90/klarity-the-enterprise-kubernetes-dashboard-built-for-the-gitops-era-272cc96f9ce6)** &nbsp;·&nbsp; **[Docker Image](https://github.com/selvarajmurugesan90/klarity/pkgs/container/klarity)**

</div>

---

## Other Projects

| Project | Description |
|---------|-------------|
| **Infrastructure as Code Templates** | Reusable Terraform modules for AWS, Azure, and GCP with security best practices and modular design |
| **Kubernetes Deployment Patterns** | Blue/Green, Canary, and A/B Testing strategies using ArgoCD, Helm, and Kubernetes custom resources |
| **MLOps Pipeline** | End-to-end pipeline using Kubeflow, MLflow, KServe, and Airflow for model training, versioning, and serving |
| **Observability Stack** | Full-stack monitoring using VictoriaMetrics, Prometheus, Grafana, FluentBit, and Elasticsearch |
| **Universal Database Operator** | Custom Kubernetes operator providing a unified interface for PostgreSQL, MySQL, and MongoDB management |

---

## Latest Blog Posts

- [**Klarity: The Enterprise Kubernetes Dashboard Built for the GitOps Era**](https://medium.com/@selvarajmurugesan90/klarity-the-enterprise-kubernetes-dashboard-built-for-the-gitops-era-272cc96f9ce6) — How I built an open-source enterprise Kubernetes observability dashboard designed around the GitOps philosophy.
- [**DevOps vs DevSecOps vs MLOps: Understanding the Evolution of Modern Software Delivery**](https://medium.com/@selvarajmurugesan90/devops-vs-devsecops-vs-mlops-understanding-the-evolution-of-modern-software-delivery-3548507273fb) — A comprehensive comparison of DevOps, DevSecOps, and MLOps methodologies with implementation strategies.
- [**Building a Universal Database Operator for Kubernetes**](https://medium.com/@selvarajmurugesan90/building-a-universal-database-operator-for-kubernetes-a-complete-guide-to-multi-database-55b4786fdfb2) — A complete guide to creating a universal database operator for managing multiple database types in Kubernetes.

---

## Technical Skills

### Cloud Platforms
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

### Container & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=red-hat-open-shift&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![Containerd](https://img.shields.io/badge/Containerd-575757?style=flat-square&logo=containerd&logoColor=white)
![Calico](https://img.shields.io/badge/Calico-FB8C00?style=flat-square&logoColor=white)

### CI/CD & GitOps
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Flux CD](https://img.shields.io/badge/Flux_CD-5468FF?style=flat-square&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Bamboo](https://img.shields.io/badge/Bamboo-0052CC?style=flat-square&logo=bamboo&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FCA121?style=flat-square&logo=gitlab&logoColor=white)
![AWS CodePipeline](https://img.shields.io/badge/CodePipeline-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-609926?style=flat-square&logo=gitea&logoColor=white)

### Infrastructure as Code
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

### AI / GenAI / LLM & MLOps
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-000000?style=flat-square&logoColor=white)
![LibreChat](https://img.shields.io/badge/LibreChat-4285F4?style=flat-square&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square&logoColor=white)
![NeMo Guardrails](https://img.shields.io/badge/NeMo_Guardrails-76B900?style=flat-square&logo=nvidia&logoColor=white)
![MCP Servers](https://img.shields.io/badge/MCP_Servers-D97757?style=flat-square&logo=anthropic&logoColor=white)
![KServe](https://img.shields.io/badge/KServe-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ModelMesh](https://img.shields.io/badge/ModelMesh-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Knative](https://img.shields.io/badge/Knative-0078D7?style=flat-square&logo=knative&logoColor=white)
![Kubeflow](https://img.shields.io/badge/Kubeflow-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)

### DevSecOps & Security
![Trivy](https://img.shields.io/badge/Trivy-2496ED?style=flat-square&logo=aqua-security&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Prisma Cloud](https://img.shields.io/badge/Prisma_Cloud-00ADEF?style=flat-square&logoColor=white)
![Sysdig](https://img.shields.io/badge/Sysdig_Secure-00B4C8?style=flat-square&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-000000?style=flat-square&logo=vault&logoColor=white)
![Sealed Secrets](https://img.shields.io/badge/Sealed_Secrets-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![External Secrets](https://img.shields.io/badge/External_Secrets-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![cert-manager](https://img.shields.io/badge/cert--manager-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Fortify](https://img.shields.io/badge/Fortify-003087?style=flat-square&logoColor=white)

### Observability & Logging
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-4285F4?style=flat-square&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![FluentBit](https://img.shields.io/badge/FluentBit-49BDA5?style=flat-square&logo=fluentd&logoColor=white)
![Graylog](https://img.shields.io/badge/Graylog-FF3633?style=flat-square&logo=graylog&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-008C99?style=flat-square&logo=new-relic&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logoColor=white)
![PRTG](https://img.shields.io/badge/PRTG-00A8E0?style=flat-square&logoColor=white)
![CheckMK](https://img.shields.io/badge/CheckMK-15D798?style=flat-square&logoColor=white)

### Data, Databases & Streaming
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=white)
![ArangoDB](https://img.shields.io/badge/ArangoDB-DDE072?style=flat-square&logo=arangodb&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazon-redshift&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)

### Workflow & Automation
![StackStorm](https://img.shields.io/badge/StackStorm-00ADEF?style=flat-square&logoColor=white)
![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

---

## GitHub Stats

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=selvarajmurugesan90&style=for-the-badge&color=0e75b6&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/selvarajmurugesan90?style=for-the-badge&logo=github&label=Followers&color=0e75b6)](https://github.com/selvarajmurugesan90?tab=followers)
[![GitHub User's stars](https://img.shields.io/github/stars/selvarajmurugesan90?style=for-the-badge&logo=github&label=Total+Stars&color=ffd700&affiliations=OWNER)](https://github.com/selvarajmurugesan90)

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=selvarajmurugesan90&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&fire=DD2727)](https://github.com/selvarajmurugesan90)

</div>

---

## Certifications

| Certification | Issuer |
|--------------|--------|
| AWS Solution Architect — Professional | Amazon Web Services |
| AWS Solution Architect — Associate | Amazon Web Services |
| AWS Cloud Practitioner | Amazon Web Services |
| Microsoft Azure Fundamentals | Microsoft |
| GitOps Fundamentals | Codefresh / CNCF |
| Trust & Inspire Leaders | FranklinCovey |

---

<div align="center">

**Open to collaborations, open-source contributions, and platform engineering discussions.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/selvarajmurugesan/)
[![Email](https://img.shields.io/badge/Email-selvarajmurugesan90%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:selvarajmurugesan90@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-%40selvarajmurugesan90-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@selvarajmurugesan90)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
