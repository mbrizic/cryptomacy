# Cryptomacy

An Ethereum game inspired by Diplomacy.

## Setup 

Prerequisites: Truffle, NPM, MetaMask

To start a development blockchain, run the following in the root directory:
```
truffle develop
```
It will start a new dev blockchain and open up the Truffle console. After that, in the truffle console, you can run:
```
test
```
to execute the Truffle tests
and:
```
migrate
```
to deploy the smart contracts.

Before starting the React app, go into the "app" directory and run:
```
npm install
```
to install the node dependencies.
Once it is finished, you can run:
```
npm start
```
To start the web app on localhost:3000