# URL Shortener Application

This repository contains the source code for a URL Shortener service built with Express, React, PostgreSQL, and Nginx.

## Getting Started

To use this application, you need to have Docker installed on your machine. Follow these steps to set up the environment:

### 1. Pull Docker Images from Docker Hub

Run the following commands to pull the required Docker images from Docker Hub:

```bash
docker pull joshvermaire/postgres-url-shortener
docker pull joshvermaire/express-url-shortener
docker pull joshvermaire/react-url-shortener
docker pull joshvermaire/nginx-url-shortener
```

### 2. Run Docker Compose
Use Docker Compose to generate and run the containers. Navigate to the directory where the compose.yaml file is located and run:

```
docker-compose up
```

This command will create and start the containers defined in the compose.yaml file.

### 3. Access the Application
Once the container is up and running, you can access the application using the following URL:

http://localhost:8080


If you have any questions, feel free to reach out!