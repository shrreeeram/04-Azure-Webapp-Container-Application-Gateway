\# Challenges



\## Challenge 1: Dedicated Subnet Requirement



\### Issue

Application Gateway deployment requires a dedicated subnet.



\### Resolution

Created a separate subnet named `appgw-subnet` before deploying the Application Gateway.



\---



\## Challenge 2: Backend Health Status



\### Issue

The backend was initially marked as unhealthy.



\### Resolution

Configured the backend settings to use \*\*Pick Host Name From Backend Target\*\*, allowing the Application Gateway to communicate correctly with the Azure Web App.



\---



\## Challenge 3: Container Image Configuration



\### Issue

The container image must be correctly configured for successful deployment.



\### Resolution

Verified the Docker Hub registry URL, image name, image tag, and exposed container port (80).



\---



\## Challenge 4: Deployment Time



\### Issue

Application Gateway provisioning took longer than expected.



\### Resolution

Waited for the deployment to complete before testing the application.

