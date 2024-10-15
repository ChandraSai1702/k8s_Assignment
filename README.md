# README: Deploying a Java Web Application on Kubernetes
This document provides a step-by-step guide to deploying a Java web application on a Tomcat server using Kubernetes.

## Prerequisites
Java (JDK 8 or higher)
Maven (for building the JAR file)
Docker (for creating the Docker image)
Kubernetes (Minikube for local deployment or any cloud Kubernetes service)
kubectl (Kubernetes command-line tool)

# Steps to Deploy the Service
### Step 1: Create YAML Files for the Service
Create the following YAML files for deploying the application in Kubernetes.
1. deployment.yml
2. service.yml
### Step 2: Create JAR/WAR for the Service
Run ```mvn clean package```
### Step 3: Create a Dockerfile
### Step 4: Build the Docker Image
### Step 5: Deploy the Application in Kubernetes
### Step 6: Access the Application
``` minikube service my-webapp --url ```
  
