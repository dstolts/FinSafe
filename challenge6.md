# FinSafe
OpenHack governance for highly regulated environments such as Financial Services



## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**


## Challenge 6 - Cost Management 

### Goals 
- Find under used resources remove wasteage and maximize cost savings
- Organize resources to enable business unit workloads owner to optimize efficiant savings & prove quota notification to manager request / P & L to workload owner
- 
### Outcomes
- Azure cost & Billing report
  - Sub, RG, Billing code or BU -> Views
- Configure Azure Quota on App REsources
- Azure Advisor - Identify cost opimizations
  - Reserve Instance - apply
  - Reduce size of resource (VM/SKU) 


### Technology Tools/Services/Lessons


## Challenge 7 - Security Information and Event Management (SIEM) / Dashboards 
- Signoff of workload by CISO
### Goals 

- Provide CISO with full visibility and evidence that workload(s) are ready and compliant to go live in production
  - dashboard to confirm sec requiremnts are met
  - Alerts put in place if workload changes 
    - Policy tampering
    - data tampering
    - change management config locks
    - SIEM & Diagnostics
    Threat Intelligence
    - Compliance REport
      - ISO 27001
        - ASC
        - Compliance Manager
        - Sentinal
      - Azure Policy Audit (PII?)


### Outcomes
- Complete CISO Dashboard
- CISO signoff
- Create sprint #3 Backlog Security work items
- Final Secure Score Output 
  - What is teams secure score
  - Highest score (or average daily score) wins


### Technology Tools/Services/Lessons


## Challenge 8 - Diagnostics Integration with 3rd Party
[Optional - Stretch] Config for 3rd Party SIEM requirement
### Goals 
- Ciso wants log telemetry and threat intel feed from both MS (Azure Security Center, Sentinal) and 3rd Party SIEM
  - Enable for both

### Outcomes
- Forward all Azure Logs to 3rd Party SIEM via EventHub
  - Identity Logs to EventHub (1)
  - Azure Activity logs to EventHub (1)
  - Azure Resource Diagnotics to EventHub (many)
    - per region
- Sentinel 
  - setup AWS Dashboard & Connector
  - setup 3rd party firewall logs

### Technology Tools/Services/Lessons


Select / Build Reference Financial Application, related deployment artifacts, data and Governance assets 

Virtual Data Center Integration 



