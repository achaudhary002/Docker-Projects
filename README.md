# 📂 Docker Projects Information

## This repository contains a collection of hands-on projects focused solely on Docker.  These were the projects I did quite time ago while I was learning Docker at the time. In these projects, I have tried to include max concepts of Containerizaton in Docker, such as Containers, Docker engine, Docker commands, writing Dockerfile, Building Dockerimage using both Docker file or automating with Docker-compose. In addition, I have also applied the concepts of Docker Networking and, finally pushed the images to docker hub.  
---

## **1. Two-tier Flask Project **
**Two-Tier Flask App Project** [two-tier-flask](./two-tier-flask-app)  
- Runs Two-tier Flask App with simple Flask MSG and connects to the MYSQL DB connection. It has Dockerfile and Docker-compose.
- Covered important concepts of Docker Networking, Isolation, and MYSQL Data Backup and Persistence.

## **1. Three-tier Django Notes, Nginx Reverse Proxy Project **
**Three-Tier Django Notes App Project** [three-tier-django-notes-app](./django-notes-app)  
- Runs Three-tier-Notes-APP Flask App with simple Notes-App which collects the notes from User and Stores it to the database.  
- Runs Nginx, Frontend, and MYSQL on separate Containers all networked in same network. 
- Nginx does Reverse proxy for '/'url to the port 8000.

--- 
## ⭐ Learn More on Next Steps:
1. Clone the repository:

```bash
git clone https://github.com/achaudhary002/Docker-Projects.git
```
2. Read The Documentation:
    Each projects include the project documentation file. It explains in detail about all the steps, commands, and troubleshooting