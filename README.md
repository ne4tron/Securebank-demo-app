
# 💳 SecureBank Demo App

A mock iOS banking application built in React to simulate real-world mobile security vulnerabilities. Designed for educational use in mobile penetration testing, reverse engineering, and application security analysis.

---

## 🔍 About

This application was developed as part of a simulated black-box iOS penetration test. It replicates multiple critical vulnerabilities commonly found in mobile apps, including:

- Hardcoded API keys  
- Bypassable authentication logic  
- Insecure data storage  
- Missing SSL pinning  
- Weak jailbreak detection

---

## 🚀 Features

- 🔐 Simulated login with bypassable logic  
- 📊 Dashboard with account balance and user info  
- 📁 User data stored in plaintext for inspection  
- ⚠️ No SSL/TLS or certificate pinning  
- 🎯 Designed for Frida, Burp Suite, MobSF, Objection, and Ghidra testing

---

## 🛠️ Installation

### Prerequisites

- Node.js (v18 or newer recommended)  
- npm or yarn

### Steps

```bash
git clone https://github.com/NE4TRON/securebank-demo-app.git
cd securebank-demo-app
npm install
npm start
