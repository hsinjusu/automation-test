# Wi-Fi Country Code Switch Tool

A lightweight automation utility for switching Wi-Fi country codes across different chipset vendors (Intel / MediaTek / Realtek).

This project demonstrates practical automation skills applied to real-world hardware and system configuration scenarios.

---

## 🔍 Background & Motivation

In hardware validation and system testing environments, Wi-Fi country code settings directly affect:
- Regulatory domain behavior
- Channel availability
- Power limits and RF compliance testing

Manually switching country codes across different Wi-Fi chipsets is error-prone and inefficient.  
This tool was created to **automate and standardize** the country code switching process, reducing manual steps and configuration mistakes during validation workflows.

---

## 🎯 Features

- Support for multiple Wi-Fi chipset vendors:
  - **Intel**
  - **MediaTek (MTK)**
  - **Realtek (RTK)**
- Unified execution flow for country code switching
- Execution logging for traceability
- Minimal setup, portable executable

---

## 🧩 Project Structure

```text
Wi-Fi Country Code Switch Tool/
├─ INTEL/          # Intel-specific scripts / configuration
├─ MTK/            # MediaTek-specific scripts / configuration
├─ RTK/            # Realtek-specific scripts / configuration
├─ Wi-Fi Country Code Switch Tool.exe
py
├─ log.txt         # Execution log
└─ README.md

Language: Python 3.10+
Libraries: Subprocess, OS, Logging (處理底層系統呼叫與日誌追蹤)
Version Control: Git / GitHub
