<p align="center">
  <img src="../lex-logo" alt="Lex Autonomous" width="200"/>
</p>

<h1 align="center">Agent Factory — Client Edition</h1>
<p align="center">AI agent lab starter kit for building and managing AI agent teams.</p>

---

# Two Delivery Tracks

This system supports two setup paths depending on your client's technical comfort level.

| | GitHub Track | Direct File Track |
|---|---|---|
| **Best for** | Tech-comfortable clients | Non-technical clients |
| **GitHub account needed** | Yes | No |
| **Setup time** | 15–20 min | 5–10 min |
| **Updates** | Client syncs their fork | You send new files |
| **Activation prompt** | `ACTIVATION_PROMPT_GITHUB.md` | `ACTIVATION_PROMPT_DIRECT.md` |

---

# What's in This Repo

```
agent-factory-client/
│
├── CLAUDE.md                                       ← Chief of Staff identity and operating rules
│
├── skills/
│   ├── agent-persona-creator/
│   │   └── SKILL.md                                ← How to build agent personas
│   └── answer-accuracy-standard/
│       └── SKILL.md                                ← Accuracy baseline for all responses
│
└── docs/
    ├── README.md                                   ← This file
    ├── ACTIVATION_PROMPT_GITHUB.md                 ← For tech-comfortable clients
    ├── ACTIVATION_PROMPT_DIRECT.md                 ← For non-technical clients
    └── NOTION_SETUP.md                             ← Blueprint Claude uses to build Notion workspace
```

---

# Requirements — Both Tracks

- **Claude Pro account** — required for Claude Projects
- **Notion account** — free tier works (notion.so)
- **Notion connector enabled** — claude.ai → Settings → Integrations → Notion → Connect

---

# GitHub Track — Setup

*Use this for clients who are comfortable with GitHub.*

### Step 1 — Client forks this repo

1. Client signs into their GitHub account at github.com
2. Client opens this repo page
3. Clicks the **Fork** button — top right corner of the page
4. Clicks **Create fork**
5. GitHub creates their own copy instantly — `github.com/[their-username]/agent-factory-client`

**Important:** Once forked, their copy is independent. If you update this repo later,
they will not receive updates automatically. They need to click "Sync fork" on their
GitHub repo, then hit the Sync icon inside their Claude Project.

### Step 2 — Create a Claude Project

1. Open claude.ai → click **Projects** → click **New Project**
2. Name it: `Chief of Staff — [Their Name]`

### Step 3 — Connect forked repo to the Project

1. Click the project name → **Project Settings**
2. Under **Files**, click **+**
3. Select **GitHub**
4. Find and select their forked repo: `[their-username]/agent-factory-client`
5. Confirm — files are now synced into project knowledge

### Step 4 — Paste the activation prompt

1. Open `docs/ACTIVATION_PROMPT_GITHUB.md` from their forked repo
2. Copy everything between the lines
3. Open a new conversation inside their Claude Project
4. Paste and send
5. Follow what Claude tells them — one step at a time

---

# Direct File Track — Setup

*Use this for non-technical clients. No GitHub required on their end.*

### Step 1 — Send the client these three files

Download and send your client:
- `CLAUDE.md` (root of repo)
- `skills/agent-persona-creator/SKILL.md`
- `skills/answer-accuracy-standard/SKILL.md`
- `docs/NOTION_SETUP.md`
- `docs/ACTIVATION_PROMPT_DIRECT.md`

### Step 2 — Client creates a Claude Project

1. Open claude.ai → click **Projects** → click **New Project**
2. Name it: `Chief of Staff — [Their Name]`

### Step 3 — Client uploads the files to Project Knowledge

1. Click the project name → **Project Settings**
2. Under **Files**, click **+**
3. Upload all four files: `CLAUDE.md`, both `SKILL.md` files, and `NOTION_SETUP.md`

### Step 4 — Client pastes the activation prompt

1. Open `ACTIVATION_PROMPT_DIRECT.md`
2. Copy everything between the lines
3. Open a new conversation inside their Claude Project
4. Paste and send
5. Follow what Claude tells them — one step at a time

### Sending updates to Direct File clients

When you update your files, send your client the new versions.
They go to Project Settings → Files → delete the old file → upload the new one.
No GitHub. No forking. Simple file swap.

---

# After Setup — What the Chief of Staff Does

**Build a new agent**
- "I need an agent that handles client onboarding."
- "Build me a copywriter named Jordan."
- "Spin up a lead qualification agent."

**Update an existing agent**
- "Add [project name] as a win for [agent name]."
- "Upgrade [agent name] with [new skill]."

**View your roster**
- "Show me the org chart."
- "Pull [agent name]'s full profile."
- "What agents do I have deployed?"

---

# Delivered by

**Lex Autonomous** — AI Operations Consulting

---

*Agent Factory Client Edition — v1.3*
