##### Creating Azure Purview 

Pre requierments 

+ Azure cli installed 



Deploy

git clone

If needed make changes to parameters region you want to deploy. Note that not all regions are available 

```
az deployment group create --resource-group "<resource-group>" --template-file https://github.com/kkaarel/azurepurview/blob/main/azuredeploy.json --parameters https://github.com/kkaarel/azurepurview/blob/main/azuredeploy.json

```



Date: 6.01.2021







