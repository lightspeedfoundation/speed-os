# Speed OS Agent Docs

This repository contains agent-facing documentation for **Speed OS**, a Manifest V3 Chromium extension from Lightspeed that replaces the browser new tab page with an intent-driven interface for `speed` CLI workflows.

# Installation
drop speed-os.crx into google chrome or brave

- chrome://extensions/
- brave://extensions/

with developer mode on

## What is in this repo

- `speed-os/skill.md` — the authoritative, full-length operational reference for AI agents

## What Speed OS is

Speed OS is a browser extension UI over `speed` command workflows, with two execution surfaces:

- **Intent field** in the main UI (natural-language-like command normalization)
- **Terminal panel** (`Ctrl/Cmd + K`) for raw CLI-style arguments

The system supports wallet-gated command execution, bridge/swap flows, Hyperliquid flows, MCP environment merge, and suggestion-driven intent templates.

## Quick usage context

- Install/load the Speed OS extension in Chromium-based browsers
- Open a new tab to access the UI
- Enter `speed ...` commands in the intent input or terminal panel
- Use `speed skill` and `speed <cmd> help` for in-product guidance

For exact command syntax, runtime behavior, safety taxonomy, and flow details, read:

- `skill.md`

## Audience

This repository is intended for:

- AI agents that need reliable execution guidance
- Developers building automation around Speed OS
- Maintainers documenting intent/CLI behavior and operational procedures

## Upstream project

Canonical upstream repository:

- [lightspeedfoundation/speed-os](https://github.com/lightspeedfoundation/speed-os)

## License

Speed OS and related Lightspeed open-source components are intended to be used under GPLv3 terms in the upstream project. Verify the canonical license text in the upstream repository before distribution.

