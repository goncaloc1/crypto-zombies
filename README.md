
### CryptoZombies Solidity Smart Contracts and the ERC721 Standard

This repository showcases a simple blockchain-based game to learn and apply Solidity smart contracts and the ERC721 standard.

##### What Was Built
- A Zombie Factory and Battle System DApp covering features such as contract ownership, payable functions, gas cost optimization and security;
- Tokens and Crypto-Collectibles: explored the ERC721 standard and how to create NFT assets for collectibles;
- App Front-ends with Web3.js;
- Understood how to build and interact with oracles to integrate external data into the DApp.


##### Cheatsheet
Rinkeby public address 0x5A3f5C90AFDF2E99Bd4fB1e1e3d292467e5C4b36

```
// Executes development network by default

truffle migrate


// Test network rinkeby

truffle migrate --network rinkeby


// With reset truffle will re-execute all the steps

truffle migrate --network rinkeby --reset


// Starts development network

truffle development


// Starts console connecting to rinkeby network

truffle console --network rinkeby


// Interacting with console

const instance = await CryptoZombies.deployed()

await web3.eth.getAccounts()

await instance.createRandomZombie("Costa")

await instance.ownerOf(0)

await instance.balanceOf('0x5A3f5C90AFDF2E99Bd4fB1e1e3d292467e5C4b36')
```
