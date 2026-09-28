<h1 align="center">Hi, I'm Nixon Varghese 👋</h1>
<h3 align="center">Senior DevOps & Cloud Engineer · Platform Engineering · SRE · DevSecOps · Kubernetes</h3>

<p align="center">
  <a href="https://linkedin.com/in/nixon-varghese"><img src="https://img.shields.io/badge/LinkedIn-nixon--varghese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@nixonv"><img src="https://img.shields.io/badge/Medium-@nixonv-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="mailto:nixvarghese01@gmail.com"><img src="https://img.shields.io/badge/Email-nixvarghese01%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🚀 About me

- 🧭 **11+ years in IT**, including **8+ years in DevOps**, spanning operations, project delivery and platform engineering across **Azure, AWS and on-prem Kubernetes**
- 🏛️ Currently a **Senior DevOps Engineer at the Ministry of Human Resources and Emiratisation (MOHRE)** in Dubai. I lead DevSecOps practices for its digital projects.
- 🤖 I build **AI platform infrastructure**: GPU-enabled Kubernetes clusters, CI/CD for on-prem model deployment, and integration with Core42 AI APIs
- 🔐 I focus on **secure delivery**: HashiCorp Vault, GitOps with ArgoCD, and shift-left scanning with SonarQube, Fortify, Gitleaks, Trivy and OWASP ZAP
- 📍 Based in **Dubai, UAE**

## 🧩 Platform engineering: an internal developer platform on Backstage

At **Core42** I helped build an **internal developer platform (IDP) on Spotify Backstage**. It gives developers one self-service **golden path** that takes them from an idea to running code in a dev environment:

```
 Pick a project      Choose infra      Approval      Infra repo          App repo + CI/CD      Deploy
 template in    -->  configuration -->  workflow -->  (Terraform /   -->  skeleton, sample  -->  to Dev
 Backstage           (sizing)                         Terragrunt)         code
```

1. **Self-service start:** the developer picks a project template in Backstage.
2. **Infra configuration:** they choose a rough infrastructure profile, such as size, environment and components.
3. **Governed approval:** the request goes through an approval step before anything is provisioned.
4. **Infrastructure as code:** an infra repo is generated with **Terraform and Terragrunt** modules and applied to **Azure**.
5. **Application scaffold:** an application repo is created with sample code and a ready-to-use **CI/CD pipeline skeleton**.
6. **First deploy:** the app is built and deployed to the **dev environment** automatically.

Behind the portal I built **Python APIs integrating with Azure Graph APIs** and connected them to the Terraform/Terragrunt layer, so the portal, identity, approvals and IaC work together as one automated workflow.

**Result:** developers get a governed environment and a deployable app from a single request, without raising infra tickets or wiring pipelines by hand.

**Scale:** our platform team ran this across **130+ Azure subscriptions**. The estate included:
- **AKS clusters** provisioned with Terraform/Terragrunt and bootstrapped with the required platform components
- **User-assigned managed identities** for secure, secretless access from workloads and pipelines
- **Argo CD** GitOps for deployments across environments
- An **automated GitLab-to-GitHub migration of 100+ repositories and their CI/CD pipelines**, converted to GitHub Actions. We used **custom Python scripts (GitLab and GitHub APIs)** together with **GitHub Actions Importer**, picking the approach case by case for each repo and pipeline

## 💼 Experience

| Role | Company | Period | Highlights |
|---|---|---|---|
| **Senior DevOps Engineer** (IT Consultant) | Ministry of Human Resources & Emiratisation, Dubai | 2026 – present | Leads DevSecOps; GPU Kubernetes for on-prem AI models; Vault rollout; ArgoCD GitOps; Harbor and VMware Tanzu delivery; reusable CI/CD and security templates for Angular, React, .NET, mobile and Python AI apps |
| **DevOps & Cloud Engineer** (Consultant) | Core42, Abu Dhabi | 2025 | Platform team managing **130+ Azure subscriptions**; AKS clusters with required platform components and user-assigned managed identities, built with Terraform and Terragrunt; Argo CD GitOps; **automated GitLab-to-GitHub migration of 100+ repos and pipelines** to GitHub Actions; Helm migrations; legacy-to-Kubernetes migrations; **Backstage IDP** with self-service infra and app scaffolding, from request through approval to a Dev deploy; Python and Azure Graph API integration; Kaniko and JFrog pipelines |
| **Technical Lead, DevSecOps** | Wipro (client: US Bank), Bangalore | 2023 – 2024 | **SRE and reliability:** set up **alerting for both infrastructure and applications**. For applications, worked with the developers to define a standard set of failure error codes and built **Splunk** dashboards and alerts on them, so failures could be detected and triaged quickly. For infrastructure, set up **SignalFx** monitoring and alert notifications. Handled production support, incident response and release management. **Cut MTTD by 30% and MTTR by 40%.** **Modernisation:** defined and designed **Azure Data Factory** workflows for the batch-job migration, including the proof of concept, and migrated legacy **Autosys** scheduling onto them, with **Azure Functions** for custom steps. Also migrated on-prem apps to Azure VMs and AKS, and cut deployment time 20% with automated pipelines. Worked across several projects. Won Wipro's Inspiring Performance Award |
| **Senior Systems Engineer, DevOps** | QC Infotech, Dubai | 2015 – 2023 | CI/CD with Jenkins and DevSecOps for React and Java e-commerce; Docker and Kubernetes; cloud cost automation with Python and Boto3; FileCatalyst SaaS on AWS and Azure with Terraform; pre-sales POCs |

