# 🥷 Gas Ninja Bot

**Autonomous Gas Intelligence Agent on BNB Chain**

A production-grade Web3 analytics dashboard for monitoring, predicting, and optimizing gas costs on BNB Chain. The Gas Ninja Bot acts as an autonomous agent that executes transactions at optimal gas prices, saving you money on every interaction.

![Gas Ninja Bot](https://img.shields.io/badge/BNB_Chain-F0B90B?style=for-the-badge&logo=binance&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

---

## ⚡ Features

### 📊 Real-Time Gas Analytics Dashboard
- Live gas price chart with 5, 20, and 50-period moving averages
- Visual execution markers highlighting agent actions at local minima
- Selectable time ranges (1h, 6h, 24h, 7d)

### 💰 Savings Tracking
- Total gas saved in BNB and USD
- Average savings per transaction (percentage & absolute)
- Best single execution delta
- Total transactions optimized

### 🎯 Efficiency Metrics
- Prediction accuracy with trend indicators
- Average wait time before execution
- Execution efficiency score
- ROI (gas saved vs. operational cost)

### 📜 Transaction History
- Sortable, filterable transaction table
- Direct links to BscScan for on-chain verification
- Color-coded savings indicators
- Pagination for large datasets

### 🚀 Transaction Scheduling
- Submit scheduled transactions (target address, calldata, value)
- Live gas price and predicted optimal execution window
- Estimated savings range
- Real-time status tracker (Scheduled → Monitoring → Executing → Completed)

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | UI framework |
| **TypeScript** | Type safety |
| **Vite** | Build tool & dev server |
| **Tailwind CSS** | Utility-first styling |
| **shadcn/ui** | Component library |
| **Recharts** | Data visualization |
| **TanStack Query** | Data fetching & caching |
| **React Router** | Client-side routing |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project
cd gas-ninja-bot

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`.

---

## 📁 Project Structure

```
src/
├── components/
│   ├── dashboard/
│   │   ├── GasTrendChart.tsx      # Gas price chart with moving averages
│   │   ├── SavingsCards.tsx        # Summary metric cards
│   │   └── EfficiencyMetrics.tsx   # Prediction & efficiency stats
│   ├── layout/
│   │   └── DashboardLayout.tsx     # App shell with navigation
│   └── ui/                        # shadcn/ui components
├── lib/
│   └── mock-data.ts               # Mock data generators
├── pages/
│   ├── Index.tsx                   # Main dashboard
│   ├── TransactionHistory.tsx      # Transaction table
│   └── ScheduleTransaction.tsx     # Schedule new transactions
└── App.tsx                        # Root with routing
```

---

## 🔮 Roadmap

- [ ] Wallet connection (MetaMask / WalletConnect)
- [ ] Live gas data from BNB Chain RPC
- [ ] Smart contract integration (GasOptimizedExecutor)
- [ ] Real-time agent prediction API
- [ ] Push notifications for optimal gas windows

---

## 📄 License

MIT
