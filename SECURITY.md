# Security Policy

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Email: **security@linguavox.uk**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Your contact info (optional)

We aim to respond within 48 hours and will keep you updated on the fix timeline.

## Scope

This policy covers:
- LinguaVox Chrome extension
- `linguavox.kossanstin.workers.dev` / `api.linguavox.uk` — Cloudflare Worker backend
- `linguavox.uk` — web dashboard

## Out of scope

- Theoretical vulnerabilities without proof of concept
- Issues in third-party services (OpenAI, Deepgram, Cloudflare) — report those to the respective vendor
- Chrome browser vulnerabilities

## Data handling

See [docs/security.md](docs/security.md) for a full explanation of how LinguaVox handles API keys, voice data, and session tokens.