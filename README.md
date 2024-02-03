# AZURE
 ### Download azure cli from https://learn.microsoft.com/en-us/cli/azure/
 ### And run Azure CLI 
 ### Run Command 
      az version

 #### You can see output like:-
     {
        
     "azure-cli": "2.56.0",
  
     "azure-cli-core": "2.56.0",
  
     "azure-cli-telemetry": "1.1.0",
  
     "extensions": {}
  
        }

## Automation : Create AZURE Resouce Group Using CLI

    az group create --name resource_name --location location_name

## Create Azure VM using Azure CLI
     az vm create `
      --resource-group automation-group `
      --name autovm `
      --image Ubuntu2204 `
      --vnet-name autovnet `
      --subnet examle-subnet `
      --generate-ssh-keys `
      --output json `
      --verbose
