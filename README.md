
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


# 📦 Install system dependencies
sudo apt update && sudo apt install -y openjdk-17-jdk wget unzip

# 📁 Download and unzip the SecureBank project
wget https://sandbox:/mnt/data/SecureBank.zip -O SecureBank.zip
unzip SecureBank.zip && cd SecureBank

# 📦 Install Node and React Native CLI (if not already installed)
npm install -g react-native-cli

# 📦 Install project dependencies
npm install

# ✅ Start Metro bundler in a separate terminal (optional)
# npx react-native start

# ▶️ Run the app on an Android device or emulator
npx react-native run-android

📌 Notes

Ensure Android Studio is installed with an emulator or connect an Android device with USB debugging enabled.

If using a physical device, run adb devices to confirm it's recognized.

If you want a backend mock API server, I can provide one too.