## 🏅 Certifications

![CKS](https://img.shields.io/badge/CKS-Certified_Kubernetes_Security_Specialist-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![CKA](https://img.shields.io/badge/CKA-Certified_Kubernetes_Administrator-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS DOP](https://img.shields.io/badge/AWS-DevOps_Engineer_Professional-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AZ-400](https://img.shields.io/badge/AZ--400-DevOps_Engineer_Expert-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104-Azure_Administrator-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-Full_Stack_Observability-1CE783?style=flat-square&logo=newrelic&logoColor=black)

Also: MCSE · ITIL v3 Foundation · Oracle Cloud Foundations · FileCatalyst Certified Admin

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Cloud** | Azure (AKS, App Service, Functions, Data Factory, Key Vault, VNet) · AWS (EKS, EC2, Lambda, VPC, IAM, S3, CloudWatch, Route 53, KMS) |
| **Kubernetes** | AKS · EKS · GKE · VMware Tanzu · Rancher · Helm · Kustomize · GPU workloads |
| **Platform engineering** | Spotify Backstage (IDP, software templates) · golden paths · self-service infrastructure |
| **IaC & GitOps** | Terraform · Terragrunt · Ansible · ArgoCD |
| **CI/CD** | GitHub Actions · GitLab CI · Azure DevOps · Jenkins · Harbor · JFrog Artifactory |
| **Containers** | Docker · Podman · Kaniko |
| **DevSecOps** | HashiCorp Vault · SonarQube · Fortify · Black Duck · Trivy · Twistlock · Gitleaks · Spectral · OWASP ZAP · Kyverno |
| **Observability** | Prometheus · Grafana · Splunk · SignalFx · New Relic · ELK/EFK · OpenTelemetry |
| **Languages** | Python (Boto3) · Bash · Go (basics) |

<p>
  <img src="https://skillicons.dev/icons?i=azure,aws,gcp,kubernetes,docker,terraform,ansible,githubactions,gitlab,jenkins,prometheus,grafana,python,bash,linux&perline=15" alt="skills"/>
</p>

## 📂 Featured projects

| Project | What it shows |
|---|---|
| [coit-simple-micro-GA](https://github.com/nixvarghese01/coit-simple-micro-GA) | Three-tier microservices (React, Spring Boot, Flask) with GitHub Actions CI/CD to **GKE**, Kustomize overlays, SonarQube, cert-manager and HPA |
| [coit-frontend-devsecops](https://github.com/nixvarghese01/coit-frontend-devsecops) | Hardened images plus **Kyverno** policies: signed images, registry allow-lists, label enforcement |
| [ecs-stateless-nginx](https://github.com/nixvarghese01/ecs-stateless-nginx) | **Terraform**: highly available ECS Fargate behind an ALB across two AZs, with a diagram-as-code architecture diagram |
| [observability](https://github.com/nixvarghese01/observability) | Go Prometheus metrics app and an **OpenTelemetry Collector** on Kubernetes, with Go CI |
| [tanzu-devslam-spring-](https://github.com/nixvarghese01/tanzu-devslam-spring-) | Spring Boot to Buildpacks to GHCR to **VMware Tanzu** |

## ✍️ Writing

- [Most commonly used AWS CLI commands asked in AWS DevOps interviews](https://medium.com/@nixonv/most-commonly-used-aws-cli-commands-asked-in-aws-devops-interviews-f00c80d6e297)
- [Secure File Transfers in the Cloud-Driven World: A Guide to Managed File Transfer Solutions](https://medium.com/@nixonv/managed-file-transfer-solutions-navigating-the-cloud-controlled-era-3ba84e3d1abb)
- [Navigating the CDN Landscape: Cost-Effective Options for Content Delivery](https://medium.com/@nixonv/navigating-the-cdn-landscape-cost-effective-options-for-content-delivery-60bac8ed0bfc)

---

<p align="center"><i>Open to conversations about platform engineering, DevSecOps and AI infrastructure. Reach out on LinkedIn.</i></p>
