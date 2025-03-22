# Blockchain-Based Bug Bounty (BBBB)

A decentralized platform for managing bug bounty programs using blockchain technology. Companies can create and manage bounties while security researchers can submit and get rewarded for finding vulnerabilities.

## Features

- Web3 Integration with MetaMask
- Smart Contract based bounty management
- Role-based access (Companies & Hunters)
- Profile management
- Real-time bounty tracking
- Secure submission handling

## Tech Stack

- Frontend: React.js
- Smart Contracts: Solidity
- Development Environment: Hardhat
- Web3 Integration: ethers.js
- Styling: Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MetaMask browser extension
- Ganache (for local blockchain)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Blockchain-Based-Bug-Bounty.git
cd Blockchain-Based-Bug-Bounty
```

2. Install dependencies:
```bash
# Install root dependencies
npm install

# Install frontend dependencies
cd frontend
npm install
```

3. Start local blockchain:
```bash
npx ganache-cli
```

4. In a new terminal, compile and deploy smart contracts:
```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
```

5. Start the frontend development server:
```bash
cd frontend
npm start
```

6. Connect MetaMask to your local blockchain (usually http://localhost:8545)

## Project Structure

```
Blockchain-Based-Bug-Bounty/
├── contracts/           # Smart contracts
├── frontend/           # React frontend application
│   ├── src/
│   │   ├── components/ # Reusable components
│   │   ├── pages/      # Page components
│   │   └── utils/      # Utility functions
├── scripts/            # Deployment scripts
├── test/              # Smart contract tests
└── hardhat.config.js  # Hardhat configuration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

