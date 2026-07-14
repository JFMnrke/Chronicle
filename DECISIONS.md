# Chronicle — Decisions

> This document records the project's confirmed decisions.
>
> Each decision answers only two questions:
>
> - What was decided?
> - Why?

---

## 2026-07-12

### Repository Split

**Decision**

Chronicle is divided into two repositories:
- A public repository for the product.
- A private repository for personal data and user-specific configuration.

**Reason**

Separate the product from the user's life.

---

### Documentation Language

**Decision**

Public documentation is written in English.

Private documentation is written in Spanish.

**Reason**

English improves accessibility and collaboration while Spanish remains the most natural language for personal planning and reflection.

---

### Canonical Sources

**Decision**

Each type of information has exactly one canonical location.

**Reason**

Avoid duplicated knowledge and keep the project easy to maintain.

---

### Documentation Philosophy

**Decision**

Documentation must remain lightweight.

**Reason**

Every document must cost less to maintain than the value it provides.

---

### Project Context

**Decision**

`PROJECT_CONTEXT.md` is a stable project contract, not a project status report.

**Reason**

Context should change rarely. Active work belongs in GitHub Issues, not in canonical documentation.

---

### Work Modes

**Decision**

Exploration and consolidation are separate phases.

**Reason**

Ideas should only become part of the project after explicit review and approval.
