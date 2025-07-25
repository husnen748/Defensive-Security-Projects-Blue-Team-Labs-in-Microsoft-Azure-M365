# Defensive Security Projects: Blue Team Labs in Microsoft Azure & M365

## 🔍 Overview

This repository presents a collection of real-world defensive security labs using Microsoft’s cloud-native technologies. Each lab simulates common blue team and SOC tasks, such as securing infrastructure, monitoring cloud environments, automating incident response, and investigating threats.

All labs were completed in the **East US Azure region** using a mix of **Microsoft 365 Defender E5 and **Azure Pay-As-You-Go** resources.

---

## 📁 Included Labs

### ✅ Microsoft Defender for Endpoint
- Applied preset security policies (Safe Links, Anti-Malware, Anti-Phishing)
- Onboarded and monitored Windows devices
- Logged into Security Copilot and explored its features
- Created and executed KQL queries for hunting
- Enabled audit logging with Microsoft Purview

---

### ✅ azure security and access control
- Built secure network architecture using NSGs and ASGs
- Controlled access using RBAC for multiple roles
- Configured Azure Firewall with DNS and route tables
- Restricted storage access using service endpoints and NSGs

---

### ✅ Monitoring and Analytics
- Set up Log Analytics Workspaces and Data Collection Rules (DCRs)
- Monitored VM performance using Azure Monitor
- Enabled Defender for SQL with data classification
- Configured auditing at server and database levels

---

### ✅ Azure SIEM & SOAR Automation
- Connected Azure Activity logs to Microsoft Sentinel
- Created analytics rules to detect Defender and CloudShell abuse
- Automated incident response with Logic Apps and playbooks
- Enabled and tuned UEBA anomaly detection
- Tested incident generation, alert grouping, and automated ownership

---

## 🧠 Skills Demonstrated

- Threat detection and hunting with KQL
- SIEM rule creation and playbook automation (Sentinel & Logic Apps)
- Endpoint protection and network segmentation
- Data classification and cloud audit configuration
- Role-based access and workload isolation
- Real-world alert triage and response workflows

---

## 🔧 Tools & Technologies

| Category              | Tools/Services |
|-----------------------|----------------|
| SIEM & SOAR           | Microsoft Sentinel, Logic Apps |
| Endpoint Protection   | Microsoft Defender for Endpoint/XDR |
| Data Protection       | Microsoft Purview, Defender for SQL |
| Monitoring & Logs     | Azure Monitor, Log Analytics, DCR |
| Network Security      | NSG, ASG, Azure Firewall |
| Access Management     | Azure AD RBAC |
| Automation & CLI      | PowerShell, Azure CLI |

---

## 💡 Notes

- These labs are based on Microsoft certification tracks AZ-500 (Azure Security Engineer) and SC-200 (Security Operations Analyst).
- All work was completed independently for hands-on learning.  
  *Note: These projects were not part of official certification exams.*
- Labs were run using an **Azure Pay-As-You-Go subscription**.
- A Microsoft 365 Developer sandbox **will be used in future lab repetitions** for additional practice.
- Resources were deleted after each run to allow for re-creation and skill refinement.
- Screenshots have been redacted where necessary to protect tenant and resource information.


---

## 🚀 Next Steps

- Integrate Microsoft Defender with Sentinel via custom connectors
- Build a hybrid honeypot lab using Defender XDR and Azure VM analytics
- Expand SOAR automation with playbook chaining and adaptive responses
- Develop custom anomaly rules and test behavioral detection scenarios
