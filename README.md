<div align="center">

  <!-- Animated Typing SVG Header Banner -->
  <a href="https://sachinmandawi.github.io/panthernote/">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=700&size=38&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=800&height=70&lines=PantherNote;Zero-Knowledge+Password+Manager;Local-First+AES-256-GCM+Encryption;Private+GitHub+DB+Vault+Sync;Built-in+2FA+Authenticator" alt="PantherNote Animated Title" />
  </a>

  <p align="center">
    <strong>🔒 Your digital life, locked, local, and zero-knowledge encrypted.</strong>
  </p>

  <p align="center">
    <a href="https://sachinmandawi.github.io/panthernote/"><img src="https://img.shields.io/badge/🚀_Live_Web_App-sachinmandawi.github.io%2Fpanthernote-8b5cf6?style=for-the-badge&logo=rocket" alt="Live App"></a>
    <a href="https://github.com/sachinmandawi/panthernote/releases/download/v1.0.0/PantherNote-Setup-1.0.0.exe"><img src="https://img.shields.io/badge/📥_Download-Windows_Installer_(.exe)-2563eb?style=for-the-badge&logo=windows" alt="Download Windows Installer"></a>
    <a href="https://github.com/sachinmandawi/panthernote/releases/download/v1.0.0/PantherNote-Portable.exe"><img src="https://img.shields.io/badge/⚡_Download-Portable_EXE-059669?style=for-the-badge&logo=windows" alt="Download Portable EXE"></a>
  </p>

  <p align="center">
    <a href="https://github.com/sachinmandawi/panthernote/releases/latest"><img src="https://img.shields.io/github/v/release/sachinmandawi/panthernote?style=for-the-badge&color=8b5cf6&logo=github" alt="Latest Release"></a>
    <a href="https://github.com/sachinmandawi/panthernote/stargazers"><img src="https://img.shields.io/github/stars/sachinmandawi/panthernote?style=for-the-badge&color=8b5cf6&logo=github" alt="Stars"></a>
    <a href="https://github.com/sachinmandawi/panthernote/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-10b981?style=for-the-badge" alt="License"></a>
  </p>

  <p align="center">
    <a href="#-about-panthernote"><strong>About</strong></a> •
    <a href="#-application-screenshots--ui-showcase"><strong>Screenshots</strong></a> •
    <a href="#-key-features"><strong>Features</strong></a> •
    <a href="#-security-architecture"><strong>Security Specs</strong></a> •
    <a href="#-tech-stack"><strong>Tech Stack</strong></a> •
    <a href="#-license"><strong>License</strong></a>
  </p>

</div>

---

> [!IMPORTANT]
> 🛡️ **Zero-Knowledge Guarantee**: Your Master Password and unencrypted vault items **NEVER** leave your browser or computer. All cryptographic encryption and decryption operations occur purely on your local device using the browser's native **Web Crypto API (SubtleCrypto)**.

---

## 📖 About PantherNote

**PantherNote** is a privacy-first, zero-knowledge digital vault and password manager crafted for individuals who value total ownership of their sensitive data.

Traditional cloud password managers store user vaults on proprietary servers that can be targeted by centralized breaches. **PantherNote eliminates the middleman entirely:**

- **Zero Centralized Servers**: Your encrypted ciphertext syncs directly to your own private GitHub repository (<code>panthernote-db</code>). Nobody—not even GitHub—can read your data without your master password.
- **True Zero-Knowledge**: Your master password never leaves your browser memory. Encryption keys are derived client-side via **PBKDF2 SHA-256** with **100,000 iterations**.
- **All-in-One Identity Vault**: Seamlessly manage **Logins**, **Debit & Credit Cards (with interactive 3D flip preview)**, **Bank Accounts**, **Secure Notes**, **Custom Categories**, and **Live 2FA TOTP Authenticator Codes**.

---

## 📸 Application Screenshots & UI Showcase

<div align="center">

### 1️⃣ Main Vault & Credentials Overview
<img src="screenshots/1-All%20Items.png" alt="All Items Overview" width="95%" />

<br />

### 2️⃣ 3D Interactive Debit & Credit Cards
<img src="screenshots/2-Debit%20Cards.png" alt="Debit Cards" width="95%" />

<br />

### 3️⃣ Built-in Live 2FA TOTP Authenticator
<img src="screenshots/3-2FA%20Authenticator.png" alt="2FA Authenticator" width="95%" />

<br />

### 4️⃣ Smart Password & Passphrase Generator
<img src="screenshots/4-Generator.png" alt="Password Generator" width="95%" />

<br />

### 5️⃣ Security & Health Audit Scanner
<img src="screenshots/5-Health%20Audit.png" alt="Health Audit" width="95%" />

<br />

### 6️⃣ Settings, Encryption Keys & Backup Options
<img src="screenshots/6-Settings%20and%20Backup.png" alt="Settings and Backup" width="95%" />

<br />

