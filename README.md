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
Update on 2024-04-24 at 7:33:14 - Update #3
Update on 2024-04-25 at 10:18:26 - Update #1
Update on 2024-04-28 at 17:39:49 - Update #1
Update on 2024-04-28 at 14:31:40 - Update #2
Update on 2024-04-29 at 9:8:36 - Update #1
Update on 2024-04-29 at 0:32:55 - Update #2
Update on 2024-04-29 at 11:49:5 - Update #3
Update on 2024-05-01 at 16:22:35 - Update #1
Update on 2024-05-01 at 8:22:42 - Update #2
Update on 2024-05-02 at 0:26:25 - Update #1
Update on 2024-05-02 at 22:25:56 - Update #2
Update on 2024-05-02 at 23:16:43 - Update #3
Update on 2024-05-03 at 6:2:13 - Update #1
Update on 2024-05-04 at 23:27:3 - Update #1
Update on 2024-05-04 at 5:34:48 - Update #2
Update on 2024-05-04 at 8:32:30 - Update #3
Update on 2024-05-06 at 0:28:2 - Update #1
Update on 2024-05-10 at 4:1:40 - Update #1
Update on 2024-05-10 at 23:17:17 - Update #2
Update on 2024-05-11 at 14:19:15 - Update #1
Update on 2024-05-11 at 8:27:35 - Update #2
Update on 2024-05-11 at 6:11:3 - Update #3
Update on 2024-05-12 at 5:37:14 - Update #1
Update on 2024-05-12 at 18:9:43 - Update #2
Update on 2024-05-12 at 10:23:45 - Update #3
Update on 2024-05-15 at 3:35:6 - Update #1
Update on 2024-05-15 at 13:24:15 - Update #2
Update on 2024-05-17 at 16:58:3 - Update #1
Update on 2024-05-19 at 12:43:59 - Update #1
Update on 2024-05-19 at 1:31:5 - Update #2
Update on 2024-05-20 at 16:27:8 - Update #1
Update on 2024-05-20 at 23:12:42 - Update #2
Update on 2024-05-20 at 12:19:12 - Update #3
Update on 2024-05-21 at 12:34:5 - Update #1
Update on 2024-05-21 at 11:8:31 - Update #2
Update on 2024-05-22 at 3:37:9 - Update #1
Update on 2024-05-23 at 16:56:29 - Update #1
Update on 2024-05-24 at 10:25:12 - Update #1
Update on 2024-05-24 at 0:49:1 - Update #2
Update on 2024-05-26 at 18:42:23 - Update #1
Update on 2024-05-27 at 1:18:50 - Update #1
Update on 2024-05-28 at 19:50:39 - Update #1
Update on 2024-05-28 at 15:28:39 - Update #2
Update on 2024-05-28 at 5:1:54 - Update #3
Update on 2024-05-29 at 9:4:13 - Update #1
Update on 2024-05-29 at 0:8:26 - Update #2
