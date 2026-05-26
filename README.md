# Cloud Workshop Practice 🌐

A simple Flask web application for learning cloud computing concepts and CI/CD pipelines on Azure.

## What is This Project?

This project demonstrates **core cloud engineering skills**:
- Running applications on **Azure VMs** (Virtual Machines)
- Deploying web apps using **Azure Container Instances** and **Azure App Service**
- Building **automated CI/CD pipelines** with GitHub Actions

## Quick Start

### Run Locally
```bash
pip install -r requirements.txt
export FLASK_APP=app.py
flask run
```
Visit `http://localhost:5000` and add messages using `?msg=hello`

### Run with Docker
```bash
docker build -t cloudworkshop-app .
docker run -p 5000:5000 cloudworkshop-app
```

## Tech Stack
- **Python + Flask** - Web application
- **Docker** - Containerization
- **GitHub Actions** - CI/CD automation
- **Azure** - Cloud hosting (VMs, Web App, Container Registry)

## Deployment
The app automatically deploys to **Azure Web App** on every push to `main` branch using GitHub Actions.

## Learn More
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)
- [GitHub Actions Guide](https://docs.github.com/en/actions)
- [Flask Documentation](https://flask.palletsprojects.com/)

**License:** Apache 2.0
