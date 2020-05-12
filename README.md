# vmbash
ARM script to install Software to VM


Command to create a Resource Group using azure cli

az group create --name trialresource --location "Central US"

Command to deploy the template to the resource group

az deployment group create --name pythonVM --resource-group trailresource -- template-file :<file_location>
