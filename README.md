# The Ledger — To-Do & Habit Tracker

A clean, elegant, paper-styled to-do list and habit tracker web application designed for daily productivity.

Live Demo: [https://sandeeptrangarajan.github.io/todo/](https://sandeeptrangarajan.github.io/todo/)

---

## ✨ Features

- **Daily Tasks**:
  - Add tasks with priority levels (Low, Medium, High) and optional due dates.
  - Interactive checkboxes with smooth completion state.
  - Automatic sorting (pending high-priority first, completed items at the bottom).
  - Overdue task indicator badges.
- **Daily Habits**:
  - Track 7-day visual consistency for habits.
  - Interactive day-by-day checkoff circles.
  - Intelligent streak counter (preserves streaks and updates dynamically).
- **Statistics Bar**:
  - Real-time counters for completed tasks, active streaks, and longest streaks.
- **Offline & Cross-Environment Persistence**:
  - Automatically saves all your data to browser `localStorage`.
  - Also compatible with sandbox iframe storage environments.

---

## 🚀 How to Deploy to GitHub Pages

1. Go to your repository on GitHub: `https://github.com/sandeeptrangarajan/todo`
2. Click **Settings** (top navigation tab).
3. In the left sidebar under "Code and automation", click **Pages**.
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` (or your default branch) and `/ (root)`.
   - Click **Save**.
5. Wait ~1-2 minutes. GitHub will provide your live URL:
   `https://sandeeptrangarajan.github.io/todo/`

> **Note**: The main file is named `index.html`, ensuring GitHub Pages and static web hosts automatically serve it at the root URL.

---

## 💻 Running Locally

Simply double-click `index.html` or open it in any web browser, or serve it using any local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```
Then visit `http://localhost:8000` (or `http://localhost:3000`).