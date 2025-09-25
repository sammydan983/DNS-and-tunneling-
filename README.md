# DNS Tunneling Detection Tool

A lightweight tool for experimenting with and detecting **DNS tunneling** techniques.  
Originally inspired by research into Cobalt Strike DNS beacons and evasion of Microsoft Defender for Endpoint, this project explores how DNS can be abused to transfer payloads and how such activity can be detected.

---

## 🚀 Overview

DNS tunneling is a technique where attackers abuse the **DNS protocol** to:
- Exfiltrate data covertly
- Establish command-and-control (C2) channels
- Evade traditional security monitoring

This project demonstrates both **how DNS tunneling works** and provides the building blocks for a **detection tool**.  
It can be useful for **researchers, students, and security engineers** interested in DNS security.

---

## ✨ Features

- Generate and test DNS tunnel traffic
- Analyze DNS queries for:
  - Long/abnormal labels
  - High-entropy subdomains
  - Excessive query rates
- Simple detection heuristics for suspicious traffic
- Extendable for advanced detection methods (e.g., ML)
- 

---

## 📂 Project Structure

