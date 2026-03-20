

---

# z-Tool – Python Multitool

**Educational & entairnement purposes only**

---

## 📖 Overview

**z-Tool** is a Python-based multitool that groups several utilities related to:

* OSINT (Open-Source Intelligence)
* basic network analysis
* website information gathering
* data inspection tools

The goal of the project is to **experiment with Python, networking, and automation** while learning how different security-related utilities work in practice.

This project is primarily intended for **learning, experimentation, and terminal-based workflows**.

---

## 🧰 Tool List

Below is a quick overview of the features currently available in **z-Tool**.
Got it. Since these are the **actual 30 menu items in your script**, I’ll rewrite a **clean README section** that matches them exactly. I’ll keep it **clear, professional, and GitHub-friendly** without adding unsafe instructions.

You can replace your current **tool table** with this.

---

# 🧰 Tool List

z-Tool contains **30 utilities** organized into three categories:

## 📂 Tool Categories

### ⚔️ Attack

Modules focused on network interaction and experimental demonstrations.

### 🔎 OSINT

Tools used to gather publicly available information.

### 🛡️ Pentest

Utilities designed to test and analyze security configurations.

---

Below is a quick description of each module.

| #      | Tool                  | Category | Description                                                                                    |
| ------ | --------------------- | -------- | ---------------------------------------------------------------------------------------------- |
| **01** | IP Info               | Attack   | Retrieves information about an IP address and can perform a basic port scan.                   |
| **02** | DDOS Attack           | Attack   | Sends large numbers of HTTP requests to test server stability and response handling.           |
| **03** | Link Grabber          | Attack   | Generates a link capable of collecting visitor network information.                            |
| **04** | Phishing Twitter      | Attack   | Demonstration login page styled after Twitter/X for educational testing environments.          |
| **05** | Phishing Instagram    | Attack   | Demonstration login page styled after Instagram.                                               |
| **06** | Mini RAT              | Attack   | Experimental client-server command system demonstrating remote command execution architecture. |
| **07** | Nitro Generator       | Attack   | Generates random Discord Nitro-style codes for demonstration purposes.                         |
| **08** | Bot Deleter (Discord) | Attack   | Utility designed to manage or remove bots from a Discord server environment.                   |
| **09** | Stealer (ngrok)       | Attack   | Demonstration data-collection endpoint exposed through an ngrok tunnel.                        |
| **10** | Stealer (Discord)     | Attack   | Demonstration module showing how authentication tokens could be collected and transmitted.     |
| **11** | Username Tracker      | OSINT    | Searches multiple websites for a specific username.                                            |
| **12** | Phone Tracker         | OSINT    | Retrieves metadata from phone numbers such as carrier and country.                             |
| **13** | Email Tracker         | OSINT    | Checks whether an email address appears on certain services.                                   |
| **14** | ID Tracker            | OSINT    | Attempts to locate a user ID across supported platforms.                                       |
| **15** | Bot Controller        | OSINT    | Command-line interface used to control connected bots or agents.                               |
| **16** | Metadata for Image    | OSINT    | Extracts EXIF metadata from image files.                                                       |
| **17** | Create Report         | OSINT    | Generates structured reports containing gathered information.                                  |
| **18** | Google Dork           | OSINT    | Generates advanced search queries for finding publicly indexed information.                    |
| **19** | TechInt               | OSINT    | Detects technologies used by a website (hosting, CMS, server stack).                           |
| **20** | Directory Fuzzer      | OSINT    | Attempts to discover hidden directories on a web server.                                       |
| **21** | XSS Search            | Pentest  | Tests web pages for possible Cross-Site Scripting vulnerabilities.                             |
| **22** | SQL Search            | Pentest  | Tests forms and URLs for SQL injection vulnerabilities.                                        |
| **23** | Vulnerability Search  | Pentest  | Searches known vulnerability databases related to detected technologies.                       |
| **24** | Scanner Web           | Pentest  | Performs a general security scan of a target website.                                          |
| **25** | Alt-Scan              | Pentest  | Additional scanning module used for network or website analysis.                               |
| **26** | Wifi-Scanner          | Pentest  | Scans nearby Wi-Fi networks and displays available information.                                |
| **27** | FireWall Search       | Pentest  | Attempts to detect firewall or web-application-firewall technologies.                          |
| **28** | File Scan             | Pentest  | Scans files for suspicious patterns or potential malware signatures.                           |
| **29** | Update                | Utility  | nothing for now.                                                              |
| **30** | Contact               | Utility  | My contact.                                                |

---





## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/cameleonnbss/z-tool
cd z-tool
pip install -r requirements.txt
```

If installing manually:

```bash
pip install phonenumbers
pip install requests
pip install discord.py
pip install flask
pip install colorama
pip install pillow
pip install pyinstaller
pip install pyngrok
pip install pyqt5
pip install beautifulsoup4
pip install reportlab
pip install python-magic-bin
pip install pefile
pip install lxml
pip install urllib3
pip install pypdf2
pip install pywin32
pip install cryptography
pip install psutil
```

---

## ▶ Running the Tool

Launch the main script:

```bash
python z-toolV1.py
```

You will see the **terminal menu** where you can select tools from **01 to 30**.

---

## 🎓 Educational Purpose

This project exists to help practice:

* Python scripting
* terminal-based tools
* networking concepts
* OSINT techniques
* basic security testing workflows

---

## 🙏 Credits

Many assets and design were provided by:

**AltWolf**

---

## ⚖️ Disclaimer

This project is provided **for educational and ethical research purposes only**.

Do **not** use this software against systems or individuals without explicit authorization.

The author assumes **no responsibility for misuse or damages** caused by this tool.

---

## 📄 License

MIT License
© 2026 camzzz

---

