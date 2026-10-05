<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1200&color=3A86D6&center=true&vCenter=true&width=640&lines=Weather+App;Live+%26+animated+forecasts;16+languages+%C2%B7+20+backgrounds;Zero+dependencies+%C2%B7+No+API+key" alt="Weather App" />

### A living, breathing weather dashboard — in a single HTML file.

Search any city and watch the page react to the real sky: rain, snow, stars, clouds, fog and lightning.

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Open--Meteo-2563EB?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Open-Meteo" />
</p>
<p>
  <img src="https://img.shields.io/badge/API%20key-not%20required-3fb67a?style=flat-square" alt="No API key" />
  <img src="https://img.shields.io/badge/dependencies-0-3a86d6?style=flat-square" alt="Zero dependencies" />
  <img src="https://img.shields.io/badge/languages-16-d946ef?style=flat-square" alt="16 languages" />
  <img src="https://img.shields.io/badge/license-MIT-orange?style=flat-square" alt="MIT" />
</p>

[✨ Features](#-features) · [⚙️ Settings](#%EF%B8%8F-settings) · [🚀 Quick start](#-quick-start) · [⌨️ Shortcuts](#%EF%B8%8F-keyboard-shortcuts) · [🗺️ Roadmap](#%EF%B8%8F-roadmap)

</div>

---

## 📸 Preview

> Add a screenshot or GIF here, e.g. `![Weather App](./preview.png)`

---

## ✨ Features

### 🌦️ Weather intelligence

| | Feature | Details |
|---|---|---|
| 🌡️ | **Current conditions** | Temperature, feels-like, humidity, pressure, UV, visibility, cloud cover, dew point |
| ⏱️ | **Hourly forecast** | 12 / 24 / 48 hour range, draggable strip with scroll hints |
| 📅 | **Daily forecast** | 7 / 10 / 14 days with min–max range bars |
| 📈 | **Trend chart** | 4 modes: temperature, feels-like, rain chance, wind |
| 🌧️ | **Precipitation** | 24-hour probability bars with total rainfall |
| 🧭 | **Wind compass** | Direction, gusts and Beaufort scale |
| 🌅 | **Sun & moon** | Sun arc, sunrise, sunset, daylight length, live moon phase |
| 🍃 | **Air quality** | European AQI, PM2.5, PM10, NO₂, O₃ |
| 🚨 | **Smart alerts** | Heat, freezing, strong wind, high UV, thunderstorm, heavy rain, poor air |
| 👕 | **Daily advice** | What to wear + scores for running, cycling, car wash, line drying |

### 🌍 Cities & search

- 🔎 Live suggestions with **flags, region and population**, keyboard navigation (↑ ↓ Enter)
- ⭐ **Favorite cities** with live temperatures side by side
- 🕘 Recent searches and one-tap **GPS location**
- 🔗 Shareable link for any city (`#lat,lon,name`)

### 🎨 Design & motion

- 🫧 **Floating pill header** that shrinks on scroll, with a sliding **°C / °F** switch
- 🌌 **Weather-driven background** — canvas particles (rain, snow, stars, shooting stars, lightning, clouds, fog) plus floating weather icons
- 🎬 Load animations, scroll-reveal, count-up temperature, self-drawing chart, skeleton loading
- 💧 Ripple clicks, toasts and tooltips everywhere
- 🖼️ Custom **SVG icon set** — no emoji, no icon library inside the app
- 🌗 5 themes, 10 style presets, glass / outline / solid cards, fully responsive and RTL-aware

---

## ⚙️ Settings

A full-option panel with **8 tabs**, live previews and a built-in animated **guide** (the pulsing `!` button next to the title).

<table>
<tr>
<td width="50%" valign="top">

**🎨 Look**
- 10 style presets (default: *Calm*)
- Light · Dark · Auto · Sepia · Midnight
- Accent color + HSL sliders
- **16 languages** with flags
- **9 fonts per language**
- Corners, text size, number weight, digit style

**🖼️ Background**
- 20 still & animated patterns: dots, grid, squares, checker, zigzag, waves, rings, bubbles, flow, aurora, stars, grain…
- Live previews + intensity slider

**🧩 Interface**
- Glass / outline / solid cards
- High contrast, compact mode, flipped columns
- Temperature-based number color
- Content width

**✨ Effects**
- Live weather background, floating icons, particles
- Scroll animations, 3D cards, cursor glow
- Progress bar, animation speed & intensity

</td>
<td width="50%" valign="top">

**🖱️ Mouse**
- Custom cursor: ring · dot · halo
- Cursor & scrollbar colors and styles

**📏 Units**
- °C / °F / K · km/h / m/s / mph / kn
- hPa / mmHg / inHg / kPa · km / mi · mm / in
- 12 / 24 h clock
- Jalali or Gregorian calendar
- Auto refresh (5 / 15 / 30 min)

**🗂️ Content**
- Show / hide any section
- **Drag & drop** section ordering
- Hourly range & forecast days
- Heat and wind alert thresholds
- Startup behavior (last city / GPS)

**💾 Data**
- Export / import settings (JSON)
- Reset to defaults, print
- Built-in guide & shortcuts

</td>
</tr>
</table>

<details>
<summary><b>🌐 Supported languages</b></summary>

<br>

Persian · English · Arabic · Turkish · German · French · Spanish · Italian · Portuguese · Russian · Chinese · Japanese · Korean · Hindi · Urdu · Dutch

Persian and English are fully translated; other languages cover the core interface and fall back to English for the rest.

</details>

---

## 🚀 Quick start

```bash
# 1. Clone
git clone https://github.com/MahdiBarkhordar/weather-app.git
cd weather-app

# 2. Open index.html in your browser — or serve it locally
npx serve .
```

> 💡 Rename `weather-app.html` to `index.html` so it opens by default (and works out of the box on **GitHub Pages**).
> 🌐 An internet connection is needed for weather data, flags and fonts.

---

## ⌨️ Keyboard shortcuts

| Key | Action |
|:---:|--------|
| <kbd>/</kbd> | Focus search |
| <kbd>,</kbd> | Open / close settings |
| <kbd>U</kbd> | Toggle °C / °F |
| <kbd>↑</kbd> <kbd>↓</kbd> <kbd>Enter</kbd> | Navigate and pick search results |
| <kbd>Esc</kbd> | Close panel or dropdown |

---

## 🧱 Tech notes

- 📄 **One self-contained file** — HTML, CSS and JavaScript, no build step
- 💾 Settings persist in `localStorage`
- 📱 Responsive, RTL / LTR aware, respects `prefers-reduced-motion`
- 🚀 Fonts load on demand, only for the language you pick

## 🔌 Data sources

| Service | Used for |
|---------|----------|
| [Open-Meteo](https://open-meteo.com) | Forecast, geocoding, air quality (free, no key) |
| [flagcdn](https://flagcdn.com) | Country flags |
| [Google Fonts](https://fonts.google.com) | Per-language typography |

---

## 🗺️ Roadmap

- [ ] 🛰️ Precipitation radar map
- [ ] 🌐 Complete translations for all 16 languages
- [ ] 🔔 Severe-weather browser notifications
- [ ] 📲 PWA & offline support

---

## 👨‍💻 Author

<div align="center">

**Mehdi Barkhordar** — web designer & developer

[![GitHub](https://img.shields.io/badge/GitHub-MahdiBarkhordar-181717?style=for-the-badge&logo=github)](https://github.com/MahdiBarkhordar)

If you like this project, give it a ⭐ — it really helps!

<sub>Released under the MIT License.</sub>

</div>
