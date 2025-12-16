# Zabbix Monitoring on AWS EC2 using Docker

This repository demonstrates a complete Zabbix monitoring setup deployed on an AWS EC2 instance using Docker and Docker Compose.

## 📌 Architecture
- Zabbix Server, Web UI, and MySQL running as Docker containers
- Zabbix Agent 2 installed on the EC2 host
- Secure communication using private IP and VPC CIDR
- Email alerts configured using Gmail SMTP

## 🛠️ Technologies Used
- AWS EC2 (Ubuntu)
- Docker & Docker Compose
- Zabbix 7.x
- Gmail SMTP for alerting

## 🚀 Features
- CPU, Memory, and Disk monitoring
- Automatic filesystem discovery (LLD)
- Problem and Recovery email notifications
- Secure security group configuration
- Production-ready setup

## 📂 Documentation
Detailed step-by-step documentation is available here:

👉 [Zabbix Monitoring Setup Document](docs/Zabbix_Monitoring_Setup_AWS_Docker.docx)

## ✅ Validation
The setup has been tested with real disk usage simulation to validate:
- Trigger activation
- Email notification delivery
- Recovery alert handling

## 📌 Use Case
This project can be used as:
- Internal monitoring reference
- Learning resource for DevOps engineers
- Production baseline for Zabbix deployment

---

⭐ If you find this useful, feel free to star the repository!
