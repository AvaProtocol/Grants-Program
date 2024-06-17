
# OAK Network Grant Proposal

* **Project Name:** Cross-Chain DEX Limit Orders
* **Team Name:** C3 Labs
* **Payment Address:** 0xFC676C7836278577a50a4aB540f4Ff7Da90D15C7 (USDC), 5HTursw8Y2cevzj2PVDAkSF6Lv5snEtiU8fyNbpZFViMTf4b (substrate address to be used for OAK)
* **[Level](https://github.com/OAK-Foundation/Grants-Program#levels):** 2 



## Project Overview

### Overview

This project is aimed at building a comprehensive and user-friendly platform for the users to create limit orders on top of the Solarbeam DEX on Moonriver (potentially can be shifted to Ethereum with the launch of the AVS).

Limit Orders essentially let the users create an intent of delayed execution, where a trade should be executed when the price of an asset is greater than or lower than a threshold.

The platform will use Ava Protocol's __price automation__ to build the limit orders functionality. 



### Project Details


The platform is composed of —
1. Web Frontend
2. Data APIs (to index liquidity pools on Solarbeam)
3. Limit Order functionality through AP's Price Automation

Initially, it'll only support a single DEX, [Solarbeam](https://solarbeam.io/). 

The core functionality of the platform will mostly be borrowed from [this demo](https://www.youtube.com/watch?v=ECgMubdbAY8)


#### Component-wise effort breakdown
1. On-chain automation (3 weeks)
2. UI/UX Design (3 weeks)
3. Web Frontend (2-3 weeks)
4. Data APIs (2 weeks)


#### Tech Stack
- Frontend
    - NextJS
    - TailwindCSS
    - [oak.js](https://github.com/AvaProtocol/oak.js)

- APIs & Indexer
    - Typescript
    - [Hono](https://hono.dev/)
    - MongoDB


### Ecosystem Fit

 
* Where and how does your project fit into the ecosystem?
The project is pivotal to the ecosystem as it can become a flagship example of using price automation in production. 

* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's user base, yourself)?
The project targets users who're actively using DEXes and want to set up more complicated trading strategies, through limit orders. 

* What need(s) does your project meet?
The project lets the users "touch grass" by helping them setup automated trading rules rather than having to be online throughout the day trying to snipe the price action.

* Are there any other projects similar to yours in OAK Network or Turing Network ecosystem?
To the best of knowledge, there is none other than the demo released by the team itself. 


## Team 

### Team members

* Name of team leader
    - Manan Gouhari
* Names of team members 
    - Rohan Pahwa

### Contact

* **Contact Name:** Manan Gouhari
* **Contact Email:** manan@findsignal.studio
* **Website:** [manangouhari.com](https://manangouhari.com)

### Legal Structure

* **Registered Address:** 3 FRASER STREET, #05-25 DUO TOWER, SINGAPORE (189352)
* **Registered Legal Entity:** Find Signal Studio PTE LTD.

### Team's experience

The team has been actively building in crypto for nearly 4 years. This time has seen us build in multiple different ecosystems — Polkadot, Tezos, and Celo to name a few. 

Manan was previously the CTO of YieldBay, where he also acquired and delivered the Mangata Auto-Compounding Grant from OAK Network.

Rohan has spent multiple years in a solutions engineering role in Tezos India Foundation, where he help several projects with on-chain integrations. 

Previously, Manan and Rohan have also won the Polkadot Euro Hackathon together. 


### Team Code Repos



* https://github.com/manangouhari
* https://github.com/rohanphw

## Development Status 

The work on the project has not started yet beyond the research into OAK's price automation feature. 


## Development Roadmap 


### Overview

* **Total Estimated Duration:** 2.5 months (10 weeks)
* **Full-Time Equivalent (FTE):** 2 FTE
* **Total Costs:** 22,000 USD (10k USDC on Ethereum + 12k USD worth AP tokens that may be unlocked 1 month after the mainnet launch, based on a price of 30-day average)


### Milestone 1 — Platform MVP

* **Estimated duration:** 1 month
* **FTE:**  2
* **Costs:** 13,200 USD (6000 USDC + 7,200 USD worth AP tokens)

Deliver an MVP of the fully-functioning limit order flow (without the web platform).



| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a write-up on how the automation flow works |
| 1. | TS Script: Protocol Simulation | We will build a script that will setup a limit order to be executed on the Solarbeam DEX through OAK's price automation |  
| 2. | Wireframes | We will submit the Lo-Fi design for the final web platform |  


### Milestone 2 Example — Additional features

* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 8,800 USD (4000 USDC + 4,800 USD worth AP tokens)

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | We will provide both **inline documentation** of the code and tutorial for anybody to spin up all the repositories to run themselves |
| 1. | Liquidity Indexer | We will build an indexer that periodically refreshes the data for liquidity pools on Solarbeam. This will come in handy to show pricing data to setup a limit order |  
| 2. | Data APIs | We will build the necessary APIs to power the platform — user sessions, token prices, etc. |  
| 3. | Web Frontend | We will deliver a fully-functioning frontend that'll allow the users to — setup a limit order, cancel limit order, check the status of their order |  



## Future Plans

In the short term, we plan to release this project for the Solarbeam community and hopefully partner with Solarbeam for them to officially redirect their users to our platform for limit orders. 

In the longer term, we intend to add more DEXes and chains to achieve more reliable price spreads and target a bigger market. We're also keen to take this up a notch with auto-trading accounts (sort of like a marketplace for trading strategies).


## Additional Information 

**How did you hear about the Grants Program?** Connections to the Ava Protocol team. 
