<div align="center">

# ⏱ CHRONO Ultra

### A Production-Grade Advanced Clock Web App

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**No frameworks. No dependencies. Just pure HTML, CSS & Vanilla JS.**

[🌐 Live Demo](#) · [📥 Download](#installation) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [File Structure](#file-structure)
- [Installation](#installation)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Voice Commands](#voice-commands)
- [PWA Installation](#pwa-installation)
- [Browser Support](#browser-support)
- [Customization](#customization)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

---

## 🧭 About

**CHRONO Ultra** is a feature-packed, production-grade clock web application built entirely with **vanilla HTML, CSS, and JavaScript** — no frameworks, no libraries, no build tools required. It loads instantly in any modern browser and can be installed as a native app on any device via PWA.

Designed for power users who want a beautiful, always-on desk clock that also works as a full productivity suite — with alarms, focus timers, world clocks, voice commands, ambient sounds, and more.

---

## ✨ Features

### 🕐 Clock Modes — 3 Types
| Mode | Description |
|------|-------------|
| **Digital** | Neon-styled digital clock with optional glow flicker effect |
| **Analog** | SVG analog clock with smooth hour/minute/second hands |
| **Flip** | Retro airport-board style flip animation with CSS 3D transforms |

### 🎨 Visual & Design
- **Glassmorphism UI** — frosted glass cards with `backdrop-filter: blur()`
- **6 Neon Accent Themes** — Blue, Pink, Green, Yellow, Purple, Orange
- **3 Clock Fonts** — Digital/LED (Orbitron), Monospace (Space Mono), Serif (Playfair Display)
- **Dark / Light Mode** — smooth transition between midnight dark and crisp light themes
- **Neon Sign Effect** — realistic CSS flicker animation on the digital clock
- **3D Perspective Tilt** — CSS `perspective` + `rotateX/Y` for immersive depth
- **Custom Cursor** — glowing circle cursor with click-expand effect
- **Particle Background** — 140-point canvas starfield, mouse-reactive, theme-color synced
- **Custom Background Images** — paste any URL, or auto-fetch from Unsplash

### ⏰ Multiple Alarms
- Set **unlimited alarms** simultaneously, each with a custom label
- Each alarm has its **own sound selection**
- Toggle alarms ON/OFF individually without deleting
- Auto-dismisses after 2 minutes; visual pulse animation when ringing
- 5 alarm sounds built-in + custom audio upload
- Alarm state persists across page refreshes via localStorage

### 🍅 Pomodoro Focus Timer
- Classic **25 / 5 / 15 minute** presets (Focus / Short Break / Long Break)
- Animated progress bar drains in real time
- **Streak tracking** — counts consecutive days with completed sessions
- **Session statistics** — today's count, total sessions, total focus hours
- **7-day bar chart** visualization built without any charting library

### ⏱ Stopwatch
- **Millisecond precision** — `HH:MM:SS.mmm` display
- **Lap recording** with individual split (delta) times
- Scrollable lap list, newest first
- Start / Stop / Lap / Reset controls

### ⏳ Countdown Timers
- Add **multiple simultaneous countdown events** (New Year, Birthday, Exam…)
- Live countdown showing days, hours, minutes, seconds
- Delete individual countdowns anytime

### 🌍 World Clock
- **6 cities** updating every second: UTC, New York, London, Tokyo, Dubai, Sydney
- Displays local date alongside time for each city
- Easily customizable by editing the `ZONES` array

### 📅 Calendar
- Full **monthly mini calendar** with previous/next navigation
- Today's date highlighted with the active accent color

### 🕉️ Pooja & Auspicious Times
- Calculates **6 Hindu prayer times** using astronomical sunrise/sunset formula
- Based on your **live geolocation** coordinates
- Includes: Brahma Muhurta, Pratah Sandhya, Madhyahna, Sayam Sandhya, Pradosh, Nishitha Kaal
- Currently active time slot is highlighted automatically
- Pre-calibrated for **Patna, Bihar** (easily changed in code)

### 🎤 Voice Commands
Full hands-free control using the Web Speech API. Say naturally:

| Voice Command | Action |
|---------------|--------|
| `"Set alarm 7 AM"` | Sets alarm for 7:00 AM |
| `"Start stopwatch"` | Starts the stopwatch |
| `"Stop stopwatch"` | Stops the stopwatch |
| `"Lap"` | Records a stopwatch lap |
| `"Start focus"` | Starts Pomodoro timer |
| `"Stop focus"` | Pauses Pomodoro timer |
| `"What time is it"` | Shows time in a toast popup |
| `"Fullscreen"` | Enters fullscreen mode |
| `"Dark mode"` | Switches to dark theme |
| `"Light mode"` | Switches to light theme |
| `"Next tab"` | Cycles to next tab |

### 📝 Sticky Notes
- Add unlimited notes with timestamps
- Responsive masonry-style grid layout
- Persisted in localStorage

### 🎵 Audio Engine — Zero Audio Files
All sounds generated **programmatically** using the Web Audio API:

**5 Alarm Sounds:**
| Sound | Synthesis Method |
|-------|-----------------|
| 🔔 Zen Bell | Sine wave 528Hz → 264Hz decay |
| ⏰ Mechanical | Square wave 7-pulse burst |
| 🐦 Bird Song | Oscillating sine with random pitch chirp |
| 📟 Digital Beep | Triple square-wave at 1000Hz |
| 🕉️ Hanuman Bell | Triangle wave chord: 528→660→792Hz |

**White Noise / Focus Sounds:**
| Sound | Audio Filter |
|-------|-------------|
| 🌧️ Rain | Bandpass 600Hz + LFO amplitude modulation |
| 🌊 Ocean | Lowpass 400Hz + slow 0.15Hz LFO swell |
| 🌲 Forest | Highpass 1200Hz subtle ambient noise |
| 🔥 Campfire | Lowpass 200Hz + 2Hz LFO crackle |

- **Custom Alarm Upload** — load your own MP3/WAV as alarm sound
- **Master Volume Slider** — global control for all audio
- **Lo-Fi Radio** — quick-link buttons to YouTube lo-fi/jazz streams

### 🏆 Achievements & Gamification
**8 Unlockable Badges:**
| Badge | Icon | Unlock Condition |
|-------|------|-----------------|
| Early Bird | 🐦 | Set alarm before 6:00 AM |
| Night Owl | 🦉 | Set alarm after 11:00 PM |
| Focus Master | 🎯 | Complete 10 Pomodoro sessions |
| Streak King | 🔥 | Maintain a 7-day streak |
| Time Lord | ⏱️ | Record 50 stopwatch laps |
| Punctual | ⚡ | Dismiss alarm within 5 seconds |
| First Focus | 🍅 | Complete your first Pomodoro |
| Alarm Setter | ⏰ | Set your first alarm |

### 💬 Daily Quotes
- 24 curated motivational quotes (including Hindi)
- Rotates daily — consistent quote all day, fresh one tomorrow

### 📱 Mobile Experience
- **Swipe gestures** — swipe left/right to navigate tabs
- **Haptic feedback** — vibration on button presses (where supported)
- **Portrait & Landscape** — layout adapts automatically
- **Home screen installable** via PWA

### 🌤️ Smart Integrations
- **Weather Widget** — local temperature via [Open-Meteo API](https://open-meteo.com/) (free, no API key needed)
- **Battery Status** — charge % and charging state via Web Battery API
- **Screen Wake Lock** — prevents display from dimming while app is active

### 💾 Data Persistence (localStorage)
Remembered across sessions:
- 12/24h preference, theme color, font selection
- Dark/Light mode, all toggle states
- All alarms (with labels and sounds)
- Sticky notes, stopwatch laps
- Pomodoro stats, streak, and daily history
- Countdown timers, volume level, clock mode

### 📤 Data Management
- **Export** — download all data as `chrono-backup.json`
- **Import** — restore from backup JSON
- **Reset** — wipe all data and start fresh

---

## 📁 File Structure

```
chrono-ultra/
│
├── index.html        ← Entire app (HTML + CSS + JS in one file)
├── sw.js             ← Service Worker for PWA offline support
├── manifest.json     ← PWA manifest (name, icons, shortcuts)
└── README.md         ← This file
```

> The entire app — all HTML structure, CSS styling, and JS logic — lives inside **one self-contained `index.html`**. No build tools, no `node_modules`, no compilation step whatsoever.

---

## 🚀 Installation

### Option 1 — Open Directly
```bash
git clone https://github.com/yourusername/chrono-ultra.git
cd chrono-ultra
# Double-click index.html or open in browser
```

### Option 2 — Local Dev Server (required for PWA features)
```bash
# Python (built-in, no install needed)
python3 -m http.server 8080

# Node.js
npx serve .

# VS Code: install "Live Server" extension → right-click index.html → Open with Live Server
```
Then open `http://localhost:8080`

### Option 3 — Deploy to GitHub Pages (Free)
1. Fork this repo
2. Go to **Settings → Pages**
3. Set Source: **Deploy from branch → main → / (root)**
4. Live URL: `https://yourusername.github.io/chrono-ultra/`

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `F` | Toggle Fullscreen |
| `Space` | Start / Pause active timer |
| `L` | Record Stopwatch Lap |
| `R` | Reset Pomodoro & Stopwatch |
| `N` | Focus Notes input box |
| `V` | Toggle Voice Commands |
| `D` | Toggle Dark / Light Mode |
| `?` | Show / Hide Shortcuts Panel |
| `Esc` | Dismiss Alarm + Hide Help |
| `1` – `7` | Jump directly to Tab 1–7 |

---

## 📱 PWA Installation

**Android / Chrome:**
1. Open in Chrome → tap **⋮ Menu** → "Add to Home Screen" → "Install"

**iPhone / Safari:**
1. Open in Safari → tap **Share ⬆** → "Add to Home Screen"

**Desktop / Chrome or Edge:**
1. Look for the **⊕ install icon** in the address bar
2. Or: go to ⚙️ Settings tab → tap **"Install CHRONO on Device"**

Once installed, the app works **fully offline**.

---

## 🌐 Browser Support

| Feature | Chrome | Edge | Firefox | Safari |
|---------|--------|------|---------|--------|
| Core Clock | ✅ | ✅ | ✅ | ✅ |
| Web Audio API | ✅ | ✅ | ✅ | ✅ |
| Speech Recognition | ✅ | ✅ | ❌ | ✅ |
| Wake Lock API | ✅ | ✅ | ✅ | ✅ |
| Battery API | ✅ | ✅ | ⚠️ | ❌ |
| Geolocation | ✅ | ✅ | ✅ | ✅ |
| Fullscreen | ✅ | ✅ | ✅ | ✅ |
| PWA / Offline | ✅ | ✅ | ⚠️ | ✅ |

---

## 🔧 Customization

### Change Default Theme
Edit the `S` state object at the top of the `<script>` block:
```js
let S = {
  theme: 'purple',  // 'blue' | 'pink' | 'green' | 'yellow' | 'purple' | 'orange'
  font: 'serif',    // 'digital' | 'mono' | 'serif'
  isDark: false,    // false = light mode
  is24h: true,
  // ...
};
```

### Add More World Clock Cities
```js
const ZONES = [
  { city: 'Mumbai',    tz: 'Asia/Kolkata',       flag: '🇮🇳' },
  { city: 'New York',  tz: 'America/New_York',   flag: '🗽' },
  { city: 'Paris',     tz: 'Europe/Paris',       flag: '🇫🇷' },
  // Add any IANA timezone string
];
```

### Change Pooja Prayer Location
```js
// In renderPooja() function — replace with your city's coordinates
const lat = 25.59;   // latitude  (Patna default)
const lng = 85.14;   // longitude (Patna default)
// Find yours at: https://www.latlong.net/
```

### Add More Daily Quotes
```js
const QUOTES = [
  'Your motivational quote here. — Author',
  'अपना quote Hindi mein bhi likh sakte ho।',
  // Rotates daily by date index
];
```

### Adjust Particle Density
```js
// In initPts() function:
const n = Math.min(200, Math.floor(cvs.width * cvs.height / 5000));
// Smaller divisor = more particles | Larger = fewer
```

---

## ⚙️ How It Works

### Clock Engine
```
setInterval(tick, 1000)
  ├── Digital: update textContent
  ├── Analog:  rotate SVG hand elements via transform attribute
  ├── Flip:    compare new vs old digit, trigger CSS 3D flip animation
  ├── World:   call toLocaleTimeString() with each IANA timezone
  ├── Alarms:  check all enabled alarms for HH:MM match at :00 seconds
  └── Chime:   fire Zen Bell on hour if enabled and hour changed
```

### Audio Pipeline (Web Audio API)
```
OscillatorNode → BiquadFilterNode → GainNode → AudioContext.destination
```
All tones, bells, and noise are synthesized in-browser — no external audio assets.

### Particle System
```
requestAnimationFrame()
  ├── Clear canvas
  ├── For each particle:
  │     ├── Apply mouse repulsion force (if within 100px)
  │     ├── Apply velocity damping (× 0.985)
  │     ├── Update position with wrap-around
  │     └── Draw circle with theme color
  └── Draw connection lines between particles < 120px apart
```

### PWA Offline Strategy
Service Worker uses a **Cache-First** strategy:
1. Check cache → serve if found
2. If not cached → fetch from network → cache the response
3. If network fails and not cached → return "Offline" fallback

---

## 🤝 Contributing

Contributions are welcome! Please:

1. **Fork** the repository
2. Create a branch: `git checkout -b feature/your-feature-name`
3. Commit changes: `git commit -m 'Add: your feature description'`
4. Push: `git push origin feature/your-feature-name`
5. Open a **Pull Request**

### Ideas Welcome
- More world clock cities selector
- Google Calendar integration
- Moon phase widget
- Sunrise / Sunset countdown
- More white noise types (café, library, thunderstorm)
- Additional achievement badges
- Full Hindi language (i18n) support
- Animated SVG analog clock themes (dark, wooden, minimal)

---

## 📄 License

```
MIT License — Copyright (c) 2025 CHRONO Ultra

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files, to deal
in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software.
```

---

## 🙏 Credits

| Resource | Usage |
|----------|-------|
| [Open-Meteo](https://open-meteo.com/) | Free weather API — no key required |
| [Unsplash](https://unsplash.com/) | Random nature background images |
| [Google Fonts](https://fonts.google.com/) | Orbitron, Space Mono, Playfair Display, Sora |
| Web Audio API | All sounds synthesized — zero audio files |
| Web Platform APIs | Geolocation, Battery, Wake Lock, Speech, Fullscreen |

---

<div align="center">

Built with ❤️ using **zero dependencies** · Runs on the bare Web Platform

⭐ **Star this repo** if CHRONO helped you stay focused!

</div>
