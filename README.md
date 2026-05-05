HCIStack

A Stack with 4 nodes and we will need a SQL PAAS/ IAAS

PROJECT PLAN - RFS 000087 - Azure Stack Service							
Pablo Villaronga 14.8.2019							
latest update 3.9.2020							

HLD Diagrams 
LLD Diagrams 

O1 -Installation of operating tools 
O2- Integration for monitoring and alerting 
O3- Enable Azure Stack integration with End-customer
O4 - Microsoft SCOM in coordination with End-Customer
O5 - Deployment of Azure Stack Management Pack 
O6 - installation and integration of cloud services 
O7 - Establishment of backup services 
O8 - Perform Azure Stack configuration backup to End-Customer provided File share 
O9 - Establishment of operational documentation 
O10 – Standard Operating Procedures and guides, including upgrade procedures for base installation, firmware, tools, cloud services, etc.
O11 - Installation and configuration of Azure Stack Hub 
O12 - Create Operational documentation and recovery procedures o Guide to assist with operational issues 
O13 - RACI and stakeholder list
O14 - Advice process for End-Customer Service Desk to contact Hardware Supplier Service Desk in case of incidents  
O15 - Test deploy a sample Azure Resource Manager (ARM) template from the Azure 
O16 - Stack Quick Start Gallery o Setup of initial on prem Azure services, for End-Customer to perform self-service provisioning 
O17  Strong Azure Stack experience that can be applied to the implementation of a multi-tenant-enabled on-premise

							
#	Task 	Status	Owner	Start date	Target date	Dependency	Comment
1	M0 - RFS Proposal accepted by Customer						
							
2	M1 - Project start (M0 +1)						
							
3	M2 - Hardware procurement (M1 +6)	            Closed			16.8.2019		Confirmed OK Architect  
	- And SW procurement						"Architect working on this with Cloud Assert and Procurement ref to meeting 25.7.2019 with Procurement.
14.8.2019: Holger will work to get CA as a vendor.
29.8.2019: SHI team Nelly Omokhodion updated PME onboarding Cloud Assert Software in progress. 
17.9.2019: New Software Quote is being shared by SHI, Source SR created, it needs first step approval by next Monday, lead time 3-4 weeks."
							
4	Creation of Architectural design documents (High Level and Low Level) for Azure Stack						13.9.2019 Latest status  be updated by oydeep Singh for PME
4.1	M3 - High level design (M1 +3)	Closed	Architect		26.7.2019		"Needs to be formally approved by the customer. DRAFT by 26.7.2019.  Target date for final 5.8.2019.
25.7.2019: Presentation 26.7.2019 to the customer
14.8.2019: Next version to be sent to the customer by 17.9.2019: Architect informed HLD ready and shared within Contoso.local Week 37

"
4.2	M4 - Low level design (M3 +3)	Ongoing	Architect		10.9.2019		"First version 10.9.2019. Will continue until 30.9.2019
25.7.2019: First HLD and then LLD.
14.8.2019: Architect has started to prepare the LLD. 
17.9.2019: Architect informed LLD will be kept open until the Project is completed"
							
5	Install Lenovo hardware and base configuration of Azure Stack						
5.1	M5 - Hardware delivery and physical setup (M4 +2)	Closed	Architect with Lenovo, Peter	To be discussed internally	To be discussed internally		"Requirements: 
- PO released to Lenovo by 26.7.2019
- HW should arrive 20.8.2019 to the DC in DK.
Physical Setup: 
- DCM request to be sent to the DCM team by 9.8.2019.
Dates to be discussed internally.
Lenovo delivery in 3 weeks.
17.9.2019: Will be updated as soon we get delivery date from Lenovo (after BOND Order confirmed)"
5.2	Secure sufficient network capacity between Azure Stack and FMO	Closed	Peter	1.8.2019	20.8.2019		"Architect & Peter Danielsen - waiting Peter back from vacation
14.8.2019: Architect confirmed that has been verified that the NW capacity exists.
17.9.2019: Double check with Architect this week"
5.3	Send DCM request to the DC team	Closed	Architect and Peter		9.8.2019		17.9.2019: PME schedule a meeting with DC site team on 18/9 to make them prepare for HW arrival in DC Ballerup.
5.4	Rack, install and connect Azure Stack HW delivered to the Customer Location	Closed	DCM team	22.8.2019	30.8.2019		"DCM request to be raised
14.8.2019: Once PO raised, Lenovo will confirm the serials numbers and the DCM request can be raised by Architect. 
17.9.2019: PME schedule a meeting with DC site team on 18/9 to make them prepare for HW arrival in DC Ballerup."
5.5	Perform network & firewall configuration	Closed	Peter	TBD	TBD		14.8.2019: Will start once the HW has arrived.
5.6	Perform the complete installation of the base Azure Stack	Closed	Lenovo	TBD	TBD		14.8.2019: Will be planned by Thomas once the HW has arrived. 
	Pre-Req for the base configuration of Azure Stack by Lenovo						
