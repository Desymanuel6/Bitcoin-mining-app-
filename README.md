# My Bitcoin Wallet

A simple non-custodial Bitcoin wallet for generating addresses, viewing balances, and sending transactions on **Bitcoin Testnet**. 
Built for learning and experimentation. 

**⚠️ WARNING: Do not use with real Bitcoin/Mainnet funds. This code is not audited.**

## Features
- Generate BIP39 12-word seed phrase
- Derive BIP84 native SegWit addresses
- Check balance and transaction history
- Create and sign transactions
- Broadcast to Bitcoin Testnet

## Tech Stack
- **Language**: JavaScript / Node.js
- **Libraries**: 
    - `bitcoinjs-lib` – Bitcoin operations
    - `bip39` – Mnemonic generation
    - `tiny-secp256k1` – ECC cryptography
    - `axios` – API calls to blockchain explorer

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/your-username/my-bitcoin-wallet.git
cd my-bitcoin-wallet
```

### 2. Install dependencies
```bash
npm init -y
npm install bitcoinjs-lib bip39 ecc tiny-secp256k1
```
