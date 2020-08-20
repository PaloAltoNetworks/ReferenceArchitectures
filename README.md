# Palo Alto Networks Reference Architectures


Reference architectures apply a platform-centric approach to secure designs for key customer environments, including SaaS, cloud, and data center. Based on validated configurations and best practices, they provide technical and design guidance in support of technical customer engagements.

Please visit the [Palo Alto Networks Reference Architectures](https://www.paloaltonetworks.com/referencearchitectures) site to access all architecture and deployment guides.

 These templates support the various Design Models and Options described in the **[Reference Architecture Guide for Microsoft Azure](https://www.paloaltonetworks.com/resources/guides/azure-architecture-guide)**.
 
 The proper use of each template is described in the August 2020 (current) deployment guides:
  - **[Deployment Guide For Microsoft Azure - Transit VNet Design Model](https://www.paloaltonetworks.com/resources/guides/azure-transit-vnet-deployment-guide)**
   - **[Deployment Guide For Microsoft Azure - Transit VNet Design Model (Common Firewall Option)](https://www.paloaltonetworks.com/resources/guides/azure-transit-vnet-deployment-guide-common-firewall-option)**
 
 ### Azure-1FW-3-interfaces-existing-environment-BS
 A firewall with (1) management interface and (2) dataplane interfaces is deployed.
 
 This template is used automatic bootstrapping with:
 - Inbound firewalls in the Single VNet Design Model (Dedicated Inbound Option).  
 - Inbound firewalls in the Scaled Design Model.  

  ### Azure-1FW-3-interfaces-existing-environment
 A firewall with (1) management interface and (2) dataplane interfaces is deployed.
  
 This template is used for: 
 - Inbound firewalls in the Single VNet Design Model (Dedicated Inbound Option).  
 - Inbound firewalls in the Scaled Design Model.  

  ### Azure-1FW-4-interfaces-existing-environment-BS
  A firewall with (1) management interface and (3) dataplane interfaces is deployed.
  
 This template is used for automatic bootstrapping with:
 - Outbound/East-West/Backhaul firewalls in the Single VNet Design Model (Dedicated Inbound Option).  
 - Firewalls in the Single VNet Design Model (Common Firewall Option).  
 - Outbound/East-West/Backhaul firewalls in the Scaled Design Model.  
 - Firewalls in the Shared Design model.  

 
 ### Azure-1FW-4-interfaces-existing-environment
  A firewall with (1) management interface and (3) dataplane interfaces is deployed.
  
  This template is used for:
 - Firewalls in the Transit VNet Design Model.  
 - Outbound/East-West/Backhaul firewalls in the Single VNet Design Model (Dedicated Inbound Option).  
 - Firewalls in the Single VNet Design Model (Common Firewall Option).  
 - Outbound/East-West/Backhaul firewalls in the Scaled Design Model.  
 - Firewalls in the Shared Design Model.  

  Specific details on the options and requirements for each template are covered in the respective README files.

If you have feedback or suggestions, send us an email at referencearchitectures@paloaltonetworks.com

# Support

This template/solution is released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

For assistance from the community, please post your questions and comments either to the GitHub page where the solution is posted or on our Live Community site dedicated to public cloud discussions at https://live.paloaltonetworks.com/t5/AWS-Azure-Discussions/bd-p/AWS_Azure_Discussions
