# piexpad — Every Coin's Whole Pie

<div align="center">
  <img src="art/mark.webp" alt="piexpad Logo" width="160" />
  <p><strong>piexpad launches Robinhood Chain coins and prints every coin's whole pie: who held the supply when trading opened, the creator's side, and the transaction behind every slice.</strong></p>

  [![Contract Address](https://img.shields.io/badge/Contract-Robinhood%20Chain-green?style=for-the-badge)](https://explorer.robinhood.com/)
  [![Ticker](https://img.shields.io/badge/Ticker-%24PIEXPAD-blue?style=for-the-badge)](#)
  [![Platform](https://img.shields.io/badge/Venue-Robinhood%20Chain%20DEX-brightgreen?style=for-the-badge)](https://explorer.robinhood.com/)
</div>

---

## 🥧 What is piexpad?

**piexpad** is a transparent token analytics and launchpad interface built on Robinhood Chain. It breaks down token allocations into an intuitive, verifiable visual pie:

- **Creator Allocation**: Exactly how much supply the dev held at trading start.
- **Top Holders & Snipers**: First three slots, top 10 holders, and associated transactions.
- **Non-Custodial**: piexpad holds no funds, requires no keys, and executes directly via your own wallet (Robinhood Wallet, MetaMask, Coinbase Wallet).

---

## ⚡ Token Information

| Property | Value |
| :--- | :--- |
| **Token Name** | **piexpad** |
| **Ticker** | **$PIEXPAD** |
| **Network** | Robinhood Chain (EVM L2) |
| **Contract Address (CA)** | `DMay7oCBcWUywffxYi8yPtPPuY8TPypjtZzHnDsgpump` |
| **Launch Venue** | [Robinhood Chain DEX](https://explorer.robinhood.com/) |
| **Official X** | [@piexpad](https://x.com/piexpad) |

---

## 🚀 Key Features

1. **Whole Pie Inspection**: Paste any mint address to inspect who owns the supply before trading.
2. **Real-time Live Monitor**: Live retro computer screen showing on-chain bonding curves and block transactions.
3. **Interactive One-Click Copy**: Built-in clipboard copying with instant UI feedback and toast alerts.
4. **Zero-Trust Security**: No backend storage of private keys or trade signing.

---

## 🛠️ Local Development

Serve the application locally using any standard static file server:

```bash
# Using Node.js serve
npx serve .

# Using Python
python -m http.server 8097
```

Navigate to `http://localhost:8097` in your browser.

---

## 🌐 Deployment

Ready for zero-build deployment on **Vercel**, **Cloudflare Pages**, or **GitHub Pages**.

```bash
vercel --prod
```
