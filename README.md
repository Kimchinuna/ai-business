# ERC-20 Lottery Machine

This project is a lottery machine implemented on the Ethereum blockchain with a smart contract written in Solidity. 

It utilizes the ERC-20 token standard and includes a user interface developed with React and JavaScript.

## Dependencies
Before getting started with this project, make sure you have the following tools and libraries installed:

Node.js and npm

Solidity Compiler (solc)

Truffle Suite

Mocha (for testing)

React.js (for front-end)

MetaMask or similar web3 provider (for interacting with Ethereum network)

## Installation
Clone the repository: git clone <repository_link>

Navigate into the project directory: cd <project_directory>

Install project dependencies: npm install

## Compiling the Smart Contract
Navigate into the Ethereum directory: cd ethereum

Compile the contracts: truffle compile

## Migrating the Smart Contract

Migrate the contracts to the local Ethereum blockchain: truffle migrate

Note: Make sure your local Ethereum blockchain is running before executing the migration command.

## Testing the Smart Contract
We use the Mocha testing framework for Solidity smart contracts. 

To run the tests, simply execute the following command in the Ethereum directory:

'truffle test'

## Running the Application
Navigate back to the project root directory.

Start the React development server: npm start

## Usage
To interact with the smart contract:

Connect MetaMask or your preferred web3 provider.

Navigate to the application URL (localhost if running locally).

Follow the on-screen prompts to enter the lottery, check the pool size, and draw winners.
