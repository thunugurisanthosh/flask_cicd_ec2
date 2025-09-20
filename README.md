# Flask CI/CD Pipeline on AWS EC2




<img width="1920" height="1016" alt="Screenshot (84)" src="https://github.com/user-attachments/assets/a9b6f316-d0af-428b-9b9e-825f7b25966a" />

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
