Hardhat-Next.js Boilerplate
This boilerplate has everything you need to start building a modern Web3 project with a Next.js front end and a Hardhat smart contract backend.

Features
Hardhat development environment

Ethers.js v6 integration

Next.js front end with Bootstrap for styling

Sample smart contract and deployment scripts

Pre-configured testing and compilation scripts

Getting Started
Prerequisites
Node.js (v16+ recommended)

npm or yarn

MetaMask or another Web3 wallet for testing frontend interactions

Installation

git clone https://github.com/your-repo/hardhat-next-starter.git
cd hardhat-next-starter
Setup Backend (Smart Contracts)
cd blockchain
npm install
Setup Frontend (Next.js)
cd ../frontend
npm install
Running the Project
Open three terminal tabs/windows:

Start Hardhat local blockchain:


cd blockchain
npx hardhat node
Deploy smart contracts to local Hardhat node:


npx hardhat run scripts/deploy.js --network localhost

Run the Next.js frontend app:
cd ../frontend
npm run dev
