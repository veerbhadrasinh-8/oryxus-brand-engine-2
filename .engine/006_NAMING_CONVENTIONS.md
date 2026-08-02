# NAMING CONVENTIONS

**Document:** Repository Naming Conventions

**Version:** 1.0.0

**Status:** Active

---

# Purpose

This document establishes the official naming conventions used throughout the Oryxus Brand Engine.

Consistent naming improves readability, navigation, automation, maintainability, and collaboration.

Every contributor—human or AI—must follow these conventions when creating new folders, files, documents, templates, frameworks, prompts, or assets.

---

# Guiding Principles

Every name should be:

- Descriptive
- Predictable
- Consistent
- Scalable
- Searchable

Names should describe purpose rather than implementation.

---

# Repository Structure

Top-level folders use lowercase.

Examples:

```
docs
frameworks
templates
playbooks
skills
prompts
agents
assets
examples
.engine
```

Do not use:

```
Documents
My Files
Misc
New Folder
Temp
```

---

# Core Documentation

Core documentation folders begin with a two-digit index.

Example:

```
00_ORYXUS_CONSTITUTION

01_RESEARCH_SYSTEM

02_BRAND_STRATEGY

03_PRD_SYSTEM
```

Benefits:

- Stable ordering
- Easier navigation
- Future scalability

---

# Chapter Naming

Inside each documentation folder:

```
README.md

Part_01_Foundations.md

Part_02_Thinking.md

Part_03_Methodology.md

Part_04_Implementation.md

REFERENCES.md

CHECKLIST.md
```

Use two-digit numbering for all sequential parts.

---

# File Naming

Markdown files follow:

```
Pascal_Case_With_Underscores.md
```

Examples:

```
Brand_Positioning.md

Customer_Personas.md

Hero_Sections.md

Website_PRD.md
```

Avoid:

```
brandposition.md

file1.md

new.md

test.md

notes.md
```

---

# README Convention

Every major folder should contain:

```
README.md
```

The README explains:

- Purpose
- Scope
- Folder structure
- Dependencies
- Related documents
- Current status

---

# Framework Naming

Framework folders use singular industry names.

Examples:

```
Restaurant

Healthcare

Luxury

Manufacturing

Education

Export

Retail

Hospitality
```

Avoid unnecessary abbreviations.

---

# Template Naming

Templates describe the deliverable.

Examples:

```
Website_PRD

Research_Report

SEO_Strategy

Developer_Handoff

Launch_Checklist
```

Templates should never include version numbers in filenames.

---

# Playbook Naming

Playbooks describe an activity.

Examples:

```
Hero_Sections

Navigation_Design

Landing_Pages

Brand_Audit

Trust_Building
```

Names should immediately communicate the workflow.

---

# Skill Naming

Skills represent professional roles.

Examples:

```
Brand_Strategist

Research_Expert

UX_Architect

UI_Architect

Frontend_Architect

SEO_Strategist
```

Avoid generic names such as:

```
Designer

Writer

Developer

Assistant
```

---

# Prompt Naming

Prompt files describe the task.

Examples:

```
Research

Brand

UX

UI

PRD

Copy

SEO

Audit
```

Prompts should remain concise.

---

# Agent Naming

Agents describe responsibility.

Examples:

```
Research_Agent

Strategy_Agent

UX_Agent

QA_Agent

Master_Orchestrator
```

Avoid naming agents after technologies or AI providers.

---

# Asset Naming

Assets should follow:

```
category-description-version.ext
```

Examples:

```
logo-primary-v1.svg

wireframe-home-v2.png

color-palette-v1.pdf
```

---

# Image Naming

Images should describe content.

Examples:

```
restaurant-homepage-wireframe.png

design-system-colors.png

navigation-flow.png
```

Avoid:

```
image1.png

photo.png

final2.png
```

---

# Diagram Naming

Examples:

```
research-process.drawio

brand-hierarchy.drawio

ux-flow.drawio
```

---

# Folder Rules

Folder names should:

- Use Pascal Case when representing named systems.
- Use lowercase for repository categories.
- Avoid spaces.
- Avoid special characters.
- Remain stable over time.

---

# Abbreviations

Use abbreviations only when they are industry standards.

Allowed:

```
PRD

UX

UI

SEO

QA

API

CMS
```

Avoid inventing repository-specific abbreviations.

---

# Version Naming

Versions belong inside documents—not filenames.

Correct:

```
Brand_Strategy.md

Version: 1.2.0
```

Incorrect:

```
Brand_Strategy_v4.md

Brand_Strategy_Final.md

Brand_Strategy_Final2.md
```

---

# Archive Policy

Deprecated documents should move to:

```
archive/
```

Do not rename active documents to:

```
old

backup

new

latest
```

Version history belongs in Git.

---

# Temporary Files

Temporary work should never be committed.

Examples:

```
draft.md

test.md

scratch.md
```

Use local workspaces instead.

---

# Consistency Rules

Before creating a new document:

1. Search the repository.
2. Check existing terminology.
3. Verify naming conventions.
4. Confirm no equivalent document already exists.

Consistency takes priority over personal preference.

---

# Examples

## Correct

```
01_RESEARCH_SYSTEM/

README.md

Part_01_Research_Philosophy.md

Part_02_Market_Research.md

CHECKLIST.md

REFERENCES.md
```

---

## Incorrect

```
Research/

chapter one.md

notes.md

new research.md

final.md
```

---

# Final Principle

Naming is part of architecture.

Good names reduce confusion, improve discoverability, simplify automation, and make the Brand Engine easier to maintain as it grows.

Every new file should look like it has always belonged in the repository.

---

**End of Naming Conventions**
