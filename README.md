# LabSkill

Distill elite research minds into AI personas. Have real intellectual conversations with them. Assemble roundtables.

**Open source · BYOK · Runs entirely in your browser · Zero backend**

## What it does

1. **Discover** — Find top researchers in any field using Claude + web search
2. **Distill** — Pull their papers from Semantic Scholar, search for talks and interviews, synthesize a deep persona with a confidence report
3. **Chat** — One-on-one conversation with the distilled persona. Persistent memory with rolling summarization.
4. **Roundtable** — 2-4 PIs discussing your research idea in four modes:
   - Academic seminar (each PI makes one specific academic move)
   - Adversarial debate (FOR vs AGAINST)
   - Structured roles (theorist / methodologist / critic / synthesizer)
   - Peer review (structured verdict)

## How to use

1. Open `index.html` in your browser (or use GitHub Pages)
2. Enter your Anthropic API key when prompted (session only — not stored permanently)
3. Distill a researcher → Save → Chat

**Cost:** ~$0.05 per distillation, ~$0.01 per conversation turn

## Get an API key

[console.anthropic.com](https://console.anthropic.com) — new accounts get $5 free credit

## Deploy to GitHub Pages

1. Fork this repo
2. Settings → Pages → Source: main branch / root
3. Your site is live at `https://yourusername.github.io/labskill`

## Privacy

Your API key is used directly from your browser to call Anthropic's API. It is stored in `sessionStorage` only (clears when you close the tab) and is never sent to any server.

Skills are saved in `localStorage` — they persist across sessions on the same browser.

## License

MIT
