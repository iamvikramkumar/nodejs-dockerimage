# Node.js Application Dockerization and Docker Hub Integration

This guide outlines the steps to create a Node.js application, Dockerize it, and push the Docker image to Docker Hub.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js
- Docker
- Docker Hub account

## Step 1: Create a Node.js Application

1. Create a new Node.js project:
   ```bash
   mkdir my-node-app
   cd my-node-app
   npm init -y

Create a simple Node.js application (e.g., app.js).

Install any necessary dependencies:
npm install express

Verify that your application runs successfully:
node app.js

Step 2: Dockerize the Node.js Application
Create a Dockerfile

Build the Docker image:

docker build -t my-node-app .

Verify the image is created successfully:

docker images

Step 3: Push Docker Image to Docker Hub
Log in to Docker Hub:

docker login

Tag the Docker image:
docker tag my-node-app:latest <your-dockerhub-username>/my-node-app:latest

Push the Docker image to Docker Hub:

docker push <your-dockerhub-username>/my-node-app:latest
Verify the image is available on Docker Hub.





