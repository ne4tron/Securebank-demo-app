# 🏦 SecureBank iOS/Android Demo App

**SecureBank** is a deliberately vulnerable mobile banking application built with React Native. Designed for **educational use only**, it simulates real-world security flaws found in mobile apps to help security professionals practice penetration testing, reverse engineering, and secure coding techniques.

---

## 🔍 Overview

SecureBank simulates the front end of a banking application with intentionally insecure features. It provides a safe environment to learn and test tools and techniques against:

- Mobile app vulnerabilities
- Weak security design patterns
- Realistic penetration testing scenarios

---

## ⚠️ Disclaimer

> **This project is intentionally insecure and should be used for learning and authorized testing only. Do NOT deploy or connect to real services or use with real credentials.**

---

## 📦 Features

- 🔐 **Simulated Login**: Bypassable hardcoded authentication
- 🔑 **Hardcoded API Keys**: In plaintext within app files
- 📁 **Insecure Local Storage**: Plaintext in AsyncStorage
- 🌐 **No SSL Pinning**: Allows MITM traffic inspection
- 🔍 **Weak Jailbreak Detection**: Easily bypassed
- 🎯 Designed for testing with:
  - Frida
  - Objection
  - MobSF
  - Burp Suite
  - Ghidra

---

## 🛠️ Technologies Used

- [React Native](https://reactnative.dev/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- [React Navigation](https://reactnavigation.org/)

---

## 🚀 Getting Started

### ✅ Prerequisites (Linux + Android)

- Node.js & npm
- Java JDK 17+
- Android Studio with SDK & emulator

### 📥 Install & Run

```bash
# Install system dependencies
sudo apt update && sudo apt install -y openjdk-17-jdk wget unzip

# Download project
wget <replace_with_your_zip_or_clone_link> -O SecureBank.zip
unzip SecureBank.zip && cd SecureBank

# Install React Native CLI and dependencies
npm install -g react-native-cli
npm install

# Start on Android device/emulator
npx react-native run-android








