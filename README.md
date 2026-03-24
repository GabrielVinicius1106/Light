# 🕯️ Study Light

A minimal, warm-toned ambient lighting web app with built-in productivity tools for focused study sessions. Open it in your browser, dim the lights, and let it set the mood.

---

## ✨ Features

- **Large live clock** — elegant serif typography displaying hours and minutes at a glance.
- **Seconds arc** — a circular progress ring that animates every second.
- **Date & period row** — shows the current weekday, full date, and time of day (Morning, Afternoon, Evening, etc.).
- **Pomodoro Timer** — built-in timer with Focus (25m), Short Break (5m), and Long Break (15m) phases, including session tracking.
- **Study Goals (To-Do List)** — keep track of your tasks directly in the app. Your goals are saved locally in your browser.
- **Theme Picker** — switch between a Warm (🕯️) amber tone and a Cool (🔵) blue-white light to match your preference.
- **Paper texture & ambient glow** — subtle background effects that reduce eye strain during long sessions.
- **Custom cursor** — an accent dot that replaces the default cursor.

---

## 🖥️ How to Use

The simplest way to use Study Light is directly from the files in your browser. No build steps or servers required!

1. **Download or Clone the repository:**
   ```bash
   git clone https://github.com/your-username/study-light.git
   ```
2. **Open the app:**
   Navigate to the project folder and double-click `index.html` to open it in your default web browser.

### Using the App
- **Themes:** Click the "Theme" button at the bottom to switch between Warm and Cool lighting.
- **Pomodoro:** Click "Start" on the Pomodoro card. It will automatically guide you through focus and break sessions.
- **Study Goals:** Type a goal in the input field and press Enter or click "Add". Check them off as you complete them.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, backdrop-filter) |
| Logic | Vanilla JavaScript (no frameworks or libraries) |
| Storage | `localStorage` for saving themes and study goals |
| Fonts | Google Fonts — *DM Serif Display* + *DM Mono* |

The core of the app is contained within `index.html` with zero external runtime dependencies beyond the Google Fonts stylesheet.

---

## 📁 Project Structure

```text
index.html         ← the main app (HTML + CSS + JS)
README.md          ← this file
assets/
  └── light.png    ← the app favicon
```

---

## 📄 License

MIT — free to use, modify, and share.