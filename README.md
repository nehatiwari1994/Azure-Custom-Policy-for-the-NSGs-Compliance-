# Title: 



# Azure Custom Policy for the NSG Compliance  



## Target audience

Deployment Engineers 

Solution Architects


# Deployment Steps

login to Azure portal & search for the Azure Policy
You will find it like mentioned below.


![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20160542.png)

Go to the definations and click +Policy defination 


![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20161440.png)

[Script for Audit and Deny Subnet without NSG](https://raw.githubusercontent.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/master/template.json) can be modified to match your current infrastructure needs.

## One Click Deploying Template
<!-- Powershell command for Translating Git URL for template.json
    $url = "https://raw.githubusercontent.com/Ganapathivarma07/LRS-Migration-AzureSQLMI/master/template.json"
    [uri]::EscapeDataString($url)
    >> uri = https%3A%2F%2Fgithub.com%2FGanapathivarma07%2FLRS-Migration-AzureSQLMI%2Fblob%2F
master%2Ftemplate.json

Base URL: https://portal.azure.com/#create/Microsoft.Template/uri
Final URL: <Base URL>/<uri>
-->
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FGanapathivarma07%2FLRS-Migration-AzureSQLMI%2Fmaster%2Ftemplate.json)


## Deploying an ARM Template using the Azure portal


## Azure services and related products


## Deployment steps



## Related references


## License & Contribute

You are responsible for the performance, the necessary testing, and if needed any regulatory clearance for any of the models produced by this toolbox.
Please refer [LICENSE](LICENSE) &  [Contribute](https://github.com/Ganapathivarma07/LRS-Migration-AzureSQLMI/blob/master/Contribute.md) for more details


