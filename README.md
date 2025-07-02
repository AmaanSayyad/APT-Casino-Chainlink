# APT-Casino-Chainlink

A blockchain-based casino platform built with Next.js and Chainlink VRF for provably fair gaming.

## Features

- Multiple casino games (Mines, Roulette, Plinko, Wheel)
- Blockchain wallet integration via RainbowKit and Wagmi
- Smart contracts for provably fair gaming
- ERC-20 token integration for betting
- Modern UI with animations and responsive design

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS, Framer Motion
- **Blockchain**: Viem, Wagmi, RainbowKit
- **Smart Contracts**: Solidity, Hardhat
- **Supported Networks**: Mantle Sepolia, Pharos Devnet

## Getting Started

### Prerequisites

- Node.js (v18+)
- Yarn, npm, or pnpm
- MetaMask or another Ethereum wallet

### Installation

1. Clone the repository
```bash
git clone https://github.com/AmaanSayyad/APT-Casino-Chainlink.git
cd APT-Casino-Chainlink
```

2. Install dependencies
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Smart Contracts

The project includes the following smart contracts:

- `Roulette.sol`: Implements a provably fair roulette game with ERC20 token integration
- `Token.sol`: Custom ERC20 token for the casino platform with treasury management

## License

MIT
