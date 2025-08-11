# Project 2 – Azure Virtual Machine Monitoring

## 📌 Overview
This project was implemented to monitor Azure Virtual Machines hosting critical services for Skill-up Technologies.  
Azure Monitor was configured to track key performance metrics and send proactive alerts for issue detection.

---

## ✅ Project Implementation

### **1. Resource Group & VM Deployment**
- Created a dedicated Resource Group.
- Deployed a VM (Windows/Linux) with free-tier eligible size (B1s/B1ls) and configured username/password.

### **2. Azure Monitor Configuration**
- Enabled performance data collection for CPU, memory, disk, and network metrics.

### **3. Metrics Monitoring**
- Accessed real-time performance data in the Metrics section.
- Adjusted time range and interval for detailed analysis.

### **4. Alerts Setup**
- Configured alert rules for CPU usage thresholds.
- Created an Action Group to send email notifications.
- Verified costs stayed within the Azure free-tier.

### **5. Testing**
- Simulated high CPU usage.
- Confirmed alerts triggered and email notifications were received successfully.

---

## 🧰 Tools & Services Used
- **Azure Services** – Resource Groups, Virtual Machines, Azure Monitor, Alerts & Action Groups

---



## 📸 Screenshots 

1. VM metrics dashboard.  

<img width="718" height="397" alt="image" src=./screenshots/Image1.png />

<img width="718" height="397" alt="image" src=./screenshots/Image2.png />

2. CPU usage alert configuration.  

<img width="718" height="397" alt="image" src=./screenshots/Image3.png />

<img width="718" height="397" alt="image" src=./screenshots/Image4.png />

3. Alert email notification received.

<img width="718" height="397" alt="image" src=./screenshots/Image5.png />

<img width="718" height="397" alt="image" src=./screenshots/Image6.png />


## 📚 Learnings
- Provisioning and configuring **Azure Virtual Machines** efficiently.
- Setting up **Azure Monitor** for VM performance tracking.
- Understanding **key performance metrics** (CPU, memory, disk, network).
- Creating and managing **alert rules** and **action groups**.
- Testing and validating monitoring and alerting workflows.

---


