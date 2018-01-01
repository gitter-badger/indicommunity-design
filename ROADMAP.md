## QUARTER 2 2017
Concept development and research
Domain name registered


## QUARTER 3 2017
• Token presale 
• Whitepaper and platform development 
• Initial part team creation 
• Project initiated with local NGOs support & affiliation 
• Community development

## QUARTER 4 2017
Non-Profit organization registration
Token Sale
Listing on various Exchanges
Distribution Plan Update
Audit and Revision
Community Plan Update
Indicoin Comm-Tech conferences and token summit
intially tour planned for India
International summits organized by the community of specific location (integrated on platform itself)
Community Summit
Hackathons for project development
Bug bounties

## QUARTER 1 2018
• Distribution protocol	development 
• Integrated and independent platform development 
• Smart Contract for Social Vault development
• Collaboration with non-profit organisations and other social   partners
• Incubation and community center setups all over the world


IndiCommunity Software Roadmap
------------------------------

This document outlines the development plan from a high level and will be updated as progress is made toward version 1.0. It should be noted that this roadmap applies only to the indicommunity platform and not to the other projects of indicommunity by CommTechLabs such as conferences, community meet-ups which will have their own teams and dedicated roadmaps once Phase 1 of software development is complete.

***Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only. CommTechLabs does not guarantee the accuracy of the information contained in this roadmap and the information is provided “as is” with no representations or warranties, express or implied.***

# Phase 1 - Distribution Protocol: Campaign Criterion :- Q1 2018

The goal of this phase is to finalize the distribution protocol and deploy the smart-contracts for it on the ethereum network. A minimal user-interface that interacts with the contracts in order for the community to offer feedback and analyse the difficulties arising when the community tries to collaborate for raising campaigns and projects on the platform and holding delegates accountable.

### Smart-Contracts (Rohan)

The indicommunity software has a number of native contracts. These are contracts that manage the core operations of the indicommunity incentivisation, funds tracking and unlocking mechanisms and exist outside the indicommunity interface. These contracts include:

  1. @indi - manages indi token transfers
  2. @vault - manages locked indi, campaign voting, and delegate elections
  3. @system - manages permissions, messages, and contract code updates demanded by community

### Expose API of smart-contracts on front-end (Rohan)

Contracts are compiled to Ethereum Virtual Machine bytecode (EVM) deployed on the network. The network nodes expose functions of these contracts as RPC end-points. Javascript functions that run on the user's broswer and communicate with these RPC end-points. The user-side actions invoke these functions for fetching or updating data on the blockchain. These functions are what any user-interface depends upon to communicate with the blockchain and it must be relatively stable before designers can start making user-facing websites and apps for the community.

### User-Authentication

Users will need ethereum wallets to be able to interact with the blockchain. Each interaction needs to first be authenticated(signed) by the user before the message can be sent to the blockchain. This is critical for interacting with the alpha version of the platform.

### Discussion and Polling Interface (Shobhit)

Command line tools facilitate integrating the RPC interface with developer build environments.

NGOs and workers raising promises targeting locked funds to unlock

# Phase 2 - Minimal Viable Platform: (Alpha) - Q2 2018

Phase 1 encapsulates the development of code that facilitates communication with the blockchain. Before a test platform can be deployed several additional features on the user-interface need to be implemented and tested.

### **Screen 0: User-login**

### **Screen 1: Main homescreen**

### **Screen 2: Decision-making**

### **Screen 3: Work


### Platform Usage Documentation (Supreet)

### Campaign costing: limiting cost alloted to campaign

### Genesis Import Testing

Tools need to be developed to bring in indicoin holders export data from the indicoin t. This will enable anyone holding indicoins to participate in the governance of funds.

### Work-reporting

This feature involves verifying the work done by the delegates matches the requirements set by the community.

### Collaborating with NGOs, Cryptocurrency Exchanges 

All money brought in by exchanges, governments, businesses to buy indicoin. Any transaction can get a cut of indicoin.

# Phase 3 - Beta Testing & Security Audits - Winter 2018, Spring 2019

During this phase the platform will undergo heavy testing with a focus on finding security issues and bug. At the end of Phase 3 version 1.0 will be tagged.

### Example campaigns

Example campaigns establishing the life-cycle of a campaign is critical to proving the platform provides the features required by the community.
Bringing in NGOs to cooperate. Raising funds for the campaign. All funds collected from markets are locked in indicoins which are decided by community where it should flow.

### Bounties for succesfully manipulating the community and unlocking funds from the platform


### Language Support

Adding support for additional langauges so that the platform can be universally be used by all communinities.

### Documentation & Tutorials


# Phase 4 - Indiex Exchange / Fall 2018


# Phase 5 - Partnership and Inclusion

