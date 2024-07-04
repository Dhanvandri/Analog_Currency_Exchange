Universal Wallet

Overview
The Universal Wallet is a cutting-edge decentralized finance (DeFi) solution that leverages Analog's stack to enable seamless transactions across different cryptocurrencies. Our goal is to create a versatile and user-friendly wallet that supports borrowing and lending protocols, allowing users to lend tokens on Blockchain users for different cryptocurriencies.

Features

Cross-Chain Transactions: Facilitates seamless transactions between different cryptocurrencies.
Borrowing and Lending Protocol: Allows users to lend tokens on Ethereum to Polygon users.
Universal Support: Compatible with a wide range of cryptocurrencies.
Security: Built with state-of-the-art security measures to protect user assets.
User-Friendly Interface: Easy-to-use interface for both novice and experienced users.

Installation

Prerequisites
Solidity (0.8.13 or higher)
Node.js (v14 or higher)
npm (v6 or higher)
Analog's SDK

Steps

Clone the Repository
git clone https://github.com/Dhanvandri/Analog_Currency_Exchange.git
cd universal-wallet
Install Dependencies
npm install

Configure Environment Variables

Create a .env file in the root directory and add your environment variables:


NODE_ENV=development
ANALOG_API_KEY=your_analog_api_key
ETHEREUM_NETWORK=https://mainnet.infura.io/v3/
POLYGON_NETWORK=https://polygon-rpc.com/

Run the Application

npm start
Usage
Create a Wallet
node createWallet.js

Check Balance
node checkBalance.js --wallet=your_wallet_address

Send Transaction

node sendTransaction.js --from=your_wallet_address --to=recipient_wallet_address --amount=amount --currency=currency

Lend Tokens

node lendTokens.js --from=your_wallet_address --to=polygon_user_address --amount=amount --currency=currency
Contributing

We welcome contributions from the community! Please follow these steps to contribute:

Fork the repository.
Create a new branch: git checkout -b my-feature-branch

Make your changes and commit them: git commit -m 'Add some feature'

Push to the branch: git push origin my-feature-branch

Submit a pull request.


Contact
For any questions or suggestions, please reach out to us at dhanvandridhan626@gmail.com.
