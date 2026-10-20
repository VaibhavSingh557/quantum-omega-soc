<h1 align="center">🌌 QUANTUM OMEGA v6.2</h1>

<h3 align="center">
  <b>Autonomous Cyber Defense, Network Recon & Quantum Security Operations</b>
</h3>

<p align="center">
  <a href="https://quantum-omega-soc.onrender.com">
    <img src="https://img.shields.io/badge/🔴_LIVE_DEMO-quantum--omega--soc.onrender.com-FF2E63?style=for-the-badge&logo=render&logoColor=white" alt="Live Demo" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-00D2FF?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Flask-Secured-10B981?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/100%25_Client_Side-Forensics-F59E0B?style=for-the-badge&logo=shield&logoColor=black" alt="Security" />
</p>

---

## ⚡ Overview

**Quantum Omega v6.2** is an elite, browser-based Cybersecurity Operations Center (SOC) suite. Built with a hardened Flask backend and a highly interactive, zero-refresh frontend, it provides enterprise-grade threat modeling, active firewall defense, forensic memory analysis, and quantum cryptographic simulations directly in your browser. 

**Privacy First:** Deep forensic processing—such as Memory Entropy analysis and AST De-obfuscation—is executed **100% client-side**. No sensitive payloads are ever uploaded to a server.

---

## 🚀 The 6 Core Engines

### 1. 🛡️ Melis Active Defense
Dynamic subnet scanning and traffic simulation. Detects SYN Floods, DNS Amplification, and Data Exfiltration, and auto-generates real-world, copy-pasteable firewall rules for `iptables`, `ufw`, and Windows `netsh`.

### 2. 📡 Real Nmap & IP Geo-Tracker
Live multi-threaded TCP socket scanning for open ports, service banner grabbing, and CVE risk profiling. Includes a live IP Geo-location and ASN tracker with offline heuristics.

### 3. 🕸️ Neural Threat Topology
Interactive Directed Acyclic Graph (DAG) visualization mapping lateral movement, attack blast-radius, and critical network choke points. Drag nodes, inject APT vectors, and sever attack paths in real-time.

### 4. 🧠 Forensic Memory Helix
Byte-level Shannon entropy analysis with high-entropy anomaly detection. Compare baseline memory states against injected packed shellcode with complete Hex/ASCII stream dumping.

### 5. 📜 Static AST De-Obfuscator
Safely unpacks Base64, Hex literals, and concatenated obfuscated payloads. Extracts real-time Control Flow Graphs (CFG) and flags suspicious primitives without executing untrusted code.

### 6. 🔐 Zero-Trust & Quantum QKD (BB84)
Simulates identity-aware micro-segmentation and device posture risk. Features a photonic polarization simulator demonstrating Quantum Key Distribution, eavesdropper (Eve) detection via QBER spikes, and live Vernam XOR stream encryption.

---

## 🔒 Security Posture

This application is strictly hardened against web vulnerabilities:
- **Strict Content Security Policy (CSP)** implemented.
- Defends against Clickjacking via `X-Frame-Options: DENY`.
- Prevents MIME-sniffing via `X-Content-Type-Options: nosniff`.
- Rejects unexpected HTTP methods (`405 Method Not Allowed`).
- Efficient asset delivery via `ETag` conditional caching.

---

## 💻 Local Development (Quick Start)

Run Quantum Omega in your own isolated lab environment:

**1. Clone the repository:**
```bash
git clone [https://github.com/YOUR-USERNAME/quantum-omega-soc.git](https://github.com/YOUR-USERNAME/quantum-omega-soc.git)
cd quantum-omega-soc
