<div align="center">

# HARSH PARDHI #

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2500&pause=1000&color=1C6EB4&center=true&vCenter=true&width=900&lines=Azure+Cloud+Engineer;Cloud+Operations+%26+Automation;Azure+%C2%B7+Terraform+%C2%B7+Kubernetes+%C2%B7+PowerShell;Automate+the+Boring.+Keep+it+Reliable.)](https://git.io/typing-svg)

<br/>

![Experience](https://img.shields.io/badge/EXPERIENCE-2_YEARS_AZURE_%26_AUTOMATION-1F3864?style=for-the-badge&logoColor=white)
![Current](https://img.shields.io/badge/CURRENT-HEXAWARE_TECHNOLOGIES-1C6EB4?style=for-the-badge&logoColor=white)
![Focus](https://img.shields.io/badge/FOCUS-CLOUD_OPS_%26_AUTOMATION-0E5A94?style=for-the-badge&logoColor=white)
![Certified](https://img.shields.io/badge/CERTIFIED-AZ--104-2EA043?style=for-the-badge&logoColor=white)

<br/>

<img src="hero-terminal13.svg" alt="Harsh Pardhi — Azure Cloud Engineer terminal card" width="100%"/>

</div>

## 👋 About Me

Software engineer at **Hexaware Technologies**, two years in, working across Azure, Microsoft 365 and automation. Most of my work follows one pattern: something is being done by hand, and it shouldn't be. I find it, script it, and put the output where people can see it.

At work that has meant migrating **5,000+ users** to Microsoft 365 with ShareGate and **5 PowerShell scripts**; deploying **StorageX Analytics** against a client's NetApp ONTAP estate and scripting collection across **9 storage VMs / 2 clusters** into **10 scheduled Power BI reports**; moving **132 Power Apps and 50+ Power Automate flows** to a new tenant; and building **Transcend**, a Power App with a Copilot Studio agent that is now the primary tracking tool for our internal PMO team.

Outside work I build infrastructure projects to go deeper — **InfraGenie**, a two-region Azure DR environment in Terraform, and **KubeScale-Ops**. Being straight about it: my Terraform and Kubernetes depth comes from those projects and one client POC rather than years of production ownership. **AZ-400** next, then **CKA**.

## 🌟 Featured Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 InfraGenie — Natural-language Azure provisioning</h4>
      <p>Turns a plain-English request into a <b>reviewable Terraform plan</b> — mapped to vetted modules, with policy checks and a cost estimate attached to the diff. Nothing reaches the subscription until a <b>human approves the plan</b>. Runs on <b>AKS</b>, with <b>Argo CD</b> for drift detection and <b>Kubecost</b> for node-level cost visibility. State is held remotely in Azure Storage.</p>
      <p><i>Architecture and infrastructure design are mine; application code was generated with AI coding agents under structured prompting.</i></p>
      <p><a href="https://github.com/HP04Harsh/infraGenie-AI-Automation-Platform">repo</a> · <a href="https://huggingface.co/HarshG05/InfraGenie-Azure-Expert">HF model (fine-tuned Qwen2.5-Coder-7B, SFT)</a></p>
      <code>Terraform</code> <code>AKS</code> <code>Argo CD</code> <code>Kubecost</code> <code>Python</code> <code>Qwen2.5-Coder-7B</code>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Azure Multi-Region DR</h4>
      <p>Active–passive two-region disaster recovery defined entirely in <b>Terraform</b> and deployed through <b>GitHub Actions</b>: Traffic Manager routing, auto-scaling VM Scale Sets and geo-replicated storage. Failed over end to end, then documented — including what broke on the way. Destroy-and-rebuild reproducible.</p>
      <p><a href="https://github.com/HP04Harsh/azure-multi-region-dr-terraform">repo</a></p>
      <code>Terraform</code> <code>Traffic Manager</code> <code>VMSS</code> <code>Azure SQL</code> <code>GitHub Actions</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>💰 KubeScale-Ops — K8s Governance &amp; FinOps</h4>
      <p>FinOps control plane where <b>Kubecost + Prometheus</b> track spend and utilization. Kubecost surfaced <b>~20% reclaimable spend</b> from rightsizing in the test cluster; manifests are GitOps-managed and validated on a <b>KinD</b> loop before they reach a real cluster.</p>
      <p><a href="https://github.com/HP04Harsh/KubeScale-Ops">repo</a></p>
      <code>Kubecost</code> <code>Prometheus</code> <code>Helm</code> <code>KinD</code> <code>GitOps</code>
    </td>
    <td width="50%" valign="top">
      <h4>🔐 k8s-sec-observability</h4>
      <p>Kubernetes policy and observability lab: <b>Kyverno</b> admission policies enforcing image and resource rules, <b>Istio</b> for service-to-service traffic, and <b>Grafana</b> dashboards over the cluster. Built to understand what "secure by default" actually costs to run.</p>
      <p><a href="https://github.com/HP04Harsh/k8s-sec-observability">repo</a></p>
      <code>Kyverno</code> <code>Istio</code> <code>Grafana</code> <code>Kubernetes</code>
    </td>
  </tr>
</table>

## 🛠️ Toolbelt

| Category | Technologies |
| :--- | :--- |
| **Cloud** | ![Azure](https://img.shields.io/badge/Azure-1C6EB4?logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Entra_ID-1F3864?logo=microsoft&logoColor=white) ![Azure Storage](https://img.shields.io/badge/Azure_Storage-0E5A94?logo=microsoftazure&logoColor=white) |
| **Containers** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1628?logo=helm&logoColor=white) ![AKS](https://img.shields.io/badge/AKS-1C6EB4?logo=microsoftazure&logoColor=white) |
| **IaC & Automation** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white) ![Bicep](https://img.shields.io/badge/Bicep-1C6EB4?logo=microsoftazure&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-1F3864?logo=powershell&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) |
| **CI/CD & GitOps** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?logo=azuredevops&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?logo=argo&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) |
| **Observability & FinOps** | ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-1C6EB4?logo=microsoftazure&logoColor=white) ![Log Analytics](https://img.shields.io/badge/Log_Analytics-KQL-0E5A94?logo=microsoftazure&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white) ![Kubecost](https://img.shields.io/badge/Kubecost-20B982?logo=kubernetes&logoColor=white) |
| **Microsoft 365 & Power Platform** | ![SharePoint](https://img.shields.io/badge/SharePoint-038387?logo=microsoftsharepoint&logoColor=white) ![Power Apps](https://img.shields.io/badge/Power_Apps-742774?logo=powerapps&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?logo=powerautomate&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) ![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-1F3864?logo=microsoft&logoColor=white) ![ShareGate](https://img.shields.io/badge/ShareGate-migration-0E5A94?logo=microsoft&logoColor=white) |
| **Languages & APIs** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1F3864?logo=databricks&logoColor=white) ![REST](https://img.shields.io/badge/REST_APIs-0E5A94?logo=fastapi&logoColor=white) ![Graph API](https://img.shields.io/badge/Microsoft_Graph-2088FF?logo=microsoft&logoColor=white) |
| **AI / GenAI** | ![Hugging Face](https://img.shields.io/badge/Hugging_Face-fine--tuned_model-FFD21E?logo=huggingface&logoColor=black) ![Qwen](https://img.shields.io/badge/Qwen2.5--Coder--7B-SFT-412991?logo=alibabacloud&logoColor=white) ![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-agents-1C6EB4?logo=microsoft&logoColor=white) |

## 🎯 Currently Building & Learning

- **AZ-400** (DevOps Engineer Expert) — sitting Sep 2026.
- **CKA** (Certified Kubernetes Administrator) — starting after AZ-400.
- **NVIDIA NCA** (AI Infrastructure Operations) — in progress.
- **InfraGenie hardening** — tighter policy checks and a clearer plan-diff review step.

## 🏅 Certifications

- **Microsoft Certified: Azure Administrator Associate (AZ-104)** — Aug 2026 ✅
- **Microsoft Certified: DevOps Engineer Expert (AZ-400)** — expected Sep 2026
- **NVIDIA NCA — AI Infrastructure Operations** — in progress
- **Claude Certified Associate — Anthropic** — expected Sep 2026

## 📈 Contribution Velocity

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=HP04Harsh&bg_color=ffffff&color=1F3864&line=1C6EB4&point=1C6EB4&area=true&hide_border=true)

## 📫 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-harsh--pardhi.vercel.app-1F3864?style=for-the-badge&logo=vercel&logoColor=white)](https://harsh-pardhi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-in%2Fharsh--pardhi-1C6EB4?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harsh-pardhi)
[![Email](https://img.shields.io/badge/Email-harshpardhi499@gmail.com-0E5A94?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshpardhi499@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-InfraGenie--Azure--Expert-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/HarshG05/InfraGenie-Azure-Expert)

<br/>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=1F3864,1C6EB4&height=140&section=footer&text=Automate%20the%20boring.%20Keep%20it%20reliable.&fontSize=28&fontColor=ffffff&fontAlignY=70)
