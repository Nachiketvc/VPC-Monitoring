# 🚀 Monitoring and Analyzing VPC Traffic with AWS CloudWatch & Flow Logs  

## 🎯 Goal  
The objective of this project was to **monitor and analyze VPC network traffic** using **AWS CloudWatch and VPC Flow Logs** to improve **network visibility, security monitoring, and troubleshooting**.  

## 🔧 What I Did  

✅ **Created two VPCs** (`10.1.0.0/16` & `10.2.0.0/16`) and established **VPC Peering**.  
✅ **Launched EC2 instances** in each VPC and configured **Security Groups**.  
✅ **Enabled VPC Flow Logs** to capture network traffic.  
✅ **Configured IAM Roles & Policies** to allow Flow Logs to send data to CloudWatch.  
✅ **Stored logs in CloudWatch Log Groups** and used **CloudWatch Logs Insights** for analysis.  
✅ **Updated Route Tables** to enable **private IP communication** between instances.  
✅ **Ran queries in CloudWatch Logs Insights** to analyze traffic patterns and detect anomalies.  

## 📌 Why This Matters  
- 🛡️ **Enhances Security** – Helps detect unauthorized access or suspicious activity.  
- 🔍 **Improves Troubleshooting** – Analyzing logs helps resolve network issues faster.  
- 📊 **Provides Network Visibility** – Enables real-time monitoring of VPC traffic.  

## 📷 Project Snapshots  
![Log-Insight](Log-Insight-1.png)  

---


