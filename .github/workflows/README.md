# Flask CI/CD Pipeline on AWS EC2

## 🚀 Project Overview
This project demonstrates a **CI/CD pipeline** for a Flask app using:
- Python Flask
- Docker
- GitHub Actions
- AWS EC2
- Nginx (Reverse Proxy)

---

## 🔹 Setup Steps

### 1. Launch EC2
- Ubuntu 22.04, allow ports 22, 80, 5000.

### 2. Install Dependencies
```bash
sudo apt update -y && sudo apt upgrade -y
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker ubuntu
sudo apt install nginx -y
