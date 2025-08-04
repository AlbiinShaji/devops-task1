# 🚀 DevOps Task 1 – CI/CD Pipeline using GitHub Actions & Docker

Hey there 👋  
This is my submission for **Task 1** of the DevOps Internship program.

In this project, I’ve set up a complete **CI/CD pipeline** using **GitHub Actions** and **Docker** to automatically build and push a simple Node.js app to **DockerHub** whenever I push code to the `main` branch.

---

## 🛠️ Tools & Technologies Used

- **Node.js + Express** – to build the basic app
- **Git & GitHub** – for version control and automation
- **GitHub Actions** – to set up the CI/CD pipeline
- **Docker & DockerHub** – for containerizing and hosting the app

---

## 🔁 What the CI/CD Pipeline Does

Every time I push code to the main branch:

1. GitHub Actions gets triggered
2. It installs dependencies for the app
3. Builds a Docker image using the Dockerfile
4. Logs in to my DockerHub using GitHub Secrets
5. Pushes the image automatically to my DockerHub account

> Fully automated! 🧠

---

## 🐳 DockerHub Link

Here’s the live Docker image I pushed:  
🔗 [https://hub.docker.com/r/a1b1nshaj1/node-demo-app](https://hub.docker.com/r/a1b1nshaj1/node-demo-app)

---

## ▶️ How to Run the App Locally (Optional)

If you want to test it on your own system:

```bash
docker pull a1b1nshaj1/node-demo-app
docker run -p 3000:3000 a1b1nshaj1/node-demo-app
