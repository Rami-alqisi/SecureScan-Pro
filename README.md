# 🔐 SecureScan Pro

> Multi-Threaded Port Scanner with Real-Time CVE Intelligence
> Integration

------------------------------------------------------------------------

## 📌 Overview

SecureScan Pro is a Python-based network reconnaissance tool that
combines:

-   ⚡ Multi-threaded TCP Port Scanning\
-   🔎 Service Banner Grabbing\
-   🧠 Real-time CVE Lookup via the National Vulnerability Database (NVD
    API)\
-   📊 Interactive Web Dashboard built with Streamlit\
-   🎯 CVSS Score Extraction & Severity Classification

This project demonstrates practical cybersecurity skills in:

-   Network scanning
-   Vulnerability intelligence gathering
-   API integration
-   Concurrent programming
-   Secure architecture design

------------------------------------------------------------------------

## 🚀 Features

-   Multi-threaded TCP scanning
-   Automatic banner grabbing
-   Service-based CVE lookup using official NVD API
-   CVSS v3.1 score extraction
-   Severity classification (Low / Medium / High / Critical)
-   Interactive vulnerability dashboard
-   CVE severity distribution charts
-   High & Critical filtering mode

------------------------------------------------------------------------

## 🏗 Architecture

SecureScan Pro │ ├── dashboard.py \# Web UI + Live Scanner ├──
cve_lookup.py \# NVD API Integration ├── utils.py \# Banner grabbing ├──
reporter.py \# JSON export (optional) ├── scanner.py \# CLI scanner
(optional) └── requirements.txt

------------------------------------------------------------------------

## ⚙️ Installation

### 1️⃣ Clone the repository

git clone https://github.com/yourusername/securescan-pro.git cd
securescan-pro

### 2️⃣ Install dependencies

pip install -r requirements.txt

------------------------------------------------------------------------

## 🔑 NVD API Setup

Request a free API key from:
https://nvd.nist.gov/developers/request-an-api-key

Then update inside your project:

API_KEY = "YOUR_API_KEY"

------------------------------------------------------------------------

## ▶️ Usage

Run the dashboard:

streamlit run dashboard.py

Then:

1.  Enter target IP address
2.  Choose port range
3.  Click **Start Scan**

------------------------------------------------------------------------

## 📊 What This Tool Does

SecureScan Pro performs:

1.  TCP Port Scanning\
2.  Service Detection via Banner Grabbing\
3.  CVE Intelligence Lookup (keyword-based)\
4.  CVSS Severity Classification

⚠️ This tool does NOT exploit vulnerabilities.\
It performs reconnaissance and vulnerability intelligence gathering
only.

------------------------------------------------------------------------

## 🎯 Educational Purpose

This project was built for:

-   Cybersecurity portfolio development
-   Understanding vulnerability intelligence workflows
-   Demonstrating API integration skills
-   Practicing concurrent network programming

------------------------------------------------------------------------

## 🔒 Legal Disclaimer

This tool is intended for:

-   Educational purposes\
-   Testing systems you own\
-   Environments where you have explicit authorization

Unauthorized scanning of networks may be illegal.

------------------------------------------------------------------------

## 👨‍💻 Author

Rami Alqisi\
Cybersecurity Student \| Network Security Enthusiast
