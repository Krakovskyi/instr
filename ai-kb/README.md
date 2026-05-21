# AI Engineering Knowledge Base

This directory is the GitHub-first structured knowledge base for Slava's AI engineering workflow.

## Core model

- GPT Web = reasoning / planning / audit / control layer.
- GitHub Markdown KB = durable project memory and planning library.
- Claude = bounded local/repo executor.
- `gpt-handoff` = sanitized reports, screenshots, and execution evidence.
- `claude-vault` = private Claude OS/config vault.

## Why GitHub instead of Google Drive

Google Drive is no longer a core workflow dependency because Drive write operations were unreliable for systematic KB maintenance. GitHub Markdown is now preferred because it provides version control, diffs, stable paths, commit history, and easier audit.

## What this KB stores

- control-center docs;
- project current states;
- task ledgers;
- task dossiers;
- feature plans;
- acceptance maps;
- decision logs;
- reusable templates.

## What this KB must not store

- secrets;
- API keys;
- tokens;
- raw Claude settings;
- private source code;
- private logs;
- unsafe screenshots;
- full raw chat dumps.

## Operating rule

One task -> one DONE state -> one bounded Claude prompt -> one evidence report -> GPT audit -> Slava decision -> next gate.
