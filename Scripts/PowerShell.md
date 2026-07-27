\# Azure PowerShell Commands



This file contains the Azure PowerShell commands used while working on this project.



\## Connect to Azure



```powershell

Connect-AzAccount

```



\## Create Resource Group



```powershell

New-AzResourceGroup `

\-Name "resource1" `

\-Location "Central India"

```



\## Verify Resource Group



```powershell

Get-AzResourceGroup

```



\## Note



Most of the resources in this project were configured through the Azure Portal.

