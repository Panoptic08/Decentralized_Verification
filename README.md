# NFT Minting DApp for Aptos

This NFT minting dApp provides a complete solution for creating, managing, and minting NFTs on the Aptos blockchain. With a sleek UI and robust backend, users can mint and manage their NFTs efficiently, while developers can easily extend the app's functionality.

## Features
- **Public Mint NFT Page**: A dedicated page where users can mint NFTs directly.
- **Create Collection Page**: Allows developers to create new NFT collections during development (not accessible in production).
- **My Collections Page**: Displays all collections created under the current Move module, with details of each collection.

## Tools & Technologies
- **React Framework**: Fast and responsive frontend built using React.
- **Vite**: Utilized for efficient development with quick build times.
- **shadcn/ui + Tailwind**: Provides modern, responsive, and customizable styling.
- **Aptos TS SDK**: For seamless interaction with the Aptos blockchain.
- **Aptos Wallet Adapter**: Allows users to connect their wallets and interact with the blockchain.
- **Node-based Move Commands**: To handle Move contract publishing, compilation, and upgrades directly in the Node environment.

## Available Move Commands

The app utilizes the [Aptos CLI npm package](https://github.com/aptos-labs/aptos-cli), allowing the following Move commands via npm scripts:

- `npm run move:publish` - Publish the Move contract.
- `npm run move:test` - Run Move unit tests.
- `npm run move:compile` - Compile the Move contract.
- `npm run move:upgrade` - Upgrade the Move contract.
- `npm run dev` - Run the frontend locally.
- `npm run deploy` - Deploy the dApp to Vercel.

For a full list of available CLI commands, run `npx aptos`.

## Prerequisites

To get started, ensure you have the following installed:

- **Node.js & npm**: For managing dependencies and running scripts.
- **Vite**: For local development.
- **Aptos Wallet**: Connect using a supported wallet (e.g., Martian, Pontem).
- **Blockchain Node Access**: Access the Aptos testnet or mainnet.

## Blockchain Integration

The app is integrated with the Aptos blockchain, leveraging the Move programming language for secure, efficient on-chain operations. The smart contract ensures the transparency and immutability of NFT transactions.

- **Contract Address**: `0x08465edc0724ba5a7e1a2ba9dc4b492672a331f76aaa19d48c0ae78bbd0221db`
- [View Contract on Explorer](https://explorer.aptoslabs.com/txn/0x08465edc0724ba5a7e1a2ba9dc4b492672a331f76aaa19d48c0ae78bbd0221db?network=devnet)
