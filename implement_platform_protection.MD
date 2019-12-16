# Implement platform protection (35-40%) 

## Implement network security 

- Configure virtual network connectivity 
- Configure Network Security Groups (NSGs) 
- Create and configure Azure Firewall - ([Overview](https://docs.microsoft.com/en-us/azure/firewall/overview)) - ([CreateAndConfigure](https://docs.microsoft.com/en-us/azure/firewall/tutorial-firewall-deploy-portal))
>Diagnostics settings targets can be a StorageAccount, an EventHub and LogAnalytics

>Network rule collections contains network rules and tag rules.

>Application rule collections contains URL targets rules. 

- Create and configure Azure Front Door service - ([Overview](https://docs.microsoft.com/nb-no/azure/frontdoor/front-door-overview)) - ([FAQ](https://docs.microsoft.com/nb-no/azure/frontdoor/front-door-faq))

> Azure Front Door Service works globally at Layer 7

> An application backend is any Internet-facing service hosted inside or outside of Azure

> The Frontdoor designer contains the option of configuring Frontend hosts, Backend pools and Routing Rules.

> The Frontdoor cache can be purged (selectively).

> Frontdoor service is global and Application gateway is regional.

- Create and configure application security groups 
- Configure remote access management 
- Configure baseline 
- Configure resource firewall 

## Implement host security 

- Configure endpoint security within the VM 
- Configure VM security 
- Harden VMs in Azure 
- Configure system updates for VMs in Azure 
- Configure baseline 

## Configure container security 

- Configure network  
- Configure authentication 
- Configure container isolation 
- Configure AKS security 
- Configure container registry 
- Cmplement vulnerability management 

## Implement Azure Resource management security 

- Create Azure resource locks 
- Manage resource group security 
- Configure Azure policies  
- Configure custom RBAC roles 
- Configure subscription and resource permission
