# 🔍 PortScanner

## 📌 Description

**PortScanner** is a lightweight tool designed to analyze open ports on a **private IP address within a local network**. It helps network administrators, students, and cybersecurity enthusiasts quickly identify exposed services on internal devices.

⚠️ **Disclaimer:** This tool is intended for educational purposes and for use on networks you own or have explicit permission to test.

---

## 🌍 Multilingual Description

### 🇬🇧 English

A simple Python-based tool to scan and analyze open ports of a private IP address on a local network.

### 🇮🇹 Italiano

Uno strumento semplice basato su Python per scansionare e analizzare le porte aperte di un indirizzo IP privato all'interno di una rete locale.

### 🇫🇷 Français

Un outil simple basé sur Python pour analyser les ports ouverts d'une adresse IP privée sur un réseau local.

### 🇪🇸 Español

Una herramienta sencilla basada en Python para analizar los puertos abiertos de una dirección IP privada en una red local.

---

## ⚙️ Features

* Scan a single target IP
* Scan a range of ports
* Fast and lightweight
* Easy to use via command line

---

## 🚀 How to Use

Make sure you have **Python 3** installed on your system.

You can copy and use the following commands:

```bash
 python3 portScanner.py -t 192.168.1.1 -p 1-100
 python3 portScanner.py -t 192.168.1.1 -p 80
 python3 portScanner.py -t scanme.nmap.org -p 22,80,443

```
## 📦 Dependencies

This tool requires **Python 3** and the following dependency:

- `termcolor`

### Install dependency

```bash
pip3 install termcolor

---

## 📂 Project Structure

```
PortScanner/
│── PortScanner.py
│── README.md
```

---

## 🛡️ Legal Notice

This software must only be used for **authorized testing and educational purposes**. The author is not responsible for misuse or damage caused by this tool.

---

## ⭐ Contributions

Contributions, issues, and feature requests are welcome. Feel free to fork this repository and submit a pull request.

---

## 👤 Author

Created by **Sergio González Sabucedo**.

---

## 📜 License

This project is licensed under the MIT License.
