# task5-minikube
# Kubernetes Deployment Project

This project demonstrates the deployment of a sample application on a local Kubernetes cluster using Minikube. The purpose of this project is to understand how to deploy, expose, and access applications using Kubernetes.

---

## **Project Overview**

In this project, I set up a Kubernetes environment on my local machine using Minikube and WSL/Ubuntu. I created a deployment YAML file to deploy a sample application and exposed it as a NodePort service to access it via a browser.

Key objectives of the project were:  
- Setting up Minikube and Kubernetes locally.  
- Deploying a containerized application using `kubectl`.  
- Exposing the application through a Kubernetes service.  
- Testing and accessing the application in the browser.  

---

## **Tools and Technologies Used**

- **Kubernetes** – for container orchestration.  
- **Minikube** – to run Kubernetes locally.  
- **kubectl** – command-line tool to interact with the cluster.  
- **WSL (Ubuntu)** – to run a Linux environment on Windows.  
- **Docker** – for containerizing the application (if applicable).  
- **VS Code** – for editing YAML and project files.  

---

## **Setup and Steps Performed**

1. **Installed WSL (Ubuntu 22.04)** on Windows.  
2. **Installed Minikube and kubectl** inside WSL.  
3. **Started Minikube** to create a local Kubernetes cluster:

   ```bash
   minikube start
