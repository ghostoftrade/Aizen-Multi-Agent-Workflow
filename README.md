# AIZEN — Multi-Agent Workflow Skills

AIZEN is an open-source AI Agent Skills Library for building multi-agent workflow systems.

This repository contains reusable `SKILL.md` files that can be copied, customized, and loaded into AI agents.

AIZEN is designed for builders who want AI agents that can do more than chat.

The goal is to create agents that can research, analyze, execute, automate, notify, support, and report.

## What Is AIZEN?

AIZEN is a multi-agent workflow skill pack.

It provides structured AI agent skills for:

- Multi-agent routing
- Crypto market intelligence
- Base ecosystem analysis
- Solana ecosystem analysis
- Content intelligence
- Partnership and growth outreach
- Community support and trust
- Project documentation
- Workflow automation
- Telegram alerts and reports
- Tool and API integration
- Launch operations
- Reporting and execution

## Why This Exists

Most AI agents fail because they only respond.

AIZEN is designed to help agents work in structured workflows.

Instead of one generic chatbot, AIZEN uses specialist skills that can be combined into a multi-agent system.

```txt
User Request
   ↓
Aizen Master Router Agent
   ↓
Specialist Agent
   ↓
Execution Workflow
   ↓
Telegram / Dashboard / Report / Content / Docs / Output
   ↓
Final Result
```

## Repository Structure

```txt
Multi-Agent-Workflow/
│
├── README.md
├── index.html
├── Aizen.jpg
│
└── skills/
    ├── aizen/
    │   └── SKILL.md
    │
    ├── crypto-market-agent/
    │   └── SKILL.md
    │
    ├── content-agent/
    │   └── SKILL.md
    │
    ├── lead-generation-agent/
    │   └── SKILL.md
    │
    ├── customer-support-agent/
    │   └── SKILL.md
    │
    ├── document-agent/
    │   └── SKILL.md
    │
    └── workflow-automation-agent/
        └── SKILL.md
```

## Available Skills

| Skill | Description |
|---|---|
| Aizen Master Router Agent | Master router that selects the right specialist agent and creates the execution path |
| Crypto Market Intelligence Agent | Analyze BTC, ETH, SOL, Base, Solana, narratives, sentiment, risk, watchlists, and Telegram market reports |
| Content Intelligence Agent | Create crypto-native content, launch campaigns, X threads, Telegram announcements, and project storytelling |
| Partnership & Growth Outreach Agent | Build KOL outreach, partner pipelines, Base/Solana ecosystem growth, and CRM-ready follow-ups |
| Community Support & Trust Agent | Handle Telegram/Discord support, FAQs, onboarding, FUD, scam warnings, and community trust workflows |
| Project Docs & Intelligence Agent | Create whitepapers, litepapers, token docs, project FAQs, roadmap summaries, and documentation audits |
| Multi-Agent Workflow Architect | Design OpenClaw, Hermes, n8n, Telegram, API, dashboard, launch, and automation workflows |

## How To Use

1. Open the `skills` folder.
2. Choose the skill you want.
3. Open the `SKILL.md` file.
4. Copy the instruction.
5. Paste it into your AI agent system.
6. Customize the inputs, tools, and output format.
7. Run the agent.

## Compatible With

These skills can be adapted for:

- OpenClaw
- Hermes
- Custom GPTs
- Claude Projects
- Cursor Agent
- n8n AI Agent
- Flowise
- LangChain
- CrewAI
- AutoGen
- Telegram Bot API
- Zapier
- Make
- Pipedream
- Activepieces
- Custom APIs
- Any custom multi-agent framework

## Core Concept

AIZEN works as a skill-based multi-agent system.

```txt
Aizen Router
   ↓
Chooses the right specialist skill
   ↓
Runs the workflow
   ↓
Formats the output
   ↓
Sends result to user, Telegram, dashboard, docs, or report
```

