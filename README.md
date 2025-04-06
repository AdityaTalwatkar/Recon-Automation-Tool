# 🛡️ Recon Automation Tool for Web Pentesting

A powerful, Python-based interactive tool designed to automate key reconnaissance tasks in the web penetration testing process. This tool simplifies and speeds up information gathering, helping cybersecurity professionals and enthusiasts conduct recon efficiently.

---

## 📌 Project Overview

This tool automates several essential tasks in the **information gathering** phase of web pentesting:
- Fetching IP address
- Generating secure passwords and wordlists
- Creating barcodes and QR codes
- Scanning phone numbers
- Discovering subdomains
- Performing port scans

---

## 🎯 Objectives

The tool allows you to:
1. 🔍 Retrieve your public IP address
2. 🔐 Generate strong passwords
3. 📝 Create custom wordlists
4. 🧾 Generate barcodes (EAN13 format)
5. 📱 Generate QR codes
6. ☎️ Get information on phone numbers (carrier and country)
7. 🌐 Scan for subdomains using a wordlist
8. 🔓 Perform port scans to identify open ports

---

## ⚙️ Technologies Used

- `Python` – Core language
- `tqdm` – Visual progress bars
- `socket` – IP resolution and port scanning
- `random` – Password generation
- `requests` – Subdomain availability
- `barcode` – Barcode generation
- `pyqrcode` – QR code creation
- `phonenumbers` – Phone number information
- `itertools` – Wordlist combinations
- `threading` – Multi-threaded port scanning

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install requests tqdm phonenumbers pyqrcode python-barcode
   ```

2. Run the tool:
   ```bash
   python main.py
   ```

3. Choose the desired operation from the interactive menu.

---

## 🖥️ Script Features & Output

- **IP Address** – Displays local IP and hostname
- **Password Generator** – Random, secure passwords
- **Wordlist Generator** – Saves permutations to file
- **Barcode Generator** – Saves EAN13 barcode as PNG
- **QR Code Generator** – Saves QR from input text/URL
- **Phone Number Info** – Carrier & country info
- **Subdomain Scanner** – Finds live subdomains from list
- **Port Scanner** – Scans IP for common open ports

---

## 🌐 Applications

- 🔐 Cybersecurity Recon & Pentesting
- 🧪 Education & Network Labs
- 🧰 IT Infrastructure Auditing
- 🧑‍💻 Research in Web Security

---

## 👨‍💻 Author

**Aditya Rajendra Talwatkar**  
📧 [adityatalwatkar@gmail.com](mailto:adityatalwatkar@gmail.com)  


---

## 📅 Last Updated

**September 21, 2024**

---

## ✅ Conclusion

This Recon Automation tool bridges multiple recon techniques into a single, user-friendly interface. It offers great educational and professional value in cybersecurity and web security analysis.
