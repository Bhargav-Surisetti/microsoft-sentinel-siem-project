# 🛡️ Microsoft Sentinel SIEM Implementation on Azure

## 📘 Overview
This project demonstrates the end-to-end implementation of **Microsoft Sentinel**, a cloud-native **Security Information and Event Management (SIEM)** and **Security Orchestration, Automation, and Response (SOAR)** solution on **Microsoft Azure**.

It provides a practical guide to deploying Sentinel, connecting data sources, enabling AI-driven analytics, and building an operational **Security Operations Center (SOC)** for real-time threat detection and automated response.

---

## 🚀 Objectives
- Deploy Microsoft Sentinel on Azure using the **Sentinel All-in-One** template.  
- Integrate **diagnostic logs** from Azure services for centralized monitoring.  
- Enable **AI-based User and Entity Behavior Analytics (UEBA)**.  
- Create **watchlists** for threat detection.  
- Perform **incident investigation and remediation** workflows.  
- Build a complete **SOC simulation** using Microsoft Sentinel.

---

## 🧰 Requirements
1. **Azure Account** – Active subscription required.  
2. **Resource Group** – To organize Sentinel-related resources.  
3. **Log Analytics Workspace** – To store logs and analytics data.  
4. **Permissions** – Owner or Contributor access in Azure.  
5. **Basic Knowledge** – Familiarity with Azure Portal and security operations.

---

## ⚙️ Implementation Steps

### **Step 1: Deploy Microsoft Sentinel**
- Use Microsoft’s [Sentinel All-In-One GitHub Template](https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One).  
- Deploy via the **“Deploy to Azure”** button to automatically create:  
  - Log Analytics Workspace  
  - Sentinel-enabled environment  
  - Automation Account and Playbooks  

### **Step 2: Connect Data Sources**
- Configure **Diagnostic Settings** in Azure resources (e.g., Azure AD, Key Vault, Storage).  
- Send logs to your Sentinel **Log Analytics Workspace**.  

### **Step 3: Enable AI (UEBA)**
- Turn on **User and Entity Behavior Analytics** in Sentinel.  
- Connect identity logs (Azure AD, Defender for Cloud Apps, Microsoft 365 Defender).  
- Use AI models to detect anomalies and suspicious user behavior.

### **Step 4: Create Watchlists**
- Create custom **CSV-based watchlists** (e.g., suspicious IPs, high-value assets).  
- Use watchlists for enhanced threat detection in Sentinel analytics rules.

### **Step 5: Create Investigation User**
- Add a **dedicated SIEM Investigator account** with least-privilege roles.  
- Assign roles like `Sentinel Reader` or `Sentinel Contributor`.  

### **Step 6: Generate Test Incidents**
- Simulate safe incidents using test accounts and sign-in attempts.  
- Validate alerts, playbooks, and automation rules in Sentinel.

### **Step 7: Investigate Incidents**
- Use **Incident Overview**, **Investigation Graph**, and **KQL Queries**.  
- Correlate alerts and identify root causes through Sentinel dashboards.  

### **Step 8: Perform Remediation**
- Disable compromised users.  
- Restore diagnostic settings and enable auditing/health monitoring.  
- Ensure continuous telemetry for proactive threat management.

---

## 📊 Results
✅ Microsoft Sentinel successfully deployed and integrated with Azure resources.  
✅ AI-based behavioral analytics (UEBA) enabled.  
✅ Watchlists, incidents, and automation workflows validated.  
✅ End-to-end SOC operations (detection → investigation → remediation) completed.

---

## 🧠 Key Learnings
- Centralized cloud-native security monitoring using Azure Sentinel.  
- AI-driven threat detection with UEBA.  
- Hands-on experience in SOC investigation and incident response.  

---

## 🧩 Tools & Technologies
- **Microsoft Azure**  
- **Microsoft Sentinel**  
- **Log Analytics Workspace**  
- **Azure Active Directory**  
- **Microsoft Defender Suite**  
- **KQL (Kusto Query Language)**  

---

## 📅 Project Info
**Author:** Bhargav Pavan Sai Surisetti  
**Date:** 08-10-2025  
**Category:** Cloud Security / SIEM Implementation  
**Platform:** Microsoft Azure  

---

## 🏁 Conclusion
This project showcases the complete lifecycle of deploying and managing a **cloud-native SIEM system** using Microsoft Sentinel. By integrating Azure resources, enabling AI analytics, and simulating incidents, it provides a comprehensive understanding of **modern SOC operations** in a cloud environment.
