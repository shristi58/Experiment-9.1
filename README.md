# Dockerize a React Application with Multi-Stage Build

## Objective
Create a production-ready Docker image for a React app using multi-stage builds to reduce image size and separate build/runtime environments.

## Steps
1. Build a React app:
   ```bash
   npx create-react-app my-react-docker-app
2. Add the provided Dockerfile and .dockerignore.

3.Build and run:

docker build -t react-app .
docker run -p 80:80 react-app

   
