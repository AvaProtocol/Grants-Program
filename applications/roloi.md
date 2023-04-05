# OAK Network Grant Proposal

* **Project Name:** Roloi
* **Team Name:** NeoPower
* **Payment Address:** `0x1f5CE2eDdaAAe75ff62729feE50F861bCDC0b62e` (ERC20 USDC)
* **[Level](https://github.com/OAK-Foundation/Grants-Program#levels):** 2 

## Project Overview

### Overview

Roloi is a payment automation platform. The scope of this grant application is to develop the main infrastructure for Roloi to schedule transactions with OAK.

### Project Details

Current payments are static! Payment platforms only allow setting a recipient and amount. But what about deadlines, interests, limits, paydays, over expenses? With such limited solutions, we fall into what we call “financial hell”.

We believe that payment solutions should adapt to people and not the other way around.

That’s why we are creating Roloi, a payment automation platform based on three main pillars:
* Token streaming
* Recurring payments
* Conditional payments


### Ecosystem Fit

Roloi’s payment platform will bring many use cases to the Polkadot ecosystem like:

![NeoPower - OAK Grant Proposal](https://user-images.githubusercontent.com/107150702/230204621-82196b83-c941-43ae-8cdd-9d6041ef4a35.jpg)

There is a big opportunity in the OAK ecosystem to build innovative products that cater to the needs of end-users. That’s where Roloi comes in, our Progressive Web App will allow creating payment flows from one wallet to another in a simple way. Our focus:
* UX
* Security

We will also provide payment infrastructure to build on top of Roloi. This way, any project will be able to easily integrate to our ecosystem.


#### Grant Scope

Our goal is to build the main infrastructure to enable the connection between our ink! smart contract in Astar and the OAK network. That’s why the proposed scope includes:
* Creation of a **UI template** for transaction automation
* Extend template with transaction automation at a **smart contract level**

**This will benefit the OAK ecosystem by providing scalable UI and smart contract templates that can be used by any team, while helping Roloi to set the foundations to integrate the recurring payments feature in the platform using OAK.**


## Team 

### Team members

We are NeoPower, a Web3 software company. Our core team members:
- **Brian Sasbon** (Co-Founder & CEO)
- **Pablo Corrado** (Co-Founder & CTO)
- **Hernán Hermida** (CGO)


### Contact

* **Contact Name:** Brian Sasbon
* **Contact Email:** bsasbon@neopower.digital
* **Website:** https://www.neopower.digital/ 

### Legal Structure

* **Registered Address:** Pacheco 2131, C1431, CABA, Buenos Aires, Argentina
* **Registered Legal Entity:** NeoPower Digital, LLC

### Team's experience

#### Founders

We are Brian and Pablo, **Software Engineers** with a Degree from the National Technological University (UTN) from Buenos Aires, Argentina, and have more than **10 years of experience** as developers for many different projects. We have strong experience working as **Full-stack Developers** and **Team Managers** for US traditional finance clients like Morgan Stanley, Visa and JP Morgan.

6 years ago **we founded NeoPower**, our own software company to work for different clients building freelance teams of designers, developers and testers.

We started our journey with NeoPower to solve real-world problems with Web3 products that are secure and have a great user experience. Roloi is our main product.


#### CGO

**Hernán S. Hermida** (aka [Milstein](https://twitter.com/MilsteinmAb)) is a **DeFi Researcher** with more than 2 years of experience contributing with educational communities in Latam. Currently, he **hosts #DeFiSpace** a weekly Twitter Spaces cycle, with more than 50 episodes, interviewing builders from different multi-chain projects, and creates content for [“La Multisig”](https://www.youtube.com/@LaMultisig), a web3 educational YouTube Channel with its own community. 

He’s the growth lead of [DeFi Argentina](https://twitter.com/DeFiArgentina) a non-profit project that helps children’s food banks in Argentina by collecting donations in cryptocurrencies. 

He’s also an **OAK ambassador** since Nov 2022.

Hernán is part of the **Roloi team** as CGO to help with the growth, research and networking strategy, leveraging his knowledge about DeFi and communities.

### Team Code Repos
* [NeoPower Github Repository](https://github.com/NeoPower-Digital)

## Development Status 

We are working with the library [inkathon](https://github.com/scio-labs/inkathon) to simplify UI development and connection to the blockchain, this allows developers to focus more on solving actual problems.

On the other hand we’ve been exploring OAK **code examples** and we identified some improvements that need to be built in the form of project templates to push forward the creation of new products using OAK.

We had the opportunity to pitch Roloi to the OAK team and our plans to **build the core infrastructure needed to configure recurring transactions from our ink! smart contract.**

## Development Roadmap 

### Overview

* **Total Estimated Duration:** 2 months
* **Full-Time Equivalent (FTE):** 4
* **Total Costs:** 50,000 USD

### Milestone 1 — Automation UI Template

* **Estimated duration:** 1 month
* **FTE:** 4
* **Costs:** 25,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | The milestone will include technical documentation of the UI project. |
| 0c. | Testing Guide | Core functions will be covered by unit tests to ensure functionality and robustness. We will describe how to run these tests in the docs. |
| 1. | UI Source Code | We will deliver a Next.js UI project that enables the execution of a simple recurring task (on-chain event) and works as a template to be reused for any team that needs automated tasks. Tools and libraries: Next.js, Typescript, Material UI, XState. *The scope of this Milestone will cover only testnet chains.* |  
| 1a. | Wallet connection | The UI will connect with Polkadot Wallets using inkathon functionalities. |  
| 1b. | Chain connections | The UI will allow the user to connect with different parachains (Astar, Mangata, etc) using inkathon functionalities. The chains must be connected with OAK. |  
| 1c. | Proxy Accounts | The UI will solve the configuration for the proxy accounts: If they don’t exist for the connected account, create them, transfer funds to each proxy account and assign them the appropriate permissions. |  
| 1d. | Create recurring task | The UI will include a simple event configured to be easily triggered recurrently on the selected chain. |  
| 1e. | Cancel task | The UI will include a form to cancel a specific OAK task ID. |  


### Milestone 2 — Automation of Smart Contract transactions 

* **Estimated Duration:** 1 month
* **FTE:** 4
* **Costs:** 25,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | The milestone will include technical documentation of the functionalities added to the UI. |
| 0c. | Testing Guide | New core functions will be fully covered by unit tests to ensure functionality and robustness. We will describe how to run these tests in the docs. |
| 0d. | Article | An article will be published that explains how to use this UI project as a starting point for generating a front-end that creates automated tasks using OAK. |
| 1. | UI Source Code | We will allow the configuration of recurring ink! smart contract transactions. *The scope of this Milestone will cover only testnet chains.* |  
| 1a. | Recurring Smart Contract transactions | Add functionality to the template project to enable configuration of automated execution of a specific **ink!** Smart contract transaction. | 
| 2. | Smart contract Source Code | We will deliver an example of an ink! smart contract as a default use case. It will include simple transactions such as transfers, events emission, or storage modification.  |  


## Future Plans

* Both template projects (UI and smart contract) will be open source for other teams to leverage
* Roloi will use both templates to fully implement recurring payments on our platform
* New features can be added to the template:
  * Allow the interaction between ink! smart contracts and OAK directly by contract code using XCM transactions.


## Additional Information 

**How did you hear about the Grants Program?** OAK Network Website & Meeting with Chris and David. 

Links:
* https://roloi.money
* https://neopower.digital