5.6.1	"Provider  deployment worksheet minimum 2 weeks prior to deployment.
"		Provider				
5.6.2	"Certificates must be ordered, and tested before the Lenovo engineer comes onsite. 
"		Provider				
5.6.3	Validate the AAD account to be used for the installation		Provider				
6	Deployment and configuration of the Azure Stack on a selected OEM certified integrated system						
6.1	M6 - Configuration of the Management Stack (M5 + 3)	Closed	Provider and Cloud Assert	1.9.2019	20.9.2019		
	Pre-Req for the base configuration of Azure Stack by Cloud Assert		Cloud Assert				
6.1.1	Connection to a SQL server		Provider				
6.1.2	Tenant Subscription		Provider				
6.1.3 	Certificate		Provider				
6.1.4	Others		Provider				
6.1.5 	Provider to provide Cloud assert tech some type of remote access to Contoso.local AzureStack 		Provider				
All activities above row 36  in grey area are completed according to Architect Sing from 3/9 2020 							
6.2	Configure vConnect Resource Provider on the Azure Stack	To start	Cloud Assert	1.9.2020	To be updated		
6.3	Integrate Azure Stack with the FMO Production Environment	To start	Cloud Assert	1.9.2020	To be updated		
6.4	Upload Provider supported base OS images to the Azure Stack Platform Image Repository 	To start	Pawel (Martin Sabransky) with Cloud Assert, Lenovo	1.9.2020	To be updated		
6.5	Test deploy a sample Azure Resource Manager (ARM) template from the Azure Stack Quick Start Gallery.	To start	Cloud Assert	1.9.2020	To be updated		
6.6	Basic operation of Azure Stack	To start	(Pawel) BAU teams	1.9.2020	To be updated		
6.7	Basic operation of native Azure stack PaaS platform	To start	(Pawel) BAU teams	1.9.2020	To be updated		
6.8	Basic operation of Azure stack IaaS platform	To start	(Pawel) BAU teams	1.9.2020	To be updated		
6.9	To confirm the BAU team and have it up and running	Ongoing	Pawel (Architect)	1.9.2020	To be updated		"17.9.2019: Architect was plAnne / Thomasd to have the dialog with Brno team and the team will be confirmed 
"
7	Together with customer establish Governance Model for the Azure Stack			1.9.2020	To be updated		
7.1	Establish Governance Model for the Azure Stack	To start	Pawel (Architect) with Contoso.local, Thomas	1.9.2020	To be updated		Finally handover to the BAU teams
8	M7 - Project closure (M6 +1)	To start	Thomas	1.9.2020	To be updated		

#This goal is to finalize the delivery by resetting the current Azure Stack configuration and:

#•Lenovo to rebuild (re-install) the Azure Stack 4 node stack with CSP License agreement setup
#•Add subscription
#•Enable IAAS & PAAS Services
#•Install/configure Vconnect to enable integrate the IAAS capacity to VMware environment (with help from Cloud Assert)
#•Contoso.local (the client) to verify the running solution
#•Prepare governance model how to operate the Azure Stack solution (in BAU)
#•Handover to Provider BAU Operation team (2 SMEs have already been upskilled in Azure Stack, but have no hands-on experience)
#•Close project

#Contoso.local RFS00087 - Background history 
#This RFS Project Scope is about implementing a 4 node Azure Stack Solution that will integrate (capacity) from FMO VMware. 
#To implement this Project support is required by Provider and 3rd party supplier Lenovo and Cloud Assert. This Project started in 2019, but then got a hard stop in summer of 2020 when Provider #technical key resource Joydep Sing (Solution designer) stopped his work for Provider.  It has been a challenge for the Account to find new  Provider Azure Stack resources to support and finalize #this RFS. The RFS has been on hold for a longer period of time now. 

