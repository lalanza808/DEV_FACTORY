## DEV_FACTORY - 2021

a development template for web3

- dev_divi  

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

# Setup

1. Install Javascript dependencies

`npm install`

2. In another terminal run a local node

`npx hardhat node`

3. Import a private key from above node output into MetaMask for testing locally

> in metamask, go to import account -> paste private key

4. Setup local network in MetaMask

> in metamask, go to settings > networks > add network
> enter New RPC URL: http://localhost:8545, enter Chain ID: 31337, Currency Symbol: ETH  

5. Deploy contract to local node

`npx hardhat run scripts/deploy.js --network localhost`

6. Save the contract address and ABI in your frontend Javascript

`cat artifacts/contracts/Greeter.sol/Greeter.json`
> copy/paste contract address from above contract deploy command into Javascript section of `index.html`
> copy/paste ABI into Javascript section of `index.html`

# TODO

* fix this shit
* create react site template
* set function
* integrate metamask_onboarding
