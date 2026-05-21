# Global Decision Log

Durable decisions for the AI engineering operating system.

## 2026-05-21 — GitHub-first handoff

Decision: use GitHub `gpt-handoff` as the primary GPT-readable evidence/report/screenshot channel.

Reason: Google Drive was not reliable enough for visual review and screenshot handling.

Status: ACTIVE

## 2026-05-21 — Claude private vault

Decision: use `claude-vault` as the private Claude OS/config vault.

Status: ACTIVE

## 2026-05-21 — Individual screenshots primary

Decision: individual raw PNG screenshots under `latest-screens/` are primary for visual review.

Contact sheets are deprecated/not primary.

Status: ACTIVE

## 2026-05-22 — Solo technical task-closure mode

Decision: when Slava works without a human technical partner, GPT + Claude cover the technical task-closing function.

Slava remains final decision-maker.

Status: ACTIVE

## 2026-05-22 — Google Drive deprecated for core KB

Decision: Google Drive is not a core workflow dependency because automated Drive writes were unreliable.

Status: ACTIVE

## 2026-05-22 — GitHub Markdown KB

Decision: use GitHub Markdown under `ai-kb/` as the durable project memory and planning library.

Status: ACTIVE

## Security boundary

Never store secrets, raw source code, raw logs, raw Claude settings, unsafe screenshots, or giant raw chat dumps in this KB.
