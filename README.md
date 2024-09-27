# DApp Project: Support Creators with Donations

Welcome to the Support Creators DApp! This decentralized application allows users to support their favorite creators by purchasing tokens and sending thank-you messages. The application is built on the Ethereum blockchain and utilizes the Fantom test network for transactions. This project is a clone of CodeEater's original project.

## Features
- Connect to Metamask wallet for seamless Ethereum transactions.
- Buy tokens to financially support creators.
- Send personalized thank-you messages with each purchase.
- View a history of messages in a user-friendly interface.
- Responsive design for an optimal experience on all devices.

## Technologies Used
- **React**: Frontend library for building the user interface.
- **Metamask**: Browser extension for managing Ethereum wallets.
- **Fantom Test Network**: Used for testing smart contracts without spending real Ether.
- **Solidity**: Programming language for writing smart contracts.
- **Hardhat**: Ethereum development environment for compiling, deploying, and testing smart contracts.
- **Vite**: A fast build tool and development server for React applications.

## Compiling and Deployment
To run this project locally, follow these steps:

1. **Compiling and Deployment on Fantomtest Network**:
   ```bash
   npx hardhat compile
   npx hardhat ignition deploy igition/modules/token.js --network fantomtest
   ```

2. **Running the app**
   ```bash
   cd client
   npm run dev
   ```


## Credits
This project is inspired by Code Eater Web3's original work https://www.youtube.com/watch?v=NxDGHynpA4s&t=1063s. Special thanks to Code Eater Web3
