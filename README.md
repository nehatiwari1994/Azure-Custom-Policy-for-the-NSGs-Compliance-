# Title: 



# Azure Custom Policy for the NSG Compliance  

This Custom Azure Policy will help customers to Audit the Subnets which are non-attached with any NSG. Other Policy in the Template will help customers to audit the NSG rules where inbound port is allowed publicly (*, internet) for any ports excluding 80 and 443. Both of these policies will also prevent from making non-compliant changes to existing resources. It will also block any noncompliant configuration for the new subnets or NSG rules.  


## Target audience

Deployment Engineers 

Solution Architects


# Deployment Steps for the Audit Subnet without NSG 

login to Azure portal & search for the Azure Policy
You will find it like mentioned below.


![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20160542.png)

Go to the definations and click +Policy defination.Fill the requested parameters and paste the script from [Script for Audit and Deny Subnet without NSG](https://raw.githubusercontent.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/master/Script%20for%20Audit%20and%20Deny%20Subnet%20without%20NSG) to the policy rule.


![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20162349.png)

Click Save.

You should see the below screen.

![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20162653.png)

## Assign the Policy to the scope

Click the Assign on the top

You will get below screen
![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20163049.png)

Fill all the required information like scope, exclusions and give it a assignement name. Click review and create.

![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20163357.png)

Once done you will be able to see the assignment mentioned below screen

![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20163544.png)


## Deployment Steps for the Audit NSG Rules 
This will help customers audit the inbound NSG rules on Subnet where inbound port is allowed publicly (*, internet) for any ports excluding 80 and 443

You can repeat the same steps as above to create and assign a new defination using the scripts in Policy rule [Script for Audit and block Internet allowed rules on NSGs on Subnet level](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Audit%20and%20block%20Internet%20allowed%20rules%20on%20NSGs%20on%20Subnet%20level)

## Error screenshot while creating a subnet without NSG 


![alt image](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Screenshot%202022-06-29%20164624.png)


## License & Contribute

You are responsible for the performance, the necessary testing, and if needed any regulatory clearance for any of the models produced by this toolbox.
Please refer [LICENSE](LICENSE) &  [Contribute](https://github.com/nehatiwari1994/Azure-Custom-Policy-for-the-NSGs-Compliance-/blob/master/Contribute.md) for more details


