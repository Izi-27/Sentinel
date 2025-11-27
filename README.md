# Sentinel

Sentinel provides real-time risk assessment for smart contracts on Polygon, empowering users to interact with DeFi confidently through a web application and browser extension.

## 🚀 Features

- **Smart Contract Risk Scoring**: Basic Green/Yellow/Red ratings for contracts via API analysis
- **Browser Extension**: Seamless integration with popular DeFi dApps (Uniswap, OpenSea)
- **Web Application**: Next.js-based interface for contract auditing
- **API Integration**: Fetches contract data from Polygon/blockchain APIs

## 🏗 Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Browser       │    │   Sentinel      │    │   Blockchain    │
│   Extension     │────│   Web App       │────│   Polygon       │
│   (Manifest V3) │    │   (Next.js)     │    │   APIs          │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

## 🛠 Tech Stack

- **Frontend/Web App**: Next.js, React, TypeScript
- **API**: Next.js API Routes
- **Extension**: Manifest V3, JavaScript
- **Blockchain**: Polygon, Ethers.js

## 📦 Quick Start

### Prerequisites

- Node.js 18+
- pnpm
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/sentinel.git
cd sentinel

# Install dependencies for the web app
cd sentinel
pnpm install

# Start the development server
pnpm dev
```

### Extension Development

To load the browser extension for development:

1. Open Chrome and navigate to `chrome://extensions`
2. Enable "Developer mode" in the top right
3. Click "Load unpacked" and select the `extension/` folder from the project root
4. The extension will be loaded and available in the browser

## 🎯 Usage

### Web Application

1. Navigate to `http://localhost:3000` (after running `pnpm dev` in `sentinel/`)
2. Paste a contract address in the interface
3. View the risk assessment report

### Browser Extension

1. Load the extension as described in Extension Development
2. Visit supported DeFi sites (e.g., Uniswap or OpenSea)
3. The extension will inject risk scores into the UI

## 📈 Current Status

This project is in early development as part of the Polygon Buildathon. The current implementation includes a basic Next.js web app with an audit API route and a Chrome extension for DeFi integration. Future phases may expand features like advanced AI analysis, transaction simulation, and portfolio scanning.

🤝 Contributing

We welcome contributions! Please see our Contributing Guide for details.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

🔗 Links

- [Polygon Buildathon](https://polygon.technology/buildathon)
- [Next.js Documentation](https://nextjs.org/docs)
- [Chrome Extension Docs](https://developer.chrome.com/docs/extensions/mv3/getstarted/)
