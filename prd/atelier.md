# Atelier

The product root: what Atelier is, for whom, and what holds across every
feature. Features, use cases and specs are under `prd/atelier/`, and each
cites this file. Decisions are numbered in `prd/atelier/decisions.md`.

## Purpose

Atelier is a software factory. It is five things:

- the loop that lets agents keep picking up tickets toward the developer's
  goal;
- the guard rails that let the developer work in a given profile and get
  consistent results;
- the map that makes clear which decisions belong to the developer, so they
  are not left to the AI;
- the window into the state of a project while it is being built;
- the landscape we work in.

The loop is the last of these to be built. The other four are useful
without it, and are used first (D11).

## Who it is for

The developer who cares about the code, and who controls its quality
without writing it. First the owner; later anyone building their own
factory from what Atelier publishes.

## Principles

- **The business is front and centre.** One product per repository, one
  language, held in `GLOSSARY.md` (D6, D7).
- **The developer owns the decisions.** Each decision has its layer, and
  the layers are written in order, from idea to code.
- **Measure, don't tag.** A principle is written down once. Signals, not
  build rules, show whether it holds.
- **Atelier is the source of truth.** Ideas start here, and every other
  part points here (D2).
- **Nothing needs Atelier to run** (D3).
- **A file lives with its subject,** unless the loop reads it (D4).
- **Custody is narrow.** Only the driver holds the factory's key. No agent
  holds a credential.
- **The trust base is built at the desk** (D9).

## Pillars

Atelier, like everything it builds, inherits the four pillars in
`PILLARS.md` (D12).

## Constraints

- Linux, on the owner's machines.
- Claude Code and Codex are both usable as the agent.
- Atelier's own tools are written in Rust.
- Everything here is public, under MIT. Instances, their data and their
  configuration never are.

## Non-goals

- Not an agent framework, and not a code review tool.
- It holds no products and no history: products live in their own
  repositories, and history in the research record.

## Deviations

None.

## Open

- Users beyond the owner: what they need first.
