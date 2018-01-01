# IndiCommunity Design

This repository contains documents describing the design of the Indicommunity platform.

## Overview

Indicommunity is a distributed blockchain-based social media platform for communities to collaborate on social issues, raise funds and resources for campaigns, plan and delegate leadership for conducting campaigns, and ensure the proper use of funds and resources towards the purpose they were created for.

Indicommunity is being developed by [CommTechLabs](https://www.commtechlabs.com/) and is powered by [indicoins](http://www.github.com/CommTechLabs/indicoin-crowdsale/) for incentivising participation on the platform. *Expect the contents of this repository to be in flux: everything is still under discussion.*

- **Indicommunity is an interface for social-governance**: Indicommunity [user-interface](interface.md) is designed to bring forth meaningful discussions on important issues and lead it to productive solutions backed by community support.

- **Indicommunity is decentralised and uncensorable**: Indicommunity [technical-infrastructure](infrastructure.md) is built as a distributed web-app by making use of the blockchain infrastructure for storing the community data. This makes the platform resilient against any censorship attempts.

- **Indicommunity is open and transparent**: Openness implies anyone can participate and no one can be barred from entry. Transparency implies all allocation of funds and resources are visible publicly and everyone has the permission to audit the records by default.

- **Indicommunity is incentivised**: Indicommunity is designed to [incentivise](distribution.md) productive interactions between users of the platform. Each discussion has a potential to develop into a campaign or a movement rewarding the participants with indicoins for their positive contributions.

- **Indicommunity is accountable**: Delegates are elected for taking responsibility for hosting and executing the campaign successfully in the real world and report back on the platform where the community approves the unlocking of funds to the delegates thus ensuring accountability. Campaigns and contributions need to match [specifications](criterion.md) to be rewarded thus ensuring accountability for all. Indicommunity is a self-governing platform where its users (indicoin holders) are the owners.

Indicommunity is a blockchain database that supports
- Fund raising
- Social interaction to decide the direction of the flow of funds
- Accountability of social funds

with cryptocurrency rewards for participation. It provides a fair accounting system which is publicly auditable. Subjective contributions by indicoin holders to the platform are accurately and transparently rewarded. The platform protocol creates open and fair economic games built into the interaction protocol of the platform thus making use of subjective inputs from individual humans to reach decisions instead of concentrating power of decision making into a single hand or having a computer make the decisions(it can't, yet).

## Design Process & Contributing

The indicommunity design specification is being developed in this repository [design repository](https://github.com/CommTechLabs/indicommunity-design). Note that repository is focussed on the overall conceptualisation of the network and the platform and does not include the technical implementation of this design which are available in their own respective repositories. Design discussions should continue to be held in this repository, via issues and pull requests. A description of the breakup of design documents:

| Resource                                   | Description              |
|--------------------------------------------|--------------------------|
| [Roadmap](ROADMAP.md)                      | Tentative timeline for platform releases and activities |
| [Interface](interface.md)                  | Front-end User-Interface flow chart |               
| [Infrastructure](infrastructure.md)        | Back-end decentralised servers and databases |
| [Distribution](distribution.md)            | Indicoin distribution protocol mapped to milestones reached |
| [Criterion](criterion.md)                  | Set of criteria with each user activity for it to clear milestones |


We've mapped out features we expect to ship:

 1. An initial [Alpha version](alpha.md) release;
 2. And soon after in [future versions](versions.md).

Join us:

 * On [telegram](https://t.me/joinchat/GOtyVEwAnWt79WDmVoQlGA) for design discussion
 * On [medium](https://medium.com/@Indi_Coin) for updates
 * By [contributing](Contributing.md)!

When contributing, please follow our [Code of Ethics and Professional Conduct](CodeOfConduct.md).
