# Welcome to F5 Distributed Cloud

The following resources are intended to get you up and running as soon as possible with some template resources.  

To apply these templates to your tenant, please apply them in the following order for best results:  

shared-\*, origin-\*.json, and lb-\*.json  

### Here is how I would apply these templates to a tenant:

[Shared Web Application Firewall Policy - Blocking](shared-appfw-blocking.json)  
[Shared Web Application Firewall Policy - Monitoring](shared-appfw-monitoring.json)  
[Shared Health Check - HTTP 200 and 302](shared-hc-http-200-302.json)  
[Shared Service Policy All IP Threat Categories](shared-service-policy-ip-threatcategories.json)  
[Shared Service Policy OFAC Deny](shared-service-policy-ofac-deny.json)  

### Optional for test/demo purposes

[Origin Server pointing to nginx.org](origin-nginx.json)  
[Load Balancer for nginx.org using shared AppFW policy](lb-nginx.json)  
