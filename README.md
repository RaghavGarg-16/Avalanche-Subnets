# Avalanche-Subnets
## Table of Contents
- Prerequisites
- Project Steps
- Smart Contracts
- Usage
- Author
- License
## Prerequisites
Before you begin, ensure you have the following tools and resources:

Unix computer (MacOS or Linux) or WSL installed on Windows
Remix online IDE
Metamask wallet extension
Web browser
Project Steps
Set up your EVM subnet: To create a custom EVM subnet on the Avalanche network, follow the instructions provided in the guide and refer to the Avalanche documentation. This will allow you to deploy your smart contracts with low fees and create a custom token.

Define your native currency: Create your own native currency to serve as the in-game currency for your DeFi Kingdom clone. This currency will be used for transactions, rewards, and various in-game activities.

Connect to Metamask: To connect your EVM Subnet to Metamask, follow the instructions in the provided guide. Make sure to select your custom EVM subnet as the network in Metamask.

Deploy basic building blocks: To deploy foundational smart contracts for your game, you can leverage Solidity and Remix. These contracts will define activities such as battling, exploring, and trading. You can find example contracts in the provided guide.

ERC20 Token Contract
Vault Contract
Test your application: You can use Remix to interact with your deployed smart contracts for your DeFi Kingdom clone. With Remix, you can deploy tokens, liquidity pools, and other important components of your game. You can also test functionalities like battling, exploring, and trading within your game.

Smart Contracts
ERC20 Token Contract: The contract is an implementation of a standard ERC20 token. It includes features such as transfers, allowances, minting, and burning. Players can utilize this token as an in-game currency.

ERC20.sol
Vault Contract: The Vault contract allows users to deposit and withdraw tokens while keeping track of the total supply and individual balances. It is used to manage liquidity within the game.

Vault.sol
Usage
To start your DeFi Kingdom adventure, follow these steps:

Set up your EVM subnet using the provided guide and Avalanche documentation.

Define your native currency within the game.

Connect your EVM Subnet to Metamask as outlined in the guide.

Deploy the foundational smart contracts using Remix.

Test your DeFi Kingdom clone by interacting with the deployed smart contracts through Remix.

Author
Raghav Garg

License
This project is licensed under the MIT License.
