<h1 align="center">Ajit Karthikeya Balla</h1>

<p align="center">
  <strong>Azure DevOps Engineer &nbsp;|&nbsp; Cloud Operations &nbsp;|&nbsp; ServiceNow CSA</strong><br/>
  Bridging enterprise operations and cloud automation — building systems that reduce toil, enforce compliance, and ship reliably.
</p>

<p align="center">
  <a href="mailto:ajitkarthikeyaballa@gmail.com">📧 Email</a> &nbsp;|&nbsp;
  <a href="https://linkedin.com/in/ajitkarthikeyaballa">💼 LinkedIn</a> &nbsp;|&nbsp;
  <a href="https://github.com/ajit-karthikeya">🐙 GitHub</a>
</p>

---

## About Me

I'm an operations engineer at Amazon with hands-on experience managing high-volume seller support workflows, cross-team escalations, and compliance at scale. Alongside that, I've trained extensively in Azure DevOps — building CI/CD pipelines, provisioning infrastructure with ARM Templates and Terraform, and deploying cloud-native applications to Azure.

My focus is on the intersection of **operational reliability** and **cloud automation**: writing the pipelines, infrastructure code, and tooling that make support environments faster, more auditable, and easier to scale.

- 🏢 Currently: Selling Partner Support Associate @ Amazon India
- ☁️ Cloud stack: Azure (App Services, VNets, SQL, Function Apps, Entra ID)
- 🔧 DevOps tooling: Azure DevOps, CI/CD, ARM, Terraform, Git
- 🎯 Certified: ServiceNow CSA | AWS Cloud Foundations | Java Foundations (Oracle)
- 📍 Based in Hyderabad, India | Open to remote and hybrid roles

---

## Tech Stack

**Cloud & Infrastructure**
Azure App Services · Virtual Networks · NSGs · Load Balancers · Application Gateway · Azure SQL · Function Apps · Storage Accounts · Entra ID (Azure AD) · Virtual Machines

**DevOps & Automation**
Azure DevOps · CI/CD Pipelines (Build + Release) · ARM Templates · Terraform · Kubernetes (YAML, concepts) · Git · GitHub Actions

**Scripting & Development**
PowerShell · Python · SQL · Bash

**Platforms & ITSM**
ServiceNow (CSA Certified) · JIRA · AWS (Foundations) · Windows Server · Linux

**Operations**
SLA Management · Incident Management · Root Cause Analysis · Escalation Handling · ITIL Fundamentals · Brand Protection Workflows

---

## Featured Projects

### 🏥 Total Absence Management Portal
> Azure App Services · Function Apps · Azure SQL · Azure DevOps CI/CD · RBAC

A production-style web portal for absence tracking, deployed to Azure via a 3-stage CI/CD pipeline (Dev → Staging → Prod). Event-driven processing via Function Apps. Network segmentation and least-privilege access enforced through VNets and Azure AD RBAC.

