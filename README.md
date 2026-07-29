# Budgeroo Releases

Download page and built installers for [Budgeroo](https://github.com/bennettkevin/budgeroo-platform) — a personal budgeting app with Windows/Mac/Linux desktop clients.

This repo is intentionally separate from (and public, unlike) the main `budgeroo-platform` source repo: GitHub Release assets on a private repo require an authenticated token to download, and that token would have to ship inside the app for auto-update to work. Keeping releases in their own public repo means installers and update checks work with no token embedded in the client, while the application source stays private.

## Download

**[bennettkevin.github.io/budgeroo-releases](https://bennettkevin.github.io/budgeroo-releases/)** — pick your OS.

Installers are also available directly from the [Releases](../../releases) page.

## Development

This project (and its parent, [budgeroo-platform](https://github.com/bennettkevin/budgeroo-platform)) was developed with assistance from [Claude Code](https://claude.com/claude-code), Anthropic's agentic coding CLI, including architecture decisions, implementation, testing, and deployment/release tooling.
