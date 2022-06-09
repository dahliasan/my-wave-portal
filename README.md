👀 View the [demo](https://waveportal-starter-project.fooxhd.repl.co/)

# Overview

This is a [buildspace](https://buildspace.so/) project.

This app allows users to send a transaction with a message to the smart contract (waves). There is also a random chance that the user wins a prize of 0.0001eth.

This contract is deployed on the goerli testnet.

# What I learned

### How to create a smart contract

- running a local ethereum network
- deploying the smart contract locally first and testing it's functionality with a run.js file

### Connect to wallet

- how to build the frontend of the app and allow it to connect to a metamask wallet
- how to deploy to a real testnet
- how to use [replit](https://replit.com/) IDE to build the frontend

### How to generate a random number for smart contracts

- It's a difficult problem
- This app uses input from block dfficulty, timestamp and a random seed number for each user
- how to set gas limits for transactions so they don't fail
- how to use `require()` to send the prize money to a specific user

# Built with

- [alchemy](https://www.alchemy.com/)
- [hardhat](https://hardhat.org/)
- ethers.js

# Acknowledgements

- [buildspace](https://buildspace.so/)

# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
