# z‑Tool – File Scanner  
*For entairnement and educational purposes only*  

## 📖 Overview | Aperçu (français)

z‑Tool is a lightweight Python multitool focused on osint and other things .  


---

## 🛠️ What each tool does

Below is a **quick‑reference table** that maps every menu entry (01 – 30) to the feature it launches, a one‑liner description and a short “how‑to‑use” note (what you have to type or what arguments are expected).

| # | Feature | Short Description | How To Use |
|---|---------|--------------------|------------|
| 01 | **IP Info** | Shows geolocation, ASN & hostname for a given IP address. | `./feature_01.py <ip>` (or run from the menu and type an IP). |
| 02 | **DDOS Attack** | Simple script to send UDP packets at high speed to flood a target host. | `python ddos_attack.py <host> <port> <threads>` – hit *Enter* after each input. |
| 03 | **Link Grabber** | Extracts all URLs from the clipboard or a supplied text file. | `link_grabber.py` → paste/clips or give `-f path/to/file.txt`. |
| 04 | **Phishing Twitter** | Generates a fake “follow” link to trick a target into visiting. | Run the script; enter target’s handle, copy the generated URL. |
| 05 | **Phishing Instagram** | Builds an Instagram “login” phishing page (simple HTML template). | `insta_phish.py` → follow prompts for victim username, output folder. |
| 06 | **Mini Rat!** | Small RAT skeleton that opens a reverse shell to the attacker. | Launch via menu; choose IP:port of your listener.not working well |
| 07 | **Nitro Generator** | Generates random Discord Nitro codes (10‑character). | `nitro_gen.py` – outputs a list in console or file. |
| 08 | **Bot Deleter (Discord)** | Removes all bots from a selected server using the Discord API. | Requires a token → enter it when prompted; choose guild ID. |
| 09 | **Stealer (ngrok)** | Packs stolen credentials into an ngrok tunnel for remote retrieval. | `stealer_ngrok.py` – start, copy ngrok URL, give to victim. |
| 10 | **Stealer (Discord)** | Exfiltrates Discord token & messages via a webhook or local file. | `stealer_discord.py` → choose output method. |
| 11 | **Username Tracker** | Looks up usernames on several services (GitHub, Twitter, etc.). | `user_tracker.py <username>` – prints service matches. |
| 12 | **Phone tracker** | Queries carrier API for phone number info (carrier name, country). | `phone_tracker.py <+number>` → shows details. |
| 13 | **Email tracker** | Resolves email domains to MX records & provider info. | `email_tracker.py <address@example.com>`. |
| 14 | **ID tracker** | Fetches public profile data from LinkedIn / X (Twitter). | `id_tracker.py <handle>` – displays name, title. |
| 15 | **Bot‑Controlleur** | Simple CLI to start/stop a Discord bot instance on demand. | `bot_controller.py` → select action, provide token. |
| 16 | **Metadata for image** | Reads EXIF data from images (camera model, GPS). | `meta_image.py <path/to/image.jpg>`. |
| 17 | **Create Report** | Formats scan results into a readable PDF/HTML report. | `create_report.py <json_file>` → outputs `report.pdf`. |
| 18 | **Google Dork** | Builds Google search queries to find public data (e.g., file types). | `google_dork.py` → enter keyword & extension. |
| 19 | **TechInt (option)** | Tech‑intelligence gathering: fetches OS info, open ports of a target. | `tech_int.py <ip>` – prints OS guess + port list. |
| 20 | **Directory Fuzzer** | Brute‑forces directories on a web server to discover hidden paths. | `dir_fuzz.py <url> <wordlist.txt>` → shows hits. |
| 21 | **XSS Search** | Scans URLs for stored/reflective XSS vulnerabilities. | `xss_search.py <url>` – prints vulnerable parameters. |
| 22 | **SQL Search** | Looks for SQL injection points in a web form or URL. | `sql_search.py <url>` – shows possible injection vectors. |
| 23 | **Vulnerability Search** | Queries public CVE databases based on OS/Software version. | `vuln_search.py <product> <version>`. |
| 24 | **Scanner Web** | Full‑page scanner: fetches HTML, finds hidden files/dirs & XSS/SQL injection. | `web_scanner.py <url>` → prints results. |
| 25 | **Alt-Scan** | Wrapper that runs all the “Alt” utilities (1–24) in one go. | `alt_scan.py` – choose which group to run. |
| 26 | **Wifi‑Scanner** | Scans local Wi‑Fi networks and shows SSID, BSSID & signal strength. | `wifi_scanner.py` → outputs list of APs. |
| 27 | **FireWall Search** | Checks if a host’s firewall blocks common ports (80/443/22). | `firewall_search.py <ip>` – prints open/closed status. |
| 28 | **File Scan** | Runs the *AntivirusScanner* on a file (same as `main.py`). | `file_scan.py <path/to/file>` – prints risk report. |
| 29 | **Update** | Pulls the latest changes from the Git repo and restarts if needed. | `update_tool.py` → auto‑updates scripts. |
| 30 | **Contact** | Shows contact information for support / author. | `contact_info.py` – prints Discord, email, etc. |


## 📦 Installation

```bash
pip install phonenumbers
pip install requests
pip install discord.py
pip install flask
pip install colorama
pip install pillow
pip install PyInstaller
pip install pyngrok
pip install PyQt5
pip install beautifulsoup4
pip install reportlab
pip install python-magic-bin
pip install pefile
pip install lxml
pip install urllib3
pip install PyPDF2
pip install pywin32
pip install cryptography
pip install psutil default, but keep the file in case)
pip install -r requirements.txt
```
just launch the "z-toolV1.PY" script


---

## 🎓 Educational Value

working in a terminal


---

## 📜 Credits

> Majority of the assets were provided by **AltWolf**.

---

## ⚖️ Disclaimer

*This tool is intended for training and educational use only.  
I am not responsible for any consequences that arise from its usage.*

---

## 📝 License

MIT © 2026 camzzz  

---
