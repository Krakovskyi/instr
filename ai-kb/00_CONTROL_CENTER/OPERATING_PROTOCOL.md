# AIKB Operating Protocol

## Core model

GPT Web is the central processor for reasoning, planning, risk control, and audit.
GitHub Markdown KB stores durable project knowledge.
Claude executes bounded local/repo tasks.
GitHub `gpt-handoff` stores sanitized execution evidence, reports, and screenshots.
GitHub `claude-vault` stores private Claude OS/config rules.

## Before a serious task

Read:

1. `START_HERE.md`
2. `ACTIVE_PROJECTS.md`
3. Target project `PROJECT_PROFILE.md`
4. Target project `CURRENT_STATE.md`
5. Target project `TASK_LEDGER.md`
6. Latest task dossier or active feature plan if relevant
7. Latest `gpt-handoff` report if execution evidence is needed

## After a serious task

Update only what changed:

- `CURRENT_STATE.md` when project status/gate changes;
- `TASK_LEDGER.md` when a task/gate completes;
- task dossier when durable task history is needed;
- `DECISION_LOG.md` when a real decision is made;
- feature plan when feature scope or implementation slices change.

## Evidence separation

- KB docs = durable memory and planning context.
- GitHub handoff = execution evidence.
- Claude report = executor self-report.
- GPT audit = external review.
- Slava acceptance = final decision.

## Command: отчёт

When Slava writes `отчёт`, GPT checks GitHub handoff first:

- `<Project>/latest-report.md`
- `<Project>/latest-summary.json`
- `<Project>/latest-visual-index.md`
- `<Project>/latest-screens/*.png` when visual review is needed

Then GPT updates KB only if durable state changed.

## Gates

Do not collapse:

- audit
- implementation
- runtime/screenshot verification
- commit
- push
- cleanup/delete/archive

## Security

Never store secrets, API keys, tokens, raw settings, private source code, private logs, unsafe screenshots, or giant chat dumps in this KB.
