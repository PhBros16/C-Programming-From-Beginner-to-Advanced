# ⚙️ C: From Zero to Master

An interactive C programming guide — from absolute zero to advanced topics — with a real GCC compiler, AI-powered code evaluation, gamification, and daily challenges.

🌐 **Live at:** [c-lang-master.vercel.app](https://c-lang-master.vercel.app)

---

## Features

- **Real GCC compiler** via Piston API (free, no setup required)
- **AI code evaluation** — Gemini analyzes your code, explains errors in Portuguese and gives feedback
- **Progressive help system** — hints unlock gradually as you fail attempts
- **XP & level system** — Curious → Apprentice → Programmer → Debugger → Hacker → C Master
- **Daily challenges** — a new coding problem every day
- **Review mode** — spaced repetition of completed topics
- **Guided projects** — Grade Calculator, Guessing Game, Caesar Cipher, Tic-Tac-Toe
- **Personal notes** — saved per section in your browser
- **Auto-save** — progress stored locally via localStorage
- **Streak tracking** — daily study streak counter

---

## Curriculum

| Phase | Topics | Course |
|-------|--------|--------|
| 0 — Start | Computational Thinking, Setup, Hello World | ✅ |
| 1 — Fundamentals | Data Types, Operators, Truth Table, I/O | ✅ |
| 2 — Control Flow | Decision Structures, Loops, Switch | ✅ |
| 3 — Structures | Functions, Arrays, Strings, Structs | Partial |
| 4 — Advanced | Pointers, Dynamic Memory, Files | ➕ Beyond |

---

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS (single file)
- **Compiler:** [Piston API](https://emkc.org) — free, public, no key required
- **AI:** Google Gemini 1.5 Flash — free tier (1M tokens/day)
- **Hosting:** Vercel (free)
- **Storage:** localStorage (client-side, no database)

---

## Deploy Your Own

### 1. Get a Gemini API Key (free)
- Go to [aistudio.google.com](https://aistudio.google.com)
- Click **Get API key** → **Create API key**
- Copy the key

### 2. Fork & Deploy to Vercel
- Fork this repository
- Go to [vercel.com](https://vercel.com) and import the repo
- Click **Deploy**

### 3. Add the API Key
- In Vercel: **Settings → Environments → Production → Add Environment Variable**
- Name: `GEMINI_API_KEY`
- Value: your Google AI Studio key
- Click **Save** → **Redeploy**

---

## Project Structure

```
├── index.html        — Complete interactive guide (single file)
├── api/
│   └── gemini.js     — Serverless function (Gemini API proxy)
├── vercel.json       — Routing configuration
└── README.md
```

---

Built for the *Introduction to Computer Programming* course.
