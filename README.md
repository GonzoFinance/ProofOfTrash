# Proof of Trash - Gorbagana Testnet Gaming

A fast-paced multiplayer reaction game that challenges players to quickly and accurately sort waste items while competing for GOR tokens on the Gorbagana testnet.

## 🎮 Game Overview

**Proof of Trash** combines environmental awareness with competitive gaming mechanics. Players compete in lightning-fast rounds where they must correctly categorize waste items as either recyclable or trash. The game features:

- **Lightning-fast gameplay**: 3-second countdown followed by instant reaction challenges
- **Educational content**: Learn proper waste sorting with 13 different item types
- **Multiplayer competition**: Up to 4 players per game session
- **Token rewards**: Win GOR tokens based on performance and accuracy
- **Real-time feedback**: Immediate visual confirmation of correct/incorrect choices

### Game Mechanics

1. **Entry Fee**: 0.5 GORB tokens per game
2. **Game Duration**: ~15 seconds per round
3. **Challenge Types**: Sort items like food scraps, plastic bottles, paper documents, etc.
4. **Scoring**: Based on reaction time and accuracy
5. **Rewards**: Fastest correct responses win the prize pool

## 🔗 Gorbagana Integration

This game is built specifically for the **Gorbagana testnet** and demonstrates the network's capabilities:

### Network Features Utilized
- **High-speed transactions**: Sub-second game state updates
- **Native token integration**: GOR token transfers for entry fees and rewards
- **Real-time gaming**: WebSocket coordination with blockchain settlement
- **Wallet integration**: Seamless Backpack wallet connectivity

### Technical Implementation
- **RPC Endpoint**: Connects to Gorbagana testnet RPC for balance queries and transactions
- **Native Tokens**: Uses GOR native tokens
- **Transaction Types**: Game entry fees, prize distributions, and balance updates
- **Network Speed**: Leverages Gorbagana's fast finality for responsive gaming

## 💻 Development Setup

### Prerequisites
- Node.js 18+ and npm
- Backpack wallet browser extension
- GOR test tokens for gameplay

### Local Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd proof-of-trash
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Configuration**
   Create a `.env` file with:
   ```
   VITE_GORBAGANA_RPC_URL=<your-gorbagana-testnet-rpc-url>
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Access the game**
   Open `http://localhost:5000` in your browser

### Project Structure
```
├── client/src/          # React frontend
│   ├── components/      # UI components
│   ├── contexts/        # Game state management
│   ├── hooks/          # React hooks
│   ├── lib/            # Wallet and utility functions
│   └── pages/          # Application pages
├── server/             # Express.js backend
│   ├── routes.ts       # API routes and WebSocket server
│   ├── storage.ts      # In-memory game state
│   └── index.ts        # Server entry point
└── shared/             # Shared types and schemas
```

## 🎯 Backpack Wallet Support

The game requires **Backpack wallet** for authentic blockchain interactions:

### Installation
1. Install [Backpack wallet extension](https://backpack.app/) in your browser
2. Create or import a wallet
3. Switch to Gorbagana testnet
4. Fund your wallet with GORB test tokens

### Usage
1. Click "Connect Backpack" in the game interface
2. Approve the connection request
3. Your wallet balance will display in GORB tokens
4. Game entry fees (0.5 GORB) are automatically deducted
5. Winnings are distributed to your wallet address

### Fallback Mode
If Backpack wallet is not detected, the game runs in demo mode with mock transactions for development and testing purposes.

## 🚀 Live Features

**Features**:
- Real Backpack wallet integration
- Live Gorbagana testnet connectivity
- Multiplayer matchmaking
- Real-time leaderboards
- Token-based economy

## 🏗️ Technical Architecture

### Frontend Stack
- **React 18** with TypeScript
- **Tailwind CSS** + shadcn/ui components
- **TanStack Query** for server state
- **Wouter** for routing
- **Vite** for development and builds

### Backend Stack
- **Node.js** + Express.js
- **WebSocket** server for real-time multiplayer
- **PostgreSQL** via Drizzle ORM (with in-memory fallback)
- **TypeScript** with ES modules

### Blockchain Integration
- **Backpack wallet** API for transaction signing
- **Gorbagana RPC** for balance queries and submissions
- **Native GOR tokens** for game economy
- **Real-time settlement** with immediate feedback

## 🎪 Game Flow

1. **Connect Wallet**: Link your Backpack wallet to the game url: gorbagana-proof-of-trash-game.replit.app
2. **Join Queue**: Click "Find Match" to enter matchmaking
3. **Wait for Players**: Up to 4 players per game session
4. **Get Ready**: 3-second countdown with visual preparation
5. **React Fast**: Sort the displayed waste item correctly
6. **See Results**: Immediate feedback and final rankings
7. **Collect Rewards**: GOR tokens distributed to winners

## 🏆 Bounty Submission

This project was created for the **Gorbagana testnet bounty program** and demonstrates:

✅ **Working multiplayer game prototype**  
✅ **Gorbagana testnet integration**  
✅ **Native GORB token usage**  
✅ **Backpack wallet support**  
✅ **Comprehensive documentation**  
✅ **Live deployment ready**  

## 📈 Performance Metrics

- **Game Start Time**: ~2.5 seconds (0.5s auto-start + 3s countdown)
- **Challenge Duration**: 15 seconds active gameplay
- **Network Latency**: Sub-second transaction confirmation
- **Concurrent Players**: Up to 4 players per game session
- **Real-time Updates**: WebSocket-based state synchronization

## 🛠️ Development Notes

### Key Features Implemented
- Real-time multiplayer coordination via WebSocket
- Educational waste sorting with 13 item types
- Immediate visual feedback for user actions
- Optimized game timing for competitive play
- Comprehensive error handling and fallbacks
- Responsive design for various screen sizes

### Network Integration
- Direct RPC calls to Gorbagana testnet
- Native token balance queries and transfers
- Transaction signing through Backpack wallet
- Real-time settlement with game state updates

---

**Built for Gorbagana Testnet Bounty Program**  
*Demonstrating high-speed blockchain gaming with educational value*
