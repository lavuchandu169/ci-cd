# 🚀 CI/CD Pipeline for Deploying an HTML File to AWS S3

This project sets up a **CI/CD pipeline** using **GitHub Actions** to automatically deploy an `index.html` file to an **AWS S3 bucket** whenever code is pushed to the `main` branch.

## 📌 Features
- ✅ **Automated deployment** of `index.html` to AWS S3.
- ✅ **GitHub Actions** triggers the deployment on every push to `main`.
- ✅ **Secure authentication** using AWS credentials stored in **GitHub Secrets**.
- ✅ **No manual intervention** required after setup.

---

## 📂 Project Structure
github/ │ ├── workflows/ │ │ ├── deploy.yml # GitHub Actions workflow file │── index.html # Static HTML file to be deployed │── main.tf # Terraform configuration for S3 bucket (optional) │── README.md
