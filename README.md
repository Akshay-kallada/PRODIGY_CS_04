## 📖 Overview

This project demonstrates the fundamentals of keystroke logging using Python and the `pynput` library. Built for ethical and educational use, it helps learners understand how input capture works at the operating system level, while promoting awareness around privacy and security boundaries.

> ✅ All testing and execution must be performed within authorized environments, such as virtual machines or consent-based lab setups.

---

## 🎯 Objectives

- 🔍 Understand OS-level input capturing
- 🧰 Implement a simple keylogger using Python
- 📝 Log keystrokes to a plain text file
- ✅ Practice safe development using a virtual environment (PEP 668 compliant)

---

## ⚙️ Setup Instructions

### ✅ Recommended Environment: Kali Linux (2024+) / Linux / Windows (Using Virtualenv)

### 1. Clone the Repository

```bash
git clone https://github.com/Jetlin_Figarez/PRODIGY_CS_04_Simple-Keylogger.git
cd PRODIGY_CS_04_Simple-Keylogger

Create and Activate Virtual Environment
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

Install Dependencies
pip install pynput

Run the Keylogger
python keylogger.py

📁 Project Structure
File/Folder	Description
keylogger.py	Main Python script for keylogging
README.md	This documentation file

🧪 Example Output (keylog.txt)
h e l l o [Key.space] w o r l d [Key.enter]

✅ Ethical Guidelines
This tool is developed strictly for:

🧪 Ethical hacking labs

🎓 Cybersecurity training & simulations

🧑‍🏫 Academic or research environments with permission

❌ Prohibited Uses
🔍 Unauthorized surveillance

👀 Spying on other users

💻 Deploying on devices without explicit consent

🚨 Violations can result in legal consequences and are against ethical cybersecurity standards.

🧠 Learning Outcomes
By completing this task, you will:

🧠 Understand how keyloggers work and the risks they pose

🔧 Gain practical experience with Python input listeners

🛡️ Learn how to work safely in virtual environments on secure systems