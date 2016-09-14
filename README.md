# azure-load-balancer1

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2Fazure-load-balancer1%2Fmaster%2FazureDeploy.json)

[<img src="https://camo.githubusercontent.com/536ab4f9bc823c2e0ce72fb610aafda57d8c6c12/687474703a2f2f61726d76697a2e696f2f76697375616c697a65627574746f6e2e706e67" data-canonical-src="http://armviz.io/visualizebutton.png" style="max-width:100%;">](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2Fazure-load-balancer1%2Fmaster%2FazureDeploy.json)


* vnet-new.json: creates new vnet with subnets and NSG
* public-lb-new.json: Create a new L4/L7 load balancer
* vmseries.json: Creates upto 10 VMseries Firewall VM along with Network interfaces and availability Sets and attaches them to public load balancer
* private-lb.json: Creates a private load balancer
* webserver.json: Creates a webserver farm and attaches them to private load balancer
* azureDeploy.json: Call all the JSON files in the correct order to create or use existing VNET, new Load Balancers, Firewall and Webserver Farm
