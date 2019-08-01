# Multi-Tenant Virtual Router 
This skillet configure multiple virtual router in VMSeries firewall to demo a multi-tenant environment . Common VR acts as Internet connected VR for the tenant VR to provide them external connectivity to WAN or Internet.

With this skillet following are configured in PANOS
1) Tenant VR
2) Common VR 
3) Static Routes from Tenant to Common VR
4) Reverse Route from Common VR to tenants
5) Common VR next hop

## Prerequisites
1) Interface configured with IP


Also you can provide the exsisting Virtual Router name else new value provided in the variable, will create a corresponding resource.


## Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.
