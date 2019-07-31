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
