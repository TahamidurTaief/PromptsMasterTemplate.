SYSTEM CONTEXT (paste once per session, before first prompt):
Project: Health Advice BD — Next.js (TS, Tailwind, React Context) frontend + Django REST Framework backend.
Target page: /admin/settings/email (frontend/app/admin/settings/email or similar path — locate exact file first).
Models already exist: SMTPConfig, NotificationEventRule, NotificationQueue (backend/apps/notifications/).
Rules for every task:
- Work on ONE piece only. Do not touch files outside stated scope.
- Do not add features, refactors, or libraries not explicitly requested.
- Match existing project code style (Tailwind classes, TS types, DRF patterns already in repo).
- Base changes only on actual files you read. Do not assume field names — grep/read first.
- If a referenced file/field does not exist, STOP and report instead of guessing.

---
GOAL: [one sentence — exact outcome]

ROLE:
- [expertise 1, e.g. "Senior Next.js + Tailwind engineer"]
- [expertise 2]
- [3-7 bullets total, scoped to this piece]

CONTEXT (files to read before editing):
- [file path 1]
- [file path 2]

RULES:
- MUST [hard requirement]
- MUST NOT [forbidden action]
- [more as needed]

EXAMPLES:
1. Input: [state] → Output: [state]
2. Input: [state] → Output: [state]

EDGE CASES:
- [case 1 that breaks naive implementation]
- [case 2]

DELIVER:
- Modify/create: [exact file path(s), nothing else]
- If logic is isolable (pure function, validator, formatter): add node assert test in same file under `if (require.main === module)` or separate `*.test.ts`, print one example output in console.
- If UI-only (JSX/animation/layout): skip node assert, instead list a 5-line manual QA checklist (steps to click through and expected result).
- No unrelated file changes. No new dependencies unless named in RULES.

BEFORE WRITING CODE:
List the mistakes you could realistically make on this exact task (3-5 bullets).
Confirm you understood GOAL + RULES in one line.
Then wait — do not output code until this confirmation is shown.
