# GCP-project-on-Configuring-Google-Cloud-HA-VPN

## In this project, I performed the following tasks:
* Created two VPC networks each with  subnets, firewall rules to allow SSH, RDP, HTTP, and ICMP and instances from the cloud shell.
* Configured HA VPN gateways and cloud routers in each VPC network from the cloud shell
* Configured four VPN tunnels between the gateway on the on-prem VPC network adn the cloud VPC network
* Configured a router interface for each VPN tunnel and corresponding BGP peering between vpc-demo and VPC on-prem.
* Configured firewall rules to allow traffic between the remote VPC and the on-prem VPC.
