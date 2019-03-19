# Crypto Star dApp

## Summary
This smart contract app places an asset, a star, on the Ethereum blockchain. A basic front-end allows the user to enter a Star name and Star id that will be placed on the blockchain. The user then may be able to look up the Star by entering the Star id.

## Details
The smart contract is published to the Rinkeby test network at address: <b>0x5AAa7488254e4aCECB97f2135Ae2CEcC7d635Fae</b>

The ERC-721 Token name is: <b>Jake Star Token</b>

The ERC-721 Token Symbol is: <b>JST</b>

A Star Transaction can be found at Transaction Hash: <b>0x9dcae7b8bc49453c00512d9b26be035bab014d02ad1c1c159ee93750a9290690</b>

The Rinkeby test network can be searched using either the contract address or transaction hash at:
<b>https://rinkeby.etherscan.io<b>

## Software Tools
The smart contract was built using Truffle and OpenZeppelin
Truffle version: <b>v5.0.7</b>
OpenZeppelin version: <b>2.1.2</b>
Infura to work with the Rinkeby test network
Metamask as a chrome plugin to allow browser based interaction with the Ethereum blockchain

# Getting Started
1. Clone / Download the Repository at:
2. Install any dependencies including:<br>
`npm install --save truffle-hdwallet-provider`<br>
`npm install --save openzeppelin-solidity`<br>
3. Enter truffle development console to compile and deploy the contract
`truffle develop`<br>
`compile` to compile<br>
`migrate --reset` to deploy locally<br>
`migrate --reset --network rinkeby` to deploy to the Rinkeby test network<br>
4. Once the contract has successfully deployed, you can run the front-end to interact with the contract<br>
`cd app`<br>
`npm run dev`<br>
