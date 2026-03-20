# z‑Tool – File Scanner  
*For training and educational purposes only*  

## 📖 Overview | Aperçu (français)

z‑Tool is a lightweight Python utility that scans individual files for suspicious patterns, prints an easy‑to‑read risk report, and can optionally save the result as a JSON file.  
> **« Pour l’entraînement et l’éducation uniquement »** – L’auteur n’est pas responsable de votre utilisation.

---

## 🛠️ What each tool does

| Tool | English Description | French Description |
|------|---------------------|--------------------|
| **`main.py` (AntivirusScanner)** | Scans a single file passed as an argument or through the interactive prompt, prints the risk level and threats found. | Analyse un fichier fourni en argument ou via l’invite interactive et affiche le niveau de risque ainsi que les menaces détectées. |
| **`Alt-Tool-Free-2.py`** | A wrapper that launches `main.py`, displays an ASCII banner, and offers a simple menu for re‑running the scanner or launching other helper scripts. | Un script d’accueil qui lance `main.py`, affiche une bannière ASCII et propose un menu pour relancer le scanner ou lancer d’autres utilitaires. |
| **`z-tool-.py`** | A companion tool used in the menu to perform additional checks (e.g., system info, quick file list). | Un script auxiliaire appelé depuis le menu pour effectuer des vérifications supplémentaires (infos système, liste rapide de fichiers…). |
| **ASCII Art functions (`print_GREEN_GREEN_gradient`, etc.)** | Generate colorful banners in the terminal for visual flair. | Génèrent des bannières colorées dans le terminal pour un effet visuel accrocheur. |

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/z-tool.git
cd z-tool

# Optional: create a virtual environment
python -m venv .venv
source .venv/bin/activate   # Windows : .vent\Scripts\activate

# Install dependencies (none by default, but keep the file in case)
pip install -r requirements.txt
```

---

## 🚀 Usage

### Interactive mode  
```bash
python main.py
```
or  
```bash
python Alt-Tool-Free-2.py
```

### Command‑line scan  
```bash
python main.py "C:\path\to\file.exe"
```

The scanner prints a concise report and asks whether you want to save it as JSON.

---

## 🎓 Educational Value

- **Simple code structure** – Easy to read, modify or extend.  
- **Real‑world example** of file‑scan logic using Python standard libraries.  
- **Terminal UI** – Demonstrates ANSI colors and ASCII art in a console app.  

Feel free to experiment with the detection heuristics, add new threat patterns, or integrate it into your own projects.

---

## 📜 Credits

> Majority of the visual assets (ASCII banners, color functions) were provided by **AltWolf**.

---

## ⚖️ Disclaimer

*This tool is intended for training and educational use only.  
I am not responsible for any consequences that arise from its usage.*

---

## 📝 License

MIT © 2026 camzzz  

---
