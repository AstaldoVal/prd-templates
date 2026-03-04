# Using prd-advisor in Google Gemini

Gemini does not support a "skills folder". Use prd-advisor via **Custom Gems** or **Personal instructions**.

---

## Option A: One Gem for prd-advisor (recommended)

1. In Gemini (gemini.google.com or Google AI Studio), go to **Create a Gem**.
2. Name and describe the Gem (e.g. "PRD Structure Advisor", "Helps choose and structure PRD templates").
3. In the Gem's **Instructions** (or "How should this Gem respond?"), paste the full content of `prd-advisor/SKILL.md` from this repo.
4. If the platform allows extra files, add `prd-advisor/references/decision-matrix.md` and `prd-advisor/references/section-catalog.md`. Otherwise, the summary tables in SKILL.md are enough.
5. Save. Use this Gem when you need help choosing a PRD template (e.g. "Help me structure a PRD for an MVP", "Which template fits a B2B feature?").

---

## Option B: Personal instructions (global nudge)

If your account has **Personal instructions** (Settings → Personal Intelligence), add a short line such as:

- "When I ask to structure a PRD or choose a template, run a context-driven workflow: ask about product type, audience, and domain; then recommend a matching template or hybrid sections and give a personalized outline."

This does not load the full skill. For the complete workflow, use a Gem (Option A).

---

## Reference

- [Customize Gemini's responses with your instructions](https://support.google.com/gemini/answer/16598625)
- [Tips for creating custom Gems](https://support.google.com/gemini/answer/15235603)
