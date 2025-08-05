# IPFS Web3 Certifier

A decentralized certification system built with Solidity and IPFS (via web3.storage). This project allows trusted issuers to generate verifiable certificates whose metadata is stored on IPFS, and whose integrity is anchored on the Ethereum blockchain.

## 🚀 Features

- Issue certificates with off-chain metadata (JSON) stored on IPFS
- On-chain registry of certificate hashes (CIDs)
- Revoke issued certificates securely
- Public verification of certificate authenticity
- Role-based access control for trusted issuers
- Modular architecture – easy to expand with frontend or NFT minting

## 🛠️ Tech Stack

- **Solidity** — Smart contract logic (Hardhat)
- **web3.storage** — IPFS + Filecoin for decentralized metadata storage
- **TypeScript** — Scripts and tests
- **Hardhat** — Development & testing framework
