# ETH-AVAX---CreateandMintToken

## Description 
Instructions: For this project, you will write a smart contract to create your own token and deploy it using HardHat or Remix. Once deployed, you should be able to interact with it for your walk-through video. From your chosen tool, the contract owner should be able to mint tokens to a provided address and any user should be able to burn and transfer tokens.

This program is an ERC20-compliant smart contract that creates your own token on a local Hardhat network. To start, the Hardhat boilerplate project provided on the Hardhat website will serve as a solid foundation. Once the Hardhat project is set up, you can begin writing your smart contract. The contract should be Remix-compatible to ensure easy interaction. Being the contract owner, you will be able to mint tokens to a specified address, while any user can burn and transfer tokens to other addresses.


## Getting Started 

### Hardhat Boilerplate Repository
https://hardhat.org/tutorial/boilerplate-project

### Executing Program
1. In the terminal, run the following command: npm install
2. To install the remixd package, run the following command: npm install -g @remix-project/remixd
3. To start the remixd server and share a local directory with the Remix IDE, run the following command: remixd -s ./ --remix-ide https://remix.ethereum.org
4. On another terminal, install the OpenZeppelin Contracts library as a dependency by executing the following command: npm install @openzeppelin/contracts
5. To run the hardhat package, and start a local Ethereum development network, open another terminal and execute the following command: npx hardhat node
6. In Remix, switch the workspaces to -connect to localhost-
7. Compile and deploy the contract.
8. You should then be able to interact with the contract.

