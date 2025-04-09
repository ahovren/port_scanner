# Port Scanner

**Port Scanner** is a Python-based network scanning application built with `tkinter` and `python-nmap`.  
It provides a clean graphical interface for conducting stealth SYN scans (`-sS`), service and version detection (`-sV`), and multi-target scanning—all with real-time feedback and report generation.

---

## Key Features

-  Multi-target scanning (IP or hostname)
-  Stealth SYN scans (`-sS`) using Nmap
-  Service and version detection (`-sV`)
-  Graphical User Interface built with `tkinter`
-  Real-time scan output in the GUI
-  Progress bar for scan tracking
-  Start and stop scan controls
-  Automatically saves results in `.txt` and `.json` formats

---

## Requirements

- Python 3.11.9
- [Nmap](https://nmap.org/download.html) installed and added to system PATH
- Python packages:
  ```bash
  pip install python-nmap
