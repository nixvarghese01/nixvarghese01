<h1 align="center">Hi, I'm Nixon Varghese 👋</h1>
<h3 align="center">Senior DevOps & Cloud Engineer · Platform Engineering · SRE · DevSecOps</h3>

<p align="center">
  <a href="https://linkedin.com/in/nixon-varghese"><img src="https://img.shields.io/badge/LinkedIn-nixon--varghese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@nixonv"><img src="https://img.shields.io/badge/Medium-@nixonv-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="mailto:nixvarghese01@gmail.com"><img src="https://img.shields.io/badge/Email-nixvarghese01%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

I build **internal developer platforms, secure delivery pipelines and Kubernetes platforms** across Azure, AWS and on-prem. I have **11+ years in IT and 8+ in DevOps**, starting in pre-sales and customer-facing engineering. I'm based in Dubai.

- 🧩 **Platform engineering:** built a Backstage IDP that runs one golden path from a template, through an approval, to infra and app repos, and on to a Dev deploy
- ☸️ **Scale:** part of a team running **130+ Azure subscriptions** with AKS, managed identities and Argo CD; **automated the migration of 100+ repos and pipelines** from GitLab to GitHub
- 🔐 **DevSecOps:** end-to-end **HashiCorp Vault** (Raft high availability, auto-unseal, Kubernetes, AppRole and OIDC auth, Agent Injector and CSI) plus shift-left scanning in templated CI/CD
- 📉 **SRE:** Splunk and SignalFx alerting for applications and infrastructure; **MTTD cut 30%, MTTR cut 40%**
- 🤖 **AI infrastructure:** GPU-enabled Kubernetes and CI/CD for on-prem model deployment

## 🧩 Golden path I've built

```
Backstage template → infra sizing → approval → infra repo (Terraform/Terragrunt → Azure) → app repo + CI/CD skeleton → deploy to Dev
```
Developers get a governed environment and a deployable app from one request, with no infra tickets. The backend is Python APIs integrating with Azure Graph APIs.

## 💼 Experience

- **Senior DevOps Engineer** · Government sector, Dubai · *2026 – now*: DevSecOps lead; templated Azure DevOps CI/CD for APIs, CMS, web and mobile apps; Vault; Argo CD; Harbor + Tanzu; GPU Kubernetes
- **DevOps & Cloud Engineer** · Core42, Abu Dhabi · *2025*: Backstage IDP, 130+ subscriptions, AKS, Terraform/Terragrunt, GitLab → GitHub migration
- **Technical Lead, DevSecOps** · Wipro (US Bank) · *2023–24*: Azure/AKS migrations, Autosys → Azure Data Factory, Splunk/SignalFx SRE; Inspiring Performance Award
- **Senior Systems Engineer, DevOps** · QC Infotech, Dubai · *2015–23*
  - **DevSecOps:** Jenkins CI/CD with security best practices for React and Java e-commerce apps; Docker and Kubernetes; Terraform; Boto3 cost automation
  - **Storage and backup:** NAS, on-prem and cloud object storage, tiered storage, tape, backup software
  - **File transfer:** accelerated UDP-based transfer (FileCatalyst SaaS on AWS and Azure)
  - **Pre-sales:** RFP responses, demos and POCs

## 🏅 Certifications

![CKS](https://img.shields.io/badge/CKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![CKA](https://img.shields.io/badge/CKA-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS DevOps Pro](https://img.shields.io/badge/AWS_DevOps_Engineer_Professional-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AZ-400](https://img.shields.io/badge/AZ--400_DevOps_Expert-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104_Azure_Admin-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic_Observability-1CE783?style=flat-square&logo=newrelic&logoColor=black)

## 🛠️ Stack

<img src="https://skillicons.dev/icons?i=azure,aws,kubernetes,docker,terraform,ansible,githubactions,gitlab,jenkins,prometheus,grafana,python,bash,linux&perline=14" alt="skills"/>

| Area | Tools |
|---|---|
| **Azure** | VMs · App Service · Blob Storage · Functions · AKS · VNet · Load Balancer · Key Vault · Data Factory · Azure DevOps |
| **AWS** | EC2 · S3 · VPC · IAM · Lambda · CloudWatch · EKS · Auto Scaling · CloudTrail · Route 53 · EBS · EFS · KMS |
| **Kubernetes** | AKS · EKS · VMware Tanzu · Rancher · Helm · Kustomize · Argo CD |
| **IaC and platform** | Terraform · Terragrunt · Ansible · Backstage |
| **CI/CD** | Azure DevOps (cloud and on-prem) · GitHub Actions · GitLab CI · Jenkins · Harbor · JFrog Artifactory |
| **Containers** | Docker · Podman · Kaniko |
| **Security** | SonarQube · Fortify · Black Duck · Synopsys · Trivy · Twistlock · Gitleaks · Spectral · OWASP ZAP |
| **Secrets** | HashiCorp Vault · Azure Key Vault · AWS Secrets Manager |
| **Observability** | Splunk · SignalFx · New Relic · Prometheus · Grafana · ELK/EFK |
| **Storage and backup** | NAS · object storage (on-prem and cloud) · tiered storage · tape · backup software · UDP file transfer (FileCatalyst) |
| **SCM and build** | Git · GitHub · GitLab · Maven · npm |
| **Languages and OS** | Python · Bash · Linux · Windows |
| **ITSM and collaboration** | Jira · ServiceNow · Confluence · Slack · Microsoft Teams · Zoom |

## 📂 Projects

- [coit-simple-micro-GA](https://github.com/nixvarghese01/coit-simple-micro-GA): three-tier microservices on GKE with GitHub Actions, Kustomize and SonarQube
- [coit-frontend-devsecops](https://github.com/nixvarghese01/coit-frontend-devsecops): hardened images and Kyverno policies (signed images, registry allow-lists)
- [ecs-stateless-nginx](https://github.com/nixvarghese01/ecs-stateless-nginx): Terraform for highly available ECS Fargate behind an ALB, with a diagram-as-code
- [observability](https://github.com/nixvarghese01/observability): Prometheus sample app and OpenTelemetry Collector on Kubernetes

## ✍️ Writing

[AWS CLI commands for DevOps interviews](https://medium.com/@nixonv/most-commonly-used-aws-cli-commands-asked-in-aws-devops-interviews-f00c80d6e297) · [Managed file transfer in the cloud](https://medium.com/@nixonv/managed-file-transfer-solutions-navigating-the-cloud-controlled-era-3ba84e3d1abb) · [Cost-effective CDN options](https://medium.com/@nixonv/navigating-the-cdn-landscape-cost-effective-options-for-content-delivery-60bac8ed0bfc)
