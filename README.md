# Deploy Azure Web App (Container) with Azure Application Gateway

## Project Overview

This project demonstrates how to deploy a containerized React application on Azure App Service and publish it securely through Azure Application Gateway. The application image is hosted on Docker Hub, while Azure Application Gateway acts as a Layer 7 Load Balancer to route HTTP requests to the backend Azure Web App.

---

## Architecture

Refer to the architecture diagram inside the Architecture folder.

---

## Project Objectives

- Deploy a containerized React application.
- Create an Azure App Service using Linux.
- Pull the container image from Docker Hub.
- Configure Azure Application Gateway.
- Route incoming HTTP traffic to the Azure Web App.
- Verify successful deployment.

---

## Azure Services Used

- Azure Resource Group
- Azure Virtual Network
- Azure Subnet
- Azure Public IP
- Azure Application Gateway
- Azure App Service
- App Service Plan

---

## Technologies Used

- Microsoft Azure
- Docker
- Docker Hub
- React
- HTTP

---

## Project Workflow

1. Create Resource Group
2. Create Virtual Network
3. Create Dedicated Subnet
4. Deploy Azure Web App
5. Configure Docker Container
6. Create Application Gateway
7. Configure Frontend Listener
8. Configure Backend Pool
9. Configure Backend Settings
10. Create Routing Rule
11. Test the Application

---

## Project Structure

Architecture/
Deployment-Guide/
Screenshots/
Video/
Scripts/
Docs/

---

## Result

The React application was successfully deployed on Azure App Service and accessed through Azure Application Gateway using the Public IP Address.

---

## Skills Demonstrated

- Azure Networking
- Azure Application Gateway
- Azure App Service
- Docker Integration
- Container Deployment
- Layer 7 Load Balancing
- Backend Pool Configuration
- HTTP Routing

---

## Future Enhancements

- HTTPS Configuration
- SSL Certificate
- Custom Domain
- Web Application Firewall (WAF)
- Azure Monitor
- GitHub Actions CI/CD
- Bicep/Terraform Deployment
