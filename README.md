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

 📸 Project Screenshots

1. About Phone
![About Phone](Screenshots/01_about%20phone.jpeg)

2️. Version
![Version](Screenshots/02_version.jpeg)

3️. Developer Option
![Developer Option](Screenshots/03_developer%20option.jpeg)

 4️. Wireless Debugging
![Wireless Debugging](Screenshots/04_wireless%20debugging.jpeg)

5️. ADB Pair
![ADB Pair](Screenshots/05_adb%20pair.png)

6️. ADB Devices
![ADB Devices](Screenshots/06_adb%20devices.png)

7️. ADB Shell
![ADB Shell](Screenshots/07_adb%20shell.png)

8️. Ifconfig
![Ifconfig](Screenshots/08_ifconfig.png.png)

9️. SD Card
![SD Card](Screenshots/08_sdcard.png)

10. LS Command
![LS](Screenshots/09_ls.png)

11. PWD
![PWD](Screenshots/10_pwd.png.png)

12. Whoami
![Whoami](Screenshots/11_whoami.png.png)

13. PS -A
![PS -A](Screenshots/12_ps-A.png.png)

14. ID Command
![ID](Screenshots/13_id.png)
