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
Update on 2024-05-29 at 11:34:47 - Update #3
Update on 2024-06-01 at 17:22:28 - Update #1
Update on 2024-06-01 at 9:44:24 - Update #2
Update on 2024-06-02 at 19:3:11 - Update #1
Update on 2024-06-02 at 5:59:22 - Update #2
Update on 2024-06-02 at 21:11:8 - Update #3
Update on 2024-06-05 at 5:8:48 - Update #1
Update on 2024-06-05 at 10:40:46 - Update #2
Update on 2024-06-07 at 5:0:11 - Update #1
Update on 2024-06-10 at 1:11:53 - Update #1
Update on 2024-06-10 at 12:29:16 - Update #2
Update on 2024-06-10 at 23:47:44 - Update #3
Update on 2024-06-11 at 2:47:19 - Update #1
Update on 2024-06-11 at 7:46:7 - Update #2
Update on 2024-06-12 at 6:52:19 - Update #1
Update on 2024-06-12 at 15:46:31 - Update #2
Update on 2024-06-13 at 22:38:38 - Update #1
Update on 2024-06-13 at 7:46:17 - Update #2
Update on 2024-06-15 at 16:18:25 - Update #1
Update on 2024-06-15 at 15:15:33 - Update #2
Update on 2024-06-16 at 18:42:53 - Update #1
Update on 2024-06-16 at 12:26:53 - Update #2
Update on 2024-06-16 at 23:5:32 - Update #3
Update on 2024-06-17 at 11:35:17 - Update #1
Update on 2024-06-17 at 4:45:18 - Update #2
Update on 2024-06-17 at 18:42:25 - Update #3
Update on 2024-06-18 at 7:21:44 - Update #1
Update on 2024-06-18 at 9:14:57 - Update #2
Update on 2024-06-19 at 17:31:52 - Update #1
Update on 2024-06-19 at 12:34:20 - Update #2
Update on 2024-06-20 at 2:20:50 - Update #1
Update on 2024-06-21 at 18:50:53 - Update #1
Update on 2024-06-21 at 15:15:54 - Update #2
Update on 2024-06-21 at 11:3:31 - Update #3
Update on 2024-06-23 at 18:42:5 - Update #1
Update on 2024-06-23 at 21:15:32 - Update #2
Update on 2024-06-23 at 8:26:6 - Update #3
Update on 2024-06-24 at 10:10:51 - Update #1
Update on 2024-06-25 at 1:12:8 - Update #1
Update on 2024-06-25 at 13:39:15 - Update #2
Update on 2024-06-25 at 5:13:36 - Update #3
Update on 2024-06-26 at 21:8:34 - Update #1
Update on 2024-06-26 at 5:31:36 - Update #2
Update on 2024-06-27 at 8:59:30 - Update #1
Update on 2024-06-28 at 8:10:16 - Update #1
Update on 2024-06-30 at 21:1:47 - Update #1
Update on 2024-06-30 at 1:11:1 - Update #2
Update on 2024-06-30 at 19:35:57 - Update #3
Update on 2024-07-01 at 0:19:11 - Update #1
Update on 2024-07-01 at 9:12:25 - Update #2
Update on 2024-07-01 at 3:16:35 - Update #3
Update on 2024-07-02 at 6:29:14 - Update #1
Update on 2024-07-02 at 3:9:43 - Update #2
Update on 2024-07-02 at 1:58:9 - Update #3
Update on 2024-07-03 at 5:9:27 - Update #1
Update on 2024-07-03 at 21:32:43 - Update #2
Update on 2024-07-03 at 18:6:29 - Update #3
Update on 2024-07-05 at 7:11:44 - Update #1
Update on 2024-07-05 at 8:7:45 - Update #2
Update on 2024-07-05 at 0:16:21 - Update #3
Update on 2024-07-06 at 16:50:28 - Update #1
Update on 2024-07-06 at 3:45:37 - Update #2
Update on 2024-07-06 at 3:18:1 - Update #3
Update on 2024-07-08 at 20:55:52 - Update #1
Update on 2024-07-08 at 21:38:53 - Update #2
Update on 2024-07-09 at 11:6:37 - Update #1
Update on 2024-07-09 at 10:28:33 - Update #2
Update on 2024-07-10 at 14:30:8 - Update #1
Update on 2024-07-10 at 7:31:47 - Update #2
Update on 2024-07-10 at 1:17:57 - Update #3
Update on 2024-07-11 at 22:54:5 - Update #1
Update on 2024-07-11 at 13:3:21 - Update #2
Update on 2024-07-11 at 18:46:32 - Update #3
Update on 2024-07-12 at 20:9:17 - Update #1
Update on 2024-07-12 at 11:57:30 - Update #2
Update on 2024-07-12 at 22:48:17 - Update #3
Update on 2024-07-13 at 2:31:4 - Update #1
Update on 2024-07-14 at 12:52:54 - Update #1
Update on 2024-07-14 at 20:14:30 - Update #2
Update on 2024-07-15 at 17:18:17 - Update #1
Update on 2024-07-16 at 1:9:52 - Update #1
Update on 2024-07-16 at 9:36:50 - Update #2
Update on 2024-07-17 at 7:34:20 - Update #1
Update on 2024-07-17 at 17:37:37 - Update #2
Update on 2024-07-18 at 21:14:39 - Update #1
Update on 2024-07-18 at 12:30:21 - Update #2
Update on 2024-07-19 at 18:29:51 - Update #1
Update on 2024-07-19 at 6:56:38 - Update #2
Update on 2024-07-19 at 3:19:4 - Update #3
Update on 2024-07-20 at 12:12:2 - Update #1
Update on 2024-07-20 at 16:40:15 - Update #2
Update on 2024-07-20 at 2:11:45 - Update #3
Update on 2024-07-21 at 19:26:55 - Update #1
Update on 2024-07-21 at 7:26:50 - Update #2
Update on 2024-07-22 at 19:34:29 - Update #1
Update on 2024-07-22 at 7:18:13 - Update #2
Update on 2024-07-22 at 11:48:51 - Update #3
Update on 2024-07-23 at 2:11:11 - Update #1
Update on 2024-07-23 at 22:24:23 - Update #2
Update on 2024-07-23 at 8:14:33 - Update #3
Update on 2024-07-24 at 3:14:24 - Update #1
Update on 2024-07-24 at 6:23:43 - Update #2
Update on 2024-07-25 at 3:56:9 - Update #1
Update on 2024-07-25 at 21:1:18 - Update #2
Update on 2024-07-25 at 1:31:44 - Update #3
Update on 2024-07-26 at 17:53:47 - Update #1
Update on 2024-07-27 at 2:34:14 - Update #1
Update on 2024-07-28 at 8:27:22 - Update #1
Update on 2024-07-28 at 3:3:37 - Update #2
Update on 2024-07-28 at 20:40:16 - Update #3
Update on 2024-07-29 at 18:44:31 - Update #1
Update on 2024-07-29 at 7:9:0 - Update #2
Update on 2024-07-30 at 7:33:39 - Update #1
Update on 2024-07-30 at 19:18:2 - Update #2
Update on 2024-07-30 at 10:27:32 - Update #3
Update on 2024-07-31 at 3:58:10 - Update #1
Update on 2024-08-01 at 10:29:33 - Update #1
Update on 2024-08-01 at 23:32:8 - Update #2
Update on 2024-08-02 at 11:22:56 - Update #1
Update on 2024-08-02 at 8:13:54 - Update #2
Update on 2024-08-05 at 23:32:7 - Update #1
Update on 2024-08-06 at 18:0:3 - Update #1