#Recent months the client (Contoso.local) has decided and committed to Provider that they will submit a PCR for Provider to reinstall the Azure Stack. The condition for this will likely be with a #CSP license agreement instead of todays EA installed Azure Stack. But how Contoso.local wants to move forward with RFS00087 depends on Provider capacity and knowledge to support Azure Stack to #Contoso.local according to SDM, who had recent dialog with Client. 

#Agreed on todays meeting for RFS00087
#To do a proper analyze how to move forwared with this RFS the Contoso.local Account need to invoke RFS Manager, Solution team and IT Architect team to review and update the RFS00087 #Solution so it meets the latest expection from Contoso.local. When this updated Solution and budget has been approved by Client. It will be the task for Provider PM and Provider's  technical Azure #Stack resources t*implement this RFS00087 Solution 

Agreed actions on todays meeting
Action 1. PM, with support from SDM. Update DPE on the recent RFS000087 SOW status and expectation (Action owner:PME)
SDM will help PM to describe the expectation  by Contoso.local  for a new  RFS Solution,  what needs to be taking into account for an updated solution (possible CSP License agreement setup etc...) PME will send this info by email.

Action 2. 
DPE to setup a meeting with Contoso.local account RFS Manager and decide exactly how to move forward (Action owner: Pawel Milkulko)
After Pawel Milkulko received email by PME, he will invite for a meeting with Contoso.local RFS Manager to agree how to move forward with RFS00087.
An updated RFS SOW will be required!

Planned to happen 3.
Provider Solution team to support with an updated RFS000087 SOW.
The new SOW for RFS00087 need t*include changes to Solution and the Project budget.
The TSM will need assistance from Provider IT Architect team for this work.

Planned to happen 4.
Provider PM and Provider Technical resources to implement the updated RFS00087 Solution.
Provider togheter with Lenovo and Cloud Assert will update a new Project Plan based on the updated SOW and restart the 
Installation/configuration of RFS00087.

Ps. Also on the second part of todays meeting Provider PM PME together with IT Architect Pablo Villaronga and SME Pavel Entner  discussed the technical details related to RFS00087 implementation. The conclusion was that If the RFS00087 receives an updated SOW which has involved Pablo Villaronga engagement and input, Provider should have confidence to manage and implement RFS00087

Contoso.local 
#Github 
https://github.Provider.com/Pablo-Villaronga/Contoso.local

-----------

1- Access to Lenovo 
2- Model with COST , Rasmus 
2.2 - Create estmation , comparison ? 
2.3 - maybe take over the licence application 
We have the need TSM to be involved for PCR  -  Lets do a Quick PCR 
3 - Governance plan 
4- continue with RFS or delete everything 
5 - start over - service operations , small capacity? 
6- No budget 
7-Lenovo to start over 
7.1 certificates are installed 
8- Have a commercial discussion with Contoso.local
9- what is your idea to move to BAU ? 
10 - Transportation issues - in channel for 2021 
11 - Technical SME - have a view abd a solution to Contoso.local

Azure Stack skills needed:

Installation of operating tools

Integration for monitoring and alerting

*Enable Azure Stack integration with End-customer Microsoft SCOM in coordination with End-Customer deployment of Azure Stack Management Pack
*Verification of management monitoring
·       Installation and integration of cloud services
·       Establishment of backup services
*Perform Azure Stack configuration backup to End-Customer provided File share
Establishment of operational documentation
Standard Operating Procedures and guides, including upgrade procedures for base installation, firmware, tools, cloud services, etc.
Installation and configuration of Azure Stack Hub
Create Operational documentation and recovery procedures

 Guide to assist with operational issues

 RACI and stakeholder list
·       Advice process for End-Customer Service Desk to contact Hardware Supplier Service Desk in case of incidents
·       Provisioning of initial Cloud services

Test deploy a sample Azure Resource Manager (ARM) template from the Azure Stack Quick Start Gallery

Setup of initial on prem Azure services, for End-Customer to perform self-service provisioning

2. For Contoso.local, Azure Stack Architect:
 Strong Azure Stack experience that can be applied to the implementation of a multi-tenant-enabled on-premise AzureStack service at Contoso.local, a major MSP / CSP in the Nordics.


