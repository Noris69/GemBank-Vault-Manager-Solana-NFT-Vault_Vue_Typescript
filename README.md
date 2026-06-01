# **GemBank Vault Manager – Solana NFT Vault Frontend**

**GemBank Vault Manager** is a **Vue 3 / TypeScript frontend application** for managing NFT vaults on the **Solana blockchain** using the **Gemworks Gem Bank SDK**.

The application allows two main user roles:

- **Bank Manager**: creates and manages a Gem Bank, handles whitelisting, and manages vaults.
- **Vault Owner**: connects to a bank, creates a personal vault, deposits NFTs, withdraws NFTs, and checks vault status.

---

## **Overview**

This project provides a simple interface for interacting with Gem Bank smart contracts on Solana.

Users can connect a wallet, create a bank, create vaults, and move NFTs between their wallet and vault. The frontend is built with **Vue 3**, **TypeScript**, **Vue Router**, **TailwindCSS**, and Solana/Web3 libraries.

---

## **Main Features**

- **Wallet connection**
- **Create and manage a Gem Bank**
- **Create a personal NFT vault**
- **Deposit NFTs into a vault**
- **Withdraw NFTs from a vault**
- **View wallet NFTs**
- **View vault NFTs**
- **Check if a vault is locked**
- **Manage whitelist**
- **Solana Web3 integration**
- **Gemworks Gem Bank SDK integration**

---

## **Tech Stack**

- **Vue 3**
- **TypeScript**
- **Vue Router**
- **TailwindCSS**
- **Solana Web3.js**
- **Gemworks Gem Farm / Gem Bank SDK**
- **Anchor**
- **Metaplex**
- **Axios**
- **Yarn / npm**

---

## **Project Structure**

```text
Vault_Back/
│
└── app/
    └── gem-bank/
        ├── src/
        │   ├── common/
        │   ├── components/
        │   ├── composables/
        │   ├── router/
        │   ├── views/
        │   │   ├── Home.vue
        │   │   ├── BankManager.vue
        │   │   └── VaultOwner.vue
        │   ├── App.vue
        │   └── main.ts
        │
        ├── package.json
        └── README.md
