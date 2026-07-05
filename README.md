# 🚀 AWS EC2 Instance Health Check Utility

A lightweight **Python-based EC2 Health Monitoring Tool** that collects and displays key system metrics from an Amazon EC2 instance, enabling administrators to quickly assess server health.

---

## 📌 Overview

This project monitors the health of an EC2 instance by retrieving essential system metrics such as:

- 🖥 CPU Utilization
- 💾 RAM (Memory) Usage
- 📀 Disk Usage

The script is useful for cloud administrators, DevOps engineers, and system administrators who need a simple command-line utility for monitoring Linux-based EC2 instances.

---

## ✨ Features

- Monitor CPU utilization
- Monitor RAM usage
- Monitor Disk usage
- Lightweight Python implementation
- Easy to configure
- Virtual environment support
- Beginner-friendly
- Suitable for AWS EC2 Linux instances

---

## 🛠 Technologies Used

- Python 3
- Linux
- AWS EC2
- Virtual Environment (venv)

---

## 📂 Project Structure

```
aws_ec2.instance_healthcheckup/
│
├── server_health.py
├── README.md
└── requirements.txt (optional)
```

---

## 📋 Prerequisites

Before running the project, ensure you have:

- Python 3.x installed
- Ubuntu/Linux EC2 Instance
- Terminal access (SSH)
- Python Virtual Environment (recommended)

---

## ⚙️ Installation

### Step 1: Install Virtual Environment

```bash
sudo apt update
sudo apt install python3-venv -y
```

---

### Step 2: Create a Virtual Environment

```bash
python3 -m venv myenv
```

---

### Step 3: Activate the Virtual Environment

```bash
source myenv/bin/activate
```

Your terminal should look similar to:

<p align="center">
<img src="https://github.com/user-attachments/assets/26b2e358-a885-4ae8-b802-3292745fdbb1" width="450">
</p>

---

### Step 4: Run the Script

```bash
python3 server_health.py
```

---

## 📊 Sample Output

The script displays system metrics similar to:

<p align="center">
<img src="https://github.com/user-attachments/assets/180afc06-0065-425a-a540-0c510ba56f4d" width="300">
</p>

Example:

```
CPU Usage  : 18%
RAM Usage  : 42%
Disk Usage : 57%
```

---

## 📸 Project Screenshot

<p align="center">
<img src="https://github.com/user-attachments/assets/196f0949-c74f-4152-a297-b58ed0191f23" width="700">
</p>

---

## 💡 Use Cases

- AWS EC2 Health Monitoring
- Linux Server Monitoring
- Cloud Administration Practice
- DevOps Learning
- Server Performance Checks
- Infrastructure Monitoring

---

## 🚀 Future Enhancements

- CloudWatch Integration
- Email Alerts
- Slack Notifications
- Disk I/O Monitoring
- Network Utilization Monitoring
- Multi-Instance Monitoring
- Scheduled Health Checks using Cron
- Grafana Dashboard Integration
- Prometheus Metrics Export
- Docker Support

---

## 📚 Skills Demonstrated

- Python Scripting
- Linux Administration
- AWS EC2
- Server Monitoring
- Infrastructure Health Checks
- Cloud Operations
- Command Line Interface (CLI)

---

## 👨‍💻 Author

**Aryan Jain**

Cloud Support Engineer | AWS | Microsoft Azure | Google Cloud Platform

---

## ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork the repository
- 📢 Share it with others

Happy Learning! 🚀
