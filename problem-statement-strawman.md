# Problem Statement — Strawman

For circulation on AINETOPS, OPSAWG, and NMOP ahead of the IETF 126 side meeting
(Friday 24 July, 08:00 CEST). This is a strawman for the room to review and
amend — the meeting reaches rough consensus by editing this text, not by
drafting one from scratch live.

## Problem statement

There is no standards-track home for YANG models governing AI agent
behavior in network management, and existing WG charters do not cover
that scope.

*(Kept to one sentence deliberately — OPSAWG's own charter opens with a
single 25-word sentence, NMOP's with two. See "Why this, why now" below
for the supporting rationale, which is not part of the statement itself.)*

## Why this, why now

- **Evidence, not aspiration.** Eight individual drafts are already active
  across OPSAWG, NMOP, and NMRG, converging independently on the same
  categories of work (see the [landscape summary](https://wiki.ietf.org/e/en/group/ops/aiops)).
  This is not a proposal to create interest — the interest already exists
  and is currently uncoordinated.
- **A real gap, not a scope expansion.** OPSAWG, NMOP, and NETCONF WG each
  have relevant expertise, but none has AI agent management for network
  operations in its current charter, and expanding any of them to absorb
  this work is not the proposed path. This statement is what establishes
  why a dedicated working group is needed.
- **The cost of waiting.** The AI tooling space (MCP, A2A, vendor
  frameworks) moves faster than the IETF's normal cycle. Every cycle
  without a standards-track path is a cycle in which vendor-specific,
  non-interoperable approaches harden into de facto practice.

## What this statement does *not* claim

For contrast — this is deliberately not a sufficient problem statement on
its own: *"AI is important for network operations."* That's an opinion,
not a gap. The statement above is meant to name the specific, missing
thing (a standards-track home) rather than assert general importance.

This statement also does not prejudge:

- Whether the meeting ends with a **direct WG proposal to IESG** or
  **defers to a BoF** — that determination is made at the close of the
  meeting, once critical mass, deliverables, and chair candidates are
  assessed.
- The **specific deliverables, tracks, or milestones** — those are
  scoped in the deliverables/milestones breakout.
- **AI/ML algorithm specification** — explicitly out of scope regardless
  of outcome; belongs in the IRTF.

## For discussion at the meeting

Come prepared to amend, not just approve. In particular:

- Is "AI agent management for network operations" the right scope
  boundary, or too broad / too narrow?
- Does the statement need to name specific interface categories (YANG
  models, NETCONF/RESTCONF extensions, MCP mapping, A2C/A2A) explicitly,
  or is the general framing sufficient?
- Is the claim that "no existing WG charter covers this" accurate and
  defensible if challenged by an OPSAWG, NMOP, or NETCONF WG chair?
