# 🕯️ Study Light

A minimal, warm-toned ambient lighting web app for focused study sessions. Open it in your browser, dim the lights, and let it set the mood.

---

## ✨ Features

- **Large live clock** — elegant serif typography displaying hours and minutes at a glance
- **Seconds arc** — a circular progress ring that animates every second
- **Date & period row** — shows the current weekday, full date, and time of day (Morning, Afternoon, Evening, etc.)
- **Brightness control** — a slider to fine-tune screen intensity for your environment
- **Warm / Cool tint toggle** — switch between a warm amber tone and a cool blue-white light to match your preference or the time of day
- **Paper texture & ambient glow** — subtle background effects that reduce eye strain during long sessions
- **Custom cursor** — a warm accent dot that replaces the default cursor
- **Smooth animations** — staggered fade-in on load for a calm, intentional feel

---

## 🖥️ Usage

| Control | Description |
|---|---|
| **Brightness slider** | Adjusts overall screen brightness from dim to full |
| **Tint button** (☀️/❄️) | Toggles between warm amber and cool blue-white themes |

The clock updates every second automatically. No interaction required — just open and focus.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, backdrop-filter) |
| Logic | Vanilla JavaScript (no frameworks or libraries) |
| Fonts | Google Fonts — *DM Serif Display* + *DM Mono* |

The entire app is a **single self-contained `.html` file** with zero external runtime dependencies beyond the Google Fonts stylesheet.

---

## 📁 Project Structure

```
assets/light.png     ← the app icon
study-light.html   ← the entire app (HTML + CSS + JS in one file)
README.md          ← this file
```

---

## 🎨 Design Decisions

- **Warm paper palette** (`#f5f0e8`) was chosen to mimic natural desk lighting and reduce blue-light fatigue
- **DM Serif Display** gives the clock a refined, timeless character without feeling sterile
- **DM Mono** is used for labels and metadata to create a clean typographic contrast
- The **cool tint mode** swaps the entire color system via CSS custom properties — no class juggling needed
- The **seconds arc** uses an SVG `stroke-dashoffset` technique for smooth, performant animation

---

## 📄 License

MIT — free to use, modify, and share.