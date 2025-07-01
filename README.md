# 💸 Fund Me App

Welcome to **Fund Me App**, a simple decentralized application (dApp) that allows users to connect their Ethereum wallet, fund a smart contract, check the balance, and withdraw ETH. Built with HTML, CSS, and JavaScript and powered by a smart contract.

---

## 🚀 Features

- Connect Ethereum wallet via MetaMask
- Fund the contract with ETH
- Check contract balance
- Withdraw funds (by contract owner)
- Clean UI with stylish layout
- Welcome message with personalized touch ✨

---

## 🧑‍💻 Author

Hello, I'm **Proffgodswill** 👋  
Glad to have you here! This dApp is part of my Web3 learning journey. Feedback and contributions are welcome.

---

## 🛠️ Technologies Used

- **HTML5** – Page structure
- **CSS3** – Gradient styling and responsive design (in `index.css`)
- **JavaScript (ES6 Modules)** – Web3 interaction
- **MetaMask** – Wallet connection
- **Hardhat (assumed)** – For local Ethereum blockchain
- **Solidity Smart Contract** – Deployed at:  
  `0x5FbDB2315678afecb367f032d93F642f64180aa3`

---

## 📂 Project Structure

.
├── index.html # Main UI
├── index.js # Web3 interactions
├── index.css # Styling
├── README.md # Project overview

markdown
Copy
Edit

---

## 📜 Smart Contract Overview

The contract includes:

- `fund()` – Payable function to fund the contract
- `withdraw()` and `cheaperWithdraw()` – To withdraw funds (owner only)
- `getFunder(index)` – Get a funder's address by index
- `getAddressToAmountFunded(address)` – Get the amount a user has funded
- `getOwner()` – View the contract owner's address
- `getPriceFeed()` – Returns the price feed address
- `getVersion()` – Returns the price feed version
- `MINIMUM_USD` – View the required minimum USD equivalent for funding

---

## ⚙️ Getting Started

### Prerequisites

- Node.js & npm
- MetaMask extension
- Hardhat (for local blockchain testing)

### Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/Blocklesschain/html-fund-me-cu.git
   cd html-fund-me-cu
Install dependencies
(If using a smart contract testing environment)

bash
Copy
Edit
npm install
Start a local server (optional)
You can use VSCode Live Server or:

bash
Copy
Edit
npx serve .
Connect MetaMask to the same network the contract is deployed on (e.g., Hardhat local chain or testnet).

📸 UI Overview
Gradient background with a clean welcome section

Buttons for wallet connection, funding, withdrawing, and balance check

Input field to specify ETH amount

📬 Feedback
Found a bug or want to suggest a feature? Open an issue or a pull request. Contributions are always welcome!

📄 License
MIT License. Free to use and modify.

Made with ❤️ by Proffgodswill
