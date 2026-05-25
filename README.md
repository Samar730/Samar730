<div align="center">

# Hi, I'm Samar 👋

**DevOps Engineer | AWS · Kubernetes · Terraform · CI/CD**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)

---

## About Me

I'm a DevOps engineer specialising in cloud-native infrastructure on AWS, with a focus on infrastructure as code, container orchestration and automated delivery pipelines. I build environments that are reliable, scalable and fully automated — from provisioning to production.

---

## Tech Stack

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![CertManager](https://img.shields.io/badge/CertManager-003EFF?style=for-the-badge&logo=letsencrypt&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Projects

### [EKS GitOps Platform — Production-Grade Kubernetes on AWS](https://github.com/Samar730/EKS-GitOps-Project)

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat&logo=amazonrds&logoColor=white)
![Secrets Manager](https://img.shields.io/badge/Secrets_Manager-DD344C?style=flat&logo=amazonaws&logoColor=white)

A production-grade Kubernetes platform on AWS EKS hosting a self-hosted Memos note-taking application. Infrastructure provisioned with modular Terraform, cluster tooling managed via Helmfile and application delivery handled through a GitOps workflow using ArgoCD.

🔹 **GitOps delivery with ArgoCD** — cluster state always reflects Git

🔹 **Automated DNS and TLS** via ExternalDNS and CertManager

🔹 **AWS Secrets Manager integration** via External Secrets Operator

🔹 **Full observability** with Prometheus and Grafana

🔹 **5 GitHub Actions pipelines** with OIDC — zero static credentials

🔹 **RDS PostgreSQL** as the managed database backend in private subnets

🔹 **AWS Secrets Manager** storing sensitive credentials, injected into pods via ESO

🔹 **Grype image scanning and Checkov IaC scanning** baked into CI

---

### [Gatus Monitoring — ECS Project](https://github.com/Samar730/ecs-gatus-monitoring)

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

A live endpoint monitoring platform running at [status.cloudbysamar.com](https://status.cloudbysamar.com) built with Gatus on ECS Fargate. Fully automated from infrastructure provisioning to container deployment with zero manual steps.

🔹 **Modular Terraform** across 7 modules: VPC, SG, IAM, ALB, ACM, Route53, ECS

🔹 **Multi-stage Docker build** deployed on ECS Fargate

🔹 **GitHub Actions CI/CD** with OIDC, Grype scanning and Checkov validation

🔹 **ALB with ACM-managed HTTPS** and HTTP to HTTPS redirect

🔹 **Commit SHA image tagging** for full deployment traceability

🔹 **Automated deployment** with no manual infrastructure steps

🔹 **OIDC federation** between GitHub Actions and AWS — no static credentials

---
