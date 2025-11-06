# 🏛️ Cyber-Law-Registry  

A **decentralized blockchain-based registry** ensuring transparent and tamper-proof documentation of cyber law records.  
This project demonstrates the application of **blockchain technology** in legal record-keeping, providing **security, transparency, and trust** among all stakeholders.

---

## 📜 Problem Statement

Traditional legal documentation systems suffer from:

- **Centralized control**, leading to data manipulation risks  
- **Opaque records** with no public verification  
- **Single points of failure**, risking total data loss  
- **Difficulty in ensuring authenticity** of digital documents  

To counter these limitations, a decentralized and immutable record-keeping solution is essential — one that offers transparency and verifiable proof of authenticity for cyber laws and legal data.

---

## 💡 Solution Overview

The **Cyber-Law-Registry** leverages **blockchain technology** to ensure:

- **Immutability:** Once submitted, records cannot be altered or deleted.  
- **Transparency:** Every transaction is publicly verifiable on Etherscan.  
- **Security:** Cryptographically protected record storage.  
- **Decentralization:** No central authority can modify or censor laws.  
- **Ease of Access:** Simple web interface for law submission and retrieval.  

Each law is recorded on the **Ethereum Sepolia Testnet** via a **Solidity Smart Contract**, with interaction handled by **Web3.js** and **MetaMask** for wallet connectivity.

---

## 🧠 Features

✅ Blockchain-based law submission and storage  
✅ Immutable and verifiable record history  
✅ Transparent contract transactions on Etherscan  
✅ Integration with MetaMask for wallet connection  
✅ Frontend interface for adding and viewing laws  
✅ Easy contract verification on the Ethereum test network  

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Blockchain Network** | Ethereum (Sepolia Testnet) |
| **Smart Contract Language** | Solidity |
| **Development IDE** | Remix IDE |
| **Frontend** | HTML, CSS, JavaScript |
| **Blockchain Interface** | Web3.js |
| **Wallet Integration** | MetaMask |
| **Deployment** | Localhost via CMD |
| **Verification Tool** | Etherscan |

---

## ⚙️ Steps to Reproduce

Follow these steps to **set up, deploy, and interact** with the Cyber-Law-Registry:

---

### 1️⃣ Clone the Repository

    git clone https://github.com/<your-username>/Cyber-Law-Registry.git
    cd Cyber-Law-Registry


## 2️⃣ Deploy the Smart Contract

Open Remix IDE.

Create a new Solidity file (e.g., CyberLawRegistry.sol).

Paste the contract code (see below).

Connect MetaMask to the Sepolia Test Network.

Compile and deploy the contract.

Copy the contract address generated after deployment.

📄 **Etherscan Transaction Details:**
Visit [Etherscan Sepolia](https://sepolia.etherscan.io)
to view your deployed contract and transactions.

---

## 3️⃣ Connect MetaMask

Open MetaMask in your browser.

Ensure it is connected to the Sepolia Test Network.

Get test ETH from a Sepolia Faucet for transactions.

Unlock the wallet and keep it connected while using the site.

---

## 4️⃣ Host Frontend Locally

Use your terminal to serve the HTML file:

    cd path/to/project
    npx http-server

or simply double-click `index.html` to open it in a browser.

---

## 5️⃣ Interact with Frontend

### a) Main Webpage

### b) Connect the Wallet

Click **"Connect Wallet"**

MetaMask popup will appear

Once connected, the wallet address will display on the screen

### c) Submit a Law

Click **"Submit Law to Blockchain"**

Enter your law details in the input box

Confirm the MetaMask transaction

Wait for it to be mined on Sepolia network

📄 **Etherscan Transaction Details:**
Each submission creates a verified blockchain transaction viewable on Etherscan.

### d) Refresh Laws

Click **"Refresh Laws"** to fetch all stored laws.

Newly added entries will appear in the list.

### e) New Law Added

The new record is displayed instantly after confirmation.

---

## 🧾 Final Result

🎉 Successfully deployed **Cyber-Law-Registry** smart contract and connected it with a working web interface.  
Users can:

- Submit laws  
- View immutable records  
- Verify entries on Etherscan  
- Interact seamlessly through MetaMask  

---

## ✅ Verify & Publish Contract Source Code

You can verify and publish your contract manually:

🔗 **Etherscan:** [https://sepolia.etherscan.io](https://sepolia.etherscan.io)

📬 **Contract Address:** `0x0c940Ea07fC023E9cFe38D6C3A6d2b62000295d5`

---

## 📷 Project Preview

<img width="647" height="635" alt="image" src="https://github.com/user-attachments/assets/c0d78e7d-460b-4444-a34d-09965311f864" />

---

## 🔮 Future Enhancements

- Integrate **IPFS** for large document storage  
- Add **Admin Role** for law verification  
- Enable **user authentication** using wallet signatures  
- Deploy on **Ethereum Mainnet** for production use  

---

## 👩‍💻 Author

Developed by: **Muskan Ahmed**

---

## 🧩 License

This project is licensed under the **MIT License**; therefore, you are free to use, modify, and distribute it.
