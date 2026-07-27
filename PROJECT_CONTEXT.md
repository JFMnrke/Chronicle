# Chronicle — Project Context

> This file contains the minimum context required to continue the project consistently.
>
> It is intentionally brief and only stores the current state of Chronicle.

---

## Identity

Chronicle is a personal operating system designed to help people navigate the direction of their attention, allowing them to live with greater intention instead of by inertia.

It serves as a mirror of how the user directs their attention, how that attention shapes projects, habits, and identity, and makes the chosen path visible without replacing the user's judgment.

Chronicle organizes, records, and automates information only to increase awareness and help the user better understand and navigate their attention. It never creates purpose; it reflects it.

Its role is not to decide who the user should become, but to help the user remember who they already decided to be.

## Working Principles

- Attention is the organizing principle of the system.
- Exploration and consolidation are separate phases.
- Every idea must have one canonical location.
- The context file must remain brief.
- Decisions are documented; conversations are not transcribed.
- Chronicle thinks with the user, never for the user.
- AI may propose changes during exploration, but may update canonical context only after explicit consolidation and user approval.

  ## Repository Structure

The Chronicle project is divided into two repositories.

### Public Repository

Contains the product itself:

- Philosophy
- Documentation
- Architecture
- Source code
- Public roadmap

### Private Repository

Contains the user's personal environment:

- Personal configurations
- Personal goals
- Activity data
- Automations
- Sensitive information

The public repository describes how Chronicle works.

The private repository describes how the user works with Chronicle.

## Canonical Sources

Each type of information has exactly one canonical location.

| Information | Canonical Location |
|-------------|--------------------|
| Project philosophy | `MANIFESTO.md` |
| Project context | `PROJECT_CONTEXT.md` |
| Architectural and product decisions | `DECISIONS.md` |
| Product vision and roadmap | `ROADMAP.md` |
| Public documentation | `docs/` |
| Source code | `src/` |
| Personal data | Private repository |
| Active work | GitHub Issues |

## AI Editing Policy

AI systems are collaborators, not decision-makers.

They may:

- Help users navigate their attention in ways that align with the goals, projects, and identity they have explicitly chosen.
- Read all public project documentation.
- Propose improvements, alternatives, and new ideas.
- Identify inconsistencies and outdated information.
- Draft updates for review.

They must never:

- Decide where the user's attention should be directed.
- Modify canonical documents without explicit user approval.
- Treat exploratory discussions as confirmed decisions.
- Create goals or priorities that have not been explicitly accepted by the user.
- Duplicate information across multiple canonical sources.

Every modification to a canonical document must result from an explicit consolidation process.
