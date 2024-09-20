# Getting Started

## Introduction
This guide will help you get started with setting up and running a simple Nginx server that serves an endpoint.

## Prerequisites
- Docker installed on your machine
- Basic knowledge of Docker and Nginx

## Steps

### 1. Clone the Repository
First, clone the repository to your local machine:
```bash
git clone https://github.com/your-repo-url.git
cd your-repo-directory

### 2. Build the docker image
docker build -t my-nginx-image .

### 3. Run the docker container
docker run -d -p 80:80 my-nginx-image

### 4. Access the Endpoint
Open your web browser and navigate to http://localhost/. You should see the content served by your Nginx server.
