# 🎮 Agentic Engineer Development Plan

> A gamified daily habit tracker built to level up AI/ML engineering skills — one quest at a time.

🔗 **[Open the Quest Board →](https://sid9394.github.io/AgenticEngineerDevelopmentPlanWebsite/)**

---

## What is this?

A personal growth dashboard disguised as an RPG quest board. Every day starts fresh with a set of skill-building tasks across three domains: **AI/RAG**, **DSA**, and **Web**. Complete quests to earn XP, level up your skills, and unlock rewards — no external accounts, no tracking, just a browser and discipline.

Built as a single `index.html` file with zero dependencies. All state lives in `localStorage`.

---

## Features

- **Daily quests** — structured tasks across AI/RAG, DSA, and Web development
- **XP system** — earn points per quest, track progress toward 400 XP daily cap
- **Difficulty tiers** — toggle quests between Easy / Medium / Hard for scaled XP rewards
- **Skill levels** — separate XP tracking for AI/RAG, DSA, and Web that feeds into individual skill levels
- **Quest notes** — inline notes per quest to log what you actually studied or built
- **Weekly streak grid** — visual 7-day history showing full completions, partial days, and rest days
- **Streak counter** — tracks consecutive fully-completed days
- **Auto day reset** — automatically archives the previous day's data and resets quests at midnight
- **Activity log** — timestamped record of every quest check/uncheck with XP and difficulty
- **Reward unlocks** — real rewards (game session, takeout, rest day) unlock at XP milestones
- **Export notes** — download all quest notes as a `.md` file for a learning log
- **No sign-up, no backend** — fully offline, runs in any browser

---

## Quest Structure

| Quest | Tag | XP (Easy / Medium / Hard) |
|---|---|---|
| LeetCode problem (NeetCode 150) | DSA | 50 / 70 / 100 |
| RAG / Agents hands-on session | AI | 80 |
| System design concept | DSA | 40 / 60 / 90 |
| AI reading / course | AI | 50 |
| Portfolio / website work | Web | 40 / 60 / 80 |
| No gaming before quests | Bonus | 30 |
| Full day streak bonus | Bonus | 70 |

---

## Rewards

| Reward | XP Required |
|---|---|
| 🎮 Game session | 100 XP |
| 🍜 Takeout treat | 200 XP |
| 🎬 Movie night | 250 XP |
| 📚 Buy a course | 350 XP |
| 🛋️ Full rest day | 400 XP |

---

## Usage

No installation needed. Just open the link or clone and open `index.html` in a browser:

```bash
git clone https://github.com/sid9394/AgenticEngineerDevelopmentPlanWebsite.git
cd AgenticEngineerDevelopmentPlanWebsite
open index.html
```

All data is stored in your browser's `localStorage` — nothing is sent anywhere.

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- Google Fonts — [Syne](https://fonts.google.com/specimen/Syne) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)
- `localStorage` for persistence
- Zero frameworks, zero build step

---

## Background

I'm a Senior AI/ML Engineer targeting agentic systems and document intelligence. This board keeps my upskilling balanced across RAG/LLM engineering, algorithmic thinking, and portfolio work — without letting any one area slide.

The gamification layer makes the daily habit sticky. Rewards are real — no cheating the system.

---

*Built for personal use. Open sourced in case it helps someone else stay consistent.*
