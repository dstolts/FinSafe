# FinSafe
OpenHack governance for highly regulated environments such as Financial Services



To Do: 
work with real customer in a sample workshop?  Sample Adoption?  

## Background
Security Blockers Sprint #1 Complete
- Automated Deployment Tool Azure DevOps for automated pipeline 
- Shared Services created
- Landing Zone Created
- minimum policy deployed
- Virtual Datacenter (VDC) Shared Service

Sprint #2 - Enhance and deploy workload



## Environment setup 
- 2 AAD Tenants (AAD P2)
  - B2B Org relationships
- 3 Sandbox
  - 1 - cloud team
  - 1 - Dev / Business Unit
  - 1 - Empty test policy
- 2 Non-Prod (Shared Service, Landing Zone)
- 2 Prod (Shared Service, Landing Zone)
- Foundation pre-created tenant, subscription, RG, MG, Security Policy
- Azure DevOps?
- Create alert for add users to network administrator - send to manager and CISO
- Secure Score #
  - Identity
  - Azure
- Security Center Basic
- Sentinal?
- Datalake storage
  - Tags highly confidental
- DR - Shared Services,  ASR, Multi-region
- Azure Advisor .. Plant one or two cost recommendations
- AWS account
- 3rd Party Firewall
- 3rd Party SIEM

- **Accounts**: The attendees have been provided a specific account for the event. It is recommended that they use their browser in private mode.  

- **Azure DevOps**: This is the recommended default tool we are using for the hack. Your team may decide to use other tools but the coaches may not be able to assist with some aspects with other products. After creating the project, the participants will have to add the hackers account of their team. Each Azure DevOps has a subscription limit of 5 free accounts and the accounts shall be set using the **Basic** access level.

- **Azure DevOps**: You can suggest to the teams to rename their accounts from Hacker1 etc. to their own names to make the rest of the event easier. For example when they will create PRs, they will know who created them. 

- **GitHub**: GitHub issue tracking system and project management is the recommended option unless a team has a strong opinion against ??????


## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**


