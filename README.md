# 🏛️ Dr. Jiang Xueqin — Predictive History AI

An AI persona of **Professor Jiang Xueqin**, creator of the [Predictive History](https://www.youtube.com/@PredictiveHistory) YouTube channel — built from 114+ lecture transcripts and distilled into 123 analytical pillars.

> *"The imagination is the animating force of the universe. Love is the unifying force."*  
> — Dr. Jiang, Civilization #60 END

---

## What This Is

Professor Jiang teaches *Predictive History* — an attempt to connect the past into a coherent story, explain the present, and predict the future. Inspired by Isaac Asimov's *Foundation* series, the goal is to build the intellectual foundations of **psychohistory**: mathematically modelling history to predict civilisational outcomes.

This chatbot embodies that persona, trained on:

| Series | Episodes | Status |
|---|---|---|
| 🔐 Secret History | #1–28 | ✅ Complete |
| 🌍 Geo-Strategy | #1–12 + Update#1–8 | ✅ Complete |
| 🏛️ Civilization | #1–60 | ✅ Complete |
| 🎮 Game Theory | #1–12 | 🔄 Ongoing |
| 📖 Great Books | #1–6 | 🔄 Ongoing |

**123 Pillars** — from the Alchemy of Power (P1) to the Decline and Fall of the American Empire (P123).

---

## Quick Start

**No installation. No build step. One file.**

1. **Clone or download** this repository
2. **Open `index.html`** in any modern browser
3. **Enter your Anthropic API key** in the sidebar (get one at [console.anthropic.com](https://console.anthropic.com))
4. Start asking Professor Jiang about history, geopolitics, or civilisation

```bash
git clone https://github.com/Mkt-2024/dr-jiang-predictive-history.git
cd dr-jiang-predictive-history
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

> **Note:** Because the app calls the Anthropic API directly from your browser, you may encounter CORS errors in some local environments. If `open index.html` doesn't work, try:
> ```bash
> python3 -m http.server 8080
> # then open http://localhost:8080
> ```

---

## Deploy to GitHub Pages (Public URL)

Turn this into a shareable link in 3 steps:

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit — Dr. Jiang AI persona"
   git remote add origin https://github.com/Mkt-2024/dr-jiang-predictive-history.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Source: **Deploy from a branch** → `main` → `/ (root)`
   - Click **Save**

3. **Share your URL:**
   ```
   https://Mkt-2024.github.io/dr-jiang-predictive-history/
   ```

GitHub Pages will serve `index.html` automatically. Your visitors enter their own Anthropic API keys — you pay nothing for their usage.

---

## API Key Security

- Keys are stored in **sessionStorage** — they clear when the browser tab is closed
- Keys are sent **directly to Anthropic's API** — they never touch any intermediate server
- The `anthropic-dangerous-direct-browser-access` header is required for browser-based calls
- Each visitor uses **their own key** — you are not billed for others' usage

---

## Try Asking Professor Jiang

- *"Why did Putin really invade Ukraine?"*
- *"What is the EOC Cycle and where are we in it?"*
- *"How did Shakespeare father the British Empire?"*
- *"What did Marx get wrong about human psychology?"*
- *"What is the Steward Principle and how does it break the Shepherd-Sheep cycle?"*
- *"Why will America invade Iran?"*
- *"How does the K-Space Matrix explain civilisational failure modes?"*
- *"What did Robespierre really understand that Napoleon didn't?"*

---

## The Analytical Framework

Professor Jiang teaches through three tools:

1. **Historical Patterns** — Does this event fit a larger recurring model? If not, something is wrong.
2. **Game Theory** — Map all actors' real interests (not stated). Find the dominant strategy.
3. **Religious Eschatology** — Every culture's sacred text reveals how they want history to end. Read it.

And one test for truth (*Theory of Truth, SH#28*):
- Does it connect the past into a coherent narrative?
- Does it explain the present?
- Does it predict the future?

---

## Technical Notes

- **Model:** `claude-sonnet-4-20250514` (change in `index.html` if desired)
- **Context:** System prompt is ~50K tokens; conversation history accumulates per session
- **File size:** ~380KB (system prompt embedded; no CDN dependencies for core logic)
- **Browser support:** All modern browsers (Chrome, Firefox, Safari, Edge)

---

## About Professor Jiang

Jiang Xueqin was born in China (1976), immigrated to Toronto at age 6, and attended **Yale University** (English Literature). He has spent 25+ years working in Chinese education reform across every level — kindergarten through university — as teacher, principal, and curriculum director.

The Predictive History YouTube channel grew from classroom lectures at a private Beijing high school. In May 2025, it grew from 300 to 20,000+ subscribers. The 60-episode Civilization course covers the full span of human history, from the Ice Age to the Fall of the American Empire.

His long-term ambition: build a school modelled on Plato's Academy and the Jedi Temple — training the next generation of historians, writers, and intellectuals to develop the science of psychohistory.

---

## ⚠️ Epistemic Guardrails

This AI persona maintains five hard-coded epistemic guardrails:

- **A — Holocaust:** Evidence is overwhelming and beyond dispute. The persona never endorses denial.
- **B — Muhammad/614 CE:** Dr. Jiang's claim that Muhammad led Jerusalem's conquest in 614 CE is a factual timeline error. The persona flags this as speculative and treats Muhammad (PBUH) and Islam with respect.
- **C — Al-Aqsa vs. Dome of Rock:** Two separate structures. Never conflated.
- **D — Game Theory:** Dr. Jiang's "game theory" is a popular heuristic, not formal mathematical game theory.
- **E — Model vs. Fact:** The entire Predictive History framework is a model, not revealed truth.

---

*Built with Claude (Anthropic) · 123 Pillars · Civ#1–60 Complete*  
*"Ad Omnisphera!" 🌌⚪👁️*
