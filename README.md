# MAC Address Changer (Python)

## Overview
Small Python utility to change the MAC address of a network interface.  
Designed for **educational and lab use** (privacy testing, network lab experiments). Not intended for misuse.

---

## ⚠️ Legal & Safety Notice
Use this tool **only** on machines and networks you own or have explicit permission to test.  
Misuse (impersonating devices, bypassing network controls, evading monitoring) is illegal and unethical.

---

## Features
- Change MAC address for a specified network interface.
- Option to set a random MAC or provide a custom MAC.
- Works on Linux (requires root). (Notes about other OS support below)

---

## Requirements
- Python 3.6+
- Linux (tested on Ubuntu). Root privileges required to change MAC.
- Optional: `macchanger` package if you prefer using system tool.

---

## Installation
```bash
git clone https://github.com/YOUR_USERNAME/mac-changer-python.git
cd mac-changer-python
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt   # if any
