# Network-Scanner-
Python NetScan is a lightweight Python tool for discovering active devices on a network. It uses ICMP ping and multithreading to scan efficiently. The tool supports automatic and manual network input, works across platforms, and outputs active hosts. Ideal for learning network scanning and building foundational cybersecurity skills.

🔍 Python NetScan (Network Scanner)

📌 Overview

Python NetScan is a lightweight network scanning tool designed to identify active devices within a network.
It uses ICMP (ping) requests and multithreading to quickly discover online hosts.

This project is built for:

🧠 Learning purposes
🔐 Basic cybersecurity practice
🧪 Network testing in controlled environments

⚙️ Features:

🌐 Automatic local network detection
📡 Ping-based host discovery
⚡ Multithreaded scanning (fast execution)
🖥️ Cross-platform support (Windows/Linux/macOS)
🧾 Simple command-line interface
📋 Sorted output of active hosts


📦 Technologies Used:
Python 3

Standard Libraries:
1.socket
2.ipaddress
3.subprocess
4.platform
5.concurrent.futures
5.re
6.sys

🚀 Installation
1. Clone the Repository
git clone https://github.com/yuvanshankar-work/Network-Scanner-.git
cd python-netscan
2. Run the Script
python netscan.py

🧪 Usage
Scan Local Network
python netscan.py

Scan Specific Network
python netscan.py 192.168.1.0/24

Shorthand Input
python netscan.py 192.168.1

Help Menu
python netscan.py -h

📋 Example Output
Scanning network: 192.168.1.0/24

Online hosts:
192.168.1.1
192.168.1.5
192.168.1.10

⚠️ Disclaimer:

1.This tool is intended only for educational purposes
2.Do NOT use on networks without proper authorization
3.The author is not responsible for any misuse or damage

🚫 Legal Notice:

Unauthorized network scanning may violate laws and regulations.
Always ensure you have permission before scanning any network.

⚠️ Limitations:

Detects only online hosts (not open ports)
May fail if:
    ICMP is blocked
    Firewall restrictions exist
Not suitable for enterprise-scale scanning

🚀 Future Improvements:

🔍 TCP/UDP Port Scanning:
🖼️ GUI Interface
📊 Scan Reports (CSV/JSON)
🧠 OS Detection (Fingerprinting)
📡 Advanced Network Mapping
