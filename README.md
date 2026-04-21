# 🐾 DATS — Decentralized Asset Tracking System

A blockchain-based decentralized application (dApp) built using **Ethereum, Solidity, Web3.js, and MetaMask** that enables secure and transparent asset tracking and ownership transfer.

This project demonstrates a complete Web3 workflow where assets (e.g., pets or items) are registered on the blockchain, ownership is tracked immutably, and users interact through a modern web interface.

---

## 🚀 Features

- 🔐 **MetaMask Wallet Integration**
  - Secure user authentication using Ethereum wallets

- 🧾 **Asset Registration**
  - Admin can register new assets on the blockchain

- 🔄 **Ownership Transfer**
  - Secure transfer of assets between wallet addresses

- 📋 **Asset Tracking**
  - View all registered assets stored on-chain

- 🔍 **Search Functionality**
  - Search assets by owner address

- 📡 **Real-time Blockchain Events**
  - Live updates using smart contract event listeners

- 🎨 **Modern UI**
  - Clean and responsive dashboard interface

---

## 🏗️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Blockchain:** Ethereum
- **Smart Contracts:** Solidity
- **Web3 Integration:** Web3.js
- **Wallet:** MetaMask
- **Development Tools:** Truffle / Hardhat (optional)

---

## 📦 Smart Contract Functions

- `addPet(name, species)` → Register new asset (admin only)
- `transferPetOwnership(petId, newOwner)` → Transfer ownership
- `getPet(petId)` → Retrieve asset details
- `getAllPets()` → Get all registered assets
- `getPetsByOwner(address)` → Get assets owned by a specific user
- `petCount()` → Total number of assets
- `contractOwner()` → Owner of the smart contract

---

## ⚙️ How It Works

1. Connect MetaMask wallet to the application  
2. Admin registers assets on the blockchain  
3. Users can view and search assets  
4. Ownership can be transferred securely via smart contract  
5. All actions are recorded immutably on Ethereum blockchain  

---

## 📡 Event System

The application listens to smart contract events such as:

- `PetAdded` → Triggered when a new asset is registered  
- `OwnershipTransferred` → Triggered when ownership changes  

These events enable real-time UI updates.

---

## 📸 Project UI

> A modern blockchain dashboard with wallet connection, asset registry, transfer system, and live logs.

---

## 🔐 Security Concept

- Blockchain ensures **immutability of asset records**
- MetaMask ensures **secure user authentication**
- Smart contracts ensure **trustless execution**

---

## 📚 Use Case

This project can be extended for:
- Pet adoption systems 🐶
- Supply chain tracking 📦
- Digital asset management 🪙
- NFT-based ownership systems 🎨

---

## 👨‍💻 Author

Developed as a **Blockchain / Web3 academic project** showcasing decentralized application development using Ethereum.

---

## ⭐ Future Improvements

- IPFS integration for decentralized storage
- Role-based access control in smart contracts
- Deployment on Ethereum testnet (Sepolia)
- Gas optimization improvements
- Backend indexing using The Graph

---

## 📜 License

This project is for educational purposes.
