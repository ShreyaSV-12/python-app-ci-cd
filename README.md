# 🚀 Flask CI/CD Deployment on AWS EC2

This project demonstrates a **complete CI/CD pipeline** for a simple Flask web application using **GitHub Actions** and **AWS EC2**.

---

## 🧠 Overview
- **Continuous Integration (CI):** Automatically runs tests on every push.
- **Continuous Deployment (CD):** Deploys the Flask app to an AWS EC2 instance using SSH.
- **Flask App:** A simple Python web app containerized using Docker.

---

## ⚙️ Tech Stack
- **Python / Flask**
- **Docker**
- **GitHub Actions (CI/CD)**
- **AWS EC2 (Deployment Server)**

---

## 🧩 Project Structure
.github/workflows/
├── ci.yml
├── deploy-to-ec2.yml
app.py
Dockerfile
requirements.txt

---

## 🚀 How It Works
1. Developer pushes code to GitHub.
2. **GitHub Actions** automatically:
   - Runs tests (CI)
   - Connects to AWS EC2 via SSH
   - Builds and runs Docker container
3. App is deployed live at:  
   `http://54.173.107.65:5000`

---

## 🧑‍💻 Author
**Shreya S V**  
📍 Computer Science Engineer | Interested in DevOps & Cloud  
💼 GitHub: [ShreyaSV-12](https://github.com/ShreyaSV-12)
