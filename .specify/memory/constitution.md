<!--
Sync Impact Report:
Version change: None → 1.0.0
List of modified principles: All principles added/defined
Added sections: Core Principles, Governance
Removed sections: None
Templates requiring updates:
  - .specify/templates/plan-template.md: Needs update to "Constitution Check" and notes on Docusaurus structure. ✅ updated
  - .specify/templates/spec-template.md: No direct content changes needed, but adherence to constitution's style/quality rules is implicit. ✅ updated
  - .specify/templates/tasks-template.md: No direct content changes needed, but adherence to constitution's file naming rules is implicit for generated files. ✅ updated
  - .specify/templates/commands/sp.constitution.md: Implicitly updated by execution. ✅ updated
Follow-up TODOs: TODO(RATIFICATION_DATE): Original adoption date needs to be set.
-->
# Docusaurus Book Project Constitution

## Core Principles

### 1. Writing Tone & Style
All content will use a friendly, simple, and beginner-friendly writing style. Paragraphs must be short, typically 2–4 sentences. Academic or complex language is to be avoided. A consistent voice will be maintained throughout all chapters.

### 2. Docusaurus Content Structure
All book content MUST be stored inside the `/content/chapters` directory. Every chapter must be a Markdown (.md or .mdx) file. Only valid Docusaurus-compatible Markdown syntax will be used. Each chapter is required to have an H1 Title at the top, a short introduction section, main content divided into H2 or H3 sections, and a summary section at the end. Fenced code blocks (` ``` `) are mandatory for all code examples. Only Markdown features supported by Docusaurus are permitted.

### 3. File Naming Conventions
File names for chapters must be in kebab-case format, for example, `introduction.md` or `chapter-1-getting-started.md`. Spaces and uppercase letters are not allowed in file names. Each chapter file must begin with a clear, descriptive name.

### 4. Sidebar & Navigation
Every chapter must include proper Docusaurus frontmatter. Chapter titles within the frontmatter must be clear and concise. Descriptions in the frontmatter must be 1–2 friendly sentences.

### 5. AI Usage & Verification
No AI-generated text may be used without explicit human review and approval. All content, regardless of origin, must be fact-checked before acceptance. All claims made within the content must be accurate and clear. AI drafts MUST be improved and verified by a human before being marked as final.

### 6. Quality & Editorial Standards
All content must be original; copying from external sources is strictly prohibited. Jargon is to be avoided unless clearly defined within the text. Examples and analogies should be used when they enhance understanding. Content must remain tightly focused on the specific goal of the chapter. Filler, repetition, and overly long blocks of text are not permitted.

### 7. Consistency
Consistent terminology must be used across all chapters. The same formatting patterns must be followed throughout the entire book. The tone and voice established in initial chapters must be maintained consistently from chapter to chapter.

### 8. Prohibited Content
Overly long paragraphs are strictly prohibited. Unsupported claims are not allowed. The use of broken Markdown syntax is forbidden. Content that violates Docusaurus formatting capabilities is not permitted.

## Governance
This Constitution supersedes all other writing practices and guidelines for this project. Any amendments to this Constitution require a documented rationale, explicit approval from project leads, and a plan for migrating existing content if necessary. All Pull Requests and content reviews MUST verify compliance with these principles.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE) | **Last Amended**: 2025-12-04
