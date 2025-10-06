# 🔍 ReconX — Advanced DNS & Google Dork Intelligence Tool

ReconX (formerly **Dork_Hunter**) is a web-based reconnaissance tool built with **Flask**.  
It helps security researchers, bug bounty hunters, and ethical hackers gather **domain intelligence** through DNS record lookups, IP geolocation, and **Google Dorks** for potential sensitive information discovery.

---

## ⚙️ Features

- 🌐 **Comprehensive DNS Lookup**
  - A, AAAA, MX, TXT, NS, CNAME, SOA, and PTR records.

- 🧭 **IP Information**
  - Uses [ipinfo.io](https://ipinfo.io) API to retrieve IP geolocation, ISP, hostname, and organization.

- 🕵️ **Google Dork Links**
  - Auto-generates categorized Google dorks to help locate sensitive files, directories, and configurations.

- 💅 **Modern UI**
  - Responsive TailwindCSS interface with gradient backgrounds and glowing effects.

---

## ✅ Installation Steps

---

## 1. Open terminal and go to project folder

```bash
cd /path/to/Top_Dork_Hunter
# Example:
# cd ~/projects/Top_Dork_Hunter
```

---

## 2. Create & activate a virtual environment

### Linux / macOS / WSL

```bash
python3 -m venv venv
source venv/bin/activate
```

### Windows — PowerShell

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

### Windows — CMD

```cmd
python -m venv venv
.\venv\Scripts\activate.bat
```

---

## 3. Install dependencies from `requirements.txt`

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

(If you don’t have a `requirements.txt`, create one or run: `pip install Flask dnspython requests`)

---

## 4. Run the app

```bash
python app.py
```

---

## 5. Open in your browser

Go to:

```
http://127.0.0.1:5000
```

---

Thank you for trying **ReconX (Dork_Hunter)** — a small, useful toolkit for safe, ethical reconnaissance and domain intelligence. If this project helped you, please consider starring the repo, sharing feedback, or contributing improvements.

---


*End of README — thank you and happy, responsible hunting!*



