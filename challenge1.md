# FinSafe
OpenHack governance for highly regulated environments such as Financial Services



## Business Goal
  **Agile deployment of [app/workload] in Azure with policy required for lockdown and sign-off by CISO monthly**

Owner: Dan Stolts


Collaborator: 

## Open Tasks
  - Create Scafolding for Challenge 1 - Dan STolts
  Create Challenge dialog / discussion from goals
    - Define Team Roles (CISO, Cloud Architect, App Owner, Network Admin, Team Member)
    - Target: 
      - Education on CAF
      - desription of preconfigured MVPv1 already deployed (Backstory) - Teams 
      - Education on working from backlog
      - Goal for team to create MVPv2 (From Backlog)
      - Use Microsoft docs and best practices to build story
        - https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/governance/policy-compliance/align-governance-journeys
        - https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/governance/journeys/index
        - https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/governance/journeys/large-enterprise/index
        - https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2Frkuehfus%2FAzureGovernanceChallengeWorkshop&data=02%7C01%7CScott.McFadden%40microsoft.com%7Cc280a78d8fcb4b04abf508d70300cfe5%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636981174337138490&sdata=iwE87WvyjbemFof2Nn4oF8DfqnTzjRN6JaiHlIbZrfM%3D&reserved=0
        
        Chalenge overview aligns with 5 disciplines
          Cost Management
          Security Baseline
          Resource Consistency
          Identity Baseline
          Deployment Acceleration
Image: https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/_images/governance/incremental-governance-example.png
  - Create descriptions with live links to training required to complete tasks
  - Build infrastructure (AS CODE) required to meet outcomes
  - Create scripts and other assets required to meet outcomes
     a. Hosted Agent deployment
     b. Contoso Bank Corporate Policies (Business Risk, Policy and Compliance and Process)
     c. Create Contoso Bank MVPv1 summary across all 5 disciplines
     d. Create Contoso Bank MVPv2 
     etc...
  - Create scripts and other assets required to deploy for customers to build on their own subscription
  - Confirm all resources / assets are included in "setup" (including licenses AzureAD P2, Azure Subscription)
  - Create Coach cheat sheet for challenge 
      - Sample Hints
      - likely common mistakes and how to get around them
      - additional helpful information to share with customers
  - Execute lab in clean environment (built from script)
     - tweak as needed
  - Deploy automated solution and test for completeness of solution (it works as expected)


## Challenge 1 - Foundation
Goals: 
- Organization Readiness
- Business Problem Identification and Understaning
- introduction to CAF Framework
- Review Foundation Already created - Understand tenant, subscription, RG, MG, Security Policy
- Create Management Group Structure
- Assign Team Roles

### Outcomes: 
- Summarize pre-created foundation & resource strategy
-- summary of environment; and why decisions were made
- Management Group Structure - Self-service portal; process
- Publish basic **shared dashboard** to communicate strategy
- Assign and create cloud team responsiblities (Hint: Complance Manager with RBAC)
  - CISO
  - CAF Discipline Owner
     - Collaboration Strategy (Team Name, [Tools: Slack, Teams, Hangouts, ???])
     {Prefer they come up with their own, other}
  - Workload Owner


### Technology Tools/Services/Lessons:
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
