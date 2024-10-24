# public
public
az storage account list --query "[?sku.name=='Standard_GRS' || sku.name=='Standard_RAGRS'].{Name:name, ResourceGroup:resourceGroup, Sku:sku.name}" -o table
https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-quickstart#clean-up-resources
https://learn.microsoft.com/en-us/mem/intune/enrollment/connect-intune-android-enterprise
