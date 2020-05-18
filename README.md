# DEFCONMeshNet
This meshnet is in early stages of forming. Please mind the mess!
## > How to Connect
- Install [Install Yggdrasil](https://yggdrasil-network.github.io/installation.html)
- Configure yggdrasil.conf
  - Linux: /etc/yggdrasil.conf
  - Windows: %PROGRAMDATA%/yggdrasil.conf
- Ensure you enable the SessionFirewall in the config, Disable AllowFromDirect, and AllowFromRemote
- Add your [closest peers](https://github.com/DEFCONMeshNet/DEFCONMeshNet/blob/master/publicnodes.csv) into the Peers section neer the top.
  - Add about 2 nearby peers.
- Review the rest of the config for settings you might like to enable. [Docs](https://yggdrasil-network.github.io/configuration.html)
- Restart Yggdrasil
- Ping ```202:7967:4d86:125c:acc1:f5bf:e719:329b``` or ```201:4771:e691:f802:373:17da:25ee:9654``` to test for connectivity.

## > Meshnet DNS
The meshnet has a managed DNS server that will resolve the .defcon tld managed by this repository. all other non-mesh and IPv4 will be forwarded to cloudflare 1.1.1.1

### Usage
Set system DNS resolver to either or both:  
-```202:7967:4d86:125c:acc1:f5bf:e719:329b```  
-```201:4771:e691:f802:373:17da:25ee:9654```

### Register new Domain
Use the "New Defcon Domain Name" Issue Template to request a Domain name with the meshnet only .defcon tld.

Popular Names and exisiting groups will need reasonable proof of ownership included in the request.

## > Adding a new Public Peer
You can connect to any peer on the network if you know their IP and Port, It is a meshnet afterall.

If you wish to have your node publicy listed, please use the Add Public Peer issue template to register a public node.

## > Known on mesh services.
To add a service, please use the Mesh Services issue template
- [DefconMeshnet Matrix](https://[0200:2c03:79b4:4257:ce90:7582:4c5a:d946])

## About  
For any questions please contact either @JRWR or @McL0v1n_ (on Twitter).  

Time and effort for organizing the DEFCON Meshnet and running its DNS servers have been thanks to volunteers over at DCDarknet.  

