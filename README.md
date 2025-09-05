<!-- Banner -->
<p align="center">
  <img src="https://img.shields.io/badge/Salesforce-LastMile%20Training-00A1E0?logo=salesforce&logoColor=white" alt="Salesforce LastMile">
  <img src="https://img.shields.io/badge/Duration-12%20Weeks-4CAF50" alt="12 Weeks">
  <img src="https://img.shields.io/badge/Focus-Admin%20|%20Apex%20|%20LWC-6A5ACD" alt="Focus">
</p>

<h1 align="center">🚀 TCS LastMile Salesforce Training (Jul–Oct 2025)</h1>
<p align="center">A hands-on learning journey across Salesforce Admin, Apex, and Lightning Web Components with an end-to-end Capstone.</p>

<p align="center">
  <!-- Profile buttons -->
  <a href="https://www.salesforce.com/trailblazer/vaibhav-s-75" target="_blank">
    <img src="https://img.shields.io/badge/Trailblazer-View%20Profile-00A1E0?logo=salesforce&logoColor=white" alt="Trailblazer Profile">
  </a>
  <a href="YOUR_SKILL_WALLET_PROFILE_LINK" target="_blank">
    <img src="https://img.shields.io/badge/Skill%20Wallet-View%20Profile-111827" alt="Skill Wallet">
  </a>
  <!-- Repo stats -->
  <img src="https://img.shields.io/github/last-commit/YOUR_GITHUB_USERNAME/tcs-lastmile-salesforce-training?label=Last%20update" alt="Last update">
  <img src="https://img.shields.io/badge/Made%20with-VS%20Code-007ACC?logo=visualstudiocode&logoColor=white" alt="VS Code">
</p>

---

## 📌 Overview
This repository documents my work in the **TCS LastMile 12-week Salesforce Training**—from fundamentals to a production-style **Capstone**. It includes weekly notes, hands-on exercises, LWC components, Apex code samples, and certification prep.

- **Tracks:** Salesforce Admin • Sales Cloud • Service Cloud • Apex • SOQL/SOSL • Async Apex • LWC  
- **Tooling:** Salesforce CLI, VS Code, GitHub Projects, Trailhead

---

## 🏆 Profiles & Badges
- 👤 **Trailblazer:** [View My Salesforce Profile](https://www.salesforce.com/trailblazer/vaibhav-s-75)  
- 🪪 **Skill Wallet:** [View Profile](YOUR_SKILL_WALLET_PROFILE_LINK)

**Trailhead Badge Showcase:**  
<p align="left">
  <img src="https://img.shields.io/badge/Trailhead-Badges%20Earned-00A1E0?logo=salesforce&logoColor=white" alt="Trailhead Badges">
  <img src="https://img.shields.io/badge/Superbadges-In%20Progress-orange?logo=salesforce&logoColor=white" alt="Superbadges">
  <img src="https://img.shields.io/badge/Modules-Completed-green?logo=salesforce&logoColor=white" alt="Modules Completed">
</p>

**Skills Badge Strip:**  
![Salesforce Admin](https://img.shields.io/badge/Admin-Progress-00A1E0?logo=salesforce&logoColor=white)
![Apex](https://img.shields.io/badge/Apex-Hands%20On-0A84FF)
![LWC](https://img.shields.io/badge/LWC-Components-6A5ACD)
![SOQL/SOSL](https://img.shields.io/badge/SOQL%2FSOSL-Queries-10B981)
![Async Apex](https://img.shields.io/badge/Async-Future%20%7C%20Batch%20%7C%20Queueable-22C55E)
![Reports & Dashboards](https://img.shields.io/badge/Analytics-Reports%20%26%20Dashboards-F59E0B)

---

## 🧭 Learning Journey
<details>
<summary><b>Weeks 1–3 • Foundations</b> — Cloud, Salesforce Fundamentals, Data Modeling, Security, Reports</summary>

- Org setup, editions, architecture, AppExchange  
- Standard vs Custom Objects, relationships, formulas, rollups  
- User/Roles/Profiles/OWD/Sharing rules  
- Reports, Dashboards, Dynamic Dashboards  
</details>

<details>
<summary><b>Weeks 4–5 • Apps & Apex</b> — Sales/Service Cloud, Automation, Apex Basics + Testing</summary>

- Leads, Campaigns, Case Management, Web-to-Lead/Case  
- Validation, Approval Process, Assignment, Escalation  
- Apex: variables, control flow, DML, SOQL/SOSL, triggers, exceptions, tests  
</details>

<details>
<summary><b>Weeks 6–7 • Advanced Dev</b> — Async Apex + LWC</summary>

- Future, Queueable, Batch, Schedulable  
- LWC: setup, folder structure, events, styling, data access  
</details>

<details>
<summary><b>Weeks 7–9 • Capstone</b> — End-to-end build</summary>

- Full implementation across Sales + Service + LWC  
- Security model, automation, analytics, deployment  
</details>

<details>
<summary><b>Weeks 10–12 • Cert & Soft Skills</b></summary>

- Salesforce Admin + Platform Developer I prep  
- Resume, mock interviews, presentations  
</details>

---

## 🧪 Tech & Tooling
- **Salesforce:** Admin, Apex, LWC, SOQL/SOSL, Reports  
- **Dev Tools:** VS Code, Salesforce CLI, Git/GitHub  
- **Project:** GitHub Projects, Issues, PRs  
- **Practice:** Trailhead Trailmixes, Hands-on Orgs

---

## 🧩 Capstone (Template)
**Title:** _YOUR_CAPSTONE_NAME_  
**Problem:** What business problem are you solving?  
**Solution:** Key objects, automations, Apex logic, LWC UIs  
**Highlights:**
- 🔐 Role/OWD/Sharing design
- ⚙️ Automation: Approval/Assignment/Flows
- 💻 Apex: Triggers, services, tests (>75% coverage)
- 🧩 LWC: interactive UI components
- 📊 Analytics: Reports & Dashboards

**Architecture Diagram:** `capstone-project/docs/architecture.png`  
**Demo:** link to slides/video/GIF

---

## 🛠️ Setup (Quick Start)
```bash
# 1) Install Salesforce CLI (sf) and login
sf --version
sf org login web --alias YOUR_ALIAS

# 2) Clone and open
git clone https://github.com/YOUR_GITHUB_USERNAME/tcs-lastmile-salesforce-training.git
cd tcs-lastmile-salesforce-training

# 3) (Optional) Create/authorize a scratch org and push metadata
sf org create scratch --definition-file config/project-scratch-def.json --alias tcs-training --duration-days 7
sf project deploy start --source-dir force-app

# 4) Open the org
sf org open --target-org tcs-training
