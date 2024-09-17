# Advanced-Avalanche-Subnets
This is a simple "Avalanche Subnets" project that is required for the completion of ETH PROOF: Advanced EVM Course. The purpose of this program is to serve as a starting point for those who are interested and curious about creating and utilizing avalanche subnets.
## Description
This program is written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract is built with a constructor, two file imports, and two functions that shows how the program mint or burn tokens. This program serves as an introduction to learn the basic understanding about Creating and Minting Tokens

This program is written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain.
There are two solidity files needed to continue with this project, ERC20.sol and Vault.sol.
## Getting Started
### Installing
### Executing Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create two new files by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file: https://github.com/MichaelJaaa/Metacrafters_Project_EVMSubnet

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "^0.8.17" (or another compatible version), 

Compile both files so click on the "Compile ERC20.sol", and "Compile Vault.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Once the contract ERC20 is deployed, copy the given address below the "Deployed/Unpinned Contracts", then proceed to Vault.sol and paste it beside the "At address" button.

There should be two deployed contracts which are the ERC20 and IERC20 contracts. Click the drop down button of both contracts.

Minting Token:
Provide a value beside the "mint" button then click the "mint" button. Confirm the transaction via Metamask.
To check if the transaction succeeded, click the "totalSupply" button of both contracts, the displayed values should increase from the past value and the updated values should be equal.

Burning Token:
Provide a value beside the "burn" button then click the "burn" button. Confirm the transaction via Metamask.
To check if the transaction succeeded, click the "totalSupply" button of both contracts, the displayed values should decrease from the past value and the updated values should be equal.
