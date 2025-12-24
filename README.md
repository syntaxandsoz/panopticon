# 👁️ The Panopticon | Device Fingerprinting Analyst

> **"Know what the web knows about you."**

![Status](https://img.shields.io/badge/Status-Operational-brightgreen)
![Security](https://img.shields.io/badge/Focus-Privacy--Auditing-red)
![Stack](https://img.shields.io/badge/Stack-Vanilla--JS-blue)

**The Panopticon** is a powerful diagnostic tool designed to demonstrate how modern browsers can be "fingerprinted" without the use of cookies. By aggregating disparate browser APIs, it exposes the hidden data points that websites collect to build a unique digital profile of your device—from hardware specifications to sensor leaks.

## 🛡️ The Philosophy

Named after the architectural concept of a prison where everyone is watched without knowing it, this project serves as a wake-up call for digital privacy. The Panopticon gathers your "Digital Exhaust" into a single interface, empowering users to visualize the invisible surveillance occurring in the background of the modern web.

## ✨ Key Features

* **Canvas Fingerprinting:** Generates a unique UID based on how your browser renders graphical text—a technique used to track users across Incognito sessions.
* **Hardware Integrity:** Detects CPU cores, estimated RAM, GPU renderer names, and device platform.
* **Network Node Analysis:** Fetches Public IP, attempts to leak Local IP via WebRTC, and measures connection latency.
* **Sensor Surveillance:** Monitors Battery levels, charging status, and live Device Orientation (Gyroscope) data.
* **Privacy Flags:** Audits "Do Not Track" headers and screen resolution inconsistencies.

## 🚀 How to Use

1.  **Clone:** Download the repository to your local machine.
2.  **Launch:** Open `index.html` in any modern browser (Chrome, Firefox, Safari).
3.  **Analyze:** View the "Hacker-style" HUD as it populates with your real-time forensic data.
4.  **Audit:** Compare the results against privacy-hardened browsers (like Mullvad or Brave) to test their effectiveness.

## 🛠️ Tech Stack

* **Core:** Vanilla JavaScript
* **Forensics:** WebGL API, WebRTC API, Battery Status API, Canvas API
* **Styling:** CSS3 (Hacker/HUD Aesthetic)

## ⚠️ Disclaimer

This tool is created for **Educational and Research purposes only**. It does not store user data unless explicitly configured with external analytics. Its goal is to provide transparency regarding browser leaks and to encourage the use of privacy-focused tools.

---
<div align="center">
  <p>Designed & Developed by <a href="https://github.com/syntaxandsoz"><b>Syntax & Soz</b></a></p>
  <p><i>"Transparency is the first step to invisibility."</i></p>
</div>
