# 👁️ The Panopticon | Device Fingerprinting Analyst

> **"Know what the web knows about you."**

![Status](https://img.shields.io/badge/Status-Operational-brightgreen)
![Security](https://img.shields.io/badge/Focus-Privacy--Auditing-red)
![Stack](https://img.shields.io/badge/Stack-Vanilla--JS-blue)

**The Panopticon** is a powerful diagnostic tool that demonstrates how modern browsers can be "fingerprinted" without the use of cookies. It exposes the hidden data points that websites collect to build a unique digital profile of your device, from hardware specifications to sensor leaks.

## 🔍 The Concept

Named after the architectural concept of a prison where everyone is watched without knowing it, this project serves as a wake-up call for digital privacy. It gathers disparate browser APIs into a single "Hacker-style" HUD to show you the "Digital Exhaust" your device leaves behind.



## ✨ Forensic Capabilities

* **Hardware Integrity:** Detects CPU cores, estimated RAM, GPU renderer names, and device platform.
* **Network Node Analysis:** Fetches Public IP, attempts to leak Local IP via WebRTC, and measures connection latency.
* **Sensor Surveillance:** Monitors Battery levels, charging status, and live Device Orientation (Gyroscope) data.
* **Canvas Fingerprinting:** Generates a unique UID based on how your browser renders graphical text—a technique used to track users across Incognito sessions.
* **Privacy Flags:** Audits "Do Not Track" headers and screen resolution inconsistencies.

## 🛠️ How it Works

The tool utilizes several low-level Browser APIs:
1.  **WebGL API:** To extract GPU and graphics driver information.
2.  **WebRTC API:** To bypass standard network protections and find local network addresses.
3.  **Battery Status API:** To monitor energy levels (often used for cross-device tracking).
4.  **Canvas API:** To render invisible patterns and hash the output into a unique Subject ID.

## 🚀 Deployment

Since this is a client-side tool, you can host it anywhere:
1.  Clone the repository.
2.  Open `index.html` in any modern browser.
3.  (Optional) Host on GitHub Pages for a live forensic link.

## ⚖️ Ethics & Purpose

This project is created for **Educational and Research purposes only**. It does not store user data (unless configured with external analytics). Its goal is to provide transparency and help users understand the necessity of privacy-hardened browsers like Mullvad or Brave.

---
<div align="center">
  <p>Designed & Developed by <a href="https://github.com/syntaxandsoz"><b>Syntax & Soz</b></a></p>
  <p><i>"Transparency is the first step to invisibility."</i></p>
</div>
