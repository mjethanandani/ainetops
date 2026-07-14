# Problem Statement — Strawman

For circulation on AINETOPS, OPSAWG, and NMOP ahead of the IETF 126 side meeting
(Friday 24 July, 08:00 CEST). This is a strawman for the room to review and
amend — the meeting reaches rough consensus by editing this text, not by
drafting one from scratch live.

## Problem statement

AI and ML techniques are increasingly being applied to network
operations: anomaly detection, closed-loop remediation, intent
translation, and autonomous device management. The IETF community has
responded with a growing number of individual drafts, but these efforts
remain disconnected — there is no working group with adopted work items
in this space, no agreed set of deliverables, and no clear
standards-track path for the work. Without coordination, the community
risks producing overlapping informational documents rather than
interoperable standards.

This working group will identify what the IETF is well-positioned to
standardize, describe categories of work appropriate for IETF
standardization, and flag where community consensus is still forming.

*(Adapted directly from the second and fourth paragraphs of the wiki's
Background section — kept generic rather than anchored in the autonomic
networking architecture, which stays in the wiki as supporting context
but isn't part of the statement the room votes rough consensus on.)*

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
- NMOP has signaled openness to complementary AI-related *experiments*
  (e.g., closed-loop automation/troubleshooting via YANG Storage and
  message-broker integration, anomaly detection, YANG topology/digital-map
  issues) — is that compatible with this statement as a parallel,
  coordinated track, or does the statement need to explicitly carve it
  out to avoid ambiguity?
