# Active Directory Attack Chain Model

## Purpose

Active Directory attacks do not succeed through single exploits.
They succeed through **compound trust failures over time**.

The goal is not domain dominance.
The goal is **progressive control amplification**.

---

## Core Principle

> In Active Directory, control emerges from relationships, not vulnerabilities.

Every AD environment is already compromised in theory.
The only unknown is **how efficiently control can be assembled**.

---

## Attack Chains vs Isolated Actions

Isolated actions focus on:
- individual vulnerabilities
- single privilege jumps
- discrete misconfigurations

Attack chains focus on:
- trust relationships
- permission inheritance
- identity reuse
- delegation paths

Chains create momentum. Isolated actions do not.

---

## Identity as the Primary Attack Surface

In AD environments:
- credentials outlive systems
- permissions accumulate silently
- trust is rarely revoked

Therefore, identities—not hosts—form the true attack surface.

---

## Chain Construction Thinking

Attack chains are built by answering:

1. **What identity do I control now?**
2. **What does this identity implicitly trust?**
3. **Where can this trust be extended or abused?**

Each answer defines the next link.

---

## Chain Acceleration Factors

Certain conditions accelerate attack chains:
- legacy service accounts
- shared administrative roles
- excessive delegation
- inconsistent security boundaries

These are force multipliers, not entry points.

---

## Risk and Timing

AD attack chains favor patience over speed:
- aggressive moves collapse chains
- noisy actions reset trust
- premature dominance exposes intent

Control should expand quietly until dominance is inevitable.

---

## Common Failure Modes

- chasing Domain Admin prematurely
- focusing on tools over relationships
- ignoring low-privilege identities
- breaking chains through impatience

---

## Output of Successful Attack Chains

Effective AD attack chains produce:
- multiple viable dominance paths
- resilient access
- optionality in execution

If only one path exists, the chain is fragile.

---

## Final Note

Active Directory compromise is not an exploit problem.
It is a **graph traversal problem under uncertainty**.
