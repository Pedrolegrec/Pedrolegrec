# Pedrolegrec Profile Repository Instructions

These instructions apply to the whole `/app/dev/Pedrolegrec` repository.

## Role

This repo owns the GitHub profile README for Pierre-Dominic Simard. It is a
small public-facing Markdown profile, not an app source repo.

## Working Rules

- Keep `README.md` concise and current with shipped public apps and social
  links.
- Verify product names and public URLs before changing external links.
- Do not add private roadmap notes, credentials, analytics snippets, or local
  workflow details to this public profile.

## Validation

Before reporting changes complete, run:

```bash
git -C /app/dev/Pedrolegrec diff --check
git -C /app/dev/Pedrolegrec status --short
```
