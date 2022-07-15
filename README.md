## Full stack NFT Marketplace built with Polygon, Solidity, IPFS, & Next.js

![NFT Marketplace](https://i.ibb.co/K2FjvH3/Home.png)

This is a code repository for the corresponding video tutorial.

Using Web 3.0 methodologies, Solidity and Metamask real Web 3.0 Application.

## Configs:

First create .secret and pest metamask first accounts private key for testing
Market deployed to:

```
0x5FbDB2315678afecb367f032d93F642f64180aa3
```

## commands:

Step 1: Run hardhat node

```bash
npx hardhat node
```

Step 2: Deploy smart contract

```bash
npx hardhat run scripts/deploy.js --network localhost
```

Step 3: Run server for frontend

```bash
npm run dev
```
