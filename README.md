<div align="center">

# ⏱ CHRONO Ultra

### A Production-Grade Advanced Clock & Productivity Web App

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

**No frameworks. No dependencies. Pure HTML, CSS & Vanilla JS.**

[🌐 Live Demo](https://prahladembedx.github.io/CHRONO-Ultra/) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [File Structure](#file-structure)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Voice Commands](#voice-commands)
- [PWA Installation](#pwa-installation)
- [Browser Support](#browser-support)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🧭 About

**CHRONO Ultra** is a feature-rich, production-grade clock and productivity web application built entirely with **vanilla HTML, CSS, and JavaScript**. No frameworks, no libraries, no build tools — just pure web platform.

It works instantly in any modern browser and can be installed as a native app on any device via PWA — completely offline.

> Designed for students, working professionals, and anyone who wants a beautiful always-on clock that also doubles as a full productivity suite.

---

## ✨ Features

### 🕐 Clock
- **Digital Mode** — Neon-styled with optional flicker animation
- **Analog Mode** — Smooth SVG clock with animated hands
- **12H / 24H Toggle** — With helpful hint for 24h format
- **Neon Effect** — Realistic CSS flicker on digital display
- **Tabular Numerals** — No jitter when digits change

### ⏰ Multiple Alarms
- Set unlimited alarms with **custom labels**
- Each alarm has its own **sound selection**
- Toggle alarms ON/OFF individually
- 4 built-in alarm sounds + **custom MP3/WAV upload**
- Browser **notifications** when alarm rings
- Visual pulse animation on clock card

### 🍅 Pomodoro Focus Timer
- 25 / 5 / 15 minute presets
- Single **Play/Pause** button
- Animated progress bar
- **7-day session history** bar chart
- **Streak tracking** across days
- Browser notification at session end

### ⏱ Stopwatch
- Millisecond precision — `HH:MM:SS.mmm`
- Single **Start/Pause** toggle button
- Lap recording with split times
- Scrollable lap history

### ⏳ Countdown Timers
- Add multiple event countdowns
- Live `Xd HH:MM:SS` format
- Browser notification support

### 🌍 World Clock
- **Search any city or country** in the world
- Add up to 8 custom time zones
- 50+ cities pre-loaded (India, USA, Europe, Asia, etc.)
- Remove individual clocks

### 📅 Calendar with Indian Festivals
- Full monthly calendar view
- **Indian festivals highlighted** on dates
- Tap any date to see festival name
- Festivals include: Diwali, Holi, Eid, Christmas, Republic Day, Independence Day, Navratri, Chhath Puja, Janmashtami, and 30+ more
- Navigate months easily

### 🕉️ Auspicious Times
- 8 daily Hindu auspicious times displayed
- Includes: Brahma Muhurta, Madhyahna, Pradosh Kaal, Midnight Time, and more
- Currently active time slot highlighted

### 🎤 Voice Commands
- Hands-free control via Web Speech API
- **Auto-stops after 5 seconds of silence**
- Supports: set alarm, start/stop stopwatch, start/stop focus, dark mode, fullscreen, and more

### 📝 Sticky Notes
- Add unlimited notes with timestamps
- Persistent across sessions

### 💊 Medicine Reminder
- Add medicines with name and time
- Browser notification at reminder time
- Mark as "Taken" with one tap

### 💧 Water Reminder
- Set interval (30 min to 2 hours)
- Track 8 glasses daily goal
- Visual glass tracker

### 📖 Study Planner
- Add subjects with daily time goals
- Per-subject study timer
- Progress bar per subject
- Notification on goal completion

### 🎵 Audio Engine
**Ambient Sounds:**
- 🌧️ Rain · 🌲 Forest · 🕉️ Om Chant
- 🙏 Ram Chant · 🐦 Birds · 🌅 Morning
- 🧘 Meditation

**Focus Frequency Tones:**
- 40Hz Gamma — Focus & Memory
- 10Hz Alpha — Relaxed Focus
- 6Hz Theta — Deep Study
- 432Hz — Healing & Stress Relief
- 528Hz Solfeggio — Clarity
- 963Hz Crown — Higher Mind

**Custom Audio:**
- Upload your own MP3/WAV as alarm sound

### 🏆 Achievements — 10 Badges
| Badge | Unlock |
|-------|--------|
| 🐦 Early Bird | Alarm before 6 AM |
| 🦉 Night Owl | Alarm after 11 PM |
| 🎯 Focus Master | 10 Pomodoros done |
| 🔥 Streak King | 7-day streak |
| ⏱️ Time Lord | 50 stopwatch laps |
| ⚡ Punctual | Dismiss alarm in 5s |
| 🍅 First Focus | First Pomodoro |
| ⏰ Alarm Setter | First alarm |
| 📚 Scholar | Study goal reached |
| 🏁 Pacer | First lap recorded |

### 🎨 Design
- **5 Color Themes** — Blue, Pink, Green, Yellow, Purple
- **3 Clock Fonts** — Digital/LED, Monospace, Serif
- **Dark / Light Mode**
- **Glassmorphism UI** with frosted glass cards
- **Particle Background** — Mouse-reactive starfield
- **Custom Background Image** — Paste any URL
- **Responsive** — Mobile, tablet, desktop

### 📱 Mobile Features
- **Swipe gestures** — Left/Right to change tabs
- **Haptic feedback** — Vibration on interactions
- **Portrait & Landscape** — Auto-adjusting layout
- **PWA Installable** — Works offline after install

### 🌤️ Smart Features
- **Weather Widget** — Live temperature via Open-Meteo (no API key)
- **Battery Status** — Charge % and charging state
- **Screen Wake Lock** — Prevents screen from sleeping
- **Daily Quote** — Rotating motivational quotes (Hindi + English)

### 💾 Data Management
- **localStorage** — Everything saved automatically
- **Export** — Backup all data as JSON
- **Import** — Restore from backup
- **Reset** — Clear all data

---

## 📁 Project Structure

```
CHRONO-Ultra/
├── index.html      # Entire app (HTML + CSS + JS)
├── sw.js           # Service Worker (PWA offline)
├── manifest.json   # PWA config (install as app)
├── favicon.ico     # Browser tab icon
├── icon-192.png    # PWA icon (192x192)
├── icon-512.png    # PWA icon (512x512)
└── README.md       # Project documentation
```

---

## 🚀 Installation

### Open Directly
```bash
git clone https://github.com/prahladembedx/CHRONO-Ultra.git
cd CHRONO-Ultra
# Open index.html in browser
```

### Local Server (for PWA features)
```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .
```
Open `http://localhost:8080`

### Live Version
```
https://prahladembedx.github.io/CHRONO-Ultra/
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `F` | Toggle Fullscreen |
| `Space` | Play / Pause active timer |
| `L` | Record Stopwatch Lap |
| `R` | Reset timers |
| `N` | Focus Notes input |
| `V` | Toggle Voice Commands |
| `D` | Toggle Dark / Light Mode |
| `?` | Show / Hide Shortcuts |
| `Esc` | Dismiss Alarm |
| `1` – `7` | Jump to Tab 1–7 |

---

## 🎤 Voice Commands

| Say | Action |
|-----|--------|
| "Set alarm 7 AM" | Sets alarm |
| "Start stopwatch" | Starts stopwatch |
| "Stop stopwatch" | Stops stopwatch |
| "Lap" | Records a lap |
| "Start focus" | Starts Pomodoro |
| "Stop focus" | Pauses Pomodoro |
| "What time" | Shows current time |
| "Dark mode" | Switches to dark |
| "Light mode" | Switches to light |
| "Fullscreen" | Enters fullscreen |

> Voice auto-stops after **5 seconds of silence**

---

## 📱 PWA Installation

**Android Chrome:**
```
Open link in Chrome
→ 3 dots ⋮ → Add to Home Screen → Install
```

**iPhone Safari:**
```
Open link in Safari
→ Share ⬆ → Add to Home Screen → Add
```

**Desktop Chrome/Edge:**
```
Look for ⊕ icon in address bar → Install
```

Works fully **offline** after installation.

---

## 🌐 Browser Support

| Feature | Chrome | Edge | Firefox | Safari |
|---------|--------|------|---------|--------|
| Core Clock | ✅ | ✅ | ✅ | ✅ |
| Web Audio | ✅ | ✅ | ✅ | ✅ |
| Notifications | ✅ | ✅ | ✅ | ✅ |
| Speech Recognition | ✅ | ✅ | ❌ | ✅ |
| Wake Lock | ✅ | ✅ | ✅ | ✅ |
| Battery API | ✅ | ✅ | ⚠️ | ❌ |
| PWA Install | ✅ | ✅ | ⚠️ | ✅ |

---

## 🔮 Future Improvements

These features are planned for upcoming versions of CHRONO Ultra:

### 🌟 Version 4 — Planned
- [ ] **Google Calendar Sync** — Import events directly
- [ ] **Moon Phase Display** — Daily lunar phase on clock
- [ ] **Sunrise & Sunset Countdown** — Exact times for your location
- [ ] **More Festival Dates** — 2027 and beyond auto-calculated
- [ ] **Flip Clock Mode** — Retro airport-style digits
- [ ] **Multi-language Support** — Hindi, Tamil, Bengali UI
- [ ] **Widget Mode** — Tiny floating clock widget
- [ ] **Cloud Sync** — Backup data to Google Drive
- [ ] **Themes Marketplace** — Community-made color themes
- [ ] **More Frequency Tones** — Binaural beats library
- [ ] **ASMR Sounds** — Keyboard typing, page turning, rain on glass

### 🛠️ Technical Improvements
- [ ] **Better PWA Icons** — Custom clock icon for home screen
- [ ] **Faster Load** — Lazy loading for audio modules
- [ ] **IndexedDB** — For larger data storage than localStorage
- [ ] **Web Workers** — Background timer accuracy improvement
- [ ] **Accessibility** — Full ARIA support for screen readers

---

## 📄 License

```
Copyright (c) 2026 prahladembedx. All Rights Reserved.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CHRONO Ultra is a personal project created with passion
by prahladembedx. While this project is publicly visible
for inspiration and learning purposes only, all rights to
the code, design, and concept are reserved by the author.

Copying, redistribution, or commercial use of this project
without written permission from the author is not allowed.

If you'd like to collaborate or have any questions,
feel free to reach out — always open to a good conversation!

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

GitHub  : https://github.com/prahladembedx
Project : https://prahladembedx.github.io/CHRONO-Ultra/

        "Built with passion, protected with purpose."
                              — prahladembedx, 2026
```

---

## 🙏 Credits

| Resource | Usage |
|----------|-------|
| [Open-Meteo](https://open-meteo.com/) | Free weather API |
| [Google Fonts](https://fonts.google.com/) | Orbitron, Space Mono, Playfair Display, Sora |
| Web Audio API | All sounds synthesized — zero audio files |
| Web Platform APIs | Geolocation, Battery, Wake Lock, Speech, Notifications |

---

<div align="center">

Built with ❤️ by **prahladembedx**

⭐ **Star this repo** if CHRONO helped you stay productive!

</div>
