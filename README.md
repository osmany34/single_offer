# 🧾 Stellar Single Offer

This project demonstrates a **single-use offer mechanism** built on the Stellar blockchain.

It allows one party to prepare and sign a transaction (such as a token transfer or offer), and another party to submit it, but only **once** and optionally **after a certain time**.

---

## 🎯 Features

- ✅ One-time-use offer (signed transaction or claimable balance)
- ⏳ Optional time lock using `timeBounds`
- 🔐 Secured using Stellar's native mechanisms (pre-signing, multisig, etc.)
- 🌐 Supports Stellar Testnet
- ⚙️ Extendable to NFTs or custom token offers

---
## 🛠️ Setup

1. Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/single-offer.git
cd single-offer
npm install
