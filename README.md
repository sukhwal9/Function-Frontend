# Nilesh Bank - Ethereum ATM DApp

A decentralized application (DApp) that allows users to interact with an Ethereum smart contract, functioning as an ATM for depositing and withdrawing ETH.

## Description

Nilesh Bank is a decentralized application (DApp) built on the Ethereum blockchain. This project enables users to connect their MetaMask wallet to interact with a deployed smart contract, allowing them to deposit and withdraw ETH (Ethereum). The DApp provides a simple interface for managing your ETH balance directly from your browser.

## Getting Started

### Installing

1. Clone the repository:

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Ensure your Ethereum development environment is set up. You can use [Hardhat](https://hardhat.org/) to compile and deploy the smart contract.

### Executing program

1. Start the development server:
    ```sh
    npm run dev
    ```

2. Open your browser and navigate to `http://localhost:3000`.

3. Connect your MetaMask wallet:
    - If MetaMask is not installed, you will see a prompt to install it.
    - If MetaMask is installed but not connected, click on the "Please connect your MetaMask wallet" button.

4. Once connected, you can:
    - View your account address and balance.
    - Deposit 1 ETH by clicking the "Deposit 1 ETH" button.
    - Withdraw 1 ETH by clicking the "Withdraw 1 ETH" button.

## Help

For any issues or common problems, you can run the following command to get help:
```sh
npx hardhat help
