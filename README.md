## DEV_FACTORY - 2021 

a development template for web3 

- divine_dev  

# REPOSITORY STATUS: not working yet : [ 

## PART 1: SETUP 

local environment 

hardhat + contract + frontend html 

0. delete folder hardhat 

1. open 2 terminals 

2. run these commands in terminal 1 

# mkdir hardhat 

# cd hardhat

# npm install --save-dev hardhat && npx hardhat

# [choose defaults for all options]

# npm i dotenv

# npm install @openzeppelin/contracts

# npm install --save-dev "hardhat@^2.6.4" "@nomiclabs/hardhat-waffle@^2.0.0" "ethereum-waffle@^3.0.0" "chai@^4.2.0" "@nomiclabs/hardhat-ethers@^2.0.0"

# cd .. 

# npm install web3 --save 

^ [use this in whatever directory your factory.html is]

# [in terminal 2] cd hardhat 

# [in terminal 2] npx hardhat node
^ this command must be run every time to start your local blockchain 

# copy a private key shown 

# in metamask, go to settings > networks > add network
# enter New RPC URL: http://localhost:8545, enter Chain ID: 31337, Currency Symbol: ETH  

# in metamask, go to import account -> paste private key 

## PART 2: DEPLOY 

1. launch smart contract [do not change anything in smart contract yet!]

# [in terminal 1] cd hardhat 

# npx hardhat run scripts/sample-script.js 

## PART 3: MODIFY

after making changes to smart contract and redeploying, 
in dev_factory.html, 

# 1. replace the content in variable ABI with the content in /artifacts/contracts/Greeter.json

# 2. Replace the content in variable contractAddress with your new address [e.g. 0x5FbDB2315678afecb367f032d93F642f64180aa3]

#

#

#

# next to do: 
    fix this shit 
    create react site template 
    set function 
    integrate metamask_onboarding 