# Degen-Token-ERC-20-
# Overview
Token(1) is an ERC20-compliant token deployed on the Avalanche network. This smart contract includes functionalities for minting, burning, transferring tokens, and redeeming items. 
# Description
This smart contract implements a custom ERC20 token with the following features:

Minting Tokens: The contract owner can mint new tokens to any specified address.
Burning Tokens: Any user can burn their own tokens.
Transferring Tokens: Standard ERC20 token transfer functionality.
Redeeming Items: Users can redeem items by burning a specified amount of tokens, which is logged with an event.

# Getting Started
Prerequisites
Remix IDE: An online IDE for Solidity development.
MetaMask: A browser extension wallet for Ethereum and compatible networks.
Avalanche Network: Ensure you have AVAX in your wallet to cover gas fees.
Deployment Steps
Open Remix IDE:

Go to Remix IDE.
Connect MetaMask:

Connect your MetaMask wallet to Remix and switch to the Avalanche network (Mainnet or Fuji Testnet).
Load the Contract:

Copy the Token(1) contract code into a new file in Remix (e.g., MyToken.sol).
Compile the Contract:

Ensure you have the correct Solidity compiler version (^0.8.0) selected.
Compile the contract.
Deploy the Contract:

In the "Deploy & run transactions" tab, select your MyToken contract.
Enter the constructor parameters (name and symbol for your token).
Click "Deploy" and confirm the transaction in MetaMask.

# Authors
Shikha Jumta jumtashikha000@gmail.com

# License
This project is licensed under the MIT License - see the LICENSE file for details
