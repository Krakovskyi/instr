# START HERE

This is the entry point for Slava's GitHub-first AI Engineering Knowledge Base.

## Core model

- GPT Web is the reasoning, planning, and audit layer.
- GitHub Markdown KB stores durable project memory and planning docs.
- Claude is the bounded local/repo executor.
- `gpt-handoff` stores sanitized execution reports, screenshots, and evidence.
- `claude-vault` stores private Claude OS/config rules.

## New GPT chat bootstrap

When starting a new project chat, search/read this KB first.

Read in this order:

1. `ai-kb/00_CONTROL_CENTER/START_HERE.md`
2. `ai-kb/00_CONTROL_CENTER/ACTIVE_PROJECTS.md`
3. `ai-kb/00_CONTROL_CENTER/OPERATING_PROTOCOL.md`
4. Target project `CURRENT_STATE.md`
5. Target project `TASK_LEDGER.md`
6. Latest task dossier or active feature plan if relevant

Then answer with:

```text
CURRENT STATE
CURRENT GATE
BOUNDARIES
NEXT SAFE STEP
```

## Do not start from scratch

Do not ask Slava to paste the whole old chat if the KB contains current state.
Do not return to closed tasks without a new reason.
Do not treat Claude reports as final truth without evidence.

## Safety

Do not store secrets, API keys, tokens, raw Claude settings, private source code, private logs, unsafe screenshots, or giant raw chat dumps in this KB.
