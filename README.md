# arm-dispatch-test
Arm Template Research/Testing for deploying landzones/marketplace integration.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FBreanna-Stryker%2Farm-dispatch-test%2Fmain%2Ftemplate.json)

Or you can execute this script from command line after checking out the template with:

az login
az deployment group create --resource-group <Your Deployment Resource group> --template-file template.json

  
You will be prompted for a service principal and secret key to execute. 
