# ARM
File arm-rg.json creates a resource group and a storage account in this group at the same time.
https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-subscription?tabs=azure-cli#create-resource-group-and-resources

To run in type in your CLI:
{code}az deployment sub create --name infraDeploy --location centralus  --template-file arm-rg.json{code}
