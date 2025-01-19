# NFT Marketplace

A decentralized NFT (Non-Fungible Token) marketplace built on Ethereum blockchain where users can mint, list, buy, and sell NFTs.

## Features

- Create and mint NFTs
- List NFTs for sale
- Purchase NFTs from the marketplace
- View NFT transaction history
- Set royalties for original creators

## Technology Stack

- Solidity ^0.8.19
- Hardhat
- OpenZeppelin Contracts
- Ethers.js
- Node.js

## Prerequisites

- Node.js (14.x or later)
- NPM or Yarn
- MetaMask wallet
- Hardhat

## Installation

1. Clone the repository
```bash
git clone https://github.com/ciphermavendev/nft-marketplace.git
cd nft-marketplace
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your configuration
```env
PRIVATE_KEY=your_private_key
NETWORK_URL=your_network_url
```

## Smart Contracts

The project includes the following smart contracts:
- `NFTMarketplace.sol`: Main marketplace contract for listing and trading NFTs

## Testing

Run the test suite:
```bash
npm test
```

## Deployment

Deploy to local network:
```bash
npx hardhat run scripts/deploy.js --network localhost
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details