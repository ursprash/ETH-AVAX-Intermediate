# ETH-AVAX-Intermediate
1. Smart contract has at least two functions
2. Value of the functions from the smart contract are visible on the frontend of the application

## Overview
This is a simple React component for a Crypto ATM application. It allows users to connect their MetaMask wallet, view their account balance, deposit and withdraw ETH, and check the owner's name.

## Smart Contract

### Assessment.sol

The `Assessment.sol` smart contract is the core component of this project. It contains at least two functions that are used to interact with the contract.

#### `getBalance()`

Returns the current balance of the contract.

#### `deposit(uint256 _amount)`

Deposits the specified amount of funds into the contract.

### Frontend Integration

The functions from the smart contract are integrated into the frontend of the application to provide a seamless user experience. Here's how they are visible on the frontend:

- The `getBalance()` function is used to display the current balance of the contract on the user interface.
- The `deposit(_amount)` function is triggered when users want to deposit funds into the contract. They can enter the amount they wish to deposit, and the frontend handles the transaction and updates the balance accordingly.

## Commands
After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
Back in the first terminal, type npm run dev to launch the front-end.


## License
This project is licensed under the MIT License. See the LICENSE file for details.
