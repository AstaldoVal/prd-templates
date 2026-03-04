# PRD Templates Collection

A curated collection of **Product Requirements Document (PRD)** templates from product leaders, tools, and frameworks. Use with AI assistants, in your product workflow, or as reference when structuring requirements.

Each folder is a source (person, company, or method). Templates are in `.txt` or `.md` for readability and version control.

---

## Structure

| Folder | Source | Description |
|--------|--------|-------------|
| **prdgpt** | prdgpt.com | Full PRD structure with Document Control, Executive Summary, Problem & Opportunity, Requirements, Success Metrics |
| **aha** | aha.io | Agile PRD, PRD Presentation (executives), Release Requirements, general PRD guide |
| **atlassian** | atlassian.com/confluence | 5-step Confluence PRD: Objective, Assumptions, Options, Docs, Open Questions |
| **monday** | monday.com | 10 components, 6 sections (overview, objectives, stakeholders, personas, functional/non-functional reqs) |
| **ofri-yehuda** | medium.com (Design Bootcamp) | "The Only PRD Template You Need" — lean structure |
| **amazon** | Working Backwards | Press Release + FAQ (alternative to traditional PRD) |
| **bmad** | BMAD Method | Full PRD template with placeholders for BMAD workflow |
| **alirezarezvani** | claude-skills (product-team) | Standard / Epic / One-Page / Feature Brief variants |
| **chatprd** | chatprd.ai | 6-section (Background, Objectives, Features, UX, Milestones, Technical) and full variant |
| **aakash-gupta** | aakashg.com | Core framework (Problem, Goals, User Stories, Acceptance Criteria) and 14-section variant |
| **peter-yang** | Peter Yang (Roblox) | 7-section summary and full template (Problem, Goals, Requirements, Launch plan) |

---

## Installation

### Templates only

Clone or copy this repository. Point your AI assistant, PRD tool, or product docs at the templates:

```bash
git clone https://github.com/AstaldoVal/prd-templates.git
cd prd-templates
```

### prd-advisor skill (context-driven template selection)

This repo includes the **prd-advisor** skill. It asks about your product type, audience, and domain, then recommends a matching template or a hybrid mix of sections.

#### Cursor

1. Clone this repo:
   ```bash
   git clone https://github.com/AstaldoVal/prd-templates.git
   cd prd-templates
   ```
2. Copy or symlink `prd-advisor/` into your project's skills directory, e.g. `.cursor/skills/prd-advisor/` or `.claude/skills/prd-advisor/`.
3. Restart Cursor. Invoke with `/prd-advisor`.

#### Claude Code

1. Clone the repo as above.
2. Copy or symlink `prd-advisor/` into Claude Code's skills directory:
   - **macOS/Linux:** `~/.claude/skills/prd-advisor/`
   - Or place in your project: `<project>/.claude/skills/prd-advisor/`
3. Restart Claude Code. Use `/prd-advisor`.

#### Other providers

If your tool expects a skill folder with `SKILL.md`, use `prd-advisor/` as that folder. Copy or symlink it into your provider's skills root (e.g. `.cursor/skills/`, `.claude/skills/`, or equivalent).

#### Using prd-advisor in ChatGPT, Gemini, Grok, and Manus

These platforms use instructions rather than a skills folder. Step-by-step guides and ready-to-paste instructions:

- **Overview and links:** [platforms/README.md](platforms/README.md)
- **ChatGPT:** [platforms/ChatGPT.md](platforms/ChatGPT.md)
- **Gemini:** [platforms/Gemini.md](platforms/Gemini.md)
- **Grok:** [platforms/Grok.md](platforms/Grok.md)
- **Manus:** [platforms/Manus.md](platforms/Manus.md)

---

## Usage

**With prd-advisor skill:** Run `/prd-advisor`. Answer a few questions (product type, audience, domain). The skill recommends a matching template or a hybrid mix of sections, then gives you a personalized outline. Use the recommended folder/file here as reference.

**Manual:** Pick a folder by source (e.g. `aakash-gupta/` for PM-heavy PRDs, `amazon/` for Working Backwards), open the template file, and copy the structure. Combine sections from multiple folders for hybrid PRDs.

---

## Adding templates

1. Create a folder: `author-name/` (lowercase, hyphen-separated).
2. Add template file(s) as `.txt` or `.md`.
3. Add a `README.md` in the folder with: source URL, author, license if known, short description.
4. Update this README and `SOURCES.md` with attribution.

---

## License and attribution

This repository is under [MIT License](LICENSE). Templates are attributed to their original authors. Each template may be subject to its original author's terms. See [SOURCES.md](SOURCES.md) for URLs and attribution. This repo aggregates for convenience; it does not replace the originals.
