<div align="center">

# Harsh Pardhi

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=1000&color=1B3A6B&center=true&vCenter=true&width=820&lines=GenAI+Engineer+%7C+Azure+%26+AKS;Agentic+AI+%C2%B7+MCP+%C2%B7+Terraform+%C2%B7+RAG;Automate+the+manual+parts.+Build+agents+that+scale.)](https://harsh-pardhi.vercel.app)

<br/>

![Experience](https://img.shields.io/badge/EXPERIENCE-2%2B_YEARS-1B3A6B?style=for-the-badge&labelColor=111C2E)
![Current](https://img.shields.io/badge/CURRENT-HEXAWARE-2A5490?style=for-the-badge&labelColor=111C2E)
![Focus](https://img.shields.io/badge/FOCUS-GenAI+%7C+AKS+%7C+Agents-8B5CF6?style=for-the-badge&labelColor=111C2E)
![Status](https://img.shields.io/badge/AZ--104-TARGETING_OCT_2026-F59E0B?style=for-the-badge&labelColor=111C2E)

<br/>

<img src="hero-terminal15.svg" alt="Harsh Pardhi — GenAI Engineer" width="100%"/>

</div>

---

## About

Cloud and AI engineer at **Hexaware Technologies**, two years in — building automation, enterprise Copilots, and (increasingly) GenAI agents on Azure.

My work follows one pattern: something is being done by hand — a migration, a permissions audit, a report rebuilt every Monday, a ticket queue at 2 a.m. — and it shouldn't be. I find it, script it in **PowerShell** or **Python**, and these days I wire it through an **AI agent** instead of only a cron job.

At work that has meant migrating **5,000+ users** of on-premises OneDrive data to **Microsoft 365** with ShareGate and PowerShell (overnight cutovers running unsupervised); deploying **StorageX Analytics** against **9 storage VMs across 2 clusters** into **10 Power BI reports** the client formally thanked us for; migrating **132 Power Apps and 50+ Power Automate flows** across 4 tenants; building **Transcend**, a Power App with a Copilot Studio agent that now runs 20+ projects; and delivering a **Terraform landing zone POC** for a client evaluation. On the same engagements I deployed **two production Copilot Studio agents** — an L1 support agent and a PMO assistant — grounded in internal SharePoint FAQs, wired to ticketing, live across all four tenants.

Outside work I build to go deeper: **InfraGenie**, an AIOps platform for Azure that uses a local LLM (Qwen2.5-Coder on Ollama) with structured prompts and self-remediation loops; a **two-region DR environment** in Terraform; and labs on **AKS GitOps**, **policy enforcement**, and observability.

Currently doubling down on **GenAI engineering**: agentic workflows with **LangGraph**, **Model Context Protocol (MCP)**, **RAG** on Azure AI Search, **LLMOps**, and deploying AI workloads on **AKS**. Working toward **AZ-104** (Oct 2026), then **AZ-400** and **AI-102**.

<div align="center">

**📍 Gondia, Maharashtra · 🏢 Hexaware, Chennai · 🌏 Open to GenAI / AI Platform / Cloud roles · ⏱ IST (UTC+5:30)**

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
| **Azure** | ![Azure](https://img.shields.io/badge/Microsoft_Azure-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Entra_ID-1B3A6B?style=flat-square&logo=microsoft&logoColor=white) ![AKS](https://img.shields.io/badge/AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![VNet](https://img.shields.io/badge/VNet_·_NSG_·_LB-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure SQL](https://img.shields.io/badge/Azure_SQL-2A5490?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Key Vault](https://img.shields.io/badge/Key_Vault_·_RBAC-2A5490?style=flat-square&logo=microsoftazure&logoColor=white) |
| **IaC & DevOps** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **GenAI / Agents** | ![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) ![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-2A5490?style=flat-square&logo=microsoft&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3A5C?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph_(learning)-4B5563?style=flat-square) ![MCP](https://img.shields.io/badge/MCP_(learning)-6B21A8?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-1B3A6B?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-111C2E?style=flat-square&logo=ollama&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-1B3A6B?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Scripting** | ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI_(learning)-009688?style=flat-square&logo=fastapi&logoColor=white) ![Graph API](https://img.shields.io/badge/Microsoft_Graph_API-2A5490?style=flat-square&logo=microsoft&logoColor=white) |
| **Microsoft 365** | ![SharePoint](https://img.shields.io/badge/SharePoint_Online-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white) ![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |
| **OS & Networking** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![Networking](https://img.shields.io/badge/DNS_·_TLS_·_Routing-2A5490?style=flat-square&logo=cloudflare&logoColor=white) |

---

## Certifications

| Certification | Issuer | Status |
| :--- | :--- | :--- |
| **Azure Fundamentals (AZ-900)** | Microsoft | ✅ Mar 2025 |
| **Azure Administrator Associate (AZ-104)** | Microsoft | 🟡 Targeting Oct 2026 |
| **DevOps Engineer Expert (AZ-400)** | Microsoft | 📅 Planned — Nov 2026 |
| **Terraform Associate (004)** | HashiCorp | 🔄 In progress |
| **Azure AI Engineer Associate (AI-102)** | Microsoft | 📅 Planned — Feb 2027 |

## Currently Building

- **GenAI & Agents deep-dive** — LangGraph agents, MCP servers, RAG on Azure AI Search, and LLMOps observability. Deploying agent workloads on AKS.
- **AZ-104** — Azure Administrator (this month).
- **Python + FastAPI** — production-grade async APIs for AI services.
- **InfraGenie v2** — adding MCP tools, LangGraph multi-agent architecture, and AKS deployment.
- **Production Kubernetes depth** — cluster operations, GitOps, cost governance, troubleshooting.

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

*Automate the manual parts. Build agents that scale.*

</div>
