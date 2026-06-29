🔍 Simple Network Port Scanner
A basic Python-based Network Port Scanner built for cybersecurity learning and internship projects.
---
📌 Project Overview
This tool scans a target IP address or hostname and checks which ports are open within a given range. It helps understand basic networking and how services listen on ports.
---
⚙️ How It Works
The scanner uses Python’s built-in `socket` library.
Working Principle:
A TCP connection is attempted to each port.
If the connection is successful → port is OPEN
If it fails → port is CLOSED
The process repeats for all ports in the given range.
Key Function Used:
`socket.connect_ex((host, port))`
Result Logic:
Returns `0` → PORT OPEN
Returns non-zero → PORT CLOSED
---
🚀 Features
Scan any IP or hostname
Custom port range (start–end)
Fast lightweight scanning
No external libraries required
---
🧰 Requirements
Python 3.x
Built-in library: `socket`
No external packages required.
---
📦 Installation
```bash
git clone https://your-repo-link.git
cd port-scanner
