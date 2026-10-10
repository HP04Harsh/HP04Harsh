<div align="center">

# 👋 Hi, I'm Harsh Pardhi

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=28&duration=3000&pause=1000&color=3CB371&center=true&vCenter=true&width=800&lines=Applied+AI+Engineer+%40+Hexaware;Building+Agentic+AI+%26+RAG+Systems;Azure+%E2%80%A2+AKS+%E2%80%A2+LangGraph+%E2%80%A2+Terraform;Automate+the+manual+parts.+Build+agents+that+scale." alt="Typing SVG" />

<br/>

<p>
  <img src="https://img.shields.io/badge/Experience-2%2B_Years-3CB371?style=for-the-badge&logo=calendar&logoColor=white" />
  <img src="https://img.shields.io/badge/Role-Software_Engineer-FFB347?style=for-the-badge&logo=hexaware&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Agentic_AI_%7C_RAG-87CEEB?style=for-the-badge&logo=ai&logoColor=white" />
  <img src="https://img.shields.io/badge/AZ--104-Certified-3CB371?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/AI--103-Next-FFB347?style=for-the-badge&logo=microsoft&logoColor=white" />
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=HP04Harsh&label=Profile%20Views&color=87CEEB&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/HP04Harsh?label=Followers&style=flat-square&color=3CB371" alt="Followers" />
  <img src="https://img.shields.io/github/stars/HP04Harsh?affiliations=OWNER&style=flat-square&color=FFB347&label=Stars" alt="Stars" />
</p>

---

</div>

## 🌟 About Me

```python
class HarshPardhi:
    def __init__(self):
        self.role = "Software Engineer @ Hexaware Technologies"
        self.location = "Gondia, Maharashtra, India 🇮🇳"
        self.experience = "2+ years"
        self.focus = ["Agentic AI", "Enterprise RAG", "Azure", "AKS"]
        self.certifications = ["AZ-900", "AZ-104"]
        self.currently_learning = ["LangGraph", "MCP", "LLMOps"]
        
    def current_work(self):
        return """
        Cloud and AI engineer building automation, enterprise Copilots, 
        and GenAI agents on Azure. My work follows one pattern: something 
        is being done by hand — and it shouldn't be.
        
        I find it, script it in PowerShell or Python, and wire it through 
        an AI agent instead of only a cron job.
        """
    
    def key_achievements(self):
        return {
            "M365 Migration": "5,000+ users migrated with PowerShell automation",
            "Storage Analytics": "9 storage VMs analyzed, 10 Power BI reports delivered",
            "Copilot Agents": "3 production agents live across 4 tenants",
            "Power Platform": "132 Power Apps + 50+ Power Automate flows migrated",
            "Internal Tools": "Built Transcend (Power App) - now manages 20+ projects"
        }
    
    def currently_building(self):
        return [
            "🤖 InfraGenie v2 — LangGraph agents + MCP tool servers + AKS",
            "🔐 Secure RAG pipelines with RBAC metadata filtering",
            "⚡ FastAPI services for agentic AI workloads",
            "📊 LLMOps observability with LangSmith and Prometheus"
        ]
```

<div align="center">

**📍 Gondia, Maharashtra · 🏢 Hexaware, Chennai · 🌏 Open to Applied AI / GenAI Engineer roles · ⏱ IST (UTC+5:30)**

</div>

---

## 🚀 Featured Projects

<div align="center">

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🤖 InfraGenie — AIOps Platform

**Self-healing Azure infrastructure powered by local LLMs**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />

<details>
<summary><b>What it does</b></summary>

- Engineers describe infrastructure needs in plain English
- Platform matches requests to reusable Terraform modules
- Runs policy checks before applying changes
- **Self-remediates** common failures automatically
- Logs ServiceNow tickets for tracking
- Publishes 10+ operational reports (FinOps, drift, orphaned VMs)

</details>

