# writing-qc

Portable Codex skill for article QA and SEO review, bundled with its local knowledge base.

## Contents

- `SKILL.md`
- `agents/openai.yaml`
- `references/qc-map.md`
- `knowledge-base/Knowledge Base for Writing`

## Install

Clone this repository into your Codex skills directory using the skill name as the folder:

```bash
git clone https://github.com/ThanaLamth/writing-qc.git "$HOME/.codex/skills/writing-qc"
```

After cloning, the skill should be available as:

```text
$writing-qc
```

## What It Does

This skill reviews article drafts or published articles for:

- factual clarity and sourcing quality
- originality and added value
- title and heading quality
- anchor text and internal-link relevance
- readability and structure
- whether strong supporting visual media is clearly needed

## Knowledge Base

The bundled knowledge base is stored under:

```text
knowledge-base/Knowledge Base for Writing
```

The reference map in `references/qc-map.md` is already configured for this bundled layout.
