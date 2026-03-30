---
name: writing-qc
description: Use when reviewing article drafts, outlines, or finished copy for SEO, search quality, heading structure, anchor text, internal linking, title wording, and compliance with Google Search guidance. Trigger for QC, audit, scoring, pass-fail review, or revision requests based on the local writing knowledge base.
---

# Writing QC

Use this skill for strict editorial and SEO quality control.

## When To Use It

Use this skill when the user wants to:

- QC an article draft before publishing
- identify SEO, heading, title, or internal-linking issues
- compare copy against Google Search guidance
- produce a pass-fail checklist with fixes
- review whether content is helpful, reliable, people-first, and non-spammy

Do not use this skill for open-ended ideation or article planning. Use `writing-consultant` for that.

## Workflow

1. Determine the review mode.
   For strict audits, produce findings first.
   For light review, group issues by severity and then give rewrite advice.
   Default to a detailed audit unless the user explicitly asks for a brief review.

2. Read only the relevant references.
   Open `references/qc-map.md` first.
   Then read only the files needed for the current draft:
   `SEO Criteria for Full Output check` for search compliance, `Heading` for structure, `Anchor Text x Ex-Internal Links` for links, and `Title Power Words` for titles.

3. Review the draft against concrete dimensions.
   Check search intent match, factual clarity, originality, heading hierarchy, title wording, anchor text quality, internal linking logic, spam-risk patterns, and whether the content needs supporting visual media.

4. Return a decisive QC result.
   Prefer a short verdict, then findings, then revision actions.
   Findings should usually be detailed issue entries, not generic summaries.

## Default Output Format

Unless the user explicitly requests a short review, structure QC output like this:

1. Verdict.
   Give `Pass`, `Revise`, or `Fail` with a short overall reason.

2. Detailed issues.
   For each issue, include:
   - severity
   - category
   - issue detail
   - why it matters
   - suggested solution

3. Highest-impact fixes.
   End with the few changes most likely to move the piece from `Revise` to `Pass`.

## Issue Writing Standard

Detailed QC findings should:

- be specific to the actual draft, not generic SEO advice
- explain the concrete problem before suggesting a fix
- state why the problem matters for users, trust, search quality, or clarity
- give an actionable solution for each issue
- prioritize evidence, originality, topical relevance, structure, links, and trust signals
- assess whether charts, tables, screenshots, diagrams, or other visual media are needed to support the article's claims or improve clarity

## Default QC Dimensions

- search quality and people-first usefulness
- Google essentials and spam-policy risk
- heading clarity and hierarchy
- title strength without clickbait overreach
- anchor text and internal/external link quality
- readability and writing discipline
- need for supporting visual media such as charts, tables, screenshots, or diagrams

## References

- Open `references/qc-map.md` for the local knowledge-base paths and recommended reading order.
