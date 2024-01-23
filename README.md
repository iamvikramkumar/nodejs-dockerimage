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

# Create a simple Node.js application (e.g., app.js).

1. Install any necessary dependencies:
   ```bash
   npm install express

2. Verify that your application runs successfully:
   ```bash
   node app.js

## Step 2: Dockerize the Node.js Application
1. Create a Dockerfile

2. Build the Docker image:
   ```bash
   docker build -t <your node app name> .

3. Verify the image is created successfully
   ```bash
   docker images

## Step 3: Push Docker Image to Docker Hub
1. Log in to Docker Hub
   ```bash
   docker login

2. Tag the Docker image:
   ```bash
   docker tag  <your node app name>:latest <your-dockerhub-username>/ <your node app name>:latest

3. Push the Docker image to Docker Hub
   ```bash
   docker push <your-dockerhub-username>/ <your node app name>:latest
4. Verify the image is available on Docker Hub.
# Congratulations! You have successfully created a React.js application, Dockerized it, and pushed the Docker image to Docker Hub.

<div align="center">
 
### Thanks For Watch This Repositories!

### <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"><i>KEEP AWESOME & STAY COOL!</i><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">

### Feel Free To Fork And Report If You Find Any Issue :)

![Star Badge](https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99)
[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/iamvikramkumar?tab=repositories)
[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/iamvikramkumar)
</div>





