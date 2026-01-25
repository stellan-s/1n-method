# Glossary

This document defines key terms used throughout the 1..n Method specification.

---

## Focus Set

The small, bounded list of work that a team is actively executing right now.

- Typically 1–3 items per team.
- Work in the focus set has full organizational support: attention, resources, and permission to complete.
- Everything else is **inert**.

**Example:** A team's focus set might contain: "Fix checkout flow errors" and "Launch beta referral program."

---

## Inert

Work that is not in the focus set.

- Inert items exist as ideas, requests, or backlog entries, but they are explicitly **not active**.
- They are not assigned, scheduled, or promised.
- Inert work may be discussed, documented, or refined, but without expectation of immediate action.
- Inert items may become active later (via replacement), or they may never be built.

**Example:** "Add dark mode" might be an inert item—acknowledged as a request, but not currently in focus.

---

## Replacement

The process by which new work enters the focus set by **displacing** existing work.

- To start something new, an existing item must leave the focus set.
- Departure happens when work is completed, explicitly abandoned, or deliberately paused.
- Replacement forces a prioritization decision: "Is this new thing more important than what we're doing now?"

**Why it matters:** Replacement prevents unbounded accumulation and ensures decisions are made with current information.

---

## Fitness for Purpose

The primary measure of whether work is complete.

- Does the solution solve the actual user problem?
- Does it work reliably in production?
- Can users accomplish their goals with it?
- Does it avoid introducing unacceptable new problems?

Fitness for purpose is a **qualitative judgment**, not a checklist or automated test. It requires honest assessment and real-world validation.

**Not the same as "quality":** Quality often means "passes tests" or "has few bugs." Fitness for purpose is broader—it includes usefulness, usability, and value.

---

## Commitment

A promise to deliver specific work within specific constraints.

In the 1..n Method:

- Commitments are limited to work in the focus set.
- Commitments respect capacity: only commit to what can be done with available resources and current knowledge.
- Inert work is **not a commitment**. Acknowledging an idea is not the same as promising to build it.

**Why it matters:** Over-commitment creates false expectations and organizational thrash.

---

## Capacity

The realistic amount of work a team can handle in a given time period.

- Capacity is bounded by human cognition, communication overhead, and the nature of the work.
- Capacity is not infinitely expandable by "working harder" or "adding more people."
- Respecting capacity means limiting the focus set to what can actually be done well.

**Why it matters:** Ignoring capacity leads to burnout, context-switching, and incomplete work.

---

## Cognitive Horizon (Optional Concept)

The time range within which a team can make reasonably informed decisions.

- Inside the horizon: Estimates have meaningful signal.
- Beyond the horizon: Estimates are guesses.

For most teams, the cognitive horizon is 1–4 weeks for detailed work, and 1–3 months for directional planning.

**Why it matters:** Commitments made beyond the cognitive horizon are unreliable.

---

## Abandonment

The deliberate decision to stop work on an item and remove it from the focus set without completing it.

- Abandonment is **not failure**—it's a recognition that the work is no longer worth the cost.
- Freeing the focus set slot allows the team to pursue something more valuable.

**Why it matters:** Not all work should finish. The ability to abandon gracefully prevents sunk-cost fallacies.

---

## Reality

The actual state of the system in production, as experienced by real users.

- Reality is the ground truth for measuring progress.
- Internal measures (tests passing, tickets closed, velocity) are proxies—they are not reality.

**Why it matters:** Optimizing for proxies without checking reality leads to building the wrong things.

---

## Sequential Priority

A way of expressing roadmap order without committing to calendar dates.

- **Now:** In the focus set, actively being worked on.
- **Next:** Top candidate to enter the focus set when capacity opens.
- **Later:** Under consideration, but not imminent.

**Why it matters:** Sequential language is honest about priority without making false time commitments.

---

## Conditional Commitment

A statement about future work that explicitly includes the conditions or assumptions on which it depends.

**Example:** "If Feature A completes as expected and no higher-priority work emerges, Feature B may enter focus in Q2."

**Why it matters:** Conditional language preserves honesty while meeting organizational planning needs.

---

This glossary defines the core vocabulary of the 1..n Method. Understanding these terms is essential for applying the method consistently.
