# Mint Your Own NFT Collection

### **Welcome 👋**
You can runt his program using: 

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project
3. Start coding!

# Mint-NFTs
For this website to talk to blockchain, we need to somehow connect our wallet to it. On website, you have a Connect Wallet button to connect your Wallet (MetaMask) to it.

Our Contract code is on this repository: https://github.com/asfandyar-malik/Mint-NFTs-Contract 

We need to deploy the contract(Check Readme.md of linked project), connect our wallet, and call our contract from this web app using the credentials we have access to now from Metamask!


📂 ABI files
The ABI file is something our web app needs to know how to communicate with our contract. The contents of the ABI file can be found in a fancy JSON file in your hardhat contract project:
artifacts/contracts/MyEpicNFT.sol/MyEpicNFT.json

We have to copy the content from your MyEpicNFT.json and then add it to MyEpicNFT.json file which is located at src/utils/MyEpicNFT.json


# View-NFTs

After NFT is minted, you can visualize your NFTs on the Rarible or Opensea marketplace!!

The link for an NFT on Rarible looks like this:
https://rinkeby.rarible.com/token/0xb6be7bd567e737c878be478ae1ab33fcf6f716e0:0


# Frontend Visuals

![image](https://user-images.githubusercontent.com/4105873/147242723-323cf945-ba21-4ddb-aeb7-c7b6fbe049c3.png)



