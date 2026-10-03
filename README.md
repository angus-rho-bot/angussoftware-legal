# angussoftware-legal

Static legal/policy pages for Angus Software — privacy policies, AI disclosure.
Decoupled from app repos so policy changes deploy on their own cadence.

- Serves **legal.angussoftware.com** (GitHub Pages + Cloudflare DNS)
- Deploy: merge to `master` → Pages rebuild (auto, no release train)
- Pages: `/ai-disclosure`, `/privacy-angus-tasks`

## AI disclosure

This site itself is built with AI assistance (Z.ai GLM via Letta agents) under
human direction. All prose is human-authored and human-approved. See
[/ai-disclosure](https://legal.angussoftware.com/ai-disclosure).

## Adding a policy page

1. Drop an HTML file in the repo root (self-contained, inline CSS — match the
   existing pages' style).
2. Link it from `index.html`.
3. Merge to master. Live in ~1 min.
