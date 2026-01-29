# DevOps Task 9 – Docker Basics (PHP Application)

## 📌 Task Overview
This task focuses on understanding Docker fundamentals by containerizing a simple PHP application. The objective is to learn how Docker images and containers work using a Dockerfile.

---

## 🛠 Tools Used
- Docker Desktop
- PHP (CLI)
- Command Prompt (CMD)

---

## 📂 Application Description
A simple PHP application is created that prints a message to the console. This application is containerized using Docker to demonstrate the basics of image creation and container execution.

---

## 🐳 Dockerfile Explanation
- **FROM php:8.2-cli**  
  Uses the official PHP CLI base image.
- **WORKDIR /app**  
  Sets the working directory inside the container.
- **COPY index.php .**  
  Copies the PHP file into the container.
- **CMD ["php", "index.php"]**  
  Executes the PHP application when the container starts.

---

## ▶️ Steps Performed
1. Installed and verified Docker installation
2. Created a simple PHP application
3. Wrote a Dockerfile for the PHP app
4. Built a Docker image using Docker CLI
5. Ran the container successfully
6. Verified output in the command line
7. Cleaned up containers and images

---

## ▶️ Docker Commands Used

```bash
docker version
docker build -t docker-task-9-php .
docker run docker-task-9-php
docker ps -a
docker stop <container_id>
docker rm <container_id>
docker rmi docker-task-9-php

📸 Output

The successful execution of the PHP application inside the Docker container is captured as a screenshot and included in the repository.

🎯 Final Outcome

This task helped me understand Docker basics, including Dockerfile structure, image creation, container execution, and cleanup. It strengthened my understanding of containerization concepts.