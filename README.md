# Avalanche Subnet Creation and Smart Contract Deployment
This provides a step-by-step guide for creating an Avalanche Subnet and deploying Solidity smart contracts using Remix and MetaMask.
## Deploying and Interacting with Smart Contracts
### 1. Open Remix IDE
Access Remix at Remix IDE.
### 2. Set Up MetaMask with Subnet
In the Remix IDE, navigate to the "Deploy & Run Transactions" tab. Set the environment to "Injected Web3" and connect MetaMask to your Subnet by selecting your MetaMask account.
### 3. Compile and Deploy Contracts
Insert your Solidity code (e.g., ERC20, Vault contracts) into Remix. Compile the code and deploy the contracts to the Avalanche Subnet using MetaMask.
### 4. Interact with Deployed Contracts
After deployment, use the provided RPC URL and funded address to interact with your contracts.## Prerequisites
Ensure you have the following:
- MetaMask extension installed in your browser
- Avalanche-CLI installed on your local machine- Access to Remix IDE: Remix IDE
- Basic knowledge of Solidity and smart contract development
## Installation of Avalanche-CLI
Install Avalanche-CLI by running the following command in your terminal:

## Subnet Creation
### 1. Start Subnet Creation Wizard
To create a new Subnet, choose a name (e.g., `mySubnet`) and execute:

Follow the interactive prompts to configure your Subnet settings.
### 2. Deploy Subnet Locally
To deploy the Subnet locally, run:

When prompted, select the "Local Network" option.
### 3. Connect to the Subnet
Use the following information to connect to your Subnet:
- RPC URL: http://127.0.0.1:9650/ext/bc/2s6py1VRcHaFLFs2tmrLTAWrtmk5W2ALFkn8ukTqEfrqBPKrdW/rpc`- **Funded Address:** `0x8db97C7cEcE249c2b98bDC0226Cc4C2A57BF52FC (with 1,000,000 units)
- Network Name: mySubnet`- **Chain ID:** `2224
- Currency Symbol: ABHI  

## Conclusion
Submitted By Abhilash101, have successfully set up an Avalanche Subnet, deployed Solidity contracts, and interacted with them using Remix and MetaMask.
