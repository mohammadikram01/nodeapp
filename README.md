# 🚀 Node.js CI/CD Demo with GitHub Actions and Docker

## 📌 Project Objective
This project demonstrates how to set up a complete CI/CD pipeline using GitHub Actions to automatically build, test, and deploy a Node.js web app using Docker.

## 🧰 Tools Used
- Node.js
- Docker
- GitHub Actions
- DockerHub

## 🗂 Folder Structure
```
nodejs-demo-app/
├── app.js
├── package.json
├── Dockerfile
├── README.md
└── .github/
    └── workflows/
        └── main.yml
```

## ⚙️ How It Works
1. GitHub Actions triggers on push to `main`.
2. Workflow installs dependencies and runs tests.
3. Builds Docker image from `Dockerfile`.
4. Pushes the image to DockerHub.

## 🔐 Secrets Used
- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`

## ✅ Output
Once deployed, the app prints:
> Hello from Node.js CI/CD Demo App!

## 📸 Screenshot
(Insert a screenshot of successful GitHub Actions run here)

## 👨‍💻 Author
Mohammad Ikram
