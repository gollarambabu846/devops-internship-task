
# DevOps Internship - Containerized App Deployment

## Project Overview
A simple web application deployed using Docker
on AWS EC2.

## Technologies
- AWS EC2
- Ubuntu 24.04
- Docker
- Nginx
- Git and GitHub

## Run Locally

Build the Docker image:

docker build -t devops-internship-app .

Run the container:

docker run -d -p 8081:8081 --name devops-app devops-internship-app

Open:

http://localhost:8081
