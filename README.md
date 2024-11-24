# Bicep-code
Case study IaC


az group create --name exampleRG --location eastus

az deployment group create --resource-group exampleRG --template-file demo.bicep
