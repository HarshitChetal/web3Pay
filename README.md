Digi3Pay

A Web3 payment system built on Ethereum Sepolia testnet.
Works similar to UPI but uses blockchain transactions instead of banks.

Users connect their MetaMask wallet, send ETH, and optionally use a vault smart contract to store funds.

What it does
Send ETH from one wallet to another (like UPI transfer)
Uses Sepolia testnet (not real money)
MetaMask is required
Includes a vault system (deposit/withdraw)
Tech Stack
Frontend: HTML/CSS/JS (or React)
Backend: Node.js / Express (if used)
Blockchain: Ethereum Sepolia
Wallet: MetaMask
Smart Contracts: Solidity
Requirements
MetaMask installed
Sepolia test ETH (from faucet)
Node.js installed
Setup
git clone https://github.com/Harshit/digi3pay.git
cd digi3pay
npm install
npm start
Usage
Open the app
Connect MetaMask
Switch to Sepolia network
Get test ETH from faucet
Enter receiver address + amount
Confirm transaction

Vault:

Deposit ETH into contract
Withdraw when needed
Notes
This project uses testnet (Sepolia), not mainnet
Transactions may take time depending on network
Gas fees are paid in Sepolia ETH
Author

Harshit Chetal
