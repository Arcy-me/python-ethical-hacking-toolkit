# 🖧 MAC Changer

A simple Python-based MAC address changer for Linux systems.

This tool allows users to modify the MAC address of a network interface directly from the command line using Python and Linux networking utilities.

---

## 📌 Overview

The project was created while learning:
- Python scripting
- Linux networking
- Command-line argument handling
- Subprocess execution
- Regular expressions

The tool automates MAC address modification by interacting with Linux network interfaces using system commands.

---

## ✨ Features

- Change MAC address of a network interface
- Display current MAC address
- Command-line interface support
- Simple and lightweight implementation
- Basic MAC address verification after modification

---

## 🛠 Technologies Used

- Python 3
- Linux Networking Utilities
- `subprocess`
- `optparse`
- `regex`

---

## ⚙ Requirements

- Python 3
- Linux Operating System
- Root / sudo privileges

---

## 🚀 Usage

### Basic Syntax

```bash
sudo python3 mac_changer.py -i <interface> -m <new-mac>
```

### Example

```bash
sudo python3 mac_changer.py -i eth0 -m 00:11:22:33:44:55
```

---

## 📥 Arguments

| Argument | Description |
|----------|-------------|
| `-i` / `--interface` | Network interface name |
| `-m` / `--mac` | New MAC address |

---

## 🧪 Example Output

```text
Current MAC address: 08:00:27:53:8b:db
Changing MAC address for eth0 to 00:11:22:33:44:55
[+] MAC address was successfully changed to 00:11:22:33:44:55
```


---

## 📖 Concepts Practiced

- Python functions
- Argument parsing
- Running Linux commands from Python
- Regular expression matching
- Network interface handling
- Basic automation scripting

---

## ⚠ Disclaimer

This project is created strictly for:
- Educational purposes
- Ethical hacking practice
- Authorized lab environments

Do not use this tool on networks or systems without proper authorization.
