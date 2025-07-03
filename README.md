
# 🏦 SecureBank iOS Demo App

**SecureBank** is a deliberately vulnerable mobile banking app built with React Native for iOS. It is designed for educational purposes in mobile penetration testing, reverse engineering, and secure coding practices.

---

## 🔍 About

This app simulates a mobile banking environment and includes a variety of common mobile security vulnerabilities:

- 🔑 Hardcoded API keys and credentials
- 🔓 Bypassable login logic
- 📁 Insecure data storage (plaintext)
- 🔐 No SSL/TLS or certificate pinning
- 📱 Weak jailbreak/root detection

---

## 🚀 Features

- Simulated login screen with weak authentication
- Dashboard with fake account info
- Local storage of sensitive user data in plaintext
- Hardcoded secrets for key management testing
- Designed for testing with Frida, MobSF, Burp Suite, Objection, and Ghidra

---

## ⚙️ Installation (Linux / Android)

```bash
# Install dependencies
sudo apt update && sudo apt install -y openjdk-17-jdk wget unzip

# Download and unzip
wget <replace_with_your_link> -O SecureBank.zip
unzip SecureBank.zip && cd SecureBank

# Install React Native CLI and project deps
npm install -g react-native-cli
npm install

# ▶️ Run the app on an Android device or emulator
npx react-native run-android

