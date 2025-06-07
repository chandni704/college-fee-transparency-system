
# 🏛️ College Fee Transparency System using Blockchain

This project implements a **blockchain-based fee payment and audit system** for universities or colleges, ensuring **transparency**, **security**, and **tamper-proof tracking** of all financial transactions like tuition payments, penalties, refunds, and audit trails.

---

## 📌 Key Features

- 🔐 Transparent and immutable fee payment records
- 📅 Schedule-based payment tracking
- 💸 Penalty management for delayed payments
- 💵 Refund processing
- ✅ Audit module for accountability
- 🧾 Admin and student frontends
- ⚙️ Smart contracts using Solidity deployed via Truffle
- 🌐 Node.js backend integration

---

## 🧠 Modules Overview

| Module      | Description |
|-------------|-------------|
| `payment.sol` | Handles payment submission and tracking |
| `penalty.sol` | Tracks and applies penalties for late fees |
| `refund.sol` | Manages refund requests and processing |
| `schedule.sol` | Defines and manages fee schedules |
| `aduit.sol` | (typo: should be `audit.sol`) Manages audit logs of all operations |

---

## 💻 Tech Stack

| Layer        | Technology |
|--------------|------------|
| Smart Contracts | Solidity (via Truffle) |
| Blockchain Platform | Ganache (Local Ethereum Blockchain) |
| Backend      | Node.js + Express |
| Frontend     | HTML/CSS (Admin and Student portals) |
| Tools        | Truffle, Ganache, MetaMask, Web3.js |

---


## 🚀 Getting Started

### 1. Prerequisites

- Node.js and npm
- Truffle Suite
- Ganache (local blockchain)
- MetaMask (browser extension)

### 2. Install Dependencies

```bash
npm install
````

### 3. Compile & Deploy Smart Contracts

```bash
cd truffle
truffle compile
truffle migrate --network development
```

### 4. Run Backend Server

```bash
node server.js
```

### 5. Open Frontend

Launch `index.html` in your browser and connect MetaMask to interact.

---

## 🛡️ Security & Transparency

All data is logged immutably on the blockchain. Admins can **not modify** fee records once written. The **audit contract** maintains a secure ledger for verification by authorities or governing bodies.

---

## 🧪 Future Enhancements

* Role-based access for department heads
* PDF receipt generation
* Email/SMS alerts for due dates
* University-wide analytics dashboard

---

## 📜 License

This project is licensed under the [MIT License](./LICENCE).
lp you clean and fix any Solidity or JS code for production readiness.

