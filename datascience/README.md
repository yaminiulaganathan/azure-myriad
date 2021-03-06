﻿# VM scale set based on the Azure Data Science VM 
This template creates a VM scale set with a load balancer and public IP address - based on the Azure Data Science VM.

The template creates a load balancer and a public IP address. Inbound NAT pools are defined to route incoming connections to the VMs in the set.

Inbound NAT rules are configured as follows:
```
SSH/RDP to the ip/dns address port 50000 to connect to VM#0
SSH/RDP to the ip/dns address port 50001 to connect to VM#1
etc..
```

![Windows 2016 screenshot](../datascience/img/datasciencewin2016.PNG)


## Deploy Windows 2016 Data Science VM to Azure
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgbowerman%2Fazure-myriad%2Fmaster%2Fdatascience%2Fazuredeploy-windows.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Deploy Ubuntu 16.04 Data Science VM to Azure
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgbowerman%2Fazure-myriad%2Fmaster%2Fdatascience%2Fazuredeploy-ubuntu.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


