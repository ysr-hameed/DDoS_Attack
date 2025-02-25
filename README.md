# DDoS Attack Script

## Disclaimer
> **This script is for educational and security testing purposes only.** Unauthorized use against any website or server is **illegal** and punishable under cybersecurity laws. Use it only with permission from the server owner.

---

## Features
- High-speed packet sending
- Multi-threading for maximum efficiency
- Target-specific attack customization
- User-friendly command-line interface

---

## Requirements
Ensure you have the following installed on your system before running the script:

- Python 3.x
- `requests` module
- `argparse` module

To install dependencies, run:
```bash
pip install requests argparse
```

---

## How to Use
Follow these steps to use the script:

### Step 1: Clone the Repository
```bash
git clone https://github.com/ysr-hameed/ddos-attack-script.git
cd ddos-attack-script
```

### Step 2: Run the Script
```bash
python ddos.py -t <target_ip> -p <port> -t <threads>
```

### Example Usage
```bash
python ddos.py -t 192.168.1.1 -p 80 -t 100
```

| Parameter | Description |
|-----------|-------------|
| `-t` | Target IP address |
| `-p` | Port number |
| `-t` | Number of threads (higher = more impact) |

---

## Legal & Ethical Usage
Using this script against unauthorized targets is **strictly prohibited**. It should only be used for:
- Penetration testing with permission
- Learning about cybersecurity threats
- Strengthening your own server security

**⚠️ Use responsibly! Misuse can result in legal consequences.**

---

## Author
Created by Yasir Hameed.

For educational and ethical hacking purposes only. 🚀

