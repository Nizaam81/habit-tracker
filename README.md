# Habit Tracker

Minimal web app to **build daily habits** and track your streaks.
No signup.
No API.
Just consistent habit building.

---

## Live Demo

https://habits-tracker-app.vercel.app/

---

## Features

- **16 preset habits** with emojis (exercise, read, meditate, code, learn, etc.)
- **Custom habits** – add any habit with custom name
- **Streak tracking:**
  - Current streak (consecutive days)
  - Best streak (personal record)
  - Per-habit streaks
- **Progress dashboard:**
  - Daily completion count
  - Completion percentage
  - Visual progress bar
  - Best streak highlight
- **GitHub-style heatmap:**
  - 77-day activity view
  - Color intensity by completion rate
  - Tooltip with daily stats
- **Full CRUD** – add, toggle, delete habits
- **Auto-save** – data persists in browser localStorage
- Clean, responsive, Apple-inspired dark UI
- No authentication
- No ads
- No watermarks

---

## Tech Stack

- React (Vite)
- Vanilla CSS (Apple-inspired UI)
- LocalStorage (data persistence)
- Vercel (static deploy)

---

## How It Works

1. **Add a habit** from 16 presets or create custom
2. **Check off habits** daily to build streaks
3. **View your dashboard** with completion stats and progress
4. **Track patterns** with the GitHub-style heatmap
5. **Edit or remove** habits anytime

> Everything is computed client-side. Nothing is uploaded.

---

## Privacy

All processing happens **locally in your browser**.
No data is sent to any server.

---

## Installation

```bash
# Clone the repo
git clone <YOUR_REPO_URL>

# Install dependencies
cd habits
npm install

# Run locally
npm run dev
```