**Zero external cost** — uses Qwen2.5-Coder locally on Ollama in Docker

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-3CB371?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HP04Harsh/infragenie-aiops)
[![Hugging Face](https://img.shields.io/badge/🤗-Hugging_Face-FFB347?style=for-the-badge)](https://huggingface.co/HarshG05/InfraGenie-Azure-Expert)

</td>
<td width="50%" valign="top">

### 🛡️ Azure Multi-Region DR

**Two-region, three-tier disaster recovery infrastructure**

<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Traffic_Manager-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />

<details>
<summary><b>Architecture highlights</b></summary>

- **Primary + Secondary regions:** Central India + South India
- **Web/App tiers:** VM Scale Sets with autoscaling
- **Data tier:** Geo-replicated Azure SQL
- **Traffic routing:** Traffic Manager + Load Balancers
- **Active/Passive topology** — standby cost proportionate to RTO
- **Reusable Terraform modules** with remote state/locking

</details>

**Question answered:** If primary region fails, how fast can the app recover?

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-3CB371?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HP04Harsh/azure-multi-region-dr-terraform)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚙️ KubeScale-Ops

**AKS governance, FinOps, and GitOps delivery**

<img src="https://img.shields.io/badge/AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />

<details>
<summary><b>Key features</b></summary>

- **FinOps control plane:** Kubecost + Prometheus track spend
- **GitOps delivery:** Argo CD with KinD validation loop
- **Policy enforcement:** Platform guardrails for safe changes
- **Reusable modules** for repeatable AKS delivery

</details>

**Built to understand:** What does "secure by default" actually cost?

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-3CB371?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HP04Harsh/KubeScale-Ops)

</td>
<td width="50%" valign="top">

### 🔐 k8s-sec-observability

**Kubernetes policy enforcement + observability stack**

<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Kyverno-000000?style=flat-square&logo=kyverno&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />

<details>
<summary><b>What's included</b></summary>

- **Kyverno policies:** Image validation, resource limits
- **Grafana dashboards:** Cluster metrics and traces
- **Automated deployment** with Terraform
- **Observability stack** wired from day one

</details>

**Day-to-day cost analysis** of running secure Kubernetes

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-3CB371?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HP04Harsh/k8s-sec-observability)

</td>
</tr>
</table>

</div>

---

## 🛠️ Technology Stack

<div align="center">

### ☁️ Cloud & Infrastructure

<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure_AKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Entra_ID-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />

### 🤖 AI & Machine Learning

<img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure_AI_Search-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAG-000000?style=for-the-badge" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />

### 💻 Development & Scripting

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

### 📊 Observability & DevOps

<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
<img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />

### 🏢 Microsoft 365

<img src="https://img.shields.io/badge/SharePoint-038387?style=for-the-badge&logo=microsoftsharepoint&logoColor=white" />
<img src="https://img.shields.io/badge/Power_Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white" />
<img src="https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=HP04Harsh&show_icons=true&theme=transparent&include_all_commits=true&count_private=true&hide_border=true&bg_color=FFFFFF&title_color=3CB371&icon_color=FFB347&text_color=333333" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HP04Harsh&layout=compact&theme=transparent&hide_border=true&bg_color=FFFFFF&title_color=3CB371&text_color=333333" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=HP04Harsh&theme=transparent&hide_border=true&background=FFFFFF&stroke=3CB371&ring=FFB347&fire=FFB347&currStreakLabel=3CB371" alt="GitHub Streak" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=HP04Harsh&theme=react-dark&hide_border=true&bg_color=FFFFFF&color=3CB371&line=FFB347&point=87CEEB&area=true" />

</div>

---

## 🏆 Certifications

<div align="center">

<table>
<tr>
<td align="center" width="20%">
<img src="https://img.shields.io/badge/AZ--900-Azure_Fundamentals-3CB371?style=for-the-badge&logo=microsoft&logoColor=white" />
<br/>
<b>✅ Earned</b>
<br/>
<small>Mar 2025</small>
</td>
<td align="center" width="20%">
<img src="https://img.shields.io/badge/AZ--104-Azure_Administrator-3CB371?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<br/>
<b>✅ Certified</b>
<br/>
<small>2026</small>
</td>
<td align="center" width="20%">
<img src="https://img.shields.io/badge/Terraform-Associate_004-FFB347?style=for-the-badge&logo=terraform&logoColor=white" />
<br/>
<b>🔄 In Progress</b>
<br/>
<small>2026</small>
</td>
<td align="center" width="20%">
<img src="https://img.shields.io/badge/AZ--400-DevOps_Expert-87CEEB?style=for-the-badge&logo=microsoft&logoColor=white" />
<br/>
<b>📅 Planned</b>
<br/>
<small>Nov 2026</small>
</td>
<td align="center" width="20%">
<img src="https://img.shields.io/badge/AI--103-AI_Apps_&_Agents-87CEEB?style=for-the-badge&logo=microsoft&logoColor=white" />
<br/>
<b>📅 Planned</b>
<br/>
<small>2027</small>
</td>
</tr>
</table>

