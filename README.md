
🚀 PROJECT : Azure App Service Monitoring & Diagnostics

🔹 Services which Used
App Service basics (PaaS)
Application Insights
Monitoring + alerts 

📘 GitHub README Content 
📌 Project Title

Azure App Service Monitoring & Diagnostics

📖 Overview

This project demonstrates how to deploy a web application on Azure App Service and configure monitoring using Application Insights. It helps in tracking performance, availability, and troubleshooting issues using logs and alerts.

🛠️ Services Used
Microsoft Azure
Azure App Service
Application Insights
Azure Monitor
⚙️ Step-by-Step Implementation
1. Create Resource Group
Go to Azure Portal
Search → Resource Groups → Create
Name: rg-app-monitoring
2. Create App Service
Search → App Services → Create
Runtime: Node.js / .NET (any)
Region: same as resource group
Click Create
3. Deploy Sample App
Go to App Service → Deployment Center
Choose Local Git / Sample Code
Deploy default app
4. Enable Application Insights
Go to App Service → Application Insights
Click Turn On
Create new instance
5. Monitor Application
Go to Application Insights
Check:
Live Metrics
Failures
Performance
6. Configure Alerts
Go to Azure Monitor → Alerts
Create Alert Rule:
Condition: CPU / Response Time
Action: Email notification
📊 Outcome
Successfully monitored application performance and failures
Configured alerts for proactive issue detection
Gained hands-on experience with Azure monitoring tools
