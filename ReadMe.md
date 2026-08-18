<div align="center">

# Harsh Pardhi

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=1000&color=1B3A6B&center=true&vCenter=true&width=820&lines=Azure+Cloud+%26+Automation+Engineer;Cloud+Operations+%C2%B7+Infrastructure+as+Code;Microsoft+365+%26+Power+Platform;Automate+the+manual+parts.+Keep+it+reliable.)](https://harsh-pardhi.vercel.app)

<br/>

![Experience](https://img.shields.io/badge/EXPERIENCE-2%2B_YEARS-1B3A6B?style=for-the-badge&labelColor=111C2E)
![Current](https://img.shields.io/badge/CURRENT-HEXAWARE_TECHNOLOGIES-2A5490?style=for-the-badge&labelColor=111C2E)
![Certified](https://img.shields.io/badge/CERTIFIED-AZ--104-1F8B3F?style=for-the-badge&labelColor=111C2E)
![Open to work](https://img.shields.io/badge/OPEN_TO-AZURE_%2F_DEVOPS_ROLES-4A7BC8?style=for-the-badge&labelColor=111C2E)

<br/>

<img src="hero-terminal.svg" alt="Harsh Pardhi — Azure Cloud & Automation Engineer" width="100%"/>

</div>

---

## About

Azure engineer at **Hexaware Technologies**, two years in, working across cloud operations, Microsoft 365 migrations and automation for enterprise clients. Most of my work follows one pattern: something is being done by hand, and it shouldn't be. I find it, script it with PowerShell or Python, and put the output somewhere people can act on it.

At work that has meant migrating **5,000+ users** of on-premises OneDrive data into **Microsoft 365** with ShareGate and PowerShell; deploying **StorageX Analytics** against a client's NetApp ONTAP estate and extracting data from **9 storage VMs across 2 clusters** into **10 Power BI reports** on data ownership and ACL exposure; moving **132 Power Apps and 50+ Power Automate flows** to a new tenant; and building **Transcend**, a Power App with a Copilot Studio agent that is now the transformation team's primary project management tool.

Outside work I build infrastructure projects to go deeper — **InfraGenie**, an AIOps platform for Azure, and a **two-region DR environment** in Terraform. **AZ-400** is next, in September.

<div align="center">

**📍 Gondia, Maharashtra · 🏢 Hexaware, Chennai · 🌏 Open to relocation & remote · ⏱ IST (UTC+5:30)**

</div>

---

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🤖 InfraGenie — AIOps Platform for Azure

A self-service platform for Azure infrastructure. An engineer describes what they need in plain English; the platform matches the request to a **reusable Terraform module** and runs policy checks before anything is applied.

After deployment it keeps watching the resource — it **remediates common failures on its own** and logs a **ServiceNow** ticket, so a problem is fixed and recorded rather than escalated at 2 a.m. A reporting agent publishes **10+ operational reports** on a schedule: FinOps spend, weekly digest, orphaned VMs.

> Development cost stayed at zero by running **Qwen2.5-Coder locally on Ollama in Docker** as the coding assistant. I architected the platform and wrote it against **SOLID principles** with structured prompt engineering, so every generated change stayed small and reviewable.

`Python` `Terraform` `Docker` `Ollama` `Qwen2.5-Coder` `ServiceNow`

[**→ Repository**](https://github.com/HP04Harsh/infragenie-aiops) · [**→ Hugging Face**](https://huggingface.co/HarshG05/InfraGenie-Azure-Expert)

</td>
<td width="50%" valign="top">

### 🛡️ Azure Multi-Region Disaster Recovery

A two-region, three-tier Azure environment built to answer one question: **if the primary region fails, how fast can the application come back?** Provisioned entirely in **Terraform** across Central and South India.

**VM Scale Sets** serve the web and application tiers, geo-replicated **Azure SQL** holds the data, and **Traffic Manager** with Load Balancers routes traffic between regions.

> Written as reusable modules with remote state and locking, using an **active/passive** topology so standby cost stayed proportionate to the recovery target instead of doubling the estate.

`Terraform` `Traffic Manager` `VM Scale Sets` `Azure SQL` `Azure Storage`

[**→ Repository**](https://github.com/HP04Harsh/azure-multi-region-dr-terraform)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ KubeScale-Ops — AKS Governance & FinOps

A learning lab for Kubernetes cost governance. **Kubecost and Prometheus** track spend and utilization across the cluster; manifests are GitOps-managed and validated on a **KinD** loop before they reach a real cluster.

Reusable **Terraform** modules with platform guardrails and workload validation for repeatable AKS delivery.

`AKS` `Terraform` `Kubecost` `Prometheus` `Helm` `GitOps`

[**→ Repository**](https://github.com/HP04Harsh/KubeScale-Ops)

</td>
<td width="50%" valign="top">

### 🔐 k8s-sec-observability

A Kubernetes policy and observability lab. **Kyverno** admission policies enforce image and resource rules, and **Grafana** dashboards sit over cluster metrics and traces.

Built to understand what "secure by default" actually costs to run and operate day to day.

`Kubernetes` `Kyverno` `Terraform` `Grafana` `Prometheus`

[**→ Repository**](https://github.com/HP04Harsh/k8s-sec-observability)

</td>
</tr>
</table>

---

## Toolbelt

| | |
| :--- | :--- |
| **Azure** | ![Azure](https://img.shields.io/badge/Microsoft_Azure-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Entra_ID-1B3A6B?style=flat-square&logo=microsoft&logoColor=white) ![VMSS](https://img.shields.io/badge/VM_Scale_Sets-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![VNet](https://img.shields.io/badge/VNet_·_NSG_·_Load_Balancer-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![Traffic Manager](https://img.shields.io/badge/Traffic_Manager-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure SQL](https://img.shields.io/badge/Azure_SQL-2A5490?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Key Vault](https://img.shields.io/badge/Key_Vault_·_RBAC-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) |
| **IaC & DevOps** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes_(AKS)-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Log Analytics](https://img.shields.io/badge/Log_Analytics_(KQL)-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Scripting** | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1B3A6B?style=flat-square&logo=postgresql&logoColor=white) ![Graph API](https://img.shields.io/badge/Microsoft_Graph_API-2A5490?style=flat-square&logo=microsoft&logoColor=white) |
| **Microsoft 365** | ![SharePoint](https://img.shields.io/badge/SharePoint_Online-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-1B3A6B?style=flat-square&logo=microsoft&logoColor=white) ![ShareGate](https://img.shields.io/badge/ShareGate-2A5490?style=flat-square&logo=microsoft&logoColor=white) |
| **AI & MLOps** | ![Azure AI Foundry](https://img.shields.io/badge/Azure_AI_Foundry-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure ML](https://img.shields.io/badge/Azure_ML-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-111C2E?style=flat-square&logo=ollama&logoColor=white) |
| **OS & Networking** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![Networking](https://img.shields.io/badge/DNS_·_TLS_·_Routing_·_Firewalls-2A5490?style=flat-square&logo=cloudflare&logoColor=white) |

---

## Certifications

| Certification | Issuer | Status |
| :--- | :--- | :--- |
| **Azure Administrator Associate (AZ-104)** | Microsoft | ✅ Aug 2026 |
| **DevOps Engineer Expert (AZ-400)** | Microsoft | 📅 Exam scheduled Sep 2026 |
| **Terraform Associate (004)** | HashiCorp | 🔄 In progress |

## Currently Building

- **AZ-400** — deepening pipelines, IaC, governance and release reliability. Exam in September.
- **Terraform Associate (004)** — module design, remote state and delivery patterns for repeatable Azure infrastructure.
- **InfraGenie hardening** — tighter policy checks and a clearer plan-diff review step before apply.
- **Production Kubernetes depth** — moving from project-scale AKS work toward cluster operations, upgrades and troubleshooting.

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=HP04Harsh&bg_color=ffffff&color=111C2E&line=1B3A6B&point=2A5490&area=true&area_color=4A7BC8&hide_border=true&custom_title=Contribution%20Activity" alt="Contribution graph" width="100%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=HP04Harsh&hide_border=true&background=ffffff&stroke=C9D2DE&ring=1B3A6B&fire=2A5490&currStreakLabel=111C2E&sideLabels=111C2E&currStreakNum=1B3A6B&sideNums=1B3A6B&dates=5A6472" alt="Commit streak" width="60%"/>

</div>

---

## Get in Touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-harsh--pardhi.vercel.app-1B3A6B?style=for-the-badge&logo=vercel&logoColor=white&labelColor=111C2E)](https://harsh-pardhi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-harsh--pardhi-2A5490?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=111C2E)](https://linkedin.com/in/harsh-pardhi)
[![Email](https://img.shields.io/badge/Email-harshpardhi477@gmail.com-4A7BC8?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111C2E)](mailto:harshpardhi477@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-1F8B3F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=111C2E)](https://harsh-pardhi.vercel.app/Harsh_Pardhi_Resume.pdf)

<br/>

*Automate the manual parts. Keep it reliable.*

</div>
