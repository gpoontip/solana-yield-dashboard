# 🔥 Solana Yield Dashboard + CLMM Position Manager

An advanced dashboard to monitor, simulate, and manage Raydium CLMM (Concentrated Liquidity Market Maker) positions on Solana — built for aggressive LP strategies like SOL/USDC and SOL/RAY.

---

## 🎯 Project Goals

- Connect Solana wallet (Phantom)
- Display real-time APRs for Raydium CLMM pools
- Track wallet LP positions: current price, tick range, fees earned
- Detect when positions are out of range
- Simulate LP returns based on custom ranges and fee projections
- Manually rebalance positions (close + reopen)
- Phase 2: Add alerts + automation

---

## 🧱 Tech Stack

- **Frontend**: React + Tailwind CSS
- **Wallet Integration**: Solana Wallet Adapter
- **Blockchain Access**: Solana Web3.js, Raydium SDK, Helius API
- **Price Feeds / APR**: Raydium SDK, Jupiter Aggregator API

---

## 🗂 Project Structure

```
src/
  components/       # Reusable UI components (cards, inputs, charts)
  hooks/            # Wallet hooks and data fetching logic
  utils/            # Helpers for ticks, APR, math
  api/              # Raydium + Jupiter API functions
```

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/solana-yield-dashboard.git
cd solana-yield-dashboard
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Dev Server

```bash
npm run dev
```

### 4. Connect Your Wallet

Ensure you have Phantom wallet installed and some devnet/testnet SOL for testing.

---

## 📈 Features (MVP)

- ✅ Connect Phantom wallet
- ✅ Show APRs for SOL/USDC & SOL/RAY CLMM pools
- ✅ Fetch & display LP positions with tick range + status
- ✅ Simulate LP performance using tick width + expected APR
- 🚧 Manual Rebalance Button (WIP)
- 🚧 APR Spike & Out-of-Range Alerts (Phase 2)

---

## 🧠 Roadmap

- [ ] Build live CLMM APR fetcher
- [ ] Fetch user LP NFTs from wallet
- [ ] Visualize tick range and price vs. LP status
- [ ] Add LP range simulator
- [ ] Manual rebalance actions (close + reopen LP)
- [ ] Add Telegram / Discord bot alerts (Phase 2)
- [ ] Full automation with keeper service (Phase 3)

---

## 🤝 Contributing

PRs and issue reports welcome. Open source contribution guidelines coming soon.

---

Built with ❤️ by [@garypoontip](https://github.com/garypoontip) to run aggressive Solana DeFi strategies with sniper precision.
