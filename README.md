# Tenge NFTKastle

Tenge NFTKastle is an NFT marketplace where users can mint their pictures as NFTs, list their NFTs for sale, and buy NFTs from other users. NFTKastle has other addition features which includes

- Stake your NFTs and earn rewards.
- Draw and mint the drawing as NFT.
- Editor to edit your pictures and use it as NFT on Hashnode, twitter, Youtube and other social media platform.
- Compete in a bounty by Playing game to win NFT.

# 🛠 Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (NextJs & Testing)
- Ethers (Blockchain Interaction)
- hardhat (Development Framework)
- Sanity (Database)
- IPFS (File hosting)

# ⛓ Blockchain Protocol used

- ERC-721 standard

# ⚙ Requirements For Initial Setup

- Install NodeJS, should work with any node version below 16.5.0
- Install Hardhat, In your terminal, you can check to see if you have Hardhat by running Hardhat version. To install Hardhat `npm i -D hardhat`. Ideal to have hardhat version 5.4 to avoid dependency issues.

# 🚀 Quick Start

📄 Clone or fork NFTKastle:

```
https://github.com/GETOfinance/tengenftkastle.git
```

💿 Install all dependencies:

```
$ cd NFTKastle
$ npm install
```

🔐 Add the required environment variables.

You can find all the required environment variables for the frontend in the `.env.local.Example` file

```
NEXT_PUBLIC_INFURA_IPFS_PROJECT_SECRET = // Infura IPFS Project secret
NEXT_PUBLIC_INFURA_IPFS_PROJECT_ID =  // Infura IPFS Project ID

```

And the required environment variables for the smart-contract in the `.env.Example` file

```
PrivateKey =  // Metamask PrivateKey
```

After adding the environment variables, Rename the file from `.env.local.Example` to `.env.local`

# 🚴‍♂️ Run the App:

```
npm run dev
```

# 🛠 test the smart-contract:

```
npx hardhat test
```

- Note :- This app was deploy to Open Campus Codex testnet, so you need to connect your wallet to Open Campus Codex testnet before you can Interact with the app.

# Contract address

```
0x5cA23Cd0D991257cA55AcCd8E749b138E77440eC
```

# ✔ Contract address on Open Campus Codex testnet

```
https://opencampus-codex.blockscout.com/address/0x5cA23Cd0D991257cA55AcCd8E749b138E77440eC
```
