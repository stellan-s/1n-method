# Metrics and Progress

The 1..n Method rejects traditional activity-based metrics (velocity, story points, tickets closed) in favor of measuring **reality**: what changed in production, and whether it's fit for purpose.

---

## The Problem with Activity Metrics

Common product development metrics include:

- **Story points per sprint**
- **Velocity trends**
- **Number of tickets closed**
- **Cycle time**
- **Burndown charts**

These metrics measure **motion**, not **value**. A team can have high velocity while building the wrong things, or low velocity while solving critical problems.

**Activity metrics optimize for throughput, not outcomes.**

---

## Principle: Measure Reality, Not Activity

The primary question is not "How much work did we do?" but **"What changed in production, and did it solve the problem?"**

### Primary Metric: Fitness for Purpose in Production

**Fitness for purpose** means:

- The solution addresses the actual user problem.
- It works reliably in the production environment.
- Users can accomplish their goals with it.
- It does not introduce unacceptable new problems.

This is a **qualitative judgment**, not a quantitative score. It requires honest assessment by the team and validation from real-world usage.

**Why not "quality"?** The term "quality" is overloaded and often means "passes tests" or "has few bugs." Fitness for purpose is broader: it includes whether the solution is useful, usable, and valuable—not just functional.

---

## Secondary Metrics: Context-Specific Signals

Depending on the problem being solved, you might measure:

- **User behavior change:** Did adoption increase? Did support tickets decrease?
- **System performance:** Did latency improve? Did errors decrease?
- **Business outcomes:** Did revenue grow? Did churn reduce?

These are **outcomes**, not outputs. They measure whether reality changed in the desired direction.

---

## Why Not Optimize for Throughput?

Some methodologies focus on maximizing throughput: "How can we ship more, faster?"

The 1..n Method does not optimize for throughput.

**Why:**

1. **Throughput encourages quantity over value.** Shipping more things is easy if you don't care whether they solve real problems.
2. **Throughput ignores the cost of maintenance.** More features mean more code to maintain, test, and support.
3. **Throughput assumes unlimited capacity.** In reality, teams have bounded focus. Optimizing for throughput leads to context-switching and reduced depth.

**Instead:** Optimize for **fitness for purpose**. Ship fewer things that matter more.

---

## Progress Is Not Linear

Traditional project management assumes progress is linear and measurable: "We're 60% done."

In reality:

- Most of the learning happens in the last 20% of the work.
- "Almost done" can stretch indefinitely.
- Problems discovered late can invalidate early assumptions.

**The 1..n Method acknowledges this.** Progress is binary: either something is fit for purpose in production, or it's not.

Intermediate states ("we shipped it but it doesn't work yet") are not progress—they're learning.

---

## How to Track Progress

Instead of burndown charts or velocity graphs, use:

### 1. Focus Set Visibility

Make the current focus set visible to the organization:

- What is in focus right now?
- What problem is each item solving?
- What does "done" look like for each?

**Why:** Transparency reduces status-check meetings and aligns expectations.

### 2. Completion Events

When something leaves the focus set (because it's done or abandoned), communicate:

- What was accomplished?
- What changed in production?
- What did we learn?

**Why:** This celebrates outcomes, not activity.

### 3. Fitness Assessments

After deploying, assess:

- Is it solving the problem?
- Are users able to use it?
- What needs to change?

**Why:** Deployment is not the finish line—fitness for purpose is.

---

## What About Velocity?

Some teams find velocity useful for internal planning. That's fine, as long as:

1. **It's not a target.** Velocity as a target incentivizes gaming the metric.
2. **It's not reported upward.** Executives don't need to know story points.
3. **It's not used to compare teams.** Velocity is context-specific and non-transferable.

If velocity helps a team estimate capacity, use it. If it creates pressure to inflate points or ship faster, abandon it.

---

## Summary

The 1..n Method measures progress by asking:

- **What changed in production?**
- **Is it fit for purpose?**
- **Did it solve the problem?**

Activity metrics (velocity, story points, tickets) are distractions. Reality is the only ground truth.

Do not optimize for throughput. Optimize for solving real problems well.
