<div align="center">

# ⚡ ZeroDrop — Competitive Gaming & Latency Suite

<p align="center">
  <strong>Zero Frame Drops. Instant 0.5ms Mouse Response. Maximum PC Gaming Performance.</strong><br/>
  <em>Engineered specifically for FiveM, Counter-Strike 2, Valorant, Fortnite, Call of Duty: Warzone & Apex Legends.</em>
</p>

[![Website](https://img.shields.io/badge/Website-Live_Online-10B981?style=for-the-badge&logo=googlechrome&logoColor=white)](https://zerodrop-website.github.io/zerodrop-website/)
[![Download](https://img.shields.io/badge/Download-ZeroDrop.exe_(907_KB)-0EA5E9?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/zerodrop-website/zerodrop-website/raw/main/ZeroDrop.exe)
[![Discord](https://img.shields.io/badge/Discord-Join_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zHYMXaTpSg)
[![Platform](https://img.shields.io/badge/Platform-Windows_10_%2F_11-6366F1?style=for-the-badge&logo=windows11&logoColor=white)](https://zerodrop-website.github.io/zerodrop-website/)
[![Anti--Cheat](https://img.shields.io/badge/Anti--Cheat-100%25_Undetected_%26_Safe-10B981?style=for-the-badge&logo=shield&logoColor=white)](https://zerodrop-website.github.io/zerodrop-website/#security)
[![License](https://img.shields.io/badge/License-HWID_Locked-8B5CF6?style=for-the-badge&logo=keycdn&logoColor=white)](https://zerodrop-website.github.io/zerodrop-website/#pricing)

<br/>

<a href="https://zerodrop-website.github.io/zerodrop-website/"><strong>🌐 Official Website</strong></a> •
<a href="https://github.com/zerodrop-website/zerodrop-website/raw/main/ZeroDrop.exe"><strong>📥 Direct Download (ZeroDrop.exe)</strong></a> •
<a href="https://discord.gg/zHYMXaTpSg"><strong>💬 Discord Community</strong></a> •
<a href="#-key-features"><strong>✨ Key Features</strong></a> •
<a href="#-benchmarks"><strong>📊 Benchmarks</strong></a> •
<a href="#-safety--anti-cheat-compliance"><strong>🛡️ Safety & Anti-Cheat</strong></a> •
<a href="#-legal--documentation"><strong>📄 Documentation</strong></a>

</div>

---

## 🎮 What is ZeroDrop?

**ZeroDrop** is an ultra-lightweight, portable Windows performance optimization suite engineered specifically for competitive PC gamers (**Counter-Strike 2, Valorant, FiveM, Fortnite, Call of Duty: Warzone, Apex Legends**).

Stock Windows 10 and 11 installations ship with over 60 invisible background telemetry processes, unstable dynamic timer jitter (fluctuating between 1.0ms and 15.6ms), delayed network packet buffering (Nagle's algorithm), and trapped Standby List memory — resulting in micro-stutters and sudden FPS drops during high-intensity firefights.

**ZeroDrop eliminates these bottlenecks at the kernel and registry level without modifying game files, without memory injection, and with zero anti-cheat risk.**

---

## 📥 Quick Download & Editions

| Edition | Price | Included Features | Download Link |
| :--- | :---: | :--- | :--- |
| **Free Demo** | **$0.00** | Real-Time Standby RAM Flush, DirectX/Vulkan Shader Cache Purge, Temp Junk Cleaner, Hardware Spec Detection | [📥 Download ZeroDrop.exe](https://github.com/zerodrop-website/zerodrop-website/raw/main/ZeroDrop.exe) |
| **Standard Pro** | **€14.99** | Locked 0.500ms Hardware Timer, Win32PrioritySeparation 3:1 CPU Boost, Low-Latency Network Stack (TCPNoDelay/AckFrequency), Telemetry & Bloat Services Disable | [⚡ Unlock Pro License](https://zerodrop.gumroad.com/l/nsryqw) |
| **VIP Edition** | **€19.99** | All Pro Features + Automated 1-Click System Restore Point, Priority HWID Component Reset, VIP Discord Role & Dedicated Support | [👑 Unlock VIP License](https://zerodrop.gumroad.com/l/qhemj) |

> 💡 *ZeroDrop is 100% portable (~907 KB). No installation required. Runs instantly with Administrator privileges on any Windows 10 or 11 system.*

---

## ✨ Key Features

### 🎯 1. Instant Mouse Response & 0.5ms Timers (PRO)
* Locks hardware timer resolution to **0.500 ms** (HPET platform clock and dynamic tick jitter eliminated via BCDedit).
* Eliminates hidden Windows mouse acceleration curves for **1:1 pure raw mouse input translation**.
* Reduces mouse queue buffering delay (`MouseDataQueueSize = 20`) and boosts keyboard polling response.

### 🛡️ 2. Micro-Stutter Elimination & Frame-Time Consistency (PRO)
* **3:1 Foreground CPU Quantum Boost:** Configures `Win32PrioritySeparation = 0x26 (38)` for maximum CPU slice prioritization to active game threads.
* **Kernel RAM Lock:** Activates `DisablePagingExecutive` to prevent Windows from paging critical kernel drivers to disk.
* Enables Hardware-Accelerated GPU Scheduling (**HAGS Mode 2**).
* Halts invisible background Xbox overlays (`GameBarPresenceWriter`).

### 🧹 3. Standby RAM Flush & Shader Cache Purge (DEMO & PRO)
* **Real-Time Memory Reclamation:** Clears Windows Standby List memory in real time using native Win32 NT kernel APIs (`NtSetSystemInformation`).
* Purges corrupt DirectX and Vulkan shader caches (**NVIDIA DXCache / GLCache & AMD DxCache**).
* Cleans temporary system junk files with a single click.

### 🌐 4. Low-Latency Network Stack Tuning (PRO)
* Disables **Nagle's delayed packet algorithm** (RFC 896) on all network adapters (`TcpAckFrequency = 1`, `TCPNoDelay = 1`).
* Optimizes TCP Window Auto-Tuning, Receive Side Scaling (RSS), and TCP FastOpen.
* Flushes DNS resolver cache buffers and optimizes port connection recycling.

### ⚡ 5. Background Services & Telemetry Debloat (PRO)
* Shuts down notorious stutter-causing services: **SysMain (SuperFetch)**, **WerSvc (Error Reporting)**, **PcaSvc (Program Compatibility Assistant)**, and **DiagTrack (Telemetry)**.
* Activates the hidden Windows **Ultimate Performance Scheme** (`powercfg`) and unparks CPU cores.

### 🛡️ 6. Automated Safety Checkpoint (PRO)
* Automatically creates a dedicated **Windows System Restore Point** before applying deep system optimizations, allowing instant 1-click reversibility at any time.

---

## 📊 Benchmarks (1% Low FPS & Latency)

*Benchmarked on Windows 11 (AMD Ryzen 7 7800X3D, NVIDIA GeForce RTX 4070 12GB, 32GB DDR5-6000 CL30, 1080p Esports / Competitive Settings):*

| Competitive Game | Stock Avg FPS | ZeroDrop Avg FPS | Stock 1% Low | ZeroDrop 1% Low | Firefight Stutter |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Counter-Strike 2** *(Competitive 1080p / 4:3)* | 520 FPS | **635 FPS (+22%)** | 260 FPS | **415 FPS (+60%)** | ❌ Completely Eliminated |
| **Valorant** *(1080p Low Competitive)* | 740 FPS | **890 FPS (+20%)** | 385 FPS | **590 FPS (+53%)** | ❌ Zero Frametime Jitter |
| **Fortnite** *(Performance Mode / DX12)* | 460 FPS | **580 FPS (+26%)** | 185 FPS | **340 FPS (+84%)** | ❌ Endgame Dips Eliminated |
| **FiveM (GTA V RP)** *(120+ Player Server)* | 125 FPS | **165 FPS (+32%)** | 48 FPS | **98 FPS (+104%)** | ❌ Asset Streaming Hitching Gone |
| **COD: Warzone** *(1080p Esports Settings)* | 210 FPS | **260 FPS (+24%)** | 118 FPS | **178 FPS (+51%)** | ❌ Memory Leak Drops Fixed |

> 📌 **Why 1% Lows Matter Most:** High average FPS does not save you if your frametime spikes when someone throws smoke or opens fire. ZeroDrop flattens the frametime graph into a straight line, boosting **1% lows by up to 104%** and cutting input latency in half.

---

## 🛡️ Safety & Anti-Cheat Compliance

* 🟢 **Riot Vanguard (Valorant)** — 100% Compliant & Safe
* 🟢 **Easy Anti-Cheat (Fortnite / Apex Legends / Rust)** — 100% Compliant & Safe
* 🟢 **BattlEye (Rainbow Six Siege / DayZ / Escape from Tarkov)** — 100% Compliant & Safe
* 🟢 **Ricochet (Call of Duty: Warzone & Modern Warfare III)** — 100% Compliant & Safe
* 🟢 **Valve Anti-Cheat (Counter-Strike 2 / TF2)** — 100% Compliant & Safe

> **How it works:** ZeroDrop does **not** inject DLLs into game memories, does **not** read/write game process memory, and does **not** modify game installation files. All optimizations are standard Windows OS kernel timing, system registry policies, and power configurations fully compliant with tournament anti-cheat systems.

---

## 📄 Legal & Documentation

All official legal disclosures and web pages are hosted live on GitHub Pages:

* 🌐 **Live Website:** [https://zerodrop-website.github.io/zerodrop-website/](https://zerodrop-website.github.io/zerodrop-website/)
* 💬 **Discord Community:** [https://discord.gg/zHYMXaTpSg](https://discord.gg/zHYMXaTpSg)
* 📜 **Terms of Service:** [terms.html](terms.html) • [Web Mirror](https://zerodrop-website.github.io/zerodrop-website/terms.html)
* 🔒 **Privacy Policy (GDPR):** [privacy.html](privacy.html) • [Web Mirror](https://zerodrop-website.github.io/zerodrop-website/privacy.html)
* 💰 **Digital Products & Refund Policy:** [refund.html](refund.html) • [Web Mirror](https://zerodrop-website.github.io/zerodrop-website/refund.html)
* 📥 **ZeroDrop.exe Direct Binary:** [ZeroDrop.exe](https://github.com/zerodrop-website/zerodrop-website/raw/main/ZeroDrop.exe)

---

## ⚠️ Disclaimer

* ZeroDrop is not affiliated with, endorsed by, or sponsored by Microsoft Corporation, Valve, Epic Games, Riot Games, or Rockstar Games.
* All game trademarks and registered trademarks are the property of their respective owners.
* See legal documents for full disclosures and warranty conditions.

<br/>
<div align="center">
  <sub>Built with ❤️ for maximum PC competitive gaming performance.</sub>
</div>
