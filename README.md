# docker-compose-project
# Three-Tier Application Deployment using Docker Compose
[![LinkedIn](https://img.shields.io/badge/Connect%20with%20me%20on-LinkedIn-blue.svg)](https://www.linkedin.com/in/aman-devops/)
[![GitHub](https://img.shields.io/github/stars/AmanPathak-DevOps.svg?style=social)](https://github.com/AmanPathak-DevOps)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/u/avian19)

![Architecture](assets/Infra.gif)

This repository showcases the deployment of a three-tier application using Docker Compose. The application consists of a MySQL database, a Node.js backend, and a React.js frontend.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)


# Project Structure
- frontend: Dockerfile and related files for the React.jsfrontend.

- backend: Dockerfile and related files for the Node.jsbackend.

- docker-compose.yml: Docker Compose configuration file.

- student-teacher-app: Code for the frontend application.

- backend: Code for the backend application.

# Deployment Steps
- Clone the Repository:

- git clone https://github.com/devcloudninjas/docker_handson_projects.git
  -cd docker-compose

- Build and Run Docker Containers: Use Docker Compose to build and run all containers:
    -docker-compose up -d
  ![Screenshot (6)](https://github.com/user-attachments/assets/096afa1d-f447-4a28-aedb-48c6ebbfe583)

# Access the Application: Open your favorite browser and visit http://localhost:80. Explore the MERN stack application!
![Screenshot (7)](https://github.com/user-attachments/assets/1fa236e5-af10-416f-8e45-f042a05cce14)