## Example Multi-Agent Workflow

```txt
User:
"I want an AI workflow that monitors crypto markets and sends daily reports to Telegram."

Aizen Master Router Agent:
Selects Crypto Market Intelligence Agent + Multi-Agent Workflow Architect.

Crypto Market Intelligence Agent:
Analyzes BTC, ETH, SOL, Base ecosystem, Solana ecosystem, narratives, risks, and watchlists.

Multi-Agent Workflow Architect:
Designs scheduled automation, Telegram report delivery, error handling, and human review.

Report Agent:
Formats the final result into a clear Telegram-ready market brief.
```

## Example Use Cases

### 1. Crypto Market Intelligence

```txt
Crypto Market Intelligence Agent
   ↓
Multi-Agent Workflow Architect
   ↓
Telegram Market Report
```

Use for:

- BTC / ETH / SOL market reports
- Base ecosystem monitoring
- Solana ecosystem monitoring
- Narrative tracking
- Token watchlists
- Market regime analysis
- Telegram alpha reports
- Risk matrix
- Scenario planning

### 2. Base or Solana Project Launch

```txt
Project Docs & Intelligence Agent
   ↓
Content Intelligence Agent
   ↓
Partnership & Growth Outreach Agent
   ↓
Community Support & Trust Agent
   ↓
Multi-Agent Workflow Architect
```

Use for:

- Token launch preparation
- Base project positioning
- Solana-style community growth
- Launch content
- Telegram announcements
- KOL outreach
- Community FAQ
- Scam warnings
- Human review workflows

### 3. Content Creation Workflow

```txt
Content Intelligence Agent
   ↓
Project Docs & Intelligence Agent
   ↓
Community Support & Trust Agent
   ↓
Twitter/X Thread or Telegram Announcement
```

Use for:

- Twitter/X threads
- Founder posts
- Launch campaigns
- Telegram announcements
- Discord announcements
- Website copy
- Narrative building
- Content calendars
- Short-form video scripts

### 4. Partnership & KOL Growth Workflow

```txt
Partnership & Growth Outreach Agent
   ↓
Content Intelligence Agent
   ↓
Multi-Agent Workflow Architect
   ↓
CRM / Google Sheets / Telegram Alert
```

Use for:

- KOL targeting
- Base ecosystem outreach
- Solana community outreach
- Alpha group outreach
- Partner proposal
- Twitter/X DM templates
- Telegram outreach
- CRM tracking
- Follow-up automation

### 5. Community Support & Trust Workflow

```txt
Community Support & Trust Agent
   ↓
Project Docs & Intelligence Agent
   ↓
Multi-Agent Workflow Architect
   ↓
Telegram Admin Alert / FAQ / Reply
```

Use for:

- Telegram support
- Discord support
- FAQ automation
- FUD handling
- Scam warnings
- Token question replies
- Community onboarding
- Admin escalation

### 6. Project Documentation Workflow

```txt
Project Docs & Intelligence Agent
   ↓
Content Intelligence Agent
   ↓
Community Support & Trust Agent
   ↓
Docs / FAQ / Litepaper / Announcement
```

Use for:

- Whitepaper summary
- Litepaper draft
- Token utility explanation
- Roadmap breakdown
- README improvement
- Project FAQ
- Community FAQ
- Pitch brief
- Documentation audit

### 7. Workflow Automation System

```txt
Aizen Master Router Agent
   ↓
Multi-Agent Workflow Architect
   ↓
Specialist Agents
   ↓
Telegram / Dashboard / Google Sheets / API / Report
```

Use for:

- OpenClaw workflows
- Hermes workflows
- n8n automations
- Telegram alerts
- Dashboard updates
- API workflows
- Scheduled reports
- Launch operations
- Human review systems
- Error handling workflows

## Skill Format

Each skill uses a structured `SKILL.md` format:

