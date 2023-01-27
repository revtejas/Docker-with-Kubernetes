## Objectives
- Building Java application using Maven
- Containerize images & Deploy to docker hub
- Deploying onto Kubernetes

## Procedure
- Commit project to Github
- Build your code to convertt that to jar file. To convert we'll use Maven build.
- Using the jar file we will be using a docker build. This is to build your java or springboot application into a docker image.
- We'll use dockerfile commands to copy the jar file into docker image.
- Once you build docker image, we need to push the docker image to docker hub because we need a repo to store our docker image
- Using the image in the docker hub, we will be deploying the application into kubernetes cluster. (It can be minicube or multiple nodes cluster)

## Pre-requisite
- Java application
- Docker installed
- Kubernetes cluster
- Basic knowledge on Mave, Docker, Kubernetes

## Implementation

