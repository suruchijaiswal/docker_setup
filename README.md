# Dockerized setup for RMA Microservices + API Gateways

# 🚀 RMA Microservices Docker Setup

This project provides a **Dockerized setup** for the **RMA Microservices** ecosystem.  
It runs the following components:

- **PostgreSQL Database**
- **Eureka Server (Service Registry)**
- **API Gateway**
- **User Management Service**
- **Project SOW Service**
- **Resource Allocation Service**
- **Reporting Integration Service**
- **Master Resource Service**

---

## 📂 Project Structure

```
project-root/
├── rma_java_microservices/
├── api-gateway-main/
└── docker-setup/   
```


## ⚙️ Prerequisites

1. **Install Docker Desktop**
   - Windows: [Download Docker Desktop](https://www.docker.com/products/docker-desktop/)
   - Enable **WSL 2 backend** in settings.
   - Allocate:
     - **4 CPUs**
     - **6–8 GB RAM**

2. **Check installation**
   ```powershell
   docker --version
   docker compose version


## Run
```
cd docker-setup
docker compose build
docker compose up -d
```

