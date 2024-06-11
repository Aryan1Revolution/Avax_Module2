Calculator DApp: The Wizard's Calculator
Welcome to Magical Calculator Dapp

Prerequisites
Node.js and npm (Node Package Manager)
MetaMask browser extension installed
Ganache (for local blockchain development)

Deployment Steps
1. Install Truffle and Ganache
Ensure you have Truffle and Ganache installed globally:
npm install -g truffle ganache-cli

3. Initialize Your Project
Create a new directory for your DApp and initialize it with Truffle:
mkdir Aryan_Dapp
cd Aryan_Dapp
truffle init

3. Write Your Smart Contract
Create a Solidity file named Calculator.sol under the contracts directory.

4. Compile Your Smart Contract
Compile your contract to generate the ABI (Application Binary Interface) file:
truffle compile

6. Start Ganache
Launch Ganache and select the Quickstart option to set up a local blockchain.

7. Deploy Your Contract
Deploy your contract to the local blockchain:
truffle migrate --network development
Paste the contract address into the app.js file.

7. Create the Frontend
Initialize your project and install Lite Server for the frontend:
npm init -y
npm install lite-server --save-dev

8. Start the Development Server
Launch the development server:
npm start

Now, behold the magic of the Wizard's Calculator as you interact with your contract through the frontend!

