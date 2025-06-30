# ZipCracker-Termux
For education purpose only 


# 🔐 ZipCracker‑Termux PRO v3.0

An advanced **Termux-friendly** Zip password cracking tool with login, auto wordlist download, animated UI, and rich progress indicators.

---

## 🚀 Features


- 🌐 Auto-downloads `rockyou.txt` if missing
- 🎨 Colored terminal output using `rich`
- ⏳ Animated spinner + progress bar
- 📦 Fast and lightweight — optimized for Termux/Linux
- ❗ Graceful error handling for missing files


---

## 🧰 Requirements

- Python 3.x
- Internet connection (to fetch wordlist)
- Termux, Linux, WSL, or Windows CMD

### Install dependencies:

```bash
pip install rich requests
```

---


---

## 🛠️ Setup & Usage

1. Ensure Python & dependencies are installed.
2. Copy both `zip.py` and this `README.md` into the same folder.
3. Run from Termux/Linux/WSL:
   ```bash
   python zip.py
   ```
4. Follow on-screen prompts:
   - Log in
   - Enter target `.zip` file
   - Tool will download `rockyou.txt` if needed
   - Cracking starts with progress display
5. View results: success (with attempts count) or failure message

---

---

## ⚠️ Disclaimer

Use responsibly — only for ethical, legal purposes (e.g. recovering your own files). Misuse may be against the law. Developers are not liable.

---

## 👤 Author

- **Developer:** Bangladesh Cyber Squad  
- **Version:** 3.0  
- **Dev : Parvez hasan
