# 🌐 WebHoro

<p align="center">
  <img src="https://img.shields.io/badge/Made%20by-akazatec-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Ubuntu-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>

**WebHoro** is a powerful Python-based website information gathering tool with a clean terminal UI. Extract IP, domain info, SSL, DNS, subdomains, technologies and more — all from one tool.

> ⚠️ **Educational Purposes Only** — This tool is built to demonstrate how website information gathering works using Python. Any misuse for unauthorized activity is strictly prohibited. The author is not responsible for any misuse.

---

## ✨ Features

- 🌐 **IP Address Info** — Domain to IP resolution with hostname
- 📋 **Whois / Domain Info** — Registrar, creation date, expiry and more
- ✅ **Website Status** — Online/offline check with response time
- 📡 **HTTP Headers** — Full header analysis
- 🔎 **DNS Info** — A, MX, NS, TXT, CNAME records
- 🔒 **SSL Certificate** — Issuer, validity, version info
- 🔍 **Subdomains Finder** — Common subdomains detection
- ⚙️ **Technology Detector** — WordPress, React, Nginx, Cloudflare and more
- 📱 **Social Media Links** — Extract social links from website
- 💾 **Source Code Download** — Save full HTML source locally
- 🚀 **All Info Extract** — Run full scan in one click

---

## ⚙️ Installation

### 📱 Termux
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/akazatec/webhoro
cd webhoro
bash setup.sh
```

### 🐧 Linux / Ubuntu / Kali
```bash
sudo apt update && sudo apt upgrade
sudo apt install python3 python3-pip git
git clone https://github.com/akazatec/webhoro
cd webhoro
bash setup.sh
```

---

## 🚀 Usage

```bash
python3 webhoro.py
```

### 📌 Steps:
1. Tool run karo
2. Target URL ya domain enter karo
3. Menu se option choose karo
4. Result dekho!

### 💡 Example:
```
[?] Enter Target URL/Domain:
└─$ google.com

[1]  IP Address
[2]  Domain Info / Whois
[3]  Website Status
...
[11] All Info Extract
[0]  Exit

└─$ 11
```

---

## 🗂️ File Structure

| File | Description |
| :--- | :--- |
| `webhoro.py` | Main Python script. |
| `setup.sh` | Auto installer script. |
| `requirements.txt` | Required dependencies. |
| `README.md` | Project documentation. |
| `LICENSE` | MIT License. |

---

## 🤝 Contributing

Contributions are welcome!
Fork → Changes → Pull Request

## ⚖️ License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

## 👤 Author

**akazatec**
- GitHub: [@akazatec](https://github.com/akazatec)

---

<p align="center">
  <i>"Explore the Web. Know Everything."</i>
</p>
