# 🔐 MAC Address Changer

A lightweight Python tool to modify network interface MAC addresses in authorized environments.

---

## 📌 Overview

This tool allows you to:

- Change the MAC address of a specified network interface
- Verify whether the change was successful
- Perform quick MAC spoofing for testing scenarios  

Designed for educational purposes and penetration testing labs.

---

## ⚙️ Features

- CLI-based interface  
- Regex-based MAC verification  
- Simple and minimal dependency usage  
- Linux compatible  

---

## 🚀 Usage

```bash
sudo python3 mac_changer.py -i eth0 -m 00:11:22:33:44:55

```
Parameters

| Flag | Description                           |
| ---- | ------------------------------------- |
| `-i` | Network interface (e.g., eth0, wlan0) |
| `-m` | New MAC address                       |


🧠 Requirements

- Python 3
- Linux system
- Root privileges
- ifconfig installed

🔍 Example Output
- [+] Changing MAC address for eth0 to 00:11:22:33:44:55
- [+] MAC address successfully changed
