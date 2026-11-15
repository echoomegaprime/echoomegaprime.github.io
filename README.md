# echoomegaprime.github.io

The published static build of the Echo Omega Prime web surface, served via
GitHub Pages. **This repository is a deployment artifact, not a source tree.**

## What is here

The compiled site exactly as Pages serves it:

- `index.html`, `404.html`, `og.jpg`, `favicon.svg` — entry, fallback, and share assets.
- `capital/`, `gate/`, `journal/`, `login/`, `playbook/` — the site's sections, one directory each.
- `assets/` — hashed JS/CSS bundles produced by the build.
- `__grok/` — the Grok install experience (install pages, homescreen artwork).
- `.nojekyll` — Pages serves the files as-is, no Jekyll processing.

## Rules

- **Do not hand-edit files in this repo.** Every file here is build output.
- The source of truth is `echoomegaprime/echo-cli` (the Echo Prime PWA). Fix
  things there, rebuild, and republish — a republish overwrites this repo's
  contents wholesale.
- No secrets, tokens, or configuration live here; anything that looks like
  config in the bundles is compiled client code.

## Related

- `echoomegaprime/echo-cli` — source of the Echo Prime PWA and Command Center front end.
- `echoomegaprime/echo-omnipresence-runtime` — the fleet monorepo behind the site's live data.
