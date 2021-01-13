##### Creating Azure Purview 

Pre requierments 

+ Azure Account with an active subscription
+ Azure active directory tenant
+ Permission to create resources in subscription
+ No Azure Policy blocking applications from creating Storage account and EventHub namespace
+ Azure cli installed 


About the Platform size and capacity

1 capacity unit can on average receive 1 api call per second



Deploy

git clone

If needed make changes to parameters region you want to deploy. Note that not all regions are available 

Or

Or use the cli below, by adding your resourceGroup
```
az deployment group create --resource-group "<resource-group>" --template-file https://github.com/kkaarel/azurepurview/blob/main/azuredeploy.json --parameters https://github.com/kkaarel/azurepurview/blob/main/azuredeploy.parameters.json
```



Date: 6.01.2021







