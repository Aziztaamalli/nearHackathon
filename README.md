# Graviola
## About
Graviola's initiative employs blockchain, AI, and randomness to autonomously produce NFTs using user-supplied and on-chain stored keywords. It processes these keywords into AI-generated portraits through Stable Diffusion, then catalogs these unique NFTs with associated rarity and other metadata attributes on the blockchain.

## App Setup
1. generate types for the frontend
    1. `cd contracts && yarn`
    2. `yarn hardhat compile`
2. run website
    1.yarn add vite-plugin-node-polyfills
    2. `cd ../frontend && yarn`
    3. `yarn dev`
