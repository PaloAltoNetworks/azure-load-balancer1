# azure-load-balancer1

vnet-new.json: creates new vnet with subnets and NSG
public-lb-new.json: Create a new L4/L7 load balancer
vmseries.json: Creates upto 10 VMseries Firewall VM along with Network interfaces and availability Sets and attaches them to public load balancer
private-lb.json: Creates a private load balancer
webserver.json: Creates a webserver farm and attaches them to private load balancer
