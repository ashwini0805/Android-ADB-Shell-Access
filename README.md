Android Debugging & Shell Access using ADB

Android Debug Bridge wireless connection and shell access project using Kali Linux and Genymotion.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Tool](https://img.shields.io/badge/Tool-ADB-blue)
![Environment](https://img.shields.io/badge/OS-Kali%20Linux-black)
![Emulator](https://img.shields.io/badge/Emulator-Genymotion-orange)
![Domain](https://img.shields.io/badge/Domain-Mobile%20Security-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

📌 Project Overview

This project demonstrates how to establish a wireless debugging connection with an Android device using ADB and gain shell access for system-level inspection and analysis.

 🎯 Objectives

- Understand how ADB works
- Establish wireless pairing with Android device
- Access Android shell environment
- Execute Linux-based system commands
- Analyze processes and network configuration

🛠 Tools & Environment

- Kali Linux (Host System)
- Android Debug Bridge (ADB)
- Physical Android Device: OPPO A3 Pro 5G
- Wireless Debugging Enabled


In a cybersecurity lab environment, a mobile security analyst remotely connects to an Android device to perform system inspection using ADB wireless debugging. Shell access is obtained to examine running processes, user context, and network configuration.

🚀 Implementation Steps
1. Enable Developer Options
- Navigate to Settings → About Phone
- Tap Build Number multiple times
- Enable Developer Mode

️2. Enable Wireless Debugging
- Go to Developer Options
- Enable Wireless Debugging
- Pair device using pairing code

️3. Establish ADB Connection
bash
adb pair <ip>:<port>
adb devices

4. Access Shell:
adb shell

5.Execute Investigation Commands:

commands:
whoami
pwd
ps -A
ip addr
