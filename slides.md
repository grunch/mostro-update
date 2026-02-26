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

# Mostro

## P2P Bitcoin sobre Lightning + Nostr

GetAlby Community Call — Febrero 2026

---

# ¿Qué es Mostro?

<div class="grid grid-cols-2 gap-4">
<div>

Exchange P2P de Bitcoin **sin custodia**, sobre **Lightning** y **Nostr**.

- **Non-custodial**: hold invoices como escrow
- **Sin KYC**: solo wallet Lightning + Nostr keys
- **Censorship resistant**: NIP-59 gift wrap
- **Open source**: core en Rust

</div>
<div>

```mermaid
graph LR
  A[Vendedor] -->|Hold Invoice| B[Mostro]
  B -->|Escrow| C[Lightning]
  D[Comprador] -->|Fiat| A
  C -->|Release| D
```

</div>
</div>

---

# App Beta — Flutter

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 📱 NWC Integrado

Conectá tu propia wallet:
- Alby
- Mutiny
- Zeus

</div>

<div v-click>

### 🔄 Restore de Trades

Backup automático entre dispositivos. Cambiás de celular, recuperás todo.

</div>

<div v-click>

### 💬 Dispute Chat

Thread privado admin-seller-buyer, gift-wrapped. Todo en la app.

</div>

</div>

<div v-click class="mt-8 text-center">

**+100 testers activos** — Public beta coming soon 🚀

</div>

---

# Mostro-skills

## Integración con IA

<div class="grid grid-cols-2 gap-8">
<div>

Skill de OpenClaw para operar Mostro vía chat:

- Crear órdenes
- Tomar trades
- Gestionar disputas

</div>
<div class="flex items-center justify-center">

<div class="bg-gray-800 rounded-lg p-4 text-sm font-mono">
<div class="text-green-400">User:</div>
<div>Creame una orden de venta por 100k sats</div>
<div class="text-blue-400 mt-2">Mostronator:</div>
<div>Orden creada: #1234</div>
<div class="text-gray-400">Seller: @user</div>
<div class="text-gray-400">Amount: 100,000 sats</div>
<div class="text-gray-400">Fiat: USD</div>
</div>

</div>
</div>

<div class="mt-8 text-center text-xl">

🤖 **Trader P2P 24/7** en tu chat de Telegram

</div>

---

# Mostro Community

## mostro.community

<div class="grid grid-cols-2 gap-8">

<div>

Programa recién lanzado para ayudar a **comunidades Bitcoin** a correr su propio nodo Mostro.

</div>

<div>

### Qué incluye:

- Soporte técnico
- Configuración guiada
- Mejores prácticas
- Visibilidad en la app

</div>

</div>

<div v-click class="mt-8 p-4 bg-green-900 rounded-lg text-center">

**Open source siempre**: cualquiera puede deployar sin permiso.  
El programa facilita el camino.

</div>

---

# Herramientas para Operadores

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 🖥️ Mostrix

Gestioná disputas desde desktop. Sin app móvil.

</div>

<div v-click>

### 🔔 Mostro-watchdog

Bot de Telegram para admins:
- Monitoreo en tiempo real
- Notificaciones de disputas
- Health checks de relays

</div>

<div v-click>

### 📊 Mostro-score-web

Análisis de reputación:
- Fetcha eventos Nostr
- Métricas objetivas
- Transparencia total

</div>

</div>

---

# Challenges Recientes

<div class="grid grid-cols-3 gap-4">

<div v-click>

### 🚀 Onboarding

**Problema**: Fricción al juntar Nostr keys + Lightning wallet  
**Solución**: Embedded wallets en test

</div>

<div v-click>

### 🔔 Notificaciones

**Problema**: Dependencia de FCM/Google  
**Experimento**: Push vía Nostr relays + background sync

</div>

<div v-click>

### 💰 Liquidez

**Problema**: Necesitamos más makers  
**Focus**: LATAM y África

</div>

</div>

---

# Cierre

## ¿Cómo participar?

<div class="grid grid-cols-2 gap-8">

<div>

### Mostro está en:

- ✅ **Mainnet**
- ✅ **Beta global**
- ✅ **mostro.community** recién lanzado

</div>

<div>

### Sumate si:

- Operás P2P y querés ser **maker**
- Tenés una comunidad Bitcoin
- Querés **testear** la app

</div>

</div>

<div class="mt-12 text-center text-2xl">

🌐 **mostro.community**  
💻 **github.com/MostroP2P**

</div>

<div class="mt-8 text-center">

Gracias 🧌

</div>

---

# Preguntas?

<div class="text-center">

🧌 Mostro — P2P Bitcoin sin custodia

mostro.community | github.com/MostroP2P

</div>
