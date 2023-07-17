

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
### Snapshots
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQFW8GuXairEvA/feedshare-shrink_2048_1536/0/1682743897814?e=1692230400&v=beta&t=B9qutLZZ97II_IjD6PocerRhF2Pv3Oin_VXvzgG-6So)
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQGQFgXqW-QCXg/feedshare-shrink_2048_1536/0/1682743897728?e=1692230400&v=beta&t=KNxIbmmLPxHvqRuAOww4hQta19Lg8C9JIEe3iNo0Z6w)
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQEH8xLXM5jeeQ/feedshare-shrink_2048_1536/0/1682743897865?e=1692230400&v=beta&t=eGzGKc0NGbLHmp3XmCk3QCHeJ6ZFQLHCaa1hXKYolqg)
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQHM2KethLmDtw/feedshare-shrink_2048_1536/0/1682743897999?e=1692230400&v=beta&t=UbyVQcTR33CwD-JvqlDzWVBPeiycY3WLHVcbcyR2CCQ)
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQHI3xlpnRVWpQ/feedshare-shrink_800/0/1682743897859?e=1692230400&v=beta&t=Mb0E-aUZIX2kHd5GRK5_nkMfmoDOe5LjzRaRfU_naxw)
![App Screenshot](https://media.licdn.com/dms/image/D4D22AQFop6fbK7KrBA/feedshare-shrink_800/0/1682743897834?e=1692230400&v=beta&t=fS92z1Km4xzGYHfbJ-wG6yo63skr-zm0po1X5bdznTw)

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

