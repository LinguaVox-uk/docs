# Contributing to LinguaVox Docs

This repo contains public documentation for [LinguaVox](https://linguavox.uk) — a Chrome extension for AI voice dictation and real-time meeting subtitles.

## What lives here

| Path | Contents |
|------|----------|
| `README.md` + locale variants | Main README in 7 languages |
| `docs/` | FAQ, integrations, security, use cases, changelog |
| `press-kit/` | Short and long product descriptions |
| `images/` | Banner and screenshots |
| `llms.txt` | AI-readable product summary |

## How to contribute

**Typo or factual error** — open an issue or submit a PR directly.

**Translation improvement** — edit the relevant `README.xx.md` file. Keep technical terms (API key, Cloudflare Worker, etc.) in English.

**New language** — open an issue first to coordinate.

**New use case or integration note** — add to `docs/use-cases.md` or `docs/integrations.md` and open a PR.

## Style notes

- Use plain Markdown — no custom HTML except in README headers (where it already exists)
- Keep sentences short — these docs are read by people in a hurry
- Technical accuracy over marketing language in the `docs/` folder
- Marketing tone is fine in README files

## Reporting a security issue

Do **not** open a public GitHub issue. Email: **security@linguavox.uk**