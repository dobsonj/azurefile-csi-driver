{
    "cloud":"AzurePublicCloud",                    // mandatory
    "tenantId": "xxxx-xxxx-xxxx-xxxx-xxxx",        // mandatory
    "subscriptionId": "xxxx-xxxx-xxxx-xxxx-xxxx",  // mandatory
    "resourceGroup": "resource-group-name",        // mandatory
    "location": "eastus2",                         // mandatory
    "aadClientId": "xxxx-xxxx-xxxx-xxxx-xxxx",     // mandatory if using service principal
    "aadClientSecret": "xxxx-xxxx-xxxx-xxxx-xxxx", // mandatory if using service principal
    "useManagedIdentityExtension": false,          // set true if using managed idenitty
    "userAssignedIdentityID": "",                  // mandatory if using managed idenitty
    "useInstanceMetadata": true,                   // optional
    "vmType": "standard",                          // optional
    "subnetName": "k8s-subnet",                    // optional
    "vnetName": "k8s-vnet-17181929",               // optional
    "vnetResourceGroup": "",                       // optional
    "cloudProviderBackoff": true                   // optional
}