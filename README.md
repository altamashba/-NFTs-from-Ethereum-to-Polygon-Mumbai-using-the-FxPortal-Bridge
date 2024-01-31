# NFTs-from-Ethereum-to-Polygon-Mumbai-using-the-FxPortal-Bridge

This guide outlines the steps to deploy an NFT collection on the Ethereum blockchain, map the collection to the Polygon network, and transfer assets via the Polygon Bridge.

## Project Overview

- Generate a 5-item collection using DALLE 2 or Midjourney.
- Store items on IPFS using pinata.cloud.
- Deploy an ERC721 or ERC1155 contract to the Goerli Ethereum Testnet.
- Implement a `promptDescription` function on the contract to return the prompt used to generate the images.
- Map the NFT collection using the Polygon network token mapper.
- Write a Hardhat script to batch mint all NFTs.
- Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.
- Approve the NFTs to be transferred.
- Deposit the NFTs to the Bridge.
- Test `balanceOf` on Mumbai.

## Step-by-Step Deployment Guide

### 1. Image Generation and IPFS Storage

- Generate a 5-item collection using DALLE 2 or Midjourney.
- Upload the items to IPFS using pinata.cloud.

### 2. Smart Contract Deployment

- Develop and deploy an ERC721 or ERC1155 contract to the Goerli Ethereum Testnet.
- Implement a `promptDescription` function on the contract to return the prompt used to generate the images.

### 3. Mapping NFT Collection to Polygon Network

- Map the NFT collection using the Polygon network token mapper.

### 4. Hardhat Scripts

- Write a Hardhat script to batch mint all NFTs.
- Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.

### 5. Bridge Transfer

- Approve the NFTs to be transferred.
- Deposit the NFTs to the Bridge.

### 6. Testing and Verification

- Test `balanceOf` on Mumbai to ensure successful transfer.

## Readme Instructions

1. **Project Overview**: Provide a brief overview of the project and its objectives.
2. **Deployment Guide**: Detail the step-by-step process for deploying the NFT collection, mapping to the Polygon network, and transferring assets via the Polygon Bridge.
3. **Dependencies**: List any required dependencies, including tools like Hardhat, IPFS, pinata.cloud, and relevant APIs.
4. **Scripts**: Include the Hardhat scripts for batch minting and transferring NFTs.
5. **Contract Information**: Provide information about the deployed smart contract, including its address and functions.
6. **Testing**: Explain how to test the functionality of the deployed NFTs on the Polygon Mumbai network.
7. **Contact Information**: Include contact details for support or inquiries.
8. **License**: Specify the license under which the project is released.

## Conclusion

Follow this guide to deploy your NFT collection on Ethereum and Polygon, enabling seamless asset transfer and maximizing market reach while reducing gas costs.

For any questions or assistance, feel free to contact us.
