---
theme: default
background: https://images.unsplash.com/photo-1639762681485-074b7f938ba0?auto=format&fit=crop&q=80&w=2832&ixlib=rb-4.0.3
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
title: Mostro - GetAlby Community Call
---

<div style="display: flex; justify-content: center; margin-bottom: 20px;">
  <img src="/mostro-logo.png" alt="Mostro Logo" style="height: 150px;">
</div>

# Mostro

## P2P Bitcoin on Lightning + Nostr

GetAlby Community Call — February 2026

---

# What is Mostro?

<div class="grid grid-cols-2 gap-4">
<div>

Non-custodial **P2P Bitcoin exchange** on **Lightning** and **Nostr**.

- **Non-custodial**: Lightning hold invoices as escrow
- **No KYC**: just Lightning wallet + Nostr keys
- **Censorship resistant**: NIP-59 gift wrap encryption
- **Open source**: Rust core, anyone can run a node

</div>
<div>

```mermaid
graph LR
  A[Seller] -->|Hold Invoice| B[Mostro]
  B -->|Escrow| C[Lightning]
  D[Buyer] -->|Fiat| A
  C -->|Release| D
```

</div>
</div>

---

# App Beta — Flutter

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 📱 NWC Integrated

Connect your own wallet:
- Alby
- Mutiny
- Zeus

</div>

<div v-click>

### 🔄 Trade Restore

Automatic backup across devices. Change phones, recover everything.

</div>

<div v-click>

### 💬 Dispute Chat

Private admin-seller-buyer thread, gift-wrapped. All in the app.

</div>

</div>

<div v-click class="mt-8 text-center">

**+100 active testers** — Public beta on zapstore and github! 🥳

</div>

---

# Mostro-skills

## AI Integration

<div class="grid grid-cols-2 gap-8">
<div>

OpenClaw skill to operate Mostro via chat:

- Create orders
- Take trades
- Manage disputes

</div>
<div class="flex items-center justify-center">

<div class="bg-gray-800 rounded-lg p-4 text-sm font-mono">
<div class="text-green-400">User:</div>
<div>Create a sell order for 100k sats</div>
<div class="text-blue-400 mt-2">Mostronator:</div>
<div>Order created: #1234</div>
<div class="text-gray-400">Seller: @user</div>
<div class="text-gray-400">Amount: 100,000 sats</div>
<div class="text-gray-400">Fiat: USD</div>
</div>

</div>
</div>

<div class="mt-8 text-center text-xl">

🤖 **24/7 P2P trader**

</div>

---

# Mostro Community

## mostro.community

<div class="grid grid-cols-2 gap-8">

<div>

Freshly launched program to help **Bitcoin communities** run their own Mostro node.

</div>

<div>

### What's included:

- Technical support
- Guided setup
- Best practices
- Visibility in the app

</div>

</div>

<div v-click class="mt-8 p-4 bg-green-900 rounded-lg text-center">

**Always open source**: anyone can deploy without permission.  
The program just makes the journey easier.

</div>

---

# Tools for Operators

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 🖥️ Mostrix

Manage disputes from desktop. No mobile app needed.

</div>

<div v-click>

### 🔔 Mostro-watchdog

Telegram bot for admins:
- Real-time monitoring
- Dispute notifications
- Relay health checks

</div>

<div v-click>

### 📊 Mostro-score-web

Reputation analysis:
- Fetches Nostr events
- Objective metrics
- Full transparency

</div>

</div>

---

# Recent Challenges

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 🚀 Onboarding

**Problem**: Friction combining Nostr keys + Lightning wallet  
**Solution**: Embedded wallets in testing

</div>

<div v-click>

### 🔔 Notifications

**Problem**: Dependency on FCM/Google  
**Experiment**: Push via Nostr relays + background sync

</div>

<div v-click>

### 💰 Liquidity

**Problem**: We need more makers  
**Focus**: LATAM and Africa

</div>

</div>

---

# Closing

## How to get involved?

<div class="grid grid-cols-2 gap-8">

<div>

### Mostro is on:

- ✅ **Mainnet**
- ✅ **Global beta**
- ✅ **mostro.community** freshly launched

</div>

<div>

### Join if you:

- Trade P2P and want to be a **maker**
- Have a Bitcoin community
- Want to **test** the app

</div>

</div>

<div class="mt-12 text-center text-2xl">

🌐 **mostro.network**  
🌐 **mostro.community**  
💻 **github.com/MostroP2P**

</div>

<div class="mt-8 text-center">

Thanks 🧌

</div>

---

# Questions?

<div class="text-center">

🧌 Mostro — Non-custodial P2P Bitcoin

mostro.network | mostro.community | github.com/MostroP2P

</div>
