

# NFT Marketplace Project

This project is an NFT marketplace that allows users to buy, sell and trade non-fungible tokens (NFTs) on the Ethereum blockchain. The project is built using the following technologies:

- Solidity
- Hardhat
- React
- Web3.js

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- Hardhat (`npm install --save-dev hardhat`)
- Ganache (for local development/testing)

### Installing

1. Clone the repository:

   ```
   git clone https://github.com/your_username/nft-marketplace.git
   ```

2. Install the dependencies:

   ```
   cd nft-marketplace
   npm install
   ```

3. Start the development blockchain:

   ```
   ganache-cli
   ```

4. Compile the smart contracts:

   ```
   npx hardhat compile
   ```

5. Migrate the smart contracts to the development blockchain:

   ```
   npx hardhat run scripts/deploy.js --network development
   ```

6. Start the React app:

   ```
   npm start
   ```

7. Open your browser and go to http://localhost:3000

## Usage

The NFT marketplace allows users to buy, sell and trade NFTs. Users can create an account, connect their Ethereum wallet and start buying and selling NFTs.

### Creating an Account

To create an account, click on the "Sign Up" button and enter your details. You will need to verify your email address to activate your account.

### Connecting your Ethereum Wallet

To connect your Ethereum wallet, click on the "Connect Wallet" button and select your wallet provider (e.g. MetaMask). Follow the prompts to connect your wallet.

### Buying NFTs

To buy an NFT, browse the marketplace and click on the NFT you want to buy. Click on the "Buy" button and confirm the transaction in your Ethereum wallet.

### Selling NFTs

To sell an NFT, go to your account dashboard and click on the "Sell NFT" button. Enter the details of the NFT and set the price. Once the NFT is listed on the marketplace, other users can buy it.

## Contributing

If you would like to contribute to the project, please submit a pull request. Make sure to follow the existing code style and add tests for any new functionality.

