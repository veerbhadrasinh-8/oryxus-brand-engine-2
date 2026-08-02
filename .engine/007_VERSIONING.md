# VERSIONING

**Document:** Repository Versioning Standard

**Version:** 1.0.0

**Status:** Active

---

# Purpose

This document defines the official versioning strategy for the Oryxus Brand Engine.

Versioning provides a structured method for tracking repository evolution, documenting methodology improvements, managing releases, and preserving historical changes.

Every meaningful modification to the Brand Engine should be reflected through version control.

---

# Objectives

The versioning system exists to:

- Track repository evolution.
- Identify methodology changes.
- Preserve historical records.
- Support collaboration.
- Simplify maintenance.
- Improve traceability.
- Enable controlled releases.

Version numbers communicate the maturity and stability of documentation.

---

# Version Format

The Brand Engine follows **Semantic Versioning (SemVer)**.

```
MAJOR.MINOR.PATCH
```

Example

```
v2.4.7
```

---

# Version Components

## MAJOR

Increase the MAJOR version when:

- Core philosophy changes.
- Repository architecture changes.
- Breaking methodology changes occur.
- Major restructuring is introduced.

Examples:

```
v1.0.0

↓

v2.0.0
```

Major versions represent significant evolution.

---

## MINOR

Increase the MINOR version when:

- A new knowledge system is completed.
- A new framework is introduced.
- A major template is added.
- Significant capabilities are expanded.

Examples

```
v1.2.0

↓

v1.3.0
```

Minor versions introduce new functionality while preserving compatibility.

---

## PATCH

Increase the PATCH version when:

- Documentation improves.
- Errors are corrected.
- Formatting improves.
- Examples are refined.
- References are updated.

Examples

```
v1.3.4

↓

v1.3.5
```

Patch releases never change repository philosophy.

---

# Repository Version

The repository has a single global version.

Example

```
v2.1.0
```

This represents the current state of the Brand Engine.

The repository version is updated only after completing meaningful milestones.

---

# Document Version

Every document also maintains an independent version.

Example

```
Project Charter

Version: 1.0.0
```

Example

```
Research System

Version: 2.1.0
```

This allows individual documents to evolve independently.

---

# Relationship Between Versions

```
Repository

v2.0.0

↓

Research System

v2.3.0

↓

Brand Strategy

v1.7.0

↓

SEO System

v1.2.0
```

Repository versions summarize the entire project.

Document versions track individual evolution.

---

# Release Stages

Every document progresses through the following lifecycle.

```
Planning

↓

Draft

↓

Review

↓

Revision

↓

Stable

↓

Archived
```

---

# Version Progression

Typical progression

```
v0.1.0

Initial Draft

↓

v0.5.0

Expanded

↓

v0.9.0

Review Complete

↓

v1.0.0

Stable Release

↓

v1.1.0

Minor Improvements

↓

v1.2.0

Additional Capability

↓

v2.0.0

Major Revision
```

---

# Pre-Release Versions

Development work may use the following states.

```
Draft

Alpha

Beta

Release Candidate
```

Examples

```
v0.2.0-alpha

v0.7.0-beta

v0.9.0-rc1
```

Stable releases should not contain pre-release labels.

---

# Repository Milestones

The following milestones normally trigger new repository versions.

| Milestone | Typical Version |
|------------|----------------:|
| Repository Foundation | v0.1.0 |
| Engine Foundation Complete | v0.2.0 |
| Constitution Complete | v1.0.0 |
| Core Systems Complete | v2.0.0 |
| Framework Library Complete | v3.0.0 |
| Templates Complete | v4.0.0 |
| Playbooks Complete | v5.0.0 |
| Skills Complete | v6.0.0 |
| Prompt Library Complete | v7.0.0 |
| Agents Complete | v8.0.0 |
| Platform Foundation | v9.0.0 |

These versions represent strategic milestones rather than deadlines.

---

# Change Classification

Every update should belong to one or more categories.

### Added

New functionality.

---

### Improved

Enhancement without changing philosophy.

---

### Fixed

Corrections.

---

### Deprecated

Scheduled for removal.

---

### Removed

Deleted intentionally.

---

### Refactored

Improved organization without changing methodology.

---

### Security

Changes affecting governance or protection.

---

# Version Update Rules

Increase the version only when:

- Methodology changes.
- New knowledge is introduced.
- Architecture evolves.
- Significant improvements are completed.

Do not increase versions for:

- Typographical corrections.
- Minor formatting.
- Whitespace changes.
- Internal comments.

---

# Documentation Requirements

Whenever a version changes:

Update:

- Document version.
- CHANGELOG.
- Repository Status (if applicable).
- Related references.

Version updates should always be traceable.

---

# Compatibility

Higher-level documents should remain compatible with lower-level documents.

If incompatibility occurs:

- Document it.
- Explain the change.
- Update dependent documentation.

Avoid silent breaking changes.

---

# Historical Integrity

Version history should never be rewritten.

Past releases remain part of the repository history.

Corrections should be introduced through new versions rather than modifying historical records.

---

# Release Checklist

Before creating a stable release verify:

- Review completed.
- Acceptance criteria satisfied.
- Terminology consistent.
- Cross-references updated.
- Changelog updated.
- Version numbers synchronized.

---

# Repository Philosophy

Versioning is not about counting changes.

It is about documenting the evolution of knowledge.

Every version should represent a measurable improvement in quality, clarity, or capability.

---

# Final Principle

Every contributor should be able to answer three questions by looking at a version number:

1. What changed?
2. Why did it change?
3. How significant was the change?

If the version cannot answer those questions, it has not been applied correctly.

---

**End of Versioning Standard**
