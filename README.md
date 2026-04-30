# Multi-Container vProfile Deployment with Docker Compose

## 📌 Overview

This project demonstrates deployment of a multi-tier application stack using Docker Compose on Linux.

The application architecture consists of multiple services working together in a production-style environment.

## 🏗️ Architecture

* **Web Layer** → Nginx
* **Application Layer** → Java/Tomcat Application
* **Database** → MySQL
* **Cache Layer** → Memcached
* **Queue Service** → RabbitMQ

## 🚀 Technologies Used

* Docker
* Docker Compose
* Linux
* Nginx
* Tomcat
* MySQL
* Memcached
* RabbitMQ

## ⚙️ How to Run

```bash
docker compose up -d
```

Check running containers:

```bash
docker ps
```

Stop services:

```bash
docker compose down
```

## 🌐 Access Application

Open in browser:

```text
http://localhost
```

## 📚 Key Learnings

* Multi-container deployments
* Container networking
* Volumes and persistent storage
* Port mapping
* Service orchestration
* Real-world DevOps architecture

## 🎯 Future Improvements

* Convert to production-ready setup
* Add CI/CD pipeline
* Add monitoring (Prometheus/Grafana)
* Security hardening
* Kubernetes deployment

## 👨‍💻 Author

Deepanshu Prabhakar
