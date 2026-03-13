# Research Digest Skill for Claude

A Claude skill that runs two recurring research digests — 
personalized to whatever you're building.

**🤖 Weekly AI Digest (Fridays):** The 2–3 most relevant AI 
research papers (from CS/ML venues) mapped to your project. 
Not a general CS digest — focused on AI/ML research with 
direct product implications. Open-source flagged. Trust signals 
for every entry. Two explanation layers — plain English and 
technical. Early signals clearly marked as unverified.

**🧠 Monthly HCI Digest:** Behavioral and HCI research 
specifically about how AI is changing human cognition, 
capability, and trust — not general UX or usability research. 
Mapped to your product decisions.

Both digests read your Claude Project context automatically. 
No setup if you're already using Projects.

---

## How it works
This is not a scheduled digest — Claude doesn't run anything 
automatically. You trigger it when you want it.

The cadence is a habit, not a push notification:
- **Fridays** → open Claude, say "Friday digest"
- **First of the month** → open Claude, say "HCI digest"

---

## Running it on a schedule

**Low-tech:** Set a recurring calendar reminder — 
Fridays for the AI digest, first of the month for HCI. 
Open Claude, say "Friday digest." Takes 10 seconds to set up.

**Automated:** Use Claude Cowork (desktop app). 
Type /schedule, describe the task, pick your cadence. 
Cowork runs it automatically whenever your computer is on.

---

## Install

### Option A — Claude.ai (web)
1. Download `research-digest-skill.skill` from [Releases](link)
2. Go to Claude.ai → Settings → Skills → Upload Skill
3. Done.

### Option B — Claude Code (CLI)
```bash
git clone https://github.com/yourname/research-digest-skill
cp -r research-digest-skill ~/.claude/skills/
```

---

## First run
If you're not in a Claude Project with existing context, 
Claude will ask you one question: a short description of 
what you're building. That's the only setup.

---

## What each digest entry includes

- 🌐 **Anyone** — plain English, no jargon
- 🔧 **If you build things** — technical substance with numbers
- A trust signal table (peer review, institution, open source, 
  benchmarks, reproducibility)
- Overall trust rating: 🟢 act on it / 🟡 directional / 🔴 early signal
- One action tag: implement now / backlog / watch / skip

---

## Trigger phrases
**AI digest:** "Friday digest" · "weekly AI research" · 
"AI papers this week" · "latest ML research" · 
"what dropped this week"

**HCI digest:** "HCI digest" · "monthly behavioral research" · 
"how AI is changing people" · "human-AI research" · 
"behavioral research for my product"

---

## Feedback
Found a paper that should have been in the digest? 
Open an issue or drop it in Discussions.

---

## Made by
[Your name] · [Your LinkedIn or site]  
Built with Claude's skill system.

⭐ Star this repo if you find it useful — helps others discover it.
