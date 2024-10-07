# public
public
az storage account list --query "[?sku.name=='Standard_GRS' || sku.name=='Standard_RAGRS'].{Name:name, ResourceGroup:resourceGroup, Sku:sku.name}" -o table
