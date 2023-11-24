# Flash Loan Finder App - on AAVE

Notes:
// USDC = 0x3355df6D4c9C3035724Fd0e3914dE96A5a83aaf4 // Zksync

## Technology Stack & Tools

- Javascript (Script)
- [Web3.js](https://web3js.readthedocs.io/en/v1.10.0/) (Blockchain Interaction)
- [Infura](https://www.infura.io) (Blockchain Connection)

## Requirements For Initial Setup

- Install [NodeJS](https://nodejs.org/en/). We recommend using the latest LTS (Long-Term-Support) version, and preferably installing NodeJS via [NVM](https://github.com/nvm-sh/nvm#intro).
- Create an [Infura](https://www.infura.io) account, you'll need to create an API key, and use the Ethereum https. Paste your API key in .env

## Setting Up

### 1. Clone/Download the Repository

### 2. Install dependencies

npm install

### 3. Configure Environment Variables

Enter you API key in .env file

- **INFURA_ID=** (Infura API Key)

### 4. Enter starting block number in index.js

"...
fromBlock: 18619505 <-- edit this value. Enter block value from which you want to start your searches
toBLock: "latest",
..."

### 5. Run the script

node index.js
