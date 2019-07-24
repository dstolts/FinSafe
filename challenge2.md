# FinSafe
OpenHack governance for highly regulated environments such as Financial Services



## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**


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



