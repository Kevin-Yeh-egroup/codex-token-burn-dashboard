# Presentation Notes

## Agent Discussion Summary

Kevin asked for a brighter, more comfortable presentation that does not require an IT background.

### Suggested roles

- `task_router`: Keep the dashboard focused on one question: how much Codex work happened, and what can we compare it with?
- `frontend_qa`: Move away from the dark billing-console look. Use a light, comfortable palette, large plain-language numbers, and clear comparison blocks.
- `workflow_designer`: Treat this as a reusable weekly/monthly work-energy report, not only a one-off token chart.
- `risk_guardian`: Keep the public page aggregate only. Do not publish local session paths, prompts, task details, credentials, or unverified billing spend.

## Plain-Language Framing

Use these terms for non-technical readers:

- `整體處理量`: Raw tokens. This is the full amount of content Codex handled.
- `新增投入量`: Fresh tokens. This is closer to the new work added during the period.
- `重複內容節省`: Cache share. This explains why a large total does not always mean equal cost.
- `工作回合`: Sessions. This is the number of Codex work conversations or runs included.

Avoid presenting USD unless there is an actual billing source or a clearly stated estimate.

## Visual Direction

- Use a bright background with soft mint, sky blue, white, and warm yellow.
- Keep the large headline for emotional impact.
- Use friendly phrases such as "工作能量紀錄" instead of billing or engineering language.
- Make mobile reading comfortable: large body text, natural Chinese wrapping, and short paragraph blocks.

## Implemented Extension Areas

- Weekly work-energy report: token usage plus completed deliverables, shown as "這些用量換到了什麼".
- Value comparison: currently uses equivalent work metrics instead of USD, including Fresh Tokens per session, cache multiplier, and output volume.
- Health signal: flags concentrated high-usage days and explains what should be checked.
- Billing view: add USD only after real billing data is connected.
- Automation candidate: later generate a weekly snapshot automatically, after the manual dashboard is useful for at least a few runs.

## Clarification Added

The weekly comparison table should use "當週用量" and "當週新增" instead of generic "整體" or "新增", because the values are per-week usage, not cumulative totals.
