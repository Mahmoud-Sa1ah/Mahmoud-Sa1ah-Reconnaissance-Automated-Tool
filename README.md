# Reconnaissance-Automated-Tool
This is **Task 1** of the **IT Solera Cyber Department Summer Internship 2025**.  
A modular, Python-based reconnaissance tool developed to automate both passive and active information gathering. The tool supports early-stage penetration testing and vulnerability assessments.

---

## 📌 Features

| Module         | Description                                                  |
|----------------|--------------------------------------------------------------|
| `--whois`      | Performs WHOIS lookup of the target domain                   |
| `--dns`        | Enumerates DNS records (A, MX, TXT, NS)                      |
| `--subdomains` | Discovers subdomains using `crt.sh` and HackerTarget         |
| `--active`     | Performs IP resolution and banner grabbing                   |
| `--ports`      | Scans common ports using Nmap                                |
| `--dirs`       | Brute-forces directories using a wordlist                    |
| `--vulns`      | Detects exposed files like `.env` or `.git/config`           |

---

## ⚙️ Installation

> **Requirements:**
- Python 3.10+
- Nmap installed and added to your system `PATH`
- PyCharm or any Python IDE

### 🔧 Setup Instructions:
1. Clone the repository or download the project files.
2. Open the project in PyCharm.
3. Install any missing dependencies via `requirements.txt` or manually.
4. Run the following command in the terminal:

```bash
python main.py mars.com --whois --dns --subdomains --ports --dirs --vulns
