# 🧠 Sid's Senior AI Engineer Prep Hub

> A personal upskilling system built to go from AI/ML Engineer at a services firm to **Senior AI Engineer at a GCC** — systematically, without losing balance.

🔗 **[Daily Quest Board →](https://sid9394.github.io/AgenticEngineerDevelopmentPlanWebsite/)**
🔗 **[Interview Playbook →](https://sid9394.github.io/AgenticEngineerDevelopmentPlanWebsite/playbook.html)**

---

## What Is This?

Two tools, one goal: land a Senior AI Engineer role at a structured product company or GCC in Bangalore.

**The Quest Board** is a gamified daily habit tracker — complete skill-building quests across AI/RAG, DSA, and Web to earn XP and unlock rewards. No guilt, no grind, just a system.

**The Interview Playbook** is a personalised prep guide built around 7+ years of production AI experience — ECU Worldwide, XPO Logistics, ADB Philippines, Google CCAI, and more — mapped directly to the questions Senior AI Engineer loops at Adobe, SAP Labs, ServiceNow, Salesforce, and Microsoft actually ask in 2026.

---

## The Two Tools

### 🎮 Daily Quest Board (`index.html`)

A single-file habit tracker disguised as an RPG quest board.

| Feature | Details |
|---|---|
| Daily quests | Structured tasks across AI/RAG, DSA, and Web |
| XP system | Earn XP per quest, track toward 400 XP daily cap |
| Difficulty tiers | Toggle Easy / Medium / Hard per quest for scaled XP |
| Skill levels | Separate XP tracking for AI/RAG, DSA, Web → individual skill levels |
| Quest notes | Inline text field per quest — log what you actually studied or built |
| Weekly streak grid | 7-day visual history: full completion (green), partial (amber), rest (grey) |
| Streak counter | Consecutive fully-completed day count in header |
| Auto day reset | Archives previous day data at midnight, resets quests automatically |
| Activity log | Timestamped record of every quest check/uncheck with XP + difficulty |
| Reward unlocks | Real rewards (game session, takeout, rest day) unlock at XP milestones |
| Export notes | Download all quest notes as a `.md` file for a daily learning log |
| No sign-up | Fully offline, no backend, zero dependencies |

**Quest structure:**

| Quest | Tag | XP (Easy / Medium / Hard) |
|---|---|---|
| LeetCode problem (NeetCode 150) | DSA | 50 / 70 / 100 |
| RAG / Agents hands-on session | AI/RAG | 80 |
| System design concept | DSA | 40 / 60 / 90 |
| AI reading / course | AI/RAG | 50 |
| Portfolio / website work | Web | 40 / 60 / 80 |
| No gaming before quests | Bonus | 30 |
| Full day streak bonus | Bonus | 70 |

**Rewards:**

| Reward | XP Needed |
|---|---|
| 🎮 Game session | 100 XP |
| 🍜 Takeout treat | 200 XP |
| 🎬 Movie night | 250 XP |
| 📚 Buy a course | 350 XP |
| 🛋️ Full rest day | 400 XP |

---

### 📖 Senior AI Engineer Interview Playbook (`playbook.html`)

A 14-section personalised interview prep site built around real 2025–26 GCC hiring data and my actual production projects.

**Target companies:** Adobe Bangalore (₹40–60L), SAP Labs (₹38–55L), ServiceNow India (₹42–65L), Salesforce India (₹40–62L), Microsoft IDC (₹45–70L), Google Bangalore (₹55–90L)

**What's inside:**

| Section | Content |
|---|---|
| 8-Week Roadmap | Week-by-week tasks: what to study, build, and ship on GitHub each week |
| Skill Gap Matrix | Honest bars for 14 skill areas vs. Senior AI Engineer bar at GCCs |
| Target Companies | 8 companies with fit analysis, salary bands, and interview loop structure |
| LLM Fundamentals | 10+ questions: attention, KV cache, tokenisation, hallucination, RAG vs fine-tuning |
| RAG & Retrieval | Chunking, hybrid search, HyDE, contextual retrieval, failure diagnosis |
| Agents & Orchestration | ReAct, orchestrator vs. LLM boundary, multi-agent patterns, debugging loops |
| System Design | 5 full worked designs: Doc Intelligence, Multilingual Bot, LLM Gateway, Compliance Agent, Enterprise RAG |
| ML Core & DSA | Bias-variance, LoRA, class imbalance + NeetCode 150 priority breakdown |
| Production & MLOps | LLM versioning, observability stack, model drift detection |
| Behavioral (STAR) | 5 themes with model answers built around my actual projects |
| Flash Cards | 18 click-to-flip cards across all topics |
| Project → Interview Map | ECU, XPO, ADB, GST CrewAI, CCAI, Life Insurance → interview talking points |
| Interview Checklist | Clickable checklist: week before, day before, during |

---

## Background

I'm a Senior AI/ML Engineer with 7+ years of production experience at Datamatics Global Services, building AI systems across logistics, government, insurance, and conversational AI. My production work includes:

- **ECU Worldwide** — Global document intelligence platform; multi-country/language invoice processing; benchmarked all frontier LLMs, selected Gemini
- **XPO Logistics** — Invoice and shipping document processing; OpenAI + Gemini combination
- **ADB Philippines** — Multilingual grievance redressal NLP system; AWS; Tagalog/Filipino language handling
- **H&P (undisclosed)** — US veterinary chain voice + chat bot using Google CCAI and LLMs
- **GST/TDS Compliance** — Multi-agent workflow using CrewAI for Indian tax compliance validation
- **Life Insurance** — Real-time fraud prediction engine with production scoring pipeline

**Target:** Senior AI Engineer roles at GCCs (Adobe, SAP Labs, ServiceNow, Salesforce, Microsoft IDC) in Bangalore, on the Staff/Principal IC track.

**Tech stack:** Python, LangChain, CrewAI, RAG, Google CCAI, Gemini, OpenAI, AWS, GCP, Azure OpenAI, FastAPI, ElasticSearch, PyTorch, HuggingFace Transformers, SpaCy, PostgreSQL, Docker

---

## Repository Structure

```
AgenticEngineerDevelopmentPlanWebsite/
├── index.html          # Daily Quest Board (gamified habit tracker)
├── playbook.html       # Senior AI Engineer Interview Playbook
└── README.md           # This file
```

---

## Running Locally

No build step, no install.

```bash
git clone https://github.com/sid9394/AgenticEngineerDevelopmentPlanWebsite.git
cd AgenticEngineerDevelopmentPlanWebsite

# Open either tool in your browser
open index.html        # Quest Board
open playbook.html     # Interview Playbook
```

All state is saved in `localStorage` — nothing sent anywhere.

---

## The 8-Week Sprint

| Week | Focus | Quest Tag |
|---|---|---|
| 1–2 | LLM internals + RAG pipeline mastery | AI/RAG |
| 3–4 | Agentic systems + system design framework | AI/RAG + DSA |
| 5 | Production layer: evals, observability, cost control | AI/RAG |
| 6 | Fine-tuning, multimodal, vector DB landscape | AI/RAG |
| 7 | Full mock interview simulations | All |
| 8 | Active applications + portfolio polish | Web |

DSA runs daily throughout all 8 weeks: 1 NeetCode 150 medium per day.

---

## Tech Stack (This Site)

- Vanilla HTML / CSS / JavaScript — zero frameworks, zero build step
- Google Fonts — [Fraunces](https://fonts.google.com/specimen/Fraunces) (display) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (code/UI)
- `localStorage` for all persistence
- GitHub Pages for hosting

---

## Live URLs

| Tool | URL |
|---|---|
| Quest Board | `https://sid9394.github.io/AgenticEngineerDevelopmentPlanWebsite/` |
| Interview Playbook | `https://sid9394.github.io/AgenticEngineerDevelopmentPlanWebsite/playbook.html` |

To enable GitHub Pages: **Settings → Pages → Source: Deploy from branch → main / (root) → Save**

---

*Built for personal use. Open sourced in case it helps someone else make the same transition.*
