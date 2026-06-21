# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README repo** for the user `ivanwooc`. It contains only `README.md` and is rendered by GitHub on the profile page.

- There is **no application code, package manifest, build system, lint config, or test suite**. There are no dependencies to install, so the startup update script is intentionally a no-op.
- The only "product" is `README.md`. To preview how it renders with GitHub styling, use [`grip`](https://github.com/joeyespo/grip) (GitHub Readme Instant Preview), which renders Markdown via GitHub's API:
  - Install (not part of the codebase, so not in the update script): `pip3 install grip`
  - Run: `~/.local/bin/grip README.md 0.0.0.0:6419` then open `http://localhost:6419`.
  - Note: `grip` calls GitHub's Markdown API and the README embeds remote images (shields.io badges and `github-readme-stats.vercel.app` stat cards), so the full preview requires network access.
- Editing the profile is just editing `README.md`; commit and push to update the live GitHub profile.
