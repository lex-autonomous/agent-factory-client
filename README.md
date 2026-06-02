# Agent Factory — Client Repository

This repository contains everything needed to deploy your AI Chief of Staff agent
and begin building your own agent lab.

---

## What's in this repo

```
agent-factory-client/
│
├── CLAUDE.md                              ← Chief of Staff instructions (main agent file)
│
├── skills/
│   ├── agent-persona-creator/
│   │   └── SKILL.md                       ← How to build agent personas
│   └── answer-accuracy-standard/
│       └── SKILL.md                       ← Accuracy baseline for all responses
│
└── docs/
    ├── README.md                          ← This file
    └── ACTIVATION_PROMPT.md              ← The single paste that starts setup
```

---

## How to deploy

### Step 1 — Get access to this repo

You should have received a link to this repo from your consultant. Either:
- Fork it to your own GitHub account, or
- Download as ZIP and push to a new private repo of your own

If you want Claude to be able to read from it directly, the repo needs to be **public**,
or you need to connect GitHub to Claude via the integrations settings.

### Step 2 — Set up your Notion workspace

Your consultant will share a Notion folder with you called AGENT FACTORY. This folder
contains your agent filing system — where all agent profiles are saved, and where the
live roster lives.

Before running activation, confirm:
- You have access to the Notion folder
- Notion is connected in claude.ai → Settings → Integrations

### Step 3 — Run activation

1. Open **claude.ai**
2. Click **Projects** in the left sidebar → **New Project**
3. Name it: `Chief of Staff — [Your Name]`
4. Open a new conversation inside the project
5. Open `docs/ACTIVATION_PROMPT.md` from this repo
6. Replace `[GITHUB_REPO_URL]` with this repo's URL
7. Replace `[NOTION_FOLDER_URL]` with your shared Notion folder URL
8. Paste the prompt into the conversation
9. Follow Claude's guided setup — one step at a time

Claude will read its instructions from this repo, ask you to name your Chief of Staff,
personalize its identity, and walk you through full activation.

---

## After activation — what your Chief of Staff does

Once live, ask your Chief of Staff to:

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

## Personalizing CLAUDE.md

After your Chief of Staff is activated, your consultant will have filled in:
- `[AGENT_NAME]` — the name you chose for your Chief of Staff
- `[YOUR_NAME]` — your name
- `[ACTIVATION_DATE]` — the date it went live

You can update CLAUDE.md at any time to adjust behavior. Push changes to the repo
and your Chief of Staff will reference the updated file in future conversations.

---

## Requirements

- Claude Pro account or higher (required for Claude Projects)
- Notion account (free tier works)
- Notion connector enabled in claude.ai Settings → Integrations
- GitHub account (to fork or host this repo)

---

## Version

Agent Factory Client Repo — v1.0
