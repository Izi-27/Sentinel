# Sentinel
Sentinel provides real-time, AI-powered risk assessment for smart contracts, empowering users to interact with DeFi confidently.


> AI-Powered Smart Contract Risk Assessment for Polygon

Sentinel provides real-time, AI-powered risk assessment for smart contracts, empowering users to interact with DeFi confidently.

## 🚀 Features

- **Smart Contract Risk Scoring**: Green/Yellow/Red ratings for any contract
- **Browser Extension**: Seamless integration with popular DeFi dApps
- **AI Analysis**: Fine-tuned LLM for vulnerability detection
- **Transaction Simulation**: MEV and front-running detection
- **Portfolio Scanner**: Analyze wallet-wide risk exposure

## 🏗 Architecture

```

┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Browser       │    │   Sentinel      │    │   Blockchain    │
│   Extension     │────│   API           │────│   Polygon       │
│   (React)       │    │   (Node.js)     │    │   Scan APIs     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
│
┌─────────────────┐
│   AI/ML         │
│   Pipeline      │
│   (Python)      │
└─────────────────┘

```

## 🛠 Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript
- **AI/ML**: Python, Hugging Face, PyTorch
- **Blockchain**: Polygon, Ethers.js, Hardhat
- **Database**: PostgreSQL, Redis
- **Infrastructure**: Docker, AWS, Vercel

## 📦 Quick Start

### Prerequisites

- Node.js 18+
- Python 3.9+
- Docker
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/sentinel.git
cd sentinel

# Install dependencies
npm run setup

# Start development environment
npm run dev
```

🎯 Usage

Web App

1. Navigate to the web application
2. Paste a contract address
3. View the risk assessment report

Browser Extension

1. Install the extension from Chrome Web Store
2. Visit any DeFi dApp
3. See risk scores directly in the UI



This project is part of the Polygon Buildathon with the following roadmap:

## Roadmap
Phase 1: Sprint to Funding (Waves 1-5)

Wave 1-2: Foundation & Setup

1. Develop a basic React dApp UI for contract address input.
2. Create a Node.js/Express backend API.
3. Integrate with PolygonScan API to fetch contract code.
4. Build a rule-based classifier to detect 3-5 common vulnerabilities (e.g., unlimited approval).
5. Display a simple risk score (Green/Yellow/Red) on the dApp.
6. Deploy the full stack on a testnet.

Wave 3-4: Build & Optimize

1. Develop and publish a Chrome extension MVP that injects the risk score into popular DeFi UIs.
2. Replace the rule-based classifier with a fine-tuned open-source LLM (e.g., Llama 3) for analysis.
3. Add a "Transaction Simulation" feature to check for potential MEV/front-running.
4. Implement user accounts to save scan history.
5. Launch a waitlist and acquire the first 100 active users.

Wave 5: Pitch & Raise

1. Compile all data (user growth, scans performed, vulnerabilities found).
2. Finalize the pitch deck and demo video.
3. Execute VC meetings facilitated by Polygon.
4. Secure initial funding.

Phase 2: Scale & Expand (Waves 6-10)

Wave 6-7: Product Expansion

1. Develop a "Portfolio Scanner" that analyzes a wallet's entire approved contract risk.
2. Launch a premium subscription with advanced features (real-time exploit alerts).
3. Form partnerships with 2-3 established DeFi protocols on Polygon.

Wave 8-9: Monetization & Growth

1. Launch a B2B API for other dApps and wallets to integrate our scoring.
2. Implement the full freemium business model and fee structure.
3. Run a targeted marketing campaign to reach 1,000+ daily active users.

Wave 10: Enterprise Ready

1. Develop an enterprise dashboard for VC firms and trading desks.
2. Pass a third-party security audit for the entire system.
3. Present the scaled product at a major event (e.g., ETHDenver).

🤝 Contributing

We welcome contributions! Please see our Contributing Guide for details.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

🔗 Links

· Documentation
· Polygon Buildathon
· Demo Video




