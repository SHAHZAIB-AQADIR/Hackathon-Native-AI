---
ID: 001
TITLE: Docusaurus Book Project Specification Creation
STAGE: spec
DATE_ISO: 2025-12-05
SURFACE: agent
MODEL: claude-sonnet-4-5-20250929
FEATURE: docusaurus-book-spec
BRANCH: 002-docusaurus-book-spec
USER: Administrator
COMMAND: /sp.specify
LABELS: ["specification", "docusaurus", "book"]
LINKS:
  SPEC: specs/002-docusaurus-book-spec/spec.md
  TICKET: null
  ADR: null
  PR: null
FILES_YAML:
  - specs/002-docusaurus-book-spec/spec.md
  - specs/002-docusaurus-book-spec/checklists/requirements.md
TESTS_YAML: []
---
PROMPT_TEXT: "You are defining the master Specification for a Docusaurus-based book project.
This document describes the full functional scope, constraints, workflows,
and expected outputs for producing a complete book.

====================================================
1. Project Overview
====================================================
Project Type: Docusaurus Book
Output Format: Markdown (.md / .mdx)
Storage Path: /content/chapters
Style: Friendly, simple, short paragraphs
Audience: Beginners (unless user specifies otherwise)

Purpose:
To generate a complete, high-quality, Docusaurus-compatible book with
consistent structure, tone  formatting, and navigation.

All outputs must comply with the Constitution.

====================================================
2. User Inputs the System Must Request
====================================================
Before generating the book, the system must request:

- Book title
- Short book description (1–3 sentences)
- Target audience
- Tone (default = friendly & simple)
- Expected number of chapters (optional)
- List of main topics or themes (optional)

If any are missing, the system must ask for them.

====================================================
3. Required Outputs
====================================================
The project MUST produce all of the following:

### A. Book Metadata
- Title
- Description
- Audience
- Tone
- Version: starting at 1.0.0

### B. Chapter Plan (from /sp.plan)
Each chapter includes:
- Chapter number
- Chapter title
- Summary (2–3 sentences)
- Sidebar position
- Filename (kebab-case)
- Required frontmatter

### C. Chapter Specifications
Each chapter must have a detailed per-chapter specification, including:
- Chapter purpose
- Target knowledge outcome
- Section list (H2/H3)
- Required examples
- Constraints (short paragraphs, friendly tone)
- Any special formatting needs

### D. Final Chapters
Each chapter must be written in correct Markdown structure:
- H1 title
- Intro section
- Clear subsections (H2/H3)
- Summary section
- Short paragraphs only
- Friendly, simple language
- Valid Docusaurus formatting
- Accurate and clean content

### E. Final Assembled Book
A complete set of Markdown files in:
### 4.1 – Planning Phase
The system must:
- Generate a logical table of contents (TOC)
- Ensure chapters follow a natural progression
- Keep chapter scopes balanced
- Ask for confirmation before locking the chapter plan

### 4.2 – Specification Phase
For each chapter:
- Generate a chapter spec using the Constitution + Plan
- Break chapter into clear, small sections
- Identify learning goals or reader outcomes
- Specify examples / diagrams if needed

### 4.3 – Writing Phase
The writing engine must:
- Follow the chapter spec exactly
- Produce short (2–4 sentence) paragraphs
- Maintain friendly beginner tone
- Use valid Docusaurus-compatible Markdown
- Follow the file naming rules
- Include required frontmatter
- Avoid unsupported Markdown or exotic syntax
### 4.4 – Verification Phase
The system must check:
- Markdown validity
- Frontmatter
- Short paragraph rule
- Tone consistency
- File naming rules
- Docusaurus compatibility

====================================================
5. Non-Functional Requirements
====================================================

### 5.1 – Quality Requirements
- Informal, friendly, simple tone
- No jargon unless defined
- No overly long or complex sections
- Clear examples where helpful
- Consistency across chapters

### 5.2 – Structural Requirements
- H1 title only once per chapter
- H2/H3 used in hierarchy
- No unnecessary Markdown features
- Follow Docusaurus constraints closely

### 5.3 – Ethical Requirements
- "No AI-generated text without verification" rule
- No hallucinated facts
- No plagiarism
- Factual correctness required

====================================================
6. Constraints
====================================================
- All content must reside in /content/chapters
- File names must be kebab-case
- All chapters must include required frontmatter
- Only Docusaurus-compatible Markdown is allowed
- Short paragraphs are mandatory
- Must follow Constitution at all times

====================================================
7. Success Criteria
====================================================
The book is considered complete when:

- All metadata is defined
- Full chapter plan is approved
- A chapter specification exists for each chapter
- All chapters are written and pass Constitution checks
- Markdown is valid and Docusaurus-compatible
- Tone, style, and structure are consistent
- All chapter files include correct frontmatter
- Book builds cleanly in Docusaurus with no errors

====================================================
8. Example Chapter Output Format
====================================================

Example Chapter File (structure required):

```markdown
```"
RESPONSE_TEXT: |
  The specification for the Docusaurus-based book project has been created successfully.
  - Branch Name: `002-docusaurus-book-spec`
  - Spec File Path: `specs/002-docusaurus-book-spec/spec.md`
  - Checklist Results: All items passed.
  The project is ready for the planning phase (`/sp.plan`).
OUTCOME: Specification created and validated.
EVALUATION: The specification accurately reflects the user's request and passed all quality checks.
