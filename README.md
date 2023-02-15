# Welcome to F5 Distributed Cloud

The following resources are intended to get you up and running as soon as possible with some template resources.

To apply these templates to your tenant, please apply them in the following order for best results:

1. shared-\*  
***Optional Steps***  
2. origin-\*.json
3. lb-\*.json

### Here is suggested order to apply these templates to a tenant:

- [Shared Web Application Firewall Policy - Blocking](shared-appfw-blocking.json)
- [Shared Web Application Firewall Policy - Monitoring](shared-appfw-monitoring.json)
- [Shared Health Check - HTTP 200 and 302](shared-hc-http-200-302.json)
- [Shared Service Policy All IP Threat Categories](shared-service-policy-ip-threatcategories.json)
- [Shared Service Policy OFAC Deny](shared-service-policy-ofac-deny.json)

### Optional for test/demo purposes

- [Origin Server pointing to nginx.org](origin-nginx.json)
- [Load Balancer for nginx.org using shared AppFW blocking policy](lb-nginx.json)

### How to use Shared objects

Shared App Firewall Policies need to be asigned at the namespace level. To enable policies, go to Load Balancers -> Security -> Service Policies -> Select Active Service Policies. From this page you can add the Shared Service Policies to the selected namespace.
