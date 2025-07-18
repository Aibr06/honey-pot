# Basic Honeypot

This is a simple Python honeypot that listens on a fake port and logs connection attempts.  
It helps you detect when someone tries to connect to your system.

---

## ✅ Features
- Listens on a chosen port (default: 2222)
- Shows the IP address and time of each connection
- Sends a fake response to the client
- Stops safely when you press `Ctrl + C`

---

## 🛠 Requirements
- Python 3 (no extra libraries needed)

---

## 🚀 How to Run
1. Open your terminal.
2. Run the script:
   ```bash
   python3 basic-honwypot.py
You’ll see:

csharp
Copy
Edit
[+] Honeypot is listening on 0.0.0.0:2222
