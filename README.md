Rinkeby public address 0x5A3f5C90AFDF2E99Bd4fB1e1e3d292467e5C4b36

#### Cheatsheet

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
