# Griffith AI Ventures — Automation

Central automation and integration scaffolding for **Griffith AI Ventures**.

## Architecture

```
Central AI Operations (Notion)
        │
   Division A          Division B
   AI Business         Cybersecurity / G-AISOC
        │                  │
        └────────┬─────────┘
                 │
   Automation & Integration Layer
   Make + APIs + MCP + scheduled workflows
                 │
     Grok · Claude · ChatGPT
```

Canonical docs live in Notion (Command Center):
- Central Management Architecture
- G-AISOC Architecture
- Automation Trust Levels
- Automations Registry

## Trust levels (summary)

| Level | Meaning |
|-------|--------|
| **Green** | Autonomous: read, draft, summarize, classify, monitor |
| **Amber** | Restricted: public posts, customer email, subscription changes, test identity |
| **Red** | Human-only: money, production access revocation, policy changes, containment, secrets |

This repository stores **structure, documentation, and Green-level workflow notes only**. Never commit credentials, API keys, or production secrets.

## Tree

```
business-operations/     # Division A
cybersecurity/           # Division B / G-AISOC
integrations/
workflows/
documentation/
```

## AI assistant roles

| Assistant | Role |
|-----------|------|
| Grok | Research & market intelligence |
| Claude | Production & development |
| ChatGPT | Strategy & QA |

## Operator

David Griffith — [dcgriffith](https://github.com/dcgriffith)
