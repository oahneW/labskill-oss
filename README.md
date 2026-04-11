# LabSkill

**Distill any researcher's thinking. Talk to their academic mind.**

🔗 **Try it:** https://oahnew.github.io/labskill-oss

LabSkill extracts the intellectual framework of academics from their published work, then lets you have conversations grounded in live literature search — not from a static snapshot, but pulling current papers as you ask.

---

## What it does

**Discover** — Search any research field and surface the most influential researchers working in it.

**Distill** — Pick a researcher. LabSkill pulls their papers from Semantic Scholar, bioRxiv, and PubMed, searches their public talks and lab website, and synthesizes everything into a structured Skill file. The Skill captures their epistemological stance, methodological preferences, reviewing standards, and an Agentic Protocol — a search strategy derived from how this researcher actually thinks about evidence.

**Chat** — Ask research questions. Before answering, the distilled PI runs targeted literature searches specific to their own epistemic standards. A neuroscientist who values fMRI/behavioral convergence will search differently from an economist who trusts RCTs. The searches are derived from each researcher's actual methodology — and both training knowledge and live search results inform the answer.

**Roundtable** — Assemble 2–4 distilled researchers and have them discuss a topic together. Generate a synthesis of the discussion, or save it as Markdown.

---

## How to use

1. Open the site and add your Anthropic API key (get one at [console.anthropic.com](https://console.anthropic.com) — $5 credit lasts a long time)
2. Search a field or pick a featured researcher to distill
3. Click **Distill** and wait 1–2 minutes
4. **Save and Chat** — ask about your research ideas, experimental designs, or field questions

---

## Disclaimer

LabSkill builds persona models from publicly available sources including published papers, public lectures, interviews, and lab websites. The distilled personas are structured approximations — they are not the real researchers, are not authorized by them, and should not be cited as representing their actual views or opinions. Use as a thinking tool only.

If you are a researcher whose work is included and have concerns, please open a GitHub issue.

---

## Data sources

Semantic Scholar · bioRxiv · PubMed · OpenAlex · Web search (talks, interviews, lab websites)

---

## License

MIT — use it, modify it, build with it.

---

## Technical

Runs entirely in your browser. Your API key is stored locally and never sent to any server other than Anthropic directly. Open source.
