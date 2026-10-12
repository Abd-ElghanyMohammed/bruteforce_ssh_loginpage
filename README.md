# Multi-Target Configuration & File Reader Automation

An interactive, menu-driven Python utility designed for batch-processing configuration files, managing target lists, and handling credential wordlists efficiently. 

## 🚀 Features

* **Interactive Menu System:** Easily navigate between different configuration workflows (SSH services and Web application setups).
* **Multi-Target Processing:** Read and iterate through a batch list of target IP addresses or web URLs from an external text file.
* **Robust File Handling:** Safely loads, parses, and cleans line-by-line inputs from user, password, and target lists using built-in exception handling (`try-except`) to prevent runtime crashes.
* **Nested Iteration Engine:** Demonstrates multi-level data structuring to loop through targets, usernames, and passwords systematically.

## 📊 Included Payload / Wordlist Specifications

The accompanying data files included in this repository have been pre-loaded with the following wordlist scales:

* **Username Payload:** `9,073,790` entries (`users.txt`)
* **Password Payload:** `17,914,018` entries (`passwords.txt`)

## 🛠️ Requirements

* Python 3.x

## ⚙️ Usage

Run the script from your terminal:
```bash
python script.py
