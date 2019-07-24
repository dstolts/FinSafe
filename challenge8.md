# FinSafe
OpenHack governance for highly regulated environments such as Financial Services


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



