#### ormsftazuredatastor4dev
#####Getting ready
######
in u14:
```
apt install nodejs-legacy && apt install -y npm
npm install -g azure-cli
```
test
```
azure --help
```
######Provisioning Resources With The Azure Resource Manager - Part 2
browse all->reource group  

list using cmd
```
azure login
azure config mode arm
azure group list
azure resource list -g ormsftazuredatastor4dev
```
######part3
{
  "$schema": "https://schema.management.azure.com/schemas/2015-01-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "parameters":{
    
  },
  "variables":{},
  "resources":[]
}
#####Azure Storage - NoSQL Storage
######Overview Of NoSQL Storage
sql databases should not be scaled horizontally.
