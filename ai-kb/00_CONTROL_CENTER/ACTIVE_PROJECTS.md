# Active Projects

This file is the first project router for new GPT chats.

## Projects

| Project | Status | Current gate | Next safe step |
|---|---|---|---|
| AgentHub | PARKED_WAITING_FOR_IGOR | parked | Wait for Igor or start a separately approved planning/audit gate. |
| BusinessLab | PARKED | planning/research | Wait for Slava/Alexey signal or start a research planning gate. |
| ClaudeOS | BASELINE_ESTABLISHED | parked | Update only when stable workflow rules change. |
| AIKB | GITHUB_BASELINE_SETUP | docs/setup | Use GitHub Markdown KB as core knowledge base; Google Drive is deprecated for core workflow. |

## Rule

Do not start implementation from this file alone.
For any project, read:

1. project `PROJECT_PROFILE.md`
2. project `CURRENT_STATE.md`
3. project `TASK_LEDGER.md`
4. latest task dossier or feature plan if relevant

## Status meanings

- PARKED: no active task; do not open new work without reason.
- WAITING: external input needed.
- PLANNING: analysis/design only.
- IMPLEMENTATION: bounded Claude task may be active.
- REVIEW: GPT/Slava audit pending.
- COMMIT_ONLY: commit gate only.
- PUSH_ONLY: push gate only.
- CLEANUP: cleanup/delete/archive gate only.
