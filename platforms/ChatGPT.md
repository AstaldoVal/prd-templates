# Using prd-advisor in ChatGPT

ChatGPT does not have a "skills" folder. The closest equivalent is a **Custom GPT** with fixed instructions (and optional Knowledge files).

---

## Option A: Custom GPT for prd-advisor (recommended)

1. Go to **Explore GPTs** → **Create** (or **My GPTs** → edit).
2. Name and describe the GPT (e.g. "PRD Structure Advisor", "Helps choose and structure PRD templates").
3. In **Instructions**, paste the full content of `prd-advisor/SKILL.md` from this repo.
4. (Optional) In **Knowledge**, upload:
   - `prd-advisor/references/decision-matrix.md`
   - `prd-advisor/references/section-catalog.md`
   Or append their content to Instructions if the field allows and you prefer one place.
5. Save. Use this GPT whenever you need help choosing a PRD template or structuring a PRD (e.g. "Help me structure a PRD for an MVP", "Which template fits a B2B feature?").

---

## Option B: Attach in a normal chat (no Custom GPT)

- Attach `prd-advisor/SKILL.md` and write: "Use this skill to help me choose a PRD structure. I'm working on [product type, audience, domain]."
- Or paste the core workflow from SKILL.md in your first message and ask the assistant to follow it.
