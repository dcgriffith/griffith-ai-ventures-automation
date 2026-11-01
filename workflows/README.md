# Workflows (GAV-AO)

## Deployed first (priority order)

| ID | File | Trust |
|----|------|-------|
| wf-01 | `wf-01-marketing-daily-draft.md` | Green → Amber publish |
| wf-02 | `wf-02-exec-weekly-brief.md` | Green |
| wf-03 | `wf-03-sec-asset-to-offer.md` | Green → Amber product launch |

## Active Grok schedules (complement)

- Daily Substack Note Draft
- Weekly Market Intelligence
- Weekly Command Center Review
- Biweekly/Friday Division Health Check

## n8n

Prefer n8n for multi-step orchestration when self-hosted. Until then, Grok schedules + this repo are the control plane.

**No Make. No Notion SoT.**
