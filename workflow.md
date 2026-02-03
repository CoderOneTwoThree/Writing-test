# Workflow

## Purpose
Define a two-tier workflow for long-form writing that mirrors software development: a macro design phase followed by modular, section-by-section execution with integration checkpoints.

## Tier 1: Macro workflow (strategy)
### Goals
- Define the overall outcome, scope, and argument architecture.
- Establish a stable section map before deep research and drafting.

### Steps
1. Vision: define outcome, audience impact, and press-release summary.
2. Scoping: set limits, exclusions, definitions, time window, and geography.
3. Planning: draft the top-level structure and evidence needs.
4. Section map: create contracts for each section (see template).
5. Breadth scan (optional): shallow sweep to validate or refine the plan.

### Macro deliverables
- vision.md
- scope.md
- plan.md
- section-map.md
- sweep.md (optional)

## Tier 2: Section workflow (execution)
Each section is treated like a module with its own mini-pipeline.

### Per-section steps
1. Micro-scope: narrow the section's specific claims and limits.
2. Targeted research: gather evidence required by the section contract.
3. Draft: produce a section draft with inline evidence notes.
4. Review: stress-test logic and evidence for that section.
5. Style pass: align with `soul.md` and the preferred language.
6. Integrate: stitch into the master draft with clean transitions.

### Per-section deliverables
- section-XX-scope.md
- section-XX-research.md
- section-XX-draft.md
- section-XX-review.md
- section-XX-style.md

## Integration checkpoints
Run integration checks at these points:
- After every 2-3 completed sections.
- After any high-risk or controversial section.
- At the end, before final review.

### Integration checklist
- Thesis alignment: does each section reinforce the main claim?
- Flow: do transitions carry the reader logically?
- Balance: are opposing views treated and rebutted where necessary?
- Evidence: are claims supported and traceable?
- Style: does the voice remain consistent?

## Section map template
- Section ID / Title
- Purpose
- Core claim (1-2 sentences)
- Inputs (facts, prior sections, sources)
- Outputs (what the reader should believe/know after)
- Evidence requirements (primary sources, stats, counter-evidence)
- Risks (weak points, contested claims)
- Transition IN (from previous section)
- Transition OUT (to next section)
- Status (not started / in progress / drafted / reviewed / integrated)

## Default folder structure (optional)
- /project
  - /sections
    - section-01
    - section-02
  - /meta
    - vision.md
    - scope.md
    - plan.md
    - section-map.md
    - sweep.md
  - /drafts
    - master.md

## Rules of engagement
- Always read `soul.md` before drafting.
- Do not skip the section contract; it prevents scope creep.
- Avoid deep research before the section map is stable.
- Use integration checkpoints to prevent drift.
