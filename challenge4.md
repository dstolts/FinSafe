# FinSafe
OpenHack governance for highly regulated environments such as Financial Services



## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**


## Challenge 4 - Resource Consistency 

### Goals 
- Define Azure Services throught resource rpovider controls across 3 env types
  - Sandbox - Allow all
  - Non-Prod - Restrict
  - Prod - Restrict

- Deploy Manage & monitor target workloads based on BU & App Resources
  - Ensure stability
  - uptime
  - Performance
- Speed to remediate performance or uptime of target workload 

### Outcomes
- Enforce Policy on all workload resources
  - Naming policy
  - tagging policy
- Define policy controls across 3 env types
  - Management Group Structury
  - Azure Policy
  - Resource Provider
- Azure monitor config & app Dashboard
  - Custom metrics
  - Service Health
  - Logs
  - App Insights
- Create Alerts & action groups
  - Create sentinal, task alerts and playbooks
  - Dynamic Threasholds

### Technology Tools/Services/Lessons