</div>

<details>
<summary><b>📝 About AI-103</b></summary>

**AI-103 replaces the retired AI-102 exam** and is built on **Microsoft Foundry** — covering Foundry projects and models, RAG pipelines, agent tooling and memory, plus evaluation and governance.

</details>

---

## 🎯 Currently Building

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🚀 In Progress

- **InfraGenie v2** — Adding MCP tool servers, LangGraph multi-agent architecture, AKS deployment
- **Secure Enterprise RAG** — RBAC metadata filtering, permission-aware retrieval
- **FastAPI AI Services** — Async APIs for RAG and agent workloads
- **AKS Platform Hardening** — Cluster operations, GitOps, cost governance

</td>
<td width="50%" valign="top">

### 📚 Learning

- **LangGraph** — State machines, conditional edges, human-in-the-loop
- **Model Context Protocol (MCP)** — Tool servers, agent communication
- **LLMOps** — Observability, evaluation, cost tracking
- **Advanced RAG** — Hybrid search, reranking, Azure AI Search

</td>
</tr>
</table>

</div>

---

## 📈 By The Numbers

<div align="center">

<table>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/Users_Migrated-5,000+-3CB371?style=for-the-badge" />
<br/>
<small>Microsoft 365</small>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Power_Apps-132-FFB347?style=for-the-badge" />
<br/>
<small>+ 50 Power Automate flows</small>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Storage_VMs-9-87CEEB?style=for-the-badge" />
<br/>
<small>Across 2 clusters</small>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Power_BI_Reports-10-3CB371?style=for-the-badge" />
<br/>
<small>Scheduled refresh</small>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Copilot_Agents-3-FFB347?style=for-the-badge" />
<br/>
<small>Production, 4 tenants</small>
</td>
</tr>
</table>

</div>

---

## 📫 Get In Touch

<div align="center">

<p>
<a href="https://harsh-pardhi.vercel.app">
<img src="https://img.shields.io/badge/Portfolio-harsh--pardhi.vercel.app-3CB371?style=for-the-badge&logo=vercel&logoColor=white" />
</a>
<a href="https://linkedin.com/in/harsh-pardhi">
<img src="https://img.shields.io/badge/LinkedIn-harsh--pardhi-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:harshpardhi477@gmail.com">
<img src="https://img.shields.io/badge/Email-harshpardhi477@gmail.com-FFB347?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://harsh-pardhi.vercel.app/Harsh_Pardhi_Resume.pdf">
<img src="https://img.shields.io/badge/Resume-Download_PDF-87CEEB?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
</a>
</p>

<p>
<a href="https://medium.com/@harshpardhi477">
<img src="https://img.shields.io/badge/Medium-@harshpardhi477-000000?style=flat-square&logo=medium&logoColor=white" />
</a>
<a href="https://leetcode.com/u/harsh_pardhi/">
<img src="https://img.shields.io/badge/LeetCode-harsh_pardhi-FFA116?style=flat-square&logo=leetcode&logoColor=white" />
</a>
<a href="https://www.hackerrank.com/profile/harshpardhi477">
<img src="https://img.shields.io/badge/HackerRank-harshpardhi477-2EC866?style=flat-square&logo=hackerrank&logoColor=white" />
</a>
</p>

<br/>

<img src="https://img.shields.io/badge/Automate_the_manual_parts._Build_agents_that_scale.-3CB371?style=for-the-badge" />

</div>

---

<div align="center">

### 💫 Thanks for visiting!

<img src="https://img.shields.io/badge/Open_to-Applied_AI_Engineer_roles-3CB371?style=flat-square" />
<img src="https://img.shields.io/badge/Relocation-Bangalore_|_Hyderabad_|_Pune_|_Chennai-FFB347?style=flat-square" />
<img src="https://img.shields.io/badge/Response_Time-Within_24_hours-87CEEB?style=flat-square" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" />

</div>
