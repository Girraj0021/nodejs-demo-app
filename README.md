# Node.js CI/CD Demo

## Project Overview

This project demonstrates a CI/CD pipeline using GitHub Actions.

## Technologies

- Node.js
- GitHub
- GitHub Actions
- Docker
- DockerHub

## CI/CD Pipeline

The pipeline performs the following steps:

1. Checkout source code
2. Setup Node.js
3. Install dependencies
4. Run tests
5. Build Docker image
6. Login to DockerHub
7. Push Docker image to DockerHub

## How to Run Locally

Install dependencies:

npm install

Start application:

npm start

Open:

http://localhost:3000

## Docker

Build image:

docker build -t nodejs-demo-app .

Run container:

docker run -p 3000:3000 nodejs-demo-app