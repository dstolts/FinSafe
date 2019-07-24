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
Security Center Basic
Sentinal?
Datalake storage
  - Tags highly confidental

- **Accounts**: The attendees have been provided a specific account for the event. It is recommended that they use their browser in private mode.  

- **Azure DevOps**: This is the recommended default tool we are using for the hack. Your team may decide to use other tools but the coaches may not be able to assist with some aspects with other products. After creating the project, the participants will have to add the hackers account of their team. Each Azure DevOps has a subscription limit of 5 free accounts and the accounts shall be set using the **Basic** access level.

- **Azure DevOps**: You can suggest to the teams to rename their accounts from Hacker1 etc. to their own names to make the rest of the event easier. For example when they will create PRs, they will know who created them. 

- **GitHub**: GitHub issue tracking system and project management is the recommended option unless a team has a strong opinion against ??????


## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**


## Challenge 1 - Foundation
Goals: 
- Organization Readiness
- Business Problem Identification and Understaning
- introduction to CAF Framework
- Review Foundation Already created - Understand tenant, subscription, RG, MG, Security Policy
- Create Management Group Structure
- Assign Team Roles

Outcomes: 
- Summarize pre-created foundation & resource strategy
- Management Group Structure - Self-service portal; process
- Publish basic **shared dashboard** to communicate strategy
- Assign and create cloud team responsiblities (Hint: Complance Manager with RBAC)
  - CISO
  - CAF Discipline Owner
     - Collaboration Strategy (Team Name, [Tools: Slack, Teams, Hangouts, ???])
  - Workload Owner


Technology Tools/Services/Lessons:
- Converting Business Challenge to Technology Solution
- Cloud Adoption Framework
- Resource Groups
- Management Groups
- Shared Dashboard
- Compliance Manager
- RBAC
- Azure DevOps


In this challenge you will learn the foundational security and governance knowledge needed to begin your journey. This includes: 
- Foundation
- Resource Strategy
- Resource Structure
- Reporting
- High-Level Azure Technology such as Subscriptions, Tenants, Management Groups, Resource Groups

![](images/caf-best-practices.png?raw=true)




- **Clear Definition of Governance**

Governance is all of the processes of governing, whether undertaken by a government, market or network, whether over a family, tribe, formal or informal organization or territory and whether through the laws, norms, power or language of an organized society.

It relates to "the processes of interaction and decision-making among the actors involved in a collective problem that lead to the creation, reinforcement, or reproduction of social norms and institutions."

In lay terms, it could be described as the political processes that exist in between formal institutions.

 

How to implement Governance - Minimal Viable Governance - MVG




to are expected to validate the following points: 



- **IMPORTANT**: ....

## Challenge 2 - Identity Baseline

This challenge is about identity and privilage. 



### Goals:
- Single identity and SSO across all subs and tenants
- Access Reviews
- Just In Time adminstration

### Outcomes:
- Create access reviews for all admin roles
  - CISO - Security Reader & Admin role
  - Network Admin
  - Policy Admin 
  - Compliance manager
  - Keyvault Admin
  - Identity Admin
  - Operations - Log Analytics
  - Identity Admin - Global Admin
    - PIM Admin
    - Magic Button
- Impliment Just In Time (JIT) and Just Enough Access (JEA) roles above
  - Investigate your roles & access (PIM)
  - Move to eligible vs permanent 
  - Evaluate your privaledges
  - Elevate a privaledge (72 hours only)
- Workload & Business ID's
    - Identify Pre-created workload owner rights
    - apply PIM
- Add PIM Audit Data to CISO Dashboard
- Deliver alerts to cloud team when admin role members added or elevated
- Create a servcie principle for X app
  - API Security


### Technology Tools/Services/Lessons:
- Privelidge Identity Management (PIM)
- Just In Time management (JIT)
- Just Enough Access (JEA)
- 


![](images/regulatory-boundaries.png?raw=true)




## Challenge 3 - Security Baseline
Goal: Continuously Monitor securuty access ()
 - Machines
 - Networks
 - Azure Services


Prevent Loss or leakage of data and PII
  - Inventory Data
  - Classify Tag
  - ensure Security based on classification
- Stopping unauthorized traffic that introduces risk to network / IT assets

- Isolate East / West Traffic
  - Environments -> sandbox, non-prod, prod
-Isolate Intenet inbound - DMZ
Manage all "External" enpoint s & IP's

Outcomes: 
Turn on & configure Security Center Standard on all subs & tenants
  - auto deploy settings for all new
  - Azuire policy  for all existing
    - Audit
    - apply if not exist
  - Setup Azure Sentinal Azure Activity Dashboard and others?
  - Inventory all azure storage accounts
    - Audit / Remediate storage without encryption
    - Review Tags and Classifications
    - Apply Azure Shares for highly classified data?  Datalake
  - network watcher
    - sentinal
    - threat analytics and network topology alerts
    Landing zone?
      - communication from workload -> shared servcies -> on-prem
        - Azure Firewall config
          - Test with Deploy IaaS or paaS
            - 2 subnets - communicate onprem
            - Netowrk (VDC) {P2S, S2S, ExpressRoute}
            - ISE -> (PowerBI) {Agent/API/HTTPS}
    SEE whiteboard notes
    

## Challenge 4 - Resource Consistency 



## Challenge 5 - Deployment Acceleration 




## Challenge 6 - Cost Management 

T

## Challenge 7 - Security Information and Event Management (SIEM) / Dashboards 



**Integration Testing**




## Challenge 8



Select / Build Reference Financial Application, related deployment artifacts, data and Governance assets 

Virtual Data Center Integration 



