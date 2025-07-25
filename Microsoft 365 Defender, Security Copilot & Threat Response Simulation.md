🔍 Overview
This lab focuses on simulating modern SOC tasks using Microsoft 365 Defender, Microsoft Defender XDR, Security Copilot, Microsoft Purview, and Defender for Endpoint. The exercises were designed to reflect real-world workflows across detection, investigation, hunting, and compliance.

✅ Lab Tasks Completed
1. 🔐 Obtained Microsoft 365 Credentials
Retrieved tenant email and admin password from lab portal/provider.

Logged in to Microsoft 365 security portal successfully.

2. 🛡️ Applied Defender for Office 365 Preset Policies
Signed into Microsoft Defender portal.

Enabled Standard and Strict preset policies:

Anti-spam

Anti-malware

Anti-phishing

Safe Links

Safe Attachments

3. 🧭 Initialized Microsoft Defender XDR Workspace
Opened Microsoft 365 Defender portal.

Verified Defender XDR workspace was initialized and ready.

4. ⚙️ Provisioned Security Copilot Capacity
Enabled Azure resource access.

Assigned Owner role at the subscription and resource group level.

Deployed and verified Security Copilot capacity.

5. 🧪 Explored Standalone Copilot
Opened Copilot portal.

Navigated tabs: Sessions, Promptbooks, Roles, and Settings.

Verified provisioning and configuration.

6. 🤖 Used Copilot Embedded in Defender XDR
Investigated a Defender XDR incident using Copilot’s embedded AI assistant.

Reviewed:

Incident summaries

Alert timeline

Relevant scripts and files

Switched to Standalone Copilot for full promptbook exploration.

7. 🕵️‍♂️ Ran a KQL Query via Copilot
Prompted Copilot to generate a custom KQL hunting query.

Executed the query under Advanced Hunting in Defender XDR.

8. 📜 Enabled Microsoft Purview Audit Logs
Accessed Microsoft Purview portal.

Enabled Audit (Standard) to capture and track user and admin activities.

9. 🧩 Initialized Microsoft Defender for Endpoint
Enabled device discovery within Defender for Endpoint.

Validated detection of a discovered Windows device.

10. 🖥️ Onboarded a Device
Downloaded onboarding package.

Executed local onboarding script on Windows client.

Device appeared in Device Inventory successfully.

11. 👥 Configured Roles
Created a custom role: Tier 1 Support.

Defined permissions and assigned users from Azure AD.

12. 🧾 Created Device Group
Created group: Regular

Target: Windows 10/11

Permissions: Full Remediation

Group assigned to Defender roles

13. ✅ Enabled Regulatory Compliance Standards
Accessed Microsoft Defender for Cloud

Enabled ISO/IEC 27001:2013 compliance standard for subscription

14. 📌 Reviewed Security Recommendations
Filtered recommendations for Azure Arc systems.

Assigned action items to admin with due date for remediation.

15. 🚨 Reviewed and Responded to Alerts
Triggered sample alerts.

Investigated via:

Alert Details

Incident Graph

Timeline

Tracked attack paths and incident severity.
