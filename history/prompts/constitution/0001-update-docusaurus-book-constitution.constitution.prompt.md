---
id: 0001
title: Update Docusaurus Book Constitution
stage: constitution
date: 2025-12-04
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: 001-docusaurus-book-spec
user: Administrator
command: /sp.constitution Follow these requirements exactly:

---------------------------------------
1. Writing Tone & Style
---------------------------------------
- Use a friendly, simple, beginner-friendly writing style.
- Keep paragraphs short (2–4 sentences).
- Avoid academic or complex language.
- Maintain a consistent voice throughout all chapters.

---------------------------------------
2. Docusaurus Structure & Formatting Rules
---------------------------------------
- All book content MUST be stored inside: /content/chapters
- Every chapter must be a Markdown (.md or .mdx) file.
- Use valid Docusaurus-compatible Markdown syntax.
- Required chapter structure:
  - H1 Title at the top (# Chapter Title)
  - Short introduction section
  - Main content divided into H2 or H3 sections
  - Summary section atthe end
- Use fenced code blocks ``` for examples.
- Use only Markdown features supported by Docusaurus.

---------------------------------------
3. File Naming Rules
---------------------------------------
- File names must be kebab-case, e.g., introduction.md, chapter-1-getting-started.md.
- No spaces, no uppercase letters.
- Each chapter file must start with a clear, descriptive name.
---------------------------------------
4. Sidebar & Navigation Conventions
---------------------------------------
- Every chapter must include proper frontmatter:
- Titles must be clear and concise.
- Descriptions must be 1–2 friendly sentences.

---------------------------------------
5. AI Usage & Verification Rules
---------------------------------------
- No AI-generated text may be used without human review.
- All content must be fact-checked before acceptance.
- All claims must be accurate and clear.
- AI drafts must be improved and verified by a human before being marked final.

---------------------------------------
6. Quality & Editorial Standards
---------------------------------------
- All content must be original (no copying from external sources).
- Avoid jargon unless defined.
- Use examples and analogies when helpful.
- Keep content tightly focused on the chapter goal.
- Avoid filler, repetition, and long blocks of text.

---------------------------------------
7. Consistency Rules
---------------------------------------
- Use consistent terminology across all chapters.
- Follow the same formatting pattern everywhere.
- Maintain the same tone and voice from chapter to chapter.

---------------------------------------
8. Prohibited Content
---------------------------------------
- No overly long paragraphs.
- No unsupported claims.
- No broken Markdown syntax.
- No content that violates Docusaurus formatting capabilities.

---------------------------------------
Write the final Constitution as a clean, structured document with numbered sections and bullet points.
Make it strict, unambiguous, and enforceable across the entire writing project.
labels: ["constitution", "docusaurus", "docs"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
tests:
  - None
---

## Prompt

Follow these requirements exactly:

---------------------------------------
1. Writing Tone & Style
---------------------------------------
- Use a friendly, simple, beginner-friendly writing style.
- Keep paragraphs short (2–4 sentences).
- Avoid academic or complex language.
- Maintain a consistent voice throughout all chapters.

---------------------------------------
2. Docusaurus Structure & Formatting Rules
---------------------------------------
- All book content MUST be stored inside: /content/chapters
- Every chapter must be a Markdown (.md or .mdx) file.
- Use valid Docusaurus-compatible Markdown syntax.
- Required chapter structure:
  - H1 Title at the top (# Chapter Title)
  - Short introduction section
  - Main content divided into H2 or H3 sections
  - Summary section at the end
- Use fenced code blocks ``` for examples.
- Use only Markdown features supported by Docusaurus.

---------------------------------------
3. File Naming Rules
---------------------------------------
- File names must be kebab-case, e.g., introduction.md, chapter-1-getting-started.md.
- No spaces, no uppercase letters.
- Each chapter file must start with a clear, descriptive name.
---------------------------------------
4. Sidebar & Navigation Conventions
---------------------------------------
- Every chapter must include proper frontmatter:
- Titles must be clear and concise.
- Descriptions must be 1–2 friendly sentences.

---------------------------------------
5. AI Usage & Verification Rules
---------------------------------------
- No AI-generated text may be used without human review.
- All content must be fact-checked before acceptance.
- All claims must be accurate and clear.
- AI drafts must be improved and verified by a human before being marked final.

---------------------------------------
6. Quality & Editorial Standards
---------------------------------------
- All content must be original (no copying from external sources).
- Avoid jargon unless defined.
- Use examples and analogies when helpful.
- Keep content tightly focused on the chapter goal.
- Avoid filler, repetition, and long blocks of text.

---------------------------------------
7. Consistency Rules
---------------------------------------
- Use consistent terminology across all chapters.
- Follow the same formatting pattern everywhere.
- Maintain the same tone and voice from chapter to chapter.

---------------------------------------
8. Prohibited Content
---------------------------------------
- No overly long paragraphs.
- No unsupported claims.
- No broken Markdown syntax.
- No content that violates Docusaurus formatting capabilities.

---------------------------------------
Write the final Constitution as a clean, structured document with numbered sections and bullet points.
Make it strict, unambiguous, and enforceable across the entire writing project.

## Response snapshot

The project constitution has been updated to Version 1.0.0. This is a MAJOR version bump as all core principles and governance rules have been newly defined. Files flagged for manual follow-up: .specify/templates/plan-template.md and TODO(RATIFICATION_DATE). Suggested commit message: docs: amend constitution to v1.0.0 (initial definition of Docusaurus book principles and governance)

## Outcome

- ✅ Impact: Constitution updated, templates identified for review.
- 🧪 Tests: No explicit tests run for constitution update.
- 📁 Files: .specify/memory/constitution.md updated.
- 🔁 Next prompts: None
- 🧠 Reflection: Successfully updated the constitution and identified downstream impacts on templates.

## Evaluation notes (flywheel)

- Failure modes observed: Bash script for PHR creation failed due to `No such file or directory`.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): Investigate `create-phr.sh` path or permissions.
