# ⚡ Cyber Guess X — Ultimate Edition

A visually stunning, feature-rich cyberpunk-themed number guessing game built in Python using **CustomTkinter**. This application features dynamic multi-language support (English/Tamil), local persistent database logging, multi-threaded text-to-speech feedback, data analytics tracking, and a sleek neon grid interface.

---

## ✨ Core Features

* **🎨 Cyberpunk CustomTkinter UI:** High-fidelity neon aesthetic optimized with responsive dark-mode elements (`#0D1117`, Pink, and Cyan accents).
* **🎯 Adaptive Difficulty Modes:** Dynamic game mechanics adjusting target range limits ($1\text{--}50$, $1\text{--}100$, $1\text{--}200$) and attempt constraints automatically.
* **📈 Embedded Matplotlib Analytics:** Real-time data visualization plotting user performance curves over the last 10 sessions.
* **🔊 Thread-Safe Text-to-Speech:** Zero-lag vocal feedback utilizing a specialized multi-threaded wrapper for `pyttsx3`.
* **🌍 Multi-Language Engine:** Seamless localized string extraction switching seamlessly between English and Tamil text structures.
* **💾 Persistent JSON Archiving:** Automatic score calculation and disk tracking via local storage variables (`cyber_stats.json`).
* **🏆 High Score Leaderboard:** Computes and locks down your Top-10 fastest completions alongside a sequential Terminal log file tracking all events.

---

## 🛠️ Tech Stack & Libraries

* **GUI Architecture:** `customtkinter`, `tkinter`
* **Data Visualization:** `matplotlib`
* **Audio Synthesis:** `pyttsx3`
* **Data Formats:** `json`, `os`, `threading`

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python 3.8+ installed on your operating system.

### 2. Installation
Clone the repository and install the required environment dependencies via terminal:

```bash
git clone [https://github.com/rubikaruby-123/SCT_SD_2.git](https://github.com/YOUR_USERNAME/cyber-guess-x.git)
cd cyber-guess-x
pip install customtkinter matplotlib pyttsx3
