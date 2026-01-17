# UIXO Roadmap

This document outlines the planned direction for **UIXO**.
It is a living document and may evolve through community discussion.

UIXO is built with a **structure-first, community-driven mindset**.
We prefer slow, stable progress over rushed features.

---

## Guiding Principles

Before features, these rules guide all decisions:

* Open source always
* Clean and readable code
* UI-first focus (not a full app builder)
* AI assists, never replaces control
* No vendor lock-in
* Community contributions matter

---

## Phase 0 — Foundation (Current)

**Goal:** Establish trust, clarity, and project structure.

* [x] Project vision and README
* [x] Contribution guidelines
* [x] License selection
* [x] Roadmap definition
* [ ] Governance documentation
* [ ] Basic project structure
* [ ] Development environment setup

---

## Phase 1 — Core UI Editor (MVP)

**Goal:** Build a usable, minimal visual UI editor.

Planned features:

* Visual canvas
* Basic layout system
* Core UI components:

  * Button
  * Input
  * Text
  * Container
* Component tree view
* Property panel for structure (no styling yet)
* Live preview

Initial focus:

* React
* Tailwind CSS

---

## Phase 2 — Code Output & Sync

**Goal:** Ensure trust in generated code.

Planned features:

* Live JSX code view
* Clean and readable output
* One-to-one mapping between UI and code
* Editable code with instant UI sync
* Export React components

Quality rules:

* No unnecessary wrappers
* No hidden logic
* Code must be production-ready

---

## Phase 3 — AI-Assisted Styling (Optional)

**Goal:** Add AI as a helper, not a decision-maker.

Planned features:

* Optional AI prompt for styling
* Apply spacing, colors, typography
* Tailwind-based styling output
* Live UI and code updates
* Ability to accept, reject, or modify AI changes

AI principles:

* Pluggable providers
* No hard dependency
* Transparent output

---

## Phase 4 — Templates & Component Library

**Goal:** Speed up real-world usage.

Planned additions:

* Built-in page templates:

  * Login
  * Signup
  * Dashboard
  * Settings
* Reusable UI blocks
* shadcn/ui integration
* Community-contributed templates

---

## Phase 5 — Framework Expansion

**Goal:** Support more ecosystems without breaking trust.

Planned support:

* Next.js
* HTML output
* Vue
* Angular

Each framework will be added carefully, one at a time.

---

## Phase 6 — Plugin & Ecosystem

**Goal:** Let the community extend UIXO.

Ideas:

* Plugin system
* Custom components
* Template marketplace (open)
* Shared prompts and design rules

---

## What Is Explicitly Out of Scope

UIXO will **not** aim to be:

* A full backend builder
* A database manager
* An IDE replacement
* A one-click full app generator

Staying focused is intentional.

---

## Community Involvement

* Roadmap discussions happen in issues and discussions
* Features may move based on feedback
* Community proposals are welcome
* Maintainers ensure long-term stability

---

## Final Note

UIXO is built for the long term.

We value:

* Stability over speed
* Trust over hype
* Community over control

This roadmap exists to guide — not to rush.

---

**Build slowly.
Build openly.
Build together.**