[View Repository →](https://github.com/ajit-karthikeya/total-absence-management-portal)

---

### 📊 SLA Compliance Dashboard
> Python · Azure SQL · Power BI / Plotly · ServiceNow API

Automated dashboard that ingests ticket data from ServiceNow, computes SLA breach risk in real time, and surfaces trend insights. Built to replicate the kind of operational intelligence tooling used in enterprise support environments.

[View Repository →](https://github.com/ajit-karthikeya/sla-compliance-dashboard)

---

### 🔐 Azure VM & Network Deployment Lab
> Azure VNet · NSGs · Windows Server · PowerShell · ARM Templates

Enterprise-grade Azure network lab: custom VNet with defined subnets, scoped NSG rules, RDP validation, and diagnostic log analysis. Demonstrates infrastructure provisioning and network security hygiene from scratch.

[View Repository →](https://github.com/ajit-karthikeya/azure-network-lab)

---

### ⚙️ ServiceNow Ticket Automation Engine
> Python · ServiceNow REST API · Azure Function Apps · PowerShell

Automated ticket triage and routing engine using the ServiceNow REST API. Ingests incoming incidents, classifies by keyword and priority, auto-assigns resolver groups, and logs resolution metadata. Reduces manual triage overhead by design.

[View Repository →](https://github.com/ajit-karthikeya/servicenow-automation-engine)

---

### 🏗️ Azure IaC Deployment Toolkit
> Terraform · ARM Templates · Azure CLI · PowerShell · GitHub Actions

Reusable Infrastructure as Code toolkit for provisioning standard Azure environments: VMs, VNets, NSGs, Storage Accounts, App Services. Includes parameterized ARM Templates, Terraform modules, and a GitHub Actions pipeline for automated deployment.

[View Repository →](https://github.com/ajit-karthikeya/azure-iac-toolkit)

---

## Operational Achievements

- Sustained **95%+ SLA compliance** across high-volume seller support queues at Amazon
- Reduced repeat contact rate on top-3 issue categories by **~20%** through structured root cause analysis
- Cut average multi-team escalation resolution cycle by **30%** through process realignment
- Maintained **100% case audit compliance** across all monthly quality reviews
- Surfaced **5+ systemic workflow gaps** that directly drove knowledge base updates

---

## Currently Learning

- Terraform advanced modules and remote state management
- GitHub Actions for Azure deployments
- Azure Monitor and Log Analytics for operational observability
- AZ-400 (Azure DevOps Engineer Expert) certification path

---

## Let's Connect

I'm actively looking for roles in **Cloud Operations**, **Azure DevOps**, or **Support Engineering** where I can apply both my operational background and cloud automation skills.

📧 ajitkarthikeyaballa@gmail.com
💼 [linkedin.com/in/ajitkarthikeyaballa](https://linkedin.com/in/ajitkarthikeyaballa)
```

---

## SECTION 4: HIGH-IMPACT PROJECT PLAN

### Project 1: SLA Compliance Dashboard

**Problem it solves:** Support teams lack real-time visibility into SLA breach risk. Most dashboards are reactive. This one predicts breach before it happens.

**Why it impresses recruiters:** Directly mirrors your Amazon experience. Shows you can translate operational pain into a software solution. Data engineering + API integration + visualization in one project.

**Core features:**
- Pull ticket data from ServiceNow REST API
- Calculate SLA breach risk score per ticket
- Visualize trends by category, team, and time period
- Email alert when breach probability exceeds threshold

**Architecture:**
```
ServiceNow API → Python ingestion script → Azure SQL (storage) → Plotly/Dash frontend → Azure App Service (hosted)
```

**Tech stack:** Python, requests, pandas, Plotly Dash, Azure SQL, Azure App Service, ServiceNow REST API

**Stretch features to make it elite:**
- Deploy via Azure DevOps CI/CD pipeline
- Add Azure Function App to run ingestion on a timer
- Add Power BI embed for executive-style reporting
- Write unit tests with pytest and include them in the pipeline

---

### Project 2: ServiceNow Ticket Automation Engine

**Problem it solves:** Tier-1 agents waste significant time manually reading and routing tickets. This engine automates triage using keyword classification and API-driven assignment.

**Why it impresses recruiters:** This is exactly what companies pay for. Shows you understand both the ops process AND can automate it. ServiceNow CSA + Python + REST APIs = rare combination.

**Core features:**
- Poll ServiceNow for new incidents via REST API
- Classify ticket type using keyword rules (or simple ML)
- Auto-assign to correct resolver group via API
- Log all actions to an audit trail in Azure SQL

**Architecture:**
```
ServiceNow REST API → Python classifier → Assignment logic → ServiceNow API (update ticket) → Azure SQL (audit log)
```

**Tech stack:** Python, ServiceNow REST API, Azure Function Apps (timer trigger), Azure SQL, PowerShell

**Stretch features:**
- Replace keyword rules with a simple scikit-learn text classifier trained on ticket history
- Add a Slack/Teams webhook notification on auto-assignment
- Deploy the Function App via ARM Template

---

### Project 3: Azure IaC Deployment Toolkit

**Problem it solves:** Spinning up consistent Azure environments manually is error-prone and slow. This toolkit provides reusable, parameterized IaC for standard enterprise Azure setups.

**Why it impresses recruiters:** IaC is non-negotiable for any DevOps role. This shows you can write Terraform modules and ARM Templates, not just click through the portal. It's the single most important project for your DevOps pivot.

**Core features:**
- Terraform module for VNet + Subnets + NSGs
- ARM Template for VM + Storage Account + App Service
- GitHub Actions pipeline that deploys the whole stack on push
- Parameterized for dev/staging/prod environments

**Architecture:**
```
GitHub (code) → GitHub Actions (trigger) → Terraform/ARM → Azure (VNet, VM, App Service, SQL)
```

**Tech stack:** Terraform, ARM Templates, Azure CLI, PowerShell, GitHub Actions, Azure (VNet, VM, App Service, Storage)

**Stretch features:**
- Add Azure Policy assignment via Terraform to enforce compliance rules
- Use Terraform remote state stored in Azure Blob Storage
- Add a destroy pipeline that tears down the environment cleanly

---

### Project 4: Brand Protection Escalation Tracker

**Problem it solves:** Brand protection teams handle hundreds of escalations weekly with no unified view of patterns. This tool identifies repeat violation categories and flags high-risk sellers.

**Why it impresses recruiters:** This is your Amazon ops experience converted into a data product. It's specific, it's real, and no other candidate is building this.

**Core features:**
- Excel/CSV input of escalation data
- Python analysis: top violation categories, repeat offender detection, resolution time trends
- Automated report generation (PDF or HTML)
- Visualizations: bar charts, heatmaps, trend lines

**Architecture:**
```
CSV/Excel input → Python (pandas, matplotlib) → Analysis engine → HTML report output → Hosted on GitHub Pages
```

**Tech stack:** Python, pandas, matplotlib, seaborn, Jinja2 (HTML templating), openpyxl, GitHub Pages

**Stretch features:**
- Add a Streamlit web UI so the tracker is interactive
- Deploy the Streamlit app to Azure App Service via CI/CD

---

### Project 5: Total Absence Management Portal (Expand Your Existing Project)

**Problem it solves:** HR teams use spreadsheets or expensive SaaS tools for absence tracking. This portal provides a lightweight, self-hosted alternative built on Azure.

**Why it impresses recruiters:** You already have this on your resume. GitHub lets you actually show the code, the pipeline, and the architecture diagram. Most candidates list projects — you need to show them.

**Core features:**
- Web frontend for submitting and viewing absence requests
- Azure SQL backend for data persistence
- Azure Function App for email notifications on approval/rejection
- 3-stage CI/CD pipeline with branch protection rules

**Architecture:**
```
Frontend (HTML/JS or React) → Azure App Service → Azure SQL → Function App (notifications) → Azure DevOps Pipeline (CI/CD)
```

**Tech stack:** Python Flask or Node.js, Azure App Service, Azure SQL, Azure Function Apps, Azure DevOps, Azure AD (auth)

**Stretch features:**
- Add Azure AD B2C for employee login
- Add ARM Template or Terraform to provision the entire infrastructure
- Write integration tests that run in the CI pipeline

---

## SECTION 5: REPOSITORY STRUCTURE TEMPLATE

### Folder Structure (use this for every project)
```
project-name/
│
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions CI/CD pipeline
│
├── src/                        # All source code lives here
│   ├── main.py (or index.js)
│   └── modules/
│       └── [feature files]
│
├── infrastructure/             # IaC files
│   ├── main.tf                 # Terraform config
│   ├── variables.tf
│   ├── outputs.tf
│   └── arm-template.json       # ARM Template if applicable
│
├── tests/                      # Unit and integration tests
│   └── test_main.py
│
├── docs/                       # Documentation and diagrams
│   └── architecture.png
│
├── scripts/                    # Utility scripts (PowerShell, Bash)
│   └── setup.ps1
│
├── .gitignore                  # Never commit secrets or venvs
├── requirements.txt            # Python dependencies
└── README.md                   # Project README (template below)
