# solidity-update-number

A Solidity project where you can store a number in a contract and retrieve it.

This project make a contract on a localtestnet with truffle, the goal is to play with contract and look at how to interact with it on the front.

You have two folder : 

  - server, that hold the front 
  - truffle, that hold the contract and truffle config

Started deploying the contract
```bash
  cd truffle && npm i 
  truffle compile && migrate
```
The truffle file is configured to deploy on the testnet by default.

Started the server 
```bash
  cd server && npm i 
  npm run dev
```
The truffle file is configured to deploy on the testnet by default.

If you have make some change in the Box contract, don't forget to copy the new ABI into server/public/box.json

To interact with the contract, you need to be connected to the local testnet.

Configure your metamask network like this : 
```bash
  New RPC URL: HTTP://127.0.0.1:7545
  Chain ID: 1337
  Currency Symbol: CPAY
````
