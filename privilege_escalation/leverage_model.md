# Privilege Escalation Leverage Model

## Purpose

Privilege escalation is not about trying everything.
It is about **identifying leverage points in asymmetric systems**.

The goal is not elevation itself.
The goal is **changing the balance of control**.

---

## Core Principle

> Privilege escalation succeeds where authority, trust, and complexity intersect.

Escalation is rarely accidental.
It is usually the result of:
- misplaced trust
- implicit assumptions
- unmanaged complexity

---

## Sources of Leverage

Effective privilege escalation comes from leverage, not brute force.

Common leverage sources include:
- trust boundaries
- permission inheritance
- service relationships
- automation and convenience mechanisms

The more a system optimizes for usability, the more leverage it creates.

---

## Local vs Relational Escalation

There are two escalation classes:

### Local Leverage
- file permissions
- scheduled tasks
- service execution context
- environment configuration

### Relational Leverage
- user-to-user trust
- service-to-service delegation
- role assumptions
- identity propagation

Relational escalation often scales faster than local escalation.

---

## Escalation Hypotheses

Before attempting escalation, form a hypothesis:

- Who trusts whom?
- What executes on behalf of whom?
- Where does convenience override strict control?

Escalation without hypotheses degenerates into guessing.

---

## Risk-Aware Escalation

Privilege escalation carries higher risk than exploitation because:
- changes are persistent
- failures are visible
- rollback is often impossible

Therefore:
- escalate once
- escalate decisively
- escalate with intent

---

## Common Failure Modes

- permission brute forcing
- tool-driven escalation attempts
- ignoring system purpose
- mistaking availability for leverage

---

## Output of Successful Escalation

Effective privilege escalation produces:
- durable access
- expanded control surface
- reduced operational friction

If escalation increases instability, leverage was misunderstood.

---

## Relationship to Post-Exploitation

Privilege escalation defines the quality of post-exploitation.

Clean escalation:
- preserves trust relationships
- enables quiet lateral options
- reduces urgency after elevation

Messy escalation forces post-exploitation to:
- stabilize access
- compensate for exposure
- operate under time pressure

Post-exploitation optionality is earned during escalation.

---

## Final Note

Privilege escalation is not luck.
It is applied system understanding.
