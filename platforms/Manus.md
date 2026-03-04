# Using prd-advisor in Manus

Manus supports **Skills**: you can upload a folder that contains **SKILL.md** (and optional reference files). The skill then appears in chat (e.g. via `/` or "use prd-advisor skill").

---

## Install prd-advisor

1. Clone or download this repository:
   ```bash
   git clone https://github.com/AstaldoVal/prd-templates.git
   cd prd-templates
   ```
2. In Manus, open **Skills** (main menu).
3. **Upload a skill:** choose **Upload** and select:
   - The **prd-advisor/** folder (it contains `SKILL.md` and `references/`), or
   - A **.zip** of the `prd-advisor/` folder.
4. If Manus asks for a single file, use **prd-advisor/SKILL.md**. The embedded summary tables in SKILL.md are enough; for best results, upload the full folder so Manus can access `references/decision-matrix.md` and `references/section-catalog.md`.

After upload, the prd-advisor skill is available (e.g. type `/` and pick "prd-advisor" or "PRD Structure Advisor").

---

## If upload is not available

- Paste the content of **prd-advisor/SKILL.md** into the chat and ask the assistant to follow it.
- Or use a one-shot prompt in your first message: "You are a PRD structure advisor. Ask about my product type, audience, and domain, then recommend a matching template and give me an outline."
