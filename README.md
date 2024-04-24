# P2P Lending platform
Peer 2 peer lending platform on the Ethereum blockchain network.

# About

We all know that in the Banking industry it is all about the constant search of bigger profits without caring about customers.

Credit borrowers are paying higher interest rates every day while people investing are having poor returns. There are also a few hidden fees that the customer doesn't know about.


# Features

  - Ask for funding (borrow)
  - Provide details of the requested funding.
  - Withdrawal of funding after successfully reached goal of full funding.
  - Repayment installments functionallity.
  - Invest in project/credit (lend)
  - Vote for revoke contract / refund investments.
  - Mark project as Fraud.
  
## Chart flow

![Chart flow](https://i.imgur.com/vRq7nAN.png)



### Requirements
* [Node.js](https://nodejs.org/)
* [Truffle](https://truffleframework.com/)
* [Ganache](https://truffleframework.com/ganache/)
* [MetaMask](https://metamask.io/)
    
### Installation

1. Start Ganache on ``localhost:7545``   

2. Build and migrate smart contracts

```sh
$ cd p2p-lending/smart-contracts
$ truffle complie
$ truffle migrate --reset --network development --verbose-rpc
```

3. Set the ``PeerToPeerLending`` contract newly published address in the [client-app/public/js/contract_interaction.js LINE:3](https://github.com/mradkov/p2p-lending/blob/370bde2a452caff4831d5e91157f733ce9921a99/client-app/public/js/contract_interaction.js#L5) 

4. Install the dependencies and devDependencies and start the server.

```sh
$ cd p2p-lending/client-app
$ npm install --save
$ npm start
```

5. Your app is running on ``http://localhost:1337``
Update on 2024-04-11 at 16:3:25 - Update #1
Update on 2024-04-11 at 11:42:41 - Update #2
Update on 2024-04-12 at 0:46:2 - Update #1
Update on 2024-04-12 at 12:31:28 - Update #2
Update on 2024-04-13 at 20:15:1 - Update #1
Update on 2024-04-13 at 0:26:11 - Update #2
Update on 2024-04-14 at 18:1:57 - Update #1
Update on 2024-04-14 at 4:12:40 - Update #2
Update on 2024-04-15 at 17:28:49 - Update #1
Update on 2024-04-15 at 5:23:0 - Update #2
Update on 2024-04-18 at 10:33:52 - Update #1
Update on 2024-04-19 at 9:18:54 - Update #1
Update on 2024-04-20 at 16:11:15 - Update #1
Update on 2024-04-20 at 7:19:33 - Update #2
Update on 2024-04-21 at 5:37:44 - Update #1
Update on 2024-04-21 at 3:37:8 - Update #2
Update on 2024-04-23 at 10:27:50 - Update #1
Update on 2024-04-23 at 10:41:12 - Update #2
Update on 2024-04-24 at 9:46:57 - Update #1
Update on 2024-04-24 at 10:38:2 - Update #2
