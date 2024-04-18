## Project name:
Bagpipes  

## Milestone nr: m1

## Grant application link:
[Grants-Program/applications/bagpipes_integration.md](https://github.com/OAK-Foundation/Grants-Program/blob/main/applications/bagpipes_integration.md)

### Payment details:   
Bagpipes Org address: [15iN8aQnPuX4vjcovenu15EtnYfcwbtiXjeKGRN3KkkzNNtt](https://assethub-polkadot.subscan.io/account/15iN8aQnPuX4vjcovenu15EtnYfcwbtiXjeKGRN3KkkzNNtt)    
We ask for 12000 USDT for m1 on Polkadot Assethub to the BagpipesOrg address. 

### M1 features:  



| nr| Name         | Delivery notes:     | Description|
|---|--------------|-----------|------------|
| 0   | Documentation | Find documentation here: [https://docs.bagpipes.io/docs/xtransfer/turing](https://docs.bagpipes.io/docs/xtransfer/turing) | Documentation        |
| 1   | XCM transfers |  XCM Asset directions: Turing > Moonriver, Moonriver > Turing, Turing > MangataX  | Functionality for sending and receiving XCM asset transfer on Turing. |
|2	|Asset support|We support Turing asset types plus TUR on Moonriver and Tur on MangataX|Support on-chain assets metadata, balances and types with Turing's assetRegistry. |
|3	|UI customization|We now support Turing chain nodes, you can run it locally or view it online here: https://app.xcmsend.com |UI Turing support, logos, styles etc|
|4	|Tests|Run Turing test by cloning the github.com/xcmsend/app.git repo and running: npm install && npm run test |Unit tests for UI and API |
|5	|API integration|Support for turing xcm transaction drafting in pr: https://github.com/XcmSend/api/pull/35 , Read docs here: https://docs.bagpipes.io/docs/xtransfer/turing#use-turing-with-our-api |support in the JSON RPC api: https://github.com/XcmSend/api|
|6	|XCM HRMP Checks|Kusama parachains hrmp ingress and egress checks in main repo. |Integrating filtering of what chains a user can perform xcm transfers from based on open HRMP channels|

### Review tips:  

##### Documentation: 
[https://docs.bagpipes.io/docs/xtransfer/turing](https://docs.bagpipes.io/docs/xtransfer/turing)   


#### Run unit tests on a linux/mac os environment: 
Make sure you have npm install and run the following commands:   
```shell 
git clone https://github.com/XcmSend/app  && cd app/ 
npm install && npm run test
```

This is the correct output to look for:
```
Checking turing Native balance ok
Checking TUR on Moonriver Balance 
Checking TUR on Moonriver Balance successful 
Drafting Transaction Turing > Moonriver
Drafting Transaction Turing > Moonriver ok
Drafting Transaction Moonriver > Turing 
Drafting Transaction Moonriver > Turing ok 
Drafting Transaction Turing > Mangatax
Drafting Transaction Turing > Mangatax ok
test for Turing Finished
```



### Test the HTTP api locally: 
```
git clone git@github.com:XcmSend/api.git 
npm install -f
npm run buildme  
npm run api
```
Read docs: [https://docs.bagpipes.io/docs/xtransfer/turing#use-turing-with-our-api](https://docs.bagpipes.io/docs/xtransfer/turing#use-turing-with-our-api)


#### Video how-to:   

[Turing > Moonriver XCM](https://drive.google.com/file/d/1-dr8exA8TqwbuhJlqnkFnS-RkBGOm8YN/view?usp=drive_link)     
[Moonriver > Turing XCM](https://drive.google.com/file/d/1Jrl5DQzu_2t4iuBKVu_hyQqzdJ8HeL9B/view?usp=drive_link)     
[Turing > MangataX XCM](https://drive.google.com/file/d/11GEzdcWewIDYSl7lKP80HCIV_kR3YOzD/view?usp=sharing)
