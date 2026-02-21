Android Debugging & Shell Access using ADB

Android Debug Bridge wireless connection and shell access project using Kali Linux and Physical devices.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Tool](https://img.shields.io/badge/Tool-ADB-blue)
![Environment](https://img.shields.io/badge/OS-Kali%20Linux-black)
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

- windows (Host System)
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

3.Go to Cmd from ADB Platform tool[download from github]

️4. Establish ADB Connection
bash
adb pair <ip>:<port>
adb devices

5. Access Shell:
adb shell

6.Execute Investigation Commands:

commands:
whoami
pwd
ps -A
ip addr

 📸 Project Screenshots


1. About Phone
<p align="center">
  <img src="Screenshots/01_about%20phone.jpeg" width="300">
</p>

2. Version
<p align="center">
  <img src="Screenshots/02_version.jpeg" width="300">
</p>

3. Developer Option
<p align="center">
  <img src="Screenshots/03_developer%20option.jpeg" width="300">
</p>

4. Wireless Debugging
<p align="center">
  <img src="Screenshots/04_wireless%20debugging.jpeg" width="300">
</p>

5. ADB Pair
<p align="center">
  <img src="Screenshots/05_adb%20pair.png" width="300">
</p>

6. ADB Devices
<p align="center">
  <img src="Screenshots/06_adb%20devices.png" width="300">
</p>

7. ADB Shell
<p align="center">
  <img src="Screenshots/07_adb%20shell.png" width="300">
</p>

8. Ifconfig
<p align="center">
  <img src="Screenshots/08_ifconfig.png.png" width="300">
</p>

9. SD Card
<p align="center">
  <img src="Screenshots/08_sdcard.png" width="300">
</p>

10. LS Command
<p align="center">
  <img src="Screenshots/09_ls.png" width="300">
</p>

11. PWD
<p align="center">
  <img src="Screenshots/10_pwd.png.png" width="300">
</p>

12. Whoami
<p align="center">
  <img src="Screenshots/11_whoami.png.png" width="300">
</p>

13. PS -A
<p align="center">
  <img src="Screenshots/12_ps-A.png.png" width="300">
</p>

14. ID Command
<p align="center">
  <img src="Screenshots/13_id.png" width="300">
</p>

