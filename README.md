# 🗳️ Decentralized Online Voting System

## 📝 Description
A blockchain-based online voting platform designed to ensure **transparency**, **security**, and **immutability** in the electoral process. This system removes the need for centralized authorities and prevents vote tampering or duplication by leveraging **Ethereum smart contracts**.

---

## 🚀 Features
- 🔐 Voter authentication with unique accounts
- ✅ One vote per user enforcement via smart contract logic
- 📊 Real-time vote counting on-chain
- 🛡️ Tamper-proof and secure architecture using blockchain
- 🧾 Admin interface for creating and managing elections

---

## 🛠️ Tech Stack

| Layer        | Tech Used                   |
|--------------|-----------------------------|
| Frontend     | HTML, CSS, JavaScript       |
| Blockchain   | Solidity (Smart Contracts)  |
| Blockchain Platform | Ethereum (via Ganache) |
| Interaction  | Web3.js                     |
| Testing/Deploy | Truffle Suite              |

---

## 📦 Installation & Setup

> ⚠️ Prerequisites:  
> - [Node.js & npm](https://nodejs.org/)  
> - [Ganache](https://trufflesuite.com/ganache/)  
> - [MetaMask](https://metamask.io/) browser extension  
> - [Truffle](https://trufflesuite.com/truffle/) (`npm install -g truffle`)

```bash
# Clone the repository
git clone https://github.com/Ashish-Rautela/Decentralized_Online_Voting_System.git
cd Decentralized_Online_Voting_System/Decentralized_Online_Voting_System-main

# Install dependencies (if applicable)
npm install

# Compile smart contracts
truffle compile

# Migrate contracts to local blockchain (Ganache must be running)
truffle migrate

# Open index.html in browser (ensure MetaMask is connected to Ganache)
