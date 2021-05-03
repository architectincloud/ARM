## Azure ARM

ARM Documentation: https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-subscription?tabs=azure-cli#create-resource-group-and-resources

> Change Management is a standardized process where we do changes in an organization.

File arm-set-enviroment-with-cm.json and parameters file arm-set-enviroment-with-cm.parameters.json creates a resource group and a storage account in this group for specific enviroment - dev, tst, uat, prd.


To run this enter in your CLI following code:

```az deployment sub create --name infraDeploy --location centralus --template-file arm-set-enviroment-with-cm.json --parameters arm-set-enviroment-with-cm.parameters.json```

```--name //is name of deployment (see at the subscription deployments tab)```

Type in the promt form envType (dev, tst, uat, prd) and the name of resource group.

# Other ARM commands samples are in arm-templates.json file.