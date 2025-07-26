# 🛡️ Microsoft 365 Defender, Security Copilot & Threat Response Simulation

This project simulates end-to-end security operations using Microsoft 365 Defender, Security Copilot, Microsoft Purview, and Defender for Endpoint. It covers threat policy configuration, incident response, role-based access, audit tracking, and compliance standards.

---

## 🔧 Lab Tasks

### ✅ 1. Defender for Office 365 & XDR Setup
- Enabled **Standard** and **Strict** preset protection policies:
  - Anti-phishing, anti-malware, anti-spam
  - Safe Links and Safe Attachments
- Defender XDR workspace was initialized successfully
- Device discovery was enabled to detect unmanaged endpoints

![Defender Policies](images/1.1.png)

![Protection Profiles](images/2.1.png)

![Anti-Spam Policies](images/3.1.png)

![Device Discovery](images/4.1.png)

📸 `./screenshots/m365-defender/defender-policies.png`  
📸 `./screenshots/m365-defender/protection-profiles.png`  
📸 `./screenshots/m365-defender/anti-spam-policies.png`  
📸 `./screenshots/m365-defender/device-discovery.png`

---

### ✅ 2. Security Copilot Provisioning
- Assigned **Owner** role in Azure IAM  
- Set up **Copilot capacity** in the Security compute portal  
- Verified provisioning completion in Copilot portal  
- Confirmed owner permissions in role assignment panel  

📸 `./screenshots/m365-defender/iam-role-assignment.png`  
📸 `./screenshots/m365-defender/copilot-capacity-setup.png`  
📸 `./screenshots/m365-defender/copilot-provisioned.png`  
📸 `./screenshots/m365-defender/copilot-role-assignment.png`

---

### ✅ 3. Endpoint Configuration & RBAC
- **Onboarded** a test device using PowerShell  
- Created custom role **Tier 1 Support** with security read permissions  
- Defined **Device Group**: Regular (Full Remediation access)

📸 `./screenshots/m365-defender/onboarded-device.png`  
📸 `./screenshots/m365-defender/role-creation.png`  
📸 `./screenshots/m365-defender/device-group.png`

---

### ✅ 4. Audit Logs & Compliance Standards
- Enabled **Audit (Standard)** logging in Microsoft Purview  
- Activated compliance standard: **ISO/IEC 27001:2013**

📸 `./screenshots/m365-defender/audit-enabled.png`  
📸 `./screenshots/m365-defender/compliance-device-inventory.png`

---

### ✅ 5. Threat Simulation & Incident Analysis
- Executed test **PowerShell alert** using simulated command  
- Verified **security alerts** in Defender portal  
- Analyzed incident propagation using **Incident Graph**

📸 `./screenshots/m365-defender/simulated-command.png`  
📸 `./screenshots/m365-defender/alert-timeline.png`  
📸 `./screenshots/m365-defender/incident-graph.png`

---

## 🧠 Skills Demonstrated

- Defender for Office 365 policy configuration  
- Security Copilot provisioning and IAM role setup  
- Device onboarding and grouping  
- Role-based access configuration  
- Audit logging and compliance standards (ISO 27001)  
- Alert triage and incident graph analysis

---

