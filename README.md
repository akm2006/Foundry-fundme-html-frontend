# FundMe dApp Frontend

This repository contains the **HTML**, **CSS**, and **JavaScript** frontend for a decentralized crowdfunding (**FundMe**) application. It provides a clean, user-friendly interface to interact with the **FundMe Smart Contract**, which is deployed on the **Sepolia testnet**.

This project demonstrates how to connect a simple web interface to a live smart contract on the Ethereum blockchain using **Ethers.js**, allowing users to connect their **MetaMask** wallet and interact with the contract's functions.

---

## ✨ Features

- **Connect Wallet**: Securely connect to the user's MetaMask wallet.  
- **Fund Contract**: Send ETH to the smart contract with a specified amount.  
- **Get Contract Balance**: View the total amount of ETH held by the contract.  
- **Withdraw Funds**: Allow the contract owner to withdraw the entire balance.  
- **Modern UI**: A clean, responsive, and dark-themed interface for easy interaction.  

---

## 🛠️ Tech Stack

- **HTML5**: For the structure of the web page.  
- **CSS3**: For modern styling and a responsive, dark-mode design.  
- **JavaScript (ES6+)**: For the application logic and DOM manipulation.  
- **Ethers.js**: A complete and compact library for interacting with the Ethereum Blockchain and its ecosystem.  

---

## 🏁 Getting Started

To get a local copy of the frontend up and running, follow these steps.

### Prerequisites

- A modern web browser (like Chrome, Firefox, or Brave)
- The **MetaMask** browser extension installed and configured for the **Sepolia Testnet**
- A code editor like **Visual Studio Code**
- The **Live Server** extension for VS Code is highly recommended for running the project locally

---

### Installation & Setup

Clone the repository:

```bash
git clone https://github.com/akm2006/Foundry-fundme-html-frontend.git
cd Foundry-fundme-html-frontend
````

---

### Review the Configuration

The smart contract configuration is located in the `index.js` file. By default, it is configured to interact with the deployed contract at:

```
0x6A4737FDa9c0c48d3666B94166c13669fe41Ae87
```

```javascript
const contractAddress = "0x6A4737FDa9c0c48d3666B94166c13669fe41Ae87";
const contractABI = [ /* ABI array */ ];
```

> If you deploy your own version of the smart contract, you will need to update the `contractAddress` and `contractABI` in `index.js`.

---

### Running the Application

1. Open the project in **VS Code**
2. Right-click the `index.html` file
3. Select **"Open with Live Server"**
4. Your browser will open a new tab with the application running
5. Connect your **MetaMask** wallet when prompted and ensure you are on the **Sepolia network** to interact with the contract

---

## 🔗 Backend Smart Contract

This frontend is designed to work with the **Foundry-FundMe** smart contract.
For details on the backend logic, testing, and deployment, please visit the smart contract repository:

➡️ [https://github.com/akm2006/Foundry-FundMe](https://github.com/akm2006/Foundry-FundMe)

```
```