```txt
---
name:
title:
description:
category:
version:
---

# Skill Name

## Role
Defines what the agent is.

## Objective
Defines what the agent should accomplish.

## What Makes This Skill Different
Explains the premium logic behind the skill.

## When To Use This Skill
Defines when the skill should be activated.

## Required Input
Defines what information the agent needs.

## Input Template
Gives users a reusable format for running the skill.

## Core Workflow
Defines the step-by-step process.

## Frameworks
Defines analysis, scoring, routing, or execution logic.

## Output Format
Defines the final response structure.

## Example Use Case
Shows how the skill works.

## Multi-Agent Collaboration
Shows how the skill works with other agents.

## Safety Rules
Defines what the agent must avoid.

## Behavior Rules
Defines how the agent should behave.

## Prompt
The reusable instruction that can be copied into an AI agent.
```

## Agent Ecosystem

AIZEN skills are designed to be copied, customized, and loaded into multi-agent systems such as:

```txt
OpenClaw
Hermes
n8n
CrewAI
AutoGen
LangChain
Flowise
Telegram Bot API
Custom GPT
Claude Projects
Cursor Agent
Custom AI Agent Frameworks
```

## Crypto Ecosystem Coverage

AIZEN is designed to support crypto-native workflows across multiple ecosystems.

```txt
BTC
→ Market direction and risk anchor.

ETH
→ Altcoin confidence and liquidity anchor.

SOL
→ Solana ecosystem and retail momentum anchor.

Base
→ Consumer crypto, AI agents, builder ecosystem, and on-chain app positioning.

Solana
→ Meme activity, retail attention, community energy, consumer apps, and fast market rotation.

Multi-Chain
→ Narrative tracking, sector rotation, market reports, and ecosystem comparison.
```

## Important Notes

AIZEN is not a one-click SaaS product.

AIZEN is a reusable AI agent skills library.

The skills are designed to help builders, creators, founders, traders, operators, communities, and developers create structured AI agent workflows.

You can use these skills as:

- System prompts
- Agent instructions
- Custom GPT instructions
- Claude project instructions
- n8n AI agent prompts
- OpenClaw skill references
- Hermes workflow references
- CrewAI role definitions
- AutoGen agent specs
- LangChain agent instructions
- Flowise agent instructions
- Telegram bot workflow prompts
- Custom multi-agent workflow templates

## Safety & Trust Principles

AIZEN is designed to be useful without making dangerous or misleading claims.

For crypto, token, and community workflows:

- Do not promise profit.
- Do not guarantee token price.
- Do not fake partnerships.
- Do not invent metrics, TVL, users, investors, grants, or exchange listings.
- Do not claim official Base or Solana support unless proven.
- Do not ask users for private keys or seed phrases.
- Do not expose Telegram bot tokens.
- Do not automate irreversible actions without human review.
- Always separate facts, assumptions, and scenarios.
- Always require human review for sensitive public claims.

## Recommended Workflow

```txt
1. Choose a skill from the skills folder.
2. Copy the SKILL.md instruction.
3. Paste it into your AI agent system.
4. Add tools, APIs, memory, or automation logic.
5. Test with real input.
6. Customize the output format.
7. Connect it into a larger workflow.
8. Add human review for sensitive actions.
9. Deploy carefully.
10. Monitor and improve.
```

## Example Prompt To Start

```txt
Use AIZEN as my master router agent.

My project:
[Project name]

Ecosystem:
[Base / Solana / Ethereum / Multi-chain]

Goal:
[What I want to build or execute]

Available tools:
[OpenClaw / Hermes / n8n / Telegram / APIs / Google Sheets / GitHub / etc.]

Output I want:
[Content / report / workflow / FAQ / docs / market intelligence / outreach plan]

Route this request to the right AIZEN specialist agent and create the execution workflow.
```

## Built By

Built by Ghost of Sol.

AIZEN is for builders who want AI agents that can actually execute workflows, not just chat.