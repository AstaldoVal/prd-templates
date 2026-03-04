# Using prd-advisor in ChatGPT, Gemini, Grok, and Manus

The prd-advisor skill is designed for Cursor and Claude Code (skills folder). The same workflow can be used in **ChatGPT**, **Google Gemini**, **Grok**, and **Manus** by pasting instructions or uploading the skill content where each platform allows.

---

## Summary by platform

| Platform   | How to use prd-advisor |
|-----------|-------------------------|
| **ChatGPT** | Custom GPT: create a GPT, paste `prd-advisor/SKILL.md` into **Instructions**; optionally add `prd-advisor/references/` to **Knowledge**. See [ChatGPT.md](ChatGPT.md). |
| **Gemini**   | **Gems**: create a Gem, paste the skill instructions. Or use **Personal instructions** for a global PRD-assistant style. See [Gemini.md](Gemini.md). |
| **Grok**     | **Workspaces** or **Customize Grok**: paste skill instructions into "How would you like Grok to respond?". See [Grok.md](Grok.md). |
| **Manus**    | **Skills** (upload): upload the `prd-advisor/` folder (contains `SKILL.md`). See [Manus.md](Manus.md). |

---

## What to paste or upload

1. **prd-advisor/SKILL.md** — the main workflow. Always include this.
2. **prd-advisor/references/decision-matrix.md** — used by the skill for recommendations. Include if the platform allows multiple files.
3. **prd-advisor/references/section-catalog.md** — used for deep dives. Include if possible.

For platforms with a single Instructions field, paste the full content of `SKILL.md`. The skill references the decision matrix and section catalog; if the assistant can't access those files, paste them into the instructions as well (append after the SKILL content), or the skill will still work with the summary tables embedded in SKILL.md.
