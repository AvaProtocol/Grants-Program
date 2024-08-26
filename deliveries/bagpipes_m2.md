## Project name:
Bagpipes  

## Milestone nr: M2

## Grant application link:
[Grants-Program/applications/bagpipes_integration.md](https://github.com/AvaProtocol/Grants-Program/blob/main/applications/bagpipes_integration.md)

### Payment details:   

Bagpipes USDC (Ethereum): 0x13d3a4dc4eddc79e5f277d4633834ba6ada15a7f    
13000 USDC

10000 USD in Ava tokens after 30 days of launch of token. Address to be provided . 


### Milestone 2:Turing Automation features


* **Estimated duration:** 7 weeks
* **FTE:**  2
* **Costs:** 13,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Documentation | Public documentation [https://docs.bagpipes.io/docs/nodes/chainTx](https://docs.bagpipes.io/docs/nodes/chainTx)  | |
| 1. | automationPrice and automationTime pallet integration | **Overdelivery, we support every pallet in Turing and Oak. This was really the only way to do it, because the pallets were much more complex than initially imagined, with depply nesting structures, particularly used with XCM.** | 
| 2. | Querying | Enable users to query the pallet storage.   |
| 3. | Tests | Tests for API and UI |
| 4. | OAK dashboard  | A home area for oak paracahin on bagpipes, containing: A growing list of oak templates; How tos. [https://alpha.bagpipes.io/#/pages/Ava](https://alpha.bagpipes.io/#/pages/Ava) |  

### Review tips:  

#### Documentation: 
[https://docs.bagpipes.io/docs/nodes/chainTx](https://docs.bagpipes.io/docs/nodes/chainTx)   


#### Docker:

##### Build
`docker build -t xcmsend:v0.3.1 .`

#### Run 
`docker pull xcmsend/xcmsend:v0.3.1`

[docker image](https://hub.docker.com/layers/xcmsend/xcmsend/0.3.1/images/sha256-f4aa5bf1fa46b00dd021c1f87c23a402be93ec2a4baacad71b3f06236b13adbc?context=explore)






