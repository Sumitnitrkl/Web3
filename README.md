# 🌐 ChatSecure: Unleash Secure Blockchain Messaging 🛡️

Welcome to **ChatSecure**, the next-generation blockchain-powered messaging app that takes secure, decentralized communication to the next level. With support for over **261+ cryptocurrency wallets**, end-to-end encryption, and real-time messaging, ChatSecure ensures that your privacy is always protected.

## 📄 Project Overview

ChatSecure is a decentralized messaging platform that leverages the power of **blockchain technology** for secure, private, and tamper-proof communication. It allows users to authenticate using **crypto wallets** and supports **real-time messaging**, **encrypted media sharing**, and **smart contracts** to ensure a fully decentralized and secure experience.

## 🌟 Features

- **🔒 End-to-End Encryption (E2EE)**: Protects your messages with **AES-GCM** encryption for secure communication, ensuring only the intended recipient can read your messages.
- **🔑 RSA Encryption for Key Exchange**: Utilizes **RSA** for secure key exchanges, ensuring message encryption keys are safe and private.
- **🛡️ Decentralized Identity (DID)**: Authenticate securely using your cryptocurrency wallet — no usernames, passwords, or centralized logins.
- **📸 Encrypted Media Sharing**: Share photos, videos, and documents securely with end-to-end encryption.
- **🚀 Real-Time Messaging**: Enjoy fast, real-time chat powered by **Socket.io** and decentralized messaging protocols like **XMTP**.
- **🔗 Crypto Wallet Integration**: Seamless login with over **261+ wallets** including **MetaMask, WalletConnect, Coinbase Wallet**, and more.
- **📜 Smart Contracts**: Manage user interactions and transactions securely through smart contracts.
- **🔄 Cross-Chain Compatibility**: Built with flexibility in mind, ChatSecure can be extended to multiple blockchains like **Ethereum**, **Binance Smart Chain**, **Polygon**, and more.

## 🛠️ Technology Stack

- **Frontend**: React, TypeScript, SCSS
- **Blockchain Integration**: XMTP (Decentralized Messaging), Web3.js, Dynamic (Wallet Authentication)
- **Encryption**: AES-GCM (for message/media encryption), RSA (for key exchange)
- **Smart Contracts**: Solidity (for managing user interactions on-chain)
- **Real-time Communication**: Socket.io
- **UI/UX**: Tailwind CSS for responsive and modern design

## 🔐 Security Features

- **256-bit AES-GCM Encryption**: Provides the highest level of security for messages and media.
- **RSA Encryption for Key Exchange**: Ensures that message encryption keys are exchanged securely between users.
- **Decentralized Architecture**: No centralized server stores your data. Messages are distributed across blockchain nodes for maximum resilience.
- **Immutable Message Integrity**: Blockchain immutability guarantees that once messages are sent, they cannot be altered or deleted.

## 🚀 APIs and Libraries Used

- **XMTP**: A decentralized protocol for real-time messaging across blockchain nodes. 
  - [XMTP API](https://xmtp.org/)
  
- **Web3.js**: A library that allows the app to interact with the Ethereum blockchain, manage wallets, and execute smart contracts.
  - [Web3.js API](https://web3js.readthedocs.io/)

- **Dynamic**: Handles wallet-based authentication, supporting over **261+ wallets**.
  - [Dynamic API](https://dynamic.xyz/)

- **Socket.io**: Enables real-time messaging between clients and servers.
  - [Socket.io API](https://socket.io/docs/)

## 📁 Example .env File

Here’s an example of the `.env` file to configure your local environment:

```bash
# Blockchain Config
REACT_APP_XMTP_API_KEY=your_xmtp_api_key
REACT_APP_WALLET_PROVIDER=https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID

# Wallet Authentication (Dynamic)
REACT_APP_DYNAMIC_CLIENT_ID=your_dynamic_client_id
REACT_APP_DYNAMIC_SECRET_KEY=your_dynamic_secret_key

# Encryption Keys (RSA & AES)
REACT_APP_RSA_PUBLIC_KEY=your_rsa_public_key
REACT_APP_AES_SECRET_KEY=your_aes_secret_key
```

Ensure you replace the placeholders with actual values for your project setup.

## 📦 Installation & Setup

### Prerequisites

- Node.js (>= 14.x)
- Yarn or npm
- A cryptocurrency wallet (e.g., MetaMask)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Sumitnitrkl/crypto-messenger.git
   cd crypto-messenger
   ```

2. **Install dependencies**:

   ```bash
   yarn install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory based on the example above.
   - Add your **API keys**, wallet provider information, and encryption configurations.

4. **Run the development server**:

   ```bash
   yarn start
   ```

   Your app should now be running on `http://localhost:3000`.

## 🔮 Future Enhancements

- **Quantum-Resistant Encryption**: Explore post-quantum cryptographic algorithms for future-proofing security.
- **Cross-Chain Wallet Support**: Add support for blockchains beyond Ethereum, like **Solana**, **Binance Smart Chain**, and **Polygon**.
- **Mobile Apps**: Build native iOS and Android apps for secure decentralized messaging on mobile.
- **Smart Contract Payments**: Introduce a payment system where users can send cryptocurrency through smart contracts during chats.

## 🤝 Contributions

We welcome all contributions! If you have ideas, feature requests, or bug fixes, feel free to fork this repo and submit a pull request. Make sure to follow the project’s contribution guidelines.

---

Developed by **Sumit Kumar** (NIT Rourkela) as part of a Web3 decentralized chat project. For more information, visit [Sumit's GitHub](https://github.com/Sumitnitrkl).

