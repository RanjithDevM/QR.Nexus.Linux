# 🐧 QR Code Generator - Linux Terminal Edition

A feature-rich QR Code Generator built entirely for the Linux Terminal using Python.

Generate, customize, save, and manage QR codes directly from your terminal without requiring a graphical interface.

---

## 🚀 Features

### 📝 QR Generation

* Text QR Codes
* URL QR Codes
* Wi-Fi QR Codes
* vCard Contact QR Codes
* UPI Payment QR Codes
* SMS QR Codes
* Email QR Codes

### 🎨 Customization

* Custom QR Colors
* Adjustable QR Size
* Custom Border Control
* Error Correction Level Selection (L, M, Q, H)

### 💾 Export Options

* Save QR Codes as PNG
* Colored PNG QR Codes
* Batch QR Generation from Text Files

### 📊 Analysis & Preview

* QR Version Information
* Module Size Details
* Data Length Analysis
* Terminal QR Preview

### 📋 Productivity Features

* Clipboard Copy Support (xclip/xsel)
* QR Generation History
* History Management & Cleanup
* Interactive Menu Interface

### 🛡 Advanced Features

* Error Correction Configuration
* Batch Processing
* QR Metadata Preview
* Terminal-Based Workflow

---

## 📸 Preview

```text
╔══════════════════════════════════════════════════════╗
║        QR CODE GENERATOR - Linux Terminal           ║
║            15 Features | Python 3                  ║
╚══════════════════════════════════════════════════════╝
```

Generate QR codes directly in your terminal and export them when needed.

---

## 🛠 Built With

* Python 3
* qrcode
* Pillow (PIL)
* JSON
* Linux Terminal Utilities

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/qr-generator-linux.git
cd qr-generator-linux
```

Install dependencies:

```bash
pip install qrcode pillow
```

Optional clipboard support:

```bash
sudo apt install xclip
```

or

```bash
sudo apt install xsel
```

---

## ▶️ Run

```bash
python3 qr_generator.py
```

---

## 📋 Available Features

| #  | Feature                   |
| -- | ------------------------- |
| 1  | Text / URL QR             |
| 2  | Wi-Fi QR                  |
| 3  | vCard Contact QR          |
| 4  | UPI Payment QR            |
| 5  | SMS QR                    |
| 6  | Email QR                  |
| 7  | Custom Color QR           |
| 8  | Save QR as PNG            |
| 9  | Batch QR Generation       |
| 10 | History Log               |
| 11 | Error Correction Selector |
| 12 | Size & Border Control     |
| 13 | QR Information Preview    |
| 14 | Clipboard Copy            |
| 15 | About & Help              |

---

## 📂 History Storage

Generated QR records are automatically stored in:

```bash
~/.qr_history.json
```

Users can view or clear history directly from the application.

---

## 🎯 Use Cases

* Quick URL Sharing
* Wi-Fi Credential Sharing
* Business Contact Cards
* UPI Payment Requests
* Event Registration
* Marketing Campaigns
* Bulk QR Generation
* Linux Productivity Tools

---

## 🔮 Future Improvements

* SVG Export
* QR Scanner Integration
* Password-Protected QR Codes
* Logo Embedding
* Dynamic QR Codes
* Multi-Color Themes
* Database Integration

---

## 👨‍💻 Developer

Developed by **Ranjith**

Built for Linux users who prefer the power of the terminal.

🐧 Generate. Save. Share. Repeat.
