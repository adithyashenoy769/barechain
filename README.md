# Blockchain Implementation

A functional blockchain system that supports **wallet creation**, **secure transactions**, and **digital signatures** using **Elliptic-Curve Cryptography (ECC)**. This project demonstrates core blockchain concepts like transaction validation, UTXO management, and Merkle Trees.

---

## Features
- **Wallet Creation**: Users can create wallets with public/private key pairs using ECC.
- **Secure Transactions**: Transactions are signed with digital signatures to ensure authenticity and prevent tampering.
- **UTXO Management**: Tracks unspent transaction outputs (UTXOs) to validate and process transactions.
- **Merkle Trees**: Efficiently verifies transaction integrity using Merkle roots.
- **User-Friendly API**: Provides simple methods for creating wallets and sending funds, e.g., `walletA.sendFunds(walletB.publicKey, 20)`.

---

## How It Works
1. **Wallets**: Users create wallets with `new Wallet();`, generating public/private key pairs using ECC.
2. **Transactions**: Transactions are signed with the sender's private key and verified using their public key.
3. **UTXOs**: Unspent transaction outputs are tracked to ensure funds are valid and not double-spent.
4. **Blocks**: Transactions are grouped into blocks, which are mined and added to the blockchain.
5. **Merkle Trees**: Each block includes a Merkle root to verify the integrity of its transactions.

---
