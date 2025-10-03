# Linux Bridge Box – OTA Latency/Timeout Runbook

Single-file, print-friendly runbook for measuring OTA performance using a Linux bridge with `tc netem` + Wireshark.

[![View live](https://img.shields.io/badge/GitHub%20Pages-Open-blue)](https://KirthikR-Tru.github.io/Linux_Bridge_Box/Linux_bridge-ota.html)

---

## 📎 Live Page
**URL:** https://KirthikR-Tru.github.io/Linux_Bridge_Box/Linux_bridge-ota.html

## 📘 What’s inside
- Network Cinfig
- Wireshark filters/metrics (DNS time, TCP connect, FTP login)
- Clean-up (qdisc & nftables)
- Temporary MQTT blocking rules

## 🚀 Quick start
1. Open the **Live Page** above (or double-click the HTML locally).
2. Follow sections in order: **Access & Sanity → Impairments → Capture → Wireshark → Clean-up**.
3. Use the **Copy** buttons on the page to run commands safely.

## 🧩 Files
- `Linux_bridge-ota.html` – the runbook (served by GitHub Pages)
- `trumeter-favicon.png` *(optional)* – favicon/logo

## 🌐 Enable GitHub Pages
Settings → **Pages** → *Deploy from a branch* → **Branch:** `main` **/ (root)** → **Save**.  
First deploy takes ~1 minute. Check **Actions → pages build and deployment**.

## 🖨️ Print/PDF
Use your browser’s **Print** to export a PDF for audit records. The page includes print styles for clean output.

## 🖼️ Screenshots
Create a `screenshots/` folder and upload images. Reference them here:
```md
![Topology](screenshots/topology.png)
