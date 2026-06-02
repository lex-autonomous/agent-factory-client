<p align="center">
  <img src="lex-logo" alt="Lex Autonomous" width="200"/>
</p>

<h1 align="center">Agent Factory — Client Edition</h1>
<p align="center">AI agent lab starter kit for building and managing AI agent teams.</p>

---

# What This Is

This repository is your complete AI agent lab setup. It contains everything your AI
Chief of Staff needs to come online — its identity, its operating rules, its skill
files, and the blueprint for building your Notion workspace.

You do not need to configure anything manually. Your Chief of Staff reads this repo
and walks you through setup as a conversation.

---

# What's in This Repo
agent-factory-client/
│
├── CLAUDE.md                         ← Chief of Staff identity and operating rules
│
├── skills/
│   ├── agent-persona-creator/
│   │   └── SKILL.md                  ← How to build agent personas
│   └── answer-accuracy-standard/
│       └── SKILL.md                  ← Accuracy baseline for all responses
│
└── docs/
├── ACTIVATION_PROMPT.md          ← The single paste that starts everything
├── NOTION_SETUP.md               ← Blueprint for building your Notion workspace
└── README.md                     ← This file

---

# Requirements

- **Claude Pro account** — required for Claude Projects
- **Notion account** — free tier works
- **Notion connector enabled** — claude.ai → Settings → Integrations → Notion → Connect

---

# How to Deploy

### Step 1 — Open the activation prompt
Go to `docs/ACTIVATION_PROMPT.md` in this repo and copy the prompt inside it.

### Step 2 — Create a Claude Project
1. Open claude.ai
2. Click **Projects** in the left sidebar
3. Click **New Project**
4. Name it: `Chief of Staff — [Your Name]`
5. Open a new conversation inside the project

### Step 3 — Paste and go
Paste the activation prompt into the conversation and send it.

Claude will:
- Read its instructions from this repo
- Ask you what you want to name your Chief of Staff
- Build your entire Notion workspace one step at a time
- Confirm when everything is live
- Ask if you are ready to build your first agent

You do not need a Notion folder. You do not need to configure anything.
Claude handles all of it.

---

# After Activation — What Your Chief of Staff Does

**Build a new agent**
- "I need an agent that handles client onboarding."
- "Build me a copywriter named Jordan."
- "Spin up a lead qualification agent — consumer-facing."

**Update an existing agent**
- "Add [project name] as a win for [agent name]."
- "Upgrade [agent name] with [new skill]."

**View your roster**
- "Show me the org chart."
- "Pull [agent name]'s full profile."
- "What agents do I have deployed?"

---

# How the Notion Workspace Gets Built

Your Chief of Staff reads `docs/NOTION_SETUP.md` and creates this in your Notion:
📁 AGENT FACTORY — [Your Name]
├── 📄 LAB OS
├── ⚙️ Chief of Staff — System Prompt Template
├── 📖 Setup Guide
├── 📁 AGENTS
└── 📊 LIVE ROSTER

Every agent gets filed to AGENTS automatically. LIVE ROSTER tracks every agent,
their version, and activation date. You never file anything manually.

---

# Delivered by

**Lex Autonomous** — AI Operations Consulting

---

*Agent Factory Client Edition — v1.1*
