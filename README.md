
# DeFi Empire: A Simple DeFi Kingdom Clone on Avalanche

### Project Overview
This project is a DeFi gaming application that recreates a simplified version of **DeFi Kingdoms** on the Avalanche blockchain. Built as part of the **Metacrafters Avalanche Subnet Course**, this clone utilizes an **EVM Subnet** on Avalanche, allowing players to engage in a digital economy with game activities like collecting assets, battling, exploring, and trading, all while earning rewards in native game tokens.

The project leverages custom tokens and smart contracts to simulate a blockchain-based world where players can interact with a decentralized finance (DeFi) environment, giving them an opportunity to explore the fundamentals of DeFi and custom subnets.

---

### Table of Contents
- [Project Features](#project-features)
- [Tech Stack](#tech-stack)
- [Setup Guide](#setup-guide)
- [Deployment Guide](#deployment-guide)
- [Project Submission Requirements](#project-submission-requirements)
- [Assessment Rubric](#assessment-rubric)

---

### Project Features
- **Custom EVM Subnet**: A private EVM-compatible blockchain on Avalanche.
- **Token Contracts**: Creation and deployment of an ERC20 token.
- **Vault Contract**: A smart contract for depositing, minting, and managing token balances.
- **DeFi Game Mechanics**: Smart contracts simulate game activities like battling, exploring, and trading.
- **Metamask Integration**: Users connect via Metamask to interact with the blockchain.

---

### Tech Stack
- **Blockchain**: Avalanche (Fuji Testnet)
- **Smart Contracts**: Solidity
- **Development Tools**: Avalanche CLI, Remix IDE, Metamask, Web Browser
- **Token Standards**: ERC20

---

### Setup Guide
1. **Set Up EVM Subnet**  
   Use the Avalanche CLI and documentation to create a custom EVM Subnet on Avalanche.

2. **Define Native Currency**  
   Set up the native in-game currency to serve as the primary medium for rewards and transactions.

3. **Connect to Metamask**  
   - Add your EVM Subnet to Metamask as a custom network.
   - Select this network to perform test transactions.

4. **Deploy Smart Contracts**  
   - **ERC20 Token Contract**: Create a simple token that players can earn and trade.
   - **Vault Contract**: Implement a Vault contract to manage deposits and withdrawals.

---

### Deployment Guide
1. **Subnet Deployment**  
   - Deploy your EVM subnet using the Avalanche CLI.
   - Link your Metamask to the subnet for test transactions.

2. **Contract Deployment**  
   - In **Remix**, deploy the ERC20 token and Vault contracts.
   - Interact with these contracts to simulate basic game mechanics.

3. **Testing**  
   Use Remix to test the functionality of each contract. Create tokens, deposit into the vault, and test withdrawals to simulate game actions.
