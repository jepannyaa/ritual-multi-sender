# 🌟 Ritual Multi Sender

**Advanced batch transaction sender for Ritual Testnet with intelligent scheduling and AI optimization**

> *Making mass token distribution fast, cheap, efficient, and scalable for the Ritual ecosystem*

## 🎯 Core Features

### 📤 Multi-Sender
- **Batch Native Token Sending** - Send RITUAL to 500+ wallets in one transaction
- **ERC20 Support** - Distribute any token on Ritual Testnet
- **Multi-Format Import**:
  - Manual entry (address + amount)
  - CSV upload
  - TXT file import
  - QR code scanning
- **Smart Validation** - Auto-detect duplicates, invalid addresses
- **Gas Optimization** - Automatic batch size calculation
- **Equal Distribution** - Set uniform amounts or custom per-wallet allocation

### ⏰ Advanced Scheduling
- **One-Time & Recurring** - Schedule for specific times or recurring (daily/weekly/monthly)
- **Timezone Support** - Auto-detect user timezone
- **Queue Management** - Pause, resume, or cancel any scheduled batch
- **Retry System** - Auto-retry failed transactions up to 10 times
- **Smart Execution** - AI-powered network congestion detection
- **Randomized Timing** - Natural-looking distribution

### 📊 Analytics & Insights
- **Real-Time Dashboard** - Live transaction volume, gas usage, success rates
- **Performance Charts** - Weekly trends, batch analytics, cost analysis
- **Transaction History** - Complete audit trail with export options
- **Gas Optimization** - AI suggestions for batch size and timing

### 🔐 Security & Reliability
- **Wallet Balance Validation** - Prevent failed transactions
- **Reentrancy Protection** - Smart contract security best practices
- **Nonce Protection** - Anti-duplicate execution
- **Emergency Stop** - Cancel all scheduled transactions instantly

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/jepannyaa/ritual-multi-sender.git
cd ritual-multi-sender

# Install dependencies
npm install

# Setup environment
cp .env.example .env.local

# Start development
npm run dev
```

## 🛠️ Configuration

**Ritual Testnet:**
- Chain ID: 1979
- RPC: https://rpc.ritualfoundation.org/
- Explorer: https://explorer.ritualfoundation.org
- Faucet: https://faucet.ritualfoundation.org

## 💻 Tech Stack

- Next.js 14 + React 18
- TypeScript
- TailwindCSS + Framer Motion
- Wagmi + RainbowKit
- Ethers.js
- Zustand + React Query
- PostgreSQL + Prisma
- Solidity Smart Contracts

## 📊 Key Statistics

- ⚡ Max 500 wallets per batch
- 💰 Gas optimized (~50% savings)
- 🔄 10x retry attempts
- 🌍 All timezones supported
- 🤖 AI-powered recommendations

## 📝 License

MIT License

---

**Built with ❤️ for the Ritual Ecosystem**
