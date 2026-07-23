# 🏋️‍♂️ Workout Timer Pro (運動計時器 Pro)

A lightweight, responsive, and cross-platform PWA (Progressive Web App) interval workout timer built specifically for **iPhone (iOS)** and **Android**. Designed for Tabata, HIIT, core workouts, and custom circuit training.

![Workout Timer Pro](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-emerald)
![License](https://img.shields.io/badge/License-MIT-blue)

👉 **Live App / 免費使用網址**: [https://aimastertoast.github.io/workout-timer/](https://aimastertoast.github.io/workout-timer/)

---

## ✨ Features (主要功能)

* 🌐 **Multi-Language UI & TTS (多語系與語音配音)**
  * Full UI and Voice Synthesis support for **Cantonese (廣東話)**, **Mandarin (普通話)**, and **English**.
* 🗣️ **Voice Prompts & Gender Control (男聲/女聲切換)**
  * Simplified countdown prompts (*"Get Ready" / "準備開始"*).
  * Choose between **Male** and **Female** voices based on system capabilities.
* 📋 **Multiple Workout Routines (自訂多組運動企劃)**
  * Create, edit, switch, and delete multiple custom workout sets (e.g., TABATA, Core, Leg Day).
* ⏱️ **Smart Timing Logic (智慧時間設定)**
  * **Dual Input**: Type exact seconds manually OR use quick-select dropdowns.
  * **Seamless Countdown**: Automatically adjusts rest periods so the 3-2-1 "Get Ready" voice prompt flows naturally without extending total rest time.
  * **No Last-Exercise Rest**: Automatically skips rest on the final movement of each round.
* 💾 **Backup & Restore (組合備份與還原)**
  * Export/Import routines via JSON format so you never lose custom workouts when clearing browser cache or switching devices.
* 📱 **PWA & Screen Wake-Lock (螢幕防鎖定)**
  * Keep screen awake during active workout.
  * Native app experience when saved to iPhone or Android Home Screen.

---

## 📲 How to Install on Phone (如何加至手機主畫面)

### iPhone (iOS Safari)
1. Open [https://aimastertoast.github.io/workout-timer/](https://aimastertoast.github.io/workout-timer/) in **Safari**.
2. Tap the **Share** button (box with upward arrow ↗️) at the bottom.
3. Scroll down and select **Add to Home Screen (加至主畫面)**.
4. Tap **Add**. Launch directly from your home screen like a native app!

### Android (Chrome)
1. Open the URL in **Chrome**.
2. Tap the **Menu** button (three dots in top-right).
3. Select **Install app** or **Add to Home Screen**.

---

## 🛠️ Tech Stack (技術棧)

* **HTML5 / Single-File App**
* **React 18** (via UMD)
* **Tailwind CSS** (for modern styling)
* **Web Speech Synthesis API** (for multi-language voice countdowns)
* **Web Audio API** (for audio beeps)
* **Web Wake Lock API** (to keep screen active)
* **HTML5 LocalStorage** (for local data persistence)

---

## 💾 Backup & Restore Routines (如何備份與還原組合)

1. **Backup**: Tap the **`💾 備份`** button in the top bar ➔ Click **Copy Backup Text**. Save it to your notes.
2. **Restore**: Tap **`還原/匯入組合`** in the routine list ➔ Paste your JSON data ➔ Tap **Confirm**.

---

## 📄 License

Distributed under the MIT License. Feel free to fork, customize, and build your own interval timer!
