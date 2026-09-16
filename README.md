# ⚡ Apex Focus — Super To-Do & Productivity Suite

A stunning, ultra-modern productivity suite built as a single zero-dependency HTML file. Powered by glassmorphism design, smooth animations, and real-time local persistence.

🌐 **Live Demo**: [https://sandeeptrangarajan.github.io/todo/](https://sandeeptrangarajan.github.io/todo/)

---

## ✨ Features

### ✅ Super-Charged Task Manager
- **Projects & Categories**: Organize tasks into 💼 Work, 🧠 Study, ⚡ Personal, 🎯 Goals, 🛒 Shopping
- **Priority Levels**: 🔴 High, 🟡 Medium, 🟢 Low with glowing color-coded chips
- **Due Date Badges**: Overdue, Due Today, Tomorrow detection
- **Smart Filtering**: All, Pending, Completed, ⭐ Starred, 🔴 Overdue views
- **Multi-Sort**: By Priority, Due Date, Newest, or A→Z
- **Subtask Progress Bars**: Visual mini progress bars per task
- **Star / Favorite**: Pin important tasks for quick access
- **Completion Ring**: Animated SVG progress ring showing daily completion %

### 🔥 Habit Streak Matrix
- 7-day visual dot grid tracker per habit
- Live streak counter with 🔥 flame badges
- Best streak history tracking
- Stat cards for: Total habits, done today, active streaks, best streak

### ⏱️ Pomodoro Focus Station
- **Focus** (25m) / **Short Break** (5m) / **Long Break** (15m) modes
- Animated circular SVG countdown arc
- Ambient soundscapes synthesized entirely with **Web Audio API** (no audio files!):
  - 🔇 Off | 🌧️ Rain | 🌲 Forest | ☕ Cafe | 🌊 White Noise
- Session dot tracker — up to 8 pom sessions shown
- Tab title shows timer countdown when running

### 📊 Analytics & Insights
- Weekly bar chart of completed tasks
- 28-day completion heatmap
- Priority distribution breakdown
- Project breakdown
- Total focus sessions & minutes logged

### 🎨 Premium Design
- Dark / Light theme toggle with smooth transition
- Glassmorphism cards with ambient gradient glow
- Google Fonts: **Outfit** + **Inter** + **JetBrains Mono**
- Micro-animations on task insert, hover, completion
- 🎉 Confetti canvas celebration when all tasks are done
- ✅ Completion chime & ⏱️ gong sounds on focus session end

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `N` | New task (from anywhere) |
| `Ctrl/Cmd + K` | Focus search bar |
| `Enter` | Submit task / habit |
| `Escape` | Close modal / blur search |
| `Space` | Play/Pause Pomodoro (Focus view) |

### 💾 Data Persistence
- All data saved to **localStorage** (works offline, no server needed)
- JSON **Export / Import** for backup and restore
- **Clear completed** and **full reset** options

---

## 🚀 GitHub Pages Deployment

This app is auto-deployed via GitHub Actions on every push to `main`.

To enable on your fork:
1. Go to **Settings → Pages**
2. Source: `Deploy from a branch`, Branch: `main`, Folder: `/ (root)`
3. Save → live at `https://<username>.github.io/todo/`

---

## 💻 Run Locally

Open `index.html` directly in any modern browser — **zero build steps, zero dependencies!**

```bash
# Or serve with any local server:
npx serve .
python -m http.server 8000
```