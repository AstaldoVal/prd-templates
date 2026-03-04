# Using prd-advisor in Grok

Grok supports **Customize Grok** (account-level instructions) and **Workspaces** with their own instructions. Use prd-advisor by pasting the skill content into one of these.

---

## Option A: Workspace for prd-advisor (recommended)

1. Create a **Workspace** (e.g. "PRD Structure Advisor").
2. In the workspace instructions ("How would you like Grok to respond?"), paste the full content of `prd-advisor/SKILL.md` from this repo.
3. Shorten if the field has a character limit; keep the core flow (Phase 1: gather context, Phase 2: recommend, Phase 3: outline) and the decision matrix summary table.
4. Use this workspace when you need help choosing a PRD template or structuring a PRD.

---

## Option B: Customize Grok (global)

1. Open **Customize Grok** from the chat interface.
2. In "How would you like Grok to respond?", paste a short version of the prd-advisor workflow:
   - "When I ask to structure a PRD or choose a template, ask about product type, audience, and domain. Then recommend a matching template or hybrid sections and give a personalized outline. Never recommend without gathering context first."
3. For full behavior, paste the full SKILL.md content if the field allows.

---

## If you don't use workspaces or custom instructions

- In the first message, paste the core workflow from `prd-advisor/SKILL.md` and add: "Use this to help me. I'm working on [product type, audience, domain]."
- Or attach the SKILL.md file if Grok supports file upload in chat.