### 7️⃣ Zero-Knowledge Master Password Unlock Screen
<img src="screenshots/7-Login%20Screen.png" alt="Login Screen" width="95%" />

<br />

### 8️⃣ Add New Vault Item Modal (Logins, Cards, Banks, Notes)
<img src="screenshots/8-Add%20New%20Vault%20Item.png" alt="Add New Vault Item" width="95%" />

</div>

---

## ✨ Key Features

<table>
  <tr>
    <td width="50%">
      <h3>🔐 Zero-Knowledge Cryptography</h3>
      <p>Military-grade <strong>AES-256-GCM</strong> encryption with <strong>PBKDF2 SHA-256</strong> (100,000 iterations). Your raw master key is never transmitted or saved anywhere.</p>
    </td>
    <td width="50%">
      <h3>☁️ Private GitHub DB Sync</h3>
      <p>Synchronizes encrypted vault data directly to your private GitHub repository (<code>panthernote-db/vault.json</code>). GitHub only ever receives scrambled ciphertext.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔑 Built-in 2FA Authenticator</h3>
      <p>Integrated live TOTP generator with 30-second countdown ring timers. Calculate RFC 6238 6-digit 2FA codes for all your accounts directly inside PantherNote.</p>
    </td>
    <td width="50%">
      <h3>🛡️ Security & Health Audit</h3>
      <p>Proactive security scanner detects weak, reused, or stale (90+ day old) passwords with instant health score feedback and zero plaintext leakage.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎨 Smart Brand Auto-Detection</h3>
      <p>Instant brand recognition for 100+ popular services, credit cards, and banks (Google, GitHub, Supabase, HDFC, SBI, PayPal) with custom brand palettes.</p>
    </td>
    <td width="50%">
      <h3>⚡ Smart 1-Tap Copy & Bulk Tools</h3>
      <p>Instant 1-tap copy for usernames, passwords, card numbers, and CVV codes with haptic toast notifications and zero text selection handles.</p>
    </td>
  </tr>
</table>

---

## 🛡️ Security Architecture

```mermaid
flowchart TD
    A["🔑 User Enters Master Password"] --> B["⚡ Web Crypto API (PBKDF2 SHA-256, 100k iterations)"]
    B --> C["🔐 Derive 256-bit AES Key"]
    C --> D{"Valid Key Verifier?"}
    D -->|Yes| E["🔓 Decrypt Local AES-256-GCM Vault Payload"]
    D -->|No| F["🚫 Lock Vault & Reject Access"]
    E --> G["📱 Render Decrypted Vault Items in UI"]
    G -->|On Vault Save| H["🔒 Encrypt Payload Locally (AES-256-GCM + 12-byte IV)"]
    H --> I["☁️ Sync Encrypted Ciphertext to Private Repo: panthernote-db"]
```

### 🔒 Cryptographic Specifications:
| Parameter | Specification | Purpose |
| :--- | :--- | :--- |
| **Cipher Algorithm** | `AES-256-GCM` | Authenticated symmetric encryption for vault records |
| **Key Derivation Function** | `PBKDF2 SHA-256` | Derives 256-bit key from Master Password |
| **Iteration Count** | `100,000 rounds` | Defense against brute-force & dictionary attacks |
| **Initialization Vector (IV)** | `12-byte CSPRNG` | Unique random IV per encryption payload |
| **Security Layer** | `Web Crypto SubtleCrypto` | Native hardware-accelerated browser cryptography |

---

## 💻 Tech Stack

<div align="center">

| Layer | Technology | Details |
| :--- | :--- | :--- |
| **Frontend Core** | `HTML5` / `Vanilla JavaScript (ES2024)` | High-performance SPA with zero heavyweight framework overhead |
| **Styling Engine** | `Vanilla CSS3` | Dark Glassmorphic Design System with fluid dynamic micro-animations |
| **Cryptography** | `Web Crypto API (SubtleCrypto)` | Native browser-based `AES-256-GCM` & `PBKDF2 SHA-256` |
| **Cloud Gatekeeper** | `Cloudflare Worker / Gatekeeper` | OAuth 2.0 PKCE authentication flow & zero-knowledge API proxy |
| **Vault Storage** | `GitHub REST API v3` | Encrypted JSON sync in user's private `panthernote-db` repository |
| **Icon System** | `FontAwesome 6 Free` | High-definition scalable vector UI icons |

</div>

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/sachinmandawi/panthernote.git
cd panthernote
```

### 📱 Desktop App
A standalone Windows desktop application (`PantherNote.exe`) is available locally under `d:\panthernote-desktop-app\dist\`.

---

## 🔒 Privacy & Open Source Guarantee

- **Zero Telemetry**: PantherNote does NOT track user actions, record analytics, or log IP addresses.
- **Client-Side Encryption**: Your master password never leaves your browser device.
- **100% Auditability**: All source code is completely open-source for full transparency.

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more details.

<div align="center">
  <br />
  <sub>Crafted with ❤️ for total privacy & security. Powered by PantherNote.</sub>
</div>
