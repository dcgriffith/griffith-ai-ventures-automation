# Division B — Cybersecurity / G-AISOC

IAM, SOC, Sentinel, and ServiceNow-oriented automation scaffolding.

## G-AISOC pipeline (target)

Identity/cloud data → Microsoft Sentinel → AI SOC Analyst → ServiceNow + Notion → **Analyst approval**

## Folders

| Path | Purpose |
|------|--------|
| `iam/` | JML/PAM notes, checklist exports |
| `soc/` | Detection notes, alert summary prompts |
| `sentinel/` | Analytic rule notes, lab connectors (no secrets) |
| `servicenow/` | Ticket field maps, draft templates |

## Trust

Analysis drafts = **Green**. Incident priority changes = **Amber**. Production containment = **Red**.
