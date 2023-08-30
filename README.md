
# Building with Polygon Bridge: NFTs on Polygon Network 🌉

## Project Overview

This project focuses on deploying an NFT collection on the Ethereum blockchain, mapping it to the Polygon network, and transferring assets via the Polygon Bridge. To add a unique touch, the images for the NFTs are generated using tools like DALLE 2 or Midjourney.

## Project Deep Dive and Starter Project

For those interested in using fxPortal, an example is provided that bridges ERC20 tokens to Polygon using a starter project.

## Tools Used

- Hardhat
- Foundry (optionally)

## Project Rubric

To successfully complete this project, you should:

1. Generate a 5-item NFT collection using DALLE 2 or Midjourney.
2. Store the generated items on IPFS using pinata.cloud.
3. Deploy an ERC721 or ERC1155 contract on the Goerli Ethereum Testnet.
4. Implement a `promptDescription` function in the contract that returns the prompt used for image generation.
5. Optionally, map your NFT collection using the Polygon network token mapper for better visualization.
6. Write a Hardhat script to batch mint all NFTs.
7. Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.
   - Approve the NFTs for transfer
   - Deposit the NFTs to the Bridge
   - Test `balanceOf` on Mumbai

## Video Walkthrough

[Watch the video walkthrough here](#) (Link to be added)

In the video, I will cover:
- The Polyproof project, a Metacraft initiative.
- Generating images from lexica.ai and storing them on pinata.cloud.
- Writing the smart contract and deploying it.
- Approving and depositing NFTs for transfer.
- Checking balances and performing tests.

## License

MIT License
