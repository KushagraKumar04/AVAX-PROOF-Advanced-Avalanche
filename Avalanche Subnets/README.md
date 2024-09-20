# DeFi Kingdom Clone on Avalanche

This repository contains the Solidity smart contracts for an ERC20 token and a Vault contract, which form the foundation of a DeFi Kingdom clone on the Avalanche network. The project allows users to collect, build, and earn rewards through game participation.

## 📝 Project Overview

This project features two core components:

### 1. **ERC20 Token Contract**
   - A standard ERC20 token implementation with functionalities for minting, burning, transferring, and approving allowances.
   - Token name: `Solidity by Example`
   - Token symbol: `SOLBYEX`
   - Decimals: `18`

   **Key Functions:**
   - `transfer(address recipient, uint amount)`: Transfer tokens from the sender to a recipient.
   - `approve(address spender, uint amount)`: Approve another address to spend tokens on the sender's behalf.
   - `transferFrom(address sender, address recipient, uint amount)`: Transfer tokens on behalf of another address.
   - `mint(uint amount)`: Mint new tokens to the sender's address.
   - `burn(uint amount)`: Burn tokens from the sender's balance.

### 2. **Vault Contract**
   - The Vault allows users to deposit ERC20 tokens and withdraw them based on shares they own in the Vault.
   - It calculates shares to mint or burn based on the total supply of tokens and deposits/withdrawals.

   **Key Functions:**
   - `deposit(uint _amount)`: Deposits tokens and mints Vault shares.
   - `withdraw(uint _shares)`: Withdraws tokens based on the user's shares and burns the corresponding amount of shares.

## ⚒️ Tools Used
- **Unix Computer (MacOS or Linux)**
- **Solidity**
- **Remix IDE**
- **Metamask**
- **Web Browser**

## 🚀 Steps to Deploy

1. **Deploy your EVM Subnet**  
   Use the Avalanche CLI to deploy your custom EVM subnet.

2. **Add Subnet to Metamask**  
   After deploying the subnet, add it as a custom network in your Metamask wallet.

3. **Connect Remix to Metamask**  
   Ensure Metamask is your selected network, then use Remix's Injected Provider to interact with your network.

4. **Deploy the Smart Contracts**  
   Using Remix, deploy both the ERC20 token and the Vault contract.

5. **Test the Application**  
   Interact with the deployed contracts using Remix to test functionalities like minting tokens, depositing, withdrawing, and burning tokens.

## 🎮 Game Concept
This project is designed to be a part of a DeFi Kingdom-like game on Avalanche, where players can collect and manage tokens, build resources, and earn rewards for their participation.

---

Feel free to contribute, suggest improvements, or report issues!
