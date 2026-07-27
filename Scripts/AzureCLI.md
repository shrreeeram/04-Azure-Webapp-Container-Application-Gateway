\# Azure CLI Commands



This file contains the Azure CLI commands that can be used to deploy or manage the resources created in this project.



\## Login



```bash

az login

```



\## Resource Group



```bash

az group create --name resource1 --location centralindia

```



\## Virtual Network



```bash

az network vnet create \\

\--resource-group resource1 \\

\--name vnet1 \\

\--address-prefix 10.0.0.0/16 \\

\--subnet-name appgw-subnet \\

\--subnet-prefix 10.0.0.0/24

```



\## Note



The remaining resources for this project were configured through the Azure Portal.

