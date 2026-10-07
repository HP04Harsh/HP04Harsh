<div align="center">

# Harsh Pardhi

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=1000&color=1B3A6B&center=true&vCenter=true&width=820&lines=Applied+AI+Engineer+%7C+Azure+%26+AKS;Agentic+AI+%C2%B7+MCP+%C2%B7+Terraform+%C2%B7+RAG;Automate+the+manual+parts.+Build+agents+that+scale.)](https://harsh-pardhi.vercel.app)

<br/>

![Experience](https://img.shields.io/badge/EXPERIENCE-2%2B_YEARS-1B3A6B?style=for-the-badge&labelColor=111C2E)
![Current](https://img.shields.io/badge/CURRENT-Software_Engineer_%40_Hexaware-2A5490?style=for-the-badge&labelColor=111C2E)
![Focus](https://img.shields.io/badge/FOCUS-Agentic_AI_%7C_RAG_%7C_AKS-4A7BC8?style=for-the-badge&labelColor=111C2E)
![AZ-104](https://img.shields.io/badge/AZ--104-CERTIFIED-1F8B3F?style=for-the-badge&labelColor=111C2E)
![AI-103](https://img.shields.io/badge/AI--103-NEXT-4A7BC8?style=for-the-badge&labelColor=111C2E)

<br/>

<img src="hero-terminal15222.svg" alt="Harsh Pardhi — Applied AI Engineer" width="100%"/>

</div>

---

## About

Cloud and AI engineer at **Hexaware Technologies**, two years in — building automation, enterprise Copilots, and GenAI agents on Azure.

My work follows one pattern: something is being done by hand — a migration, a permissions audit, a report rebuilt every Monday, a ticket queue at 2 a.m. — and it shouldn't be. I find it, script it in **PowerShell** or **Python**, and these days I wire it through an **AI agent** instead of only a cron job.

At work that has meant migrating **5,000+ users** of on-premises OneDrive data to **Microsoft 365** with ShareGate and PowerShell (overnight cutovers running unsupervised); deploying **StorageX Analytics** against **9 storage VMs across 2 clusters** into **10 Power BI reports** the client formally thanked us for; migrating **132 Power Apps and 50+ Power Automate flows** across 4 tenants; building **Transcend**, a Power App with a Copilot Studio agent that now runs 20+ projects; and delivering a **Terraform landing zone POC** for a client evaluation. On the same engagements I deployed **three production Copilot Studio agents** — an L1 support agent and a PMO assistant — grounded in internal SharePoint FAQs, wired to ticketing, live across all four tenants.

Outside work I build to go deeper: **InfraGenie**, an AIOps platform for Azure that uses a local LLM (Qwen2.5-Coder on Ollama in Docker) with structured prompts and self-remediation loops; a **two-region DR environment** in Terraform; and labs on **AKS GitOps**, **policy enforcement**, and observability.

Right now I'm building on the GenAI side: agentic workflows with **LangGraph**, **Model Context Protocol (MCP)**, **RAG** on **Azure AI Search**, **LLMOps** observability, and deploying AI workloads on **AKS**.

<div align="center">

**📍 Gondia, Maharashtra · 🏢 Hexaware, Chennai · 🌏 Open to Applied AI / GenAI Engineer roles · ⏱ IST (UTC+5:30)**

</div>

---

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🤖 InfraGenie — AIOps Platform for Azure

A self-service platform for Azure infrastructure. Engineers describe what they need in plain English; the platform matches the request to a reusable **Terraform** module and runs policy checks before anything is applied.

After deployment it keeps watching — it **remediates common failures on its own** and logs a **ServiceNow** ticket. A reporting agent publishes **10+ operational reports** on FinOps spend, orphaned VMs, and drift.

> Built with zero external cost using **Qwen2.5-Coder locally on Ollama in Docker** as the coding assistant. Architected against SOLID principles with structured prompt engineering.

`Python` `Terraform` `Docker` `Ollama` `Qwen2.5-Coder` `ServiceNow`

[**→ Repository**](https://github.com/HP04Harsh/infragenie-aiops) · [**→ Hugging Face**](https://huggingface.co/HarshG05/InfraGenie-Azure-Expert)

</td>
<td width="50%" valign="top">

### 🛡️ Azure Multi-Region Disaster Recovery

A two-region, three-tier Azure environment — **if the primary region fails, how fast can the app come back?** Provisioned entirely in **Terraform** across Central and South India.

**VM Scale Sets** serve web/app tiers, geo-replicated **Azure SQL** holds data, **Traffic Manager** + Load Balancers route traffic.

> Reusable modules with remote state/locking, active/passive topology to keep standby cost proportionate to the RTO rather than doubling the estate.

`Terraform` `Traffic Manager` `VM Scale Sets` `Azure SQL`

[**→ Repository**](https://github.com/HP04Harsh/azure-multi-region-dr-terraform)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ KubeScale-Ops — AKS Governance & FinOps

A Kubernetes lab for cost and governance: **Kubecost** and **Prometheus** track spend and utilization; manifests are GitOps-managed and validated on a **KinD** loop before reaching a real cluster.

Reusable **Terraform** modules with platform guardrails for repeatable AKS delivery.

`AKS` `Terraform` `Kubecost` `Prometheus` `Helm` `GitOps`

[**→ Repository**](https://github.com/HP04Harsh/KubeScale-Ops)

</td>
<td width="50%" valign="top">

### 🔐 k8s-sec-observability

A Kubernetes policy and observability lab: **Kyverno** admission policies enforce image and resource rules; **Grafana** dashboards over cluster metrics and traces.

Built to understand what "secure by default" actually costs to run day-to-day.

`Kubernetes` `Kyverno` `Terraform` `Grafana` `Prometheus`

[**→ Repository**](https://github.com/HP04Harsh/k8s-sec-observability)

</td>
</tr>
</table>

---

## Toolbelt

| | |
| :--- | :--- |
| **Azure** | ![Azure](https://img.shields.io/badge/Microsoft_Azure-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Entra_ID-1B3A6B?style=flat-square&logo=microsoft&logoColor=white) ![AKS](https://img.shields.io/badge/AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![VNet](https://img.shields.io/badge/VNet_%C2%B7_NSG_%C2%B7_LB-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure SQL](https://img.shields.io/badge/Azure_SQL-2A5490?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Key Vault](https://img.shields.io/badge/Key_Vault_%C2%B7_RBAC-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) |
| **IaC & DevOps** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **GenAI & Agents** | ![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure AI Search](https://img.shields.io/badge/Azure_AI_Search-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-2A5490?style=flat-square&logo=microsoft&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1B3A6B?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-2A5490?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-4A7BC8?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-1B3A6B?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-111C2E?style=flat-square&logo=ollama&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Log Analytics](https://img.shields.io/badge/Log_Analytics_(KQL)-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Scripting** | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1B3A6B?style=flat-square&logo=postgresql&logoColor=white) ![Graph API](https://img.shields.io/badge/Microsoft_Graph_API-2A5490?style=flat-square&logo=microsoft&logoColor=white) |
| **Microsoft 365** | ![SharePoint](https://img.shields.io/badge/SharePoint_Online-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![ShareGate](https://img.shields.io/badge/ShareGate-2A5490?style=flat-square&logo=microsoft&logoColor=white) |
| **OS & Networking** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![Networking](https://img.shields.io/badge/DNS_%C2%B7_TLS_%C2%B7_Routing_%C2%B7_Firewalls-2A5490?style=flat-square&logo=cloudflare&logoColor=white) |

---

## Certifications

| Certification | Issuer | Status |
| :--- | :--- | :--- |
| **Azure Fundamentals (AZ-900)** | Microsoft | ✅ Mar 2025 |
| **Azure Administrator Associate (AZ-104)** | Microsoft | ✅ Earned |
| **Terraform Associate (004)** | HashiCorp | 🔄 In progress |
| **DevOps Engineer Expert (AZ-400)** | Microsoft | 📅 Planned |
| **Azure AI Apps and Agents Developer Associate (AI-103)** | Microsoft | 📅 Planned |

> **AI-103 replaces the retired AI-102 exam** and is built on **Microsoft Foundry** — Foundry projects and models, RAG pipelines, agent tooling and memory, plus evaluation and governance.

## Currently Building

- **InfraGenie v2** — adding MCP tool servers, a LangGraph multi-agent architecture, and AKS deployment.
- **Agentic workflows** — LangGraph orchestration with human-in-the-loop and guardrails, on Azure AI Search RAG.
- **AI service APIs** — async FastAPI services for RAG and agent workloads.
- **AKS platform hardening** — cluster operations, GitOps delivery, cost governance, troubleshooting.

---

## Get in Touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-harsh--pardhi.vercel.app-1B3A6B?style=for-the-badge&logo=vercel&logoColor=white&labelColor=111C2E)](https://harsh-pardhi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-harsh--pardhi-2A5490?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=111C2E)](https://linkedin.com/in/harsh-pardhi)
[![Email](https://img.shields.io/badge/Email-harshpardhi477@gmail.com-4A7BC8?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111C2E)](mailto:harshpardhi477@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-1F8B3F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=111C2E)](https://harsh-pardhi.vercel.app/Harsh_Pardhi_Resume.pdf)

<br/>

*Automate the manual parts. Build agents that scale.*

</div>
