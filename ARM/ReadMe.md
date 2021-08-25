This template will deploy two webapps, to two specified locations. 

How to deploy from cloud shell: 
new-azureresourcedeployment -resourcegroupname "resourcegroupname" -file "filename" 
 - For this to work the ARM-template has to be stored in the cloud shell storage account. 

Both templates are linked to https://github.com/maggavelli/contosocoffee.git repository that will deploy the website.
