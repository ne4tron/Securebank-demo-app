# 🏦 SecureBank iOS Demo App

**SecureBank** is a deliberately vulnerable iOS mobile banking app built with **React Native**. Designed for **educational use in iOS penetration testing**, this app simulates real-world flaws found in iOS applications, making it perfect for training with Frida, Objection, and MobSF.

---

## ⚠️ Disclaimer

> This app is **intentionally insecure**. It is for **educational** and **authorized testing** only. Do **not** connect to real banking APIs, use real credentials, or deploy in production environments.

---

## 📱 Purpose

SecureBank replicates vulnerable logic and insecure storage patterns commonly seen in iOS applications to support security researchers, students, and red teams.

Built to be tested with:

- 🧬 [Frida](https://frida.re/)
- 🔍 [Objection](https://github.com/sensepost/objection)
- 🧰 [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
- 📡 [Burp Suite](https://portswigger.net/burp)
- 🧠 [Ghidra](https://ghidra-sre.org/)

---

## 🚨 Key Vulnerabilities Simulated

| Vulnerability        | Description                                                       |
|----------------------|-------------------------------------------------------------------|
| 🔐 Hardcoded Secrets | API keys and credentials embedded directly in source code         |
| 🔓 Login Bypass      | Authentication logic handled entirely on the client               |
| 📁 Insecure Storage  | Sensitive user data stored in plaintext in AsyncStorage           |
| 🧾 No SSL Pinning    | API traffic uses HTTP; no certificate validation                  |
| 📱 Jailbreak Bypass  | Detection logic trivially bypassable using Frida or Objection     |

---

## 🚀 Getting Started (macOS for iOS only)

### ✅ Prerequisites

- macOS with [Xcode](https://developer.apple.com/xcode/) installed
- [Node.js](https://nodejs.org/)
- [CocoaPods](https://guides.cocoapods.org/using/getting-started.html): `sudo gem install cocoapods`
- [React Native CLI](https://reactnative.dev/docs/environment-setup) (`npm install -g react-native-cli`)

### ⚙️ Setup & Run

```bash
# Clone the repo
git clone https://github.com/your-username/SecureBank.git
cd SecureBank

# Install Node dependencies
npm install

# Install iOS native dependencies
cd ios && pod install && cd ..

# Run the app on iOS simulator
npx react-native run-ios










