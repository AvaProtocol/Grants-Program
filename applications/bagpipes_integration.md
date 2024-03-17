# Bagpipes | OAK Network Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Grants Program Process](https://github.com/OAK-Foundation/Grants-Program#process) on how to submit a proposal.

* **Project Name:** OAK Bagpipes No-Code Flow Builder 
* **Team Name:** Bagpipes Org
* **Payment Address:** BagpipesOrg Multisig (5Gn4zF9iY8FbVCcHy1jtrvQjvvfyFJLaTEuq78NgmfjUBqtB), for use on OAK Polkadot, or AssetHub (DOT, USDT)
* **[Level](https://github.com/OAK-Foundation/Grants-Program#levels):** 2  

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview

Bagpipes enables a wide selection of features on chains connected to cross-chain infrastructure, accessible and connectable all in one place. We provide an easy to use drag and drop interface where users can build their own dapps that utilize the best parts of each parachain. Users no longer need to find a developer to code up a MVP, with Bagpipes, a user can get a cross-chain MVP application up and running in minutes. We want to integrate OAK’s advanced scheduling functionality into Bagpipes toolbox. Allowing anyone to utilize the scheduling features based on their needs in a user friendly way. 

Our favored analogy

Polkadot infrastructure is the train infrastructure across an entire region. 
Current chain native apps are like local train services. 
To travel across the region you have to make many hops using different platforms.
Bagpipes lets you design your own train services, so you can go anywhere without stops or hops.

<img src="media/images/bagpipes/bagpipes-example.png" style="width:1200px";>


### Overview

Project Description

The Bagpipes mission is to make building on decentralized applications simple and accessible for everyone, enabling greater productivity, through automation of workflows, from mini-dapps to fully fledged dapps with complex processes. Bagpipes gives a lot of powers to the end users by allowing them to drag and drop together a cross chain workflow and utilize the best pallets from each chain. Solving personal productivity needs, team workflows, or to build dapps for their own set of users. 

The synergy

Bagpipes is an easy to use drag and drop interface for quickly creating custom cross chain application scenarios. 
OAK is an automation blockchain that enable users to build on-chain scheduling with price and time triggers. With “XCM”,  users can use OAK on other chains:

Use cases:

Users can leverage bagpipes as middleware to use OAK automation blockchain to add automation, scheduling and triggers into their workflows. 


Imagine:

Stripe for Web3:
a user can create a bagpipe an drop an OAK node onto the canvas, and connect time trigger into a workflow that takes 1 KSM from a user account every month. 
The user persists this bagpipe and connects to it via an endpoint. 
Read more Bagpipes use cases here: https://xcmsend.github.io/users/profile.html



### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):



Milestone 1 - Initial Bagpipes Integration (3-4 weeks)

Enable cross-chain XCM asset transfers between Turing Network, Kusama and assethub(Kusama assethub).
HRMP checks
Balances, accounts and basic pallet support
Support for Turing in main UI and API
User tutorials and documentation

Milestone 2 - Turing Custom features (4-5  weeks)

Implement Automation pallets integration.
Advanced scheduling 
Support Turings assets and asset types

<img src="media/images/bagpipes/bagpipes-wireframe.jpg" style="width:1200px";>


## Team 

### Team members

* Ramsey Ajram (ramsey@decentration.org)
* Filip Kalebo (filip@firosolutions.com)

### Contact

* **Contact Name:** Ramsey Ajram
* **Contact Email:** ramsey@decentration.org
* **Website:** https://bagpipes.io

### Legal Structure

* **Registered Address:** 008 Westbourne Studios, W10 5JJ, London, UK

* **Registered Legal Entity:** Decentration Trust Company (UIN: 470-2018-233-GB-001 )

### Team's experience

Ramsey Ajram bio:

Hi I’m Ramsey, I’ve been interested in building something that makes this ecosystem - of parachains, primitives, pallets and tools - more accessible to more people, especially the creative and entrepreneurial minds who have a desire to solve their own problems and/or solve other people’s problems, so they can be more effective at experimenting and realizing their ideas and automating their systems and processes..

I have quite a wide ranging experience in the ecosystem. I’m very familiar with the substrate/polkadot repos, and have launched a live parachain, taking it through a crowdloan on Kusama (kabocha parachain). 

I am the product owner of  “supersig” pallet+UI, (where you can create an org, like multisig but you can add and remove members).

I then attended the Polkadot Blockchain Academy, which took me from a hacky mechanic to a blockchain engineer. . And now I want to leverage all of that experience and knowledge gained, channel it into Bagpipes, and make life easier and fun for the next wave of users. 


Filip: 

Started working with information security in 2011 with a love for open source and an urge to explore. Since then, Filip has worked on offensive security for several Fortune 30 companies, trained a red team responsible for finding bugs in Amazon, Facebook and several large entities. 

In the defensive line, Filip has worked on enterprise intrusion detection systems and anti-malware projects. 

In 2014, he started to operate a public Bitcoin node service, thereafter snowballing into Ethereum and Monero development. Filip was introduced to Rust at an OpenSource meetup a few years ago, and is now combining his passion for Rust and web3. In 2021, he started as one of the first Rust developers for early stages of Picasso chain, moved a year later to Edgeware to perform a major substrate version upgrade, and from the pains of this experience, he was compelled to work on an open source project called Uptest, which was funded by the Polkadot Treasury. 


### Team Code Repos

* https://github.com/xcmsend


Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

* https://github.com/decentration
* https://github.com/flipchan


## Development Status 

Bagpipes is a project that was created 8 months ago, and developement is ongoing. This grant is part of a wider funded project and will therefore benefit from continuous version releases. 


## Development Roadmap 

### Overview

* **Total Estimated Duration:** 3 months
* **Full-Time Equivalent (FTE):**  2
* **Total Costs:** $35k ($25k USDC and $10k in OAK which may be blockered by OAK launch, therefore we will assume 12k for M1 and 13k for M2 and then 10k at OAK launch based on 0.22 launch price )

### Milestone 1: Initial Bagpipes integration 


* **Estimated duration:** 1 month
* **FTE:**  2
* **Costs:** 12,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Documentation | Document and user examples  |
| 1. | XCM transfers | Functionality for sending and receiving XCM asset transfer on Turing. Turing <> Kusama Turing <> Kusama Assethub |
| 2. | Asset support | Support on-chain assets metadata, balances and types with Turing's assetRegistry.  |
| 3. | UI customization | UI Turing support |
| 4. | Tests | Unit tests for UI and API  |  
| 5. | API integration | support in the JSON RPC api: https://github.com/XcmSend/api |  
| 6. | XCM HRMP Checks | Integrating filtering of what chains a user can perform xcm transfers from based on open HRMP channels |  


### Milestone 2:Turing Automation features


* **Estimated duration:** 7 weeks
* **FTE:**  2
* **Costs:** 13,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Documentation | Public documentation and user examples |
| 1. | automationPrice and automationTime pallet integration | Add these price and time triggers to Actions in bagpipes. |
| 2. |Querying | Enable users to query the pallet storage.  |
| 3. | Tests | Tests for API and UI |
| 4. | OAK dashboard  | A home area for oak paracahin on bagpipes, containing: A growing list of oak templates; How tos. oak.bagpipes.io This area can also added to by the OAK community.  |  
