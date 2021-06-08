
# Election - DAPP Tutorial
Build your first decentralized application, or Dapp, on the Ethereum Network!


## Code
https://github.com/Javed69/Ethereum-Voting-Dapp

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. 
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## This is how an Client server architecture works at a very high level.
<img src="./Client Server Architecture.png">

## This is how an Ethereum Dapp looks at a high level:
<img src="./Ethereum Dapp.png">

## Step 1. Clone the project
`git clone https://github.com/Javed69/Ethereum-Voting-Dapp`

## Step 2. Install dependencies
```
$ cd election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000



