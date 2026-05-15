# Strategic Audit After Cycle 002

## Status

Completed

## Reflection type

Strategic audit / Project governance

## Scope

This audit reviews the project after `cycle_001` and `cycle_002`.

It does not prove a new mathematical result, introduce a new source theorem,
or review `FJ41` in detail. `FJ41` is used only as the current procedural
handoff into cycle 003.

## Inputs read

This audit is based on the repository state recorded in:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `ESTABLISHED_RESULTS.md`;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/*.md`;
- `reflections/cycle_001_reflection.md`;
- `reflections/cycle_002_reflection.md`;
- `modules/cycle_001/FJ01*` through `FJ20*`;
- `modules/cycle_002/FJ21*` through `FJ40*`.

No new external source is used in this audit.

## Executive diagnosis

The project is healthy as a source-disciplined research archive, but it is
entering a phase where source discipline can start imitating progress.

Cycle 001 built a usable foundation: simplified Farrell--Jones formulation,
classifying spaces, virtually cyclic groups, basic examples, Nil warnings,
known cases, inheritance, proof-technology vocabulary, and first target
selection.

Cycle 002 did more than bookkeeping. It produced a real route movement:
the \(G_{p,q}\)-family was moved through Brown finite generation plus a
Bass--Serre freeness bridge into the finite-rank free-by-cyclic route.

The strategic danger is that the next several modules could verify BNS,
Bieri, Bieri--Renz, Karrass--Solitar variants, finite-index inheritance, and
formulation conventions without forcing a decision about the active target.
That would create a beautiful archive and a weak research program. The
project now needs sharper gates.

## What Is Working

### Source discipline is real

The project reliably distinguishes:

- definitions;
- examples;
- theorem maps;
- source-verified claims;
- project-selection decisions;
- warnings;
- open problems;
- failed or negative selection results.

This is the main structural achievement of the first two cycles. It prevents
the project from treating local indicability, HNN splittings, hierarchy
vocabulary, or epimorphisms to \(\mathbb Z\) as automatic Farrell--Jones
routes.

### The target has narrowed

`T-001` began as torsion-free one-relator residual gap analysis. Cycle 002
made this concrete by separating named routes:

- hyperbolic;
- finite-dimensional CAT(0);
- virtually solvable;
- hyperbolic-by-cyclic/free-by-cyclic;
- version-aware inheritance.

The residual ledger is conservative in the right way. It records missing
bridges, not counterexamples.

### The project has one genuine positive bridge

The \(G_{p,q}\)-family is the most important cycle-002 artifact. It is not
just a source row. It has the full project rhythm:

1. identify a residual bucket;
2. select a source;
3. run a computation;
4. find the missing bridge;
5. verify the bridge;
6. record a route subtraction.

This should be treated as the model for future progress.

## Strategic Risks

### Risk 1. Literature verification without route delta

Several current next-step candidates are legitimate sources:
Bieri--Neumann--Strebel, Bieri, Bieri--Renz, Karrass--Solitar, finite-index
inheritance sources, and source-convention sources around `FJ02`.

The risk is not that these sources are irrelevant. The risk is that verifying
them one by one can become decorative unless each source check changes the
attack surface.

Every literature module from here should answer:

```text
What route became possible, impossible, narrower, or closed because of this
source check?
```

If the answer is "none yet," the module must say why the source check was
still necessary and what decision it enables.

### Risk 2. Open-question inflation

`OPEN_QUESTIONS.md` is useful, but it is now large enough that questions can
accumulate faster than decisions. This can make the project feel active while
postponing hard choices.

Open questions should be grouped into:

- active blockers;
- deferred foundations;
- optional refinements;
- closed or historical trail markers.

Only active blockers should drive the next three to five modules.

### Risk 3. RB-004 can become too absorbing

`RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\), was a good
choice because it fed directly into `FJ26`. It has already paid off once.

But after the \(G_{p,q}\)-family, the next `RB-004` work is more source-heavy:
BNS membership, Bieri finiteness hypotheses, Bieri--Renz higher invariants,
or Karrass--Solitar cleanup routes. That is acceptable only if it produces a
candidate, a bridge, or a principled stop.

If `RB-004` cannot produce a new source-ready candidate within a bounded
window, the project should pivot to another residual bucket rather than keep
reading adjacent sources indefinitely.

### Risk 4. `FJ02` is still formulation debt

Deferring `FJ02` was correct during the simplified first pass. It is no
longer harmless if the project begins using:

- coefficients in additive categories;
- `FJCw`;
- `FICwF`;
- finite wreath product formulations;
- full \(\mathcal{FJ}\) inheritance;
- finite-index overgroup arguments whose source formulation is stronger than
  the simplified ring-coefficient version.

`FJ02` should not interrupt every group-theoretic module, but it must
interrupt before formulation mismatch becomes a proof input.

### Risk 5. Too many theorem maps, too few attack packets

The ledgers are good at saying what a theorem does. The next phase needs
more artifacts that package an attack:

```text
group or family;
presentation or construction;
target status;
known route overlap;
missing bridge;
exact source needed;
decision criterion;
stop condition.
```

Without attack packets, source checks have no friction.

## Strategic Rules For Cycle 003

### Rule 1. Every source module needs a route-delta table

Each source-verification module should include:

| Question | Required answer |
|---|---|
| What theorem was checked? | Exact statement and hypotheses. |
| What route does it affect? | Named route or residual bucket. |
| What does it enable? | Candidate, bridge, subtraction, or closure. |
| What does it not enable? | Explicit non-use warning. |
| What is the next decision? | Continue, pivot, or stop. |

This prevents bibliography from becoming self-justifying.

### Rule 2. No more than three consecutive source-only modules

After at most three source-only modules, the project must do one of:

- select a concrete candidate;
- close a source route as non-actionable;
- move to a different residual bucket;
- complete a formulation checkpoint such as `FJ02`;
- write a failed-attempt or no-candidate artifact.

### Rule 3. Residual buckets need stop conditions

For `RB-004`, a reasonable stop condition is:

```text
If direct BNS/Bieri/Bieri--Renz/Karrass--Solitar checks do not produce a
new concrete source-ready candidate or route bridge by the next decision
checkpoint, pause RB-004 and audit another residual bucket.
```

This is not abandonment. It is how the project avoids circling a source
cluster.

### Rule 4. Attack packets before new computations

Before another worked example or family computation, create a compact attack
packet. The packet should say why the example is not merely:

- already virtually solvable;
- already covered by the \(G_{p,q}\)-family;
- just another calibration example;
- dependent on unverified formulation changes.

### Rule 5. Separate route subtractions from known-case expansion

Known-case expansion is useful, but cycle 003 should not drift into a general
known-classes survey. Add known cases only when they interact with the active
target or when a cycle checkpoint explicitly changes targets.

## Recommended Cycle-003 Shape

### Immediate window

The next few modules should be treated as a bounded decision window, not an
open-ended source-reading sequence.

| Module slot | Recommended task | Decision pressure |
|---|---|---|
| `FJ42` | Bieri (1976) primary-source verification | Does it give an actionable normal-subgroup bridge, and under which finiteness hypothesis? |
| `FJ43` | Route-delta checkpoint for BNS/Bieri/Karrass--Solitar | Continue `RB-004` only if a route or candidate has become sharper. |
| `FJ44` | Karrass--Solitar dihedral finite-index handling, if still relevant | Decide whether the cleanup theorem can actually route cases under project formulation. |
| `FJ45` | Attack packet or no-candidate artifact | Select a concrete candidate or pause `RB-004`. |

If `FJ42` or `FJ43` shows that the source cluster is not producing a concrete
route, do not automatically proceed to Bieri--Renz. Record the obstruction
and pivot.

### Mid-cycle checkpoint

By `FJ50`, the project should have one of:

- a new concrete `RB-004` candidate;
- a new route subtraction;
- a proof that the current `RB-004` source cluster is non-actionable for now;
- a completed finite-index/formulation bridge;
- a decision to switch to another residual bucket.

### Candidate pivot buckets

If `RB-004` stalls, the next audit should compare:

| Bucket | Why it may be better | Main risk |
|---|---|---|
| `RB-005` finite-index / virtually compact special | Directly addresses a known caution from `FJ24` and `FJ27`. | May force `FJ02` or source-formulation reconciliation. |
| `RB-006` compact special or CAT(0)-looking one-relator cases | Could produce geometric route subtractions. | Needs one-relator cubulation/specialness sources. |
| `RB-007` virtually solvable recognition | Could turn a conditional route into explicit examples. | Classification may be a source-heavy detour. |
| hierarchy-to-route extraction | Uses the Linton vocabulary already adopted. | Easy to overstate hierarchy as a route without extra hypotheses. |

## Recommended Artifact Templates

### Attack packet template

```markdown
# Attack Packet. Short name

## Candidate

## Why this is not already removed

## Known source data

## Missing bridge

## Decision criterion

## Stop condition
```

### Route-delta template

```markdown
## Route delta

- Route affected:
- Exact theorem checked:
- Hypothesis gained:
- Hypothesis still missing:
- Residual bucket affected:
- Does this remove a case? yes/no
- Next decision:
```

### No-candidate artifact template

```markdown
# No-Candidate Note. Route or source cluster

## Source cluster checked

## What was hoped for

## What failed

## What remains usable

## Why the project should pivot or pause
```

## Governance Decisions

1. `T-001` remains a valid active target, but only if the project keeps
   forcing route decisions.
2. `RB-004` remains valid through the immediate Bieri/BNS decision window.
3. `FJ02` should be promoted from "eventual foundation" to "conditional
   blocker": it interrupts as soon as source formulations become route input.
4. Open questions should be pruned into active blockers, deferred
   foundations, optional refinements, and closed trail markers.
5. The project should measure cycle-003 success by route movement, not by
   number of sources verified.

## Success Criteria For The Next Ten Modules

By the next strategic checkpoint, the project should produce at least one of:

- a new concrete source-ready candidate outside the \(G_{p,q}\)-family;
- a new verified route subtraction;
- a completed finite-index or formulation bridge that unlocks an existing
  route;
- a documented failed source cluster with a pivot decision;
- a completed `FJ02` or source-conventions artifact because formulation debt
  became active.

If none of these occurs, the project is drifting.

## Current Procedural Handoff

`FJ41` is the current handoff state after cycle 002: direct BNS theorem use
has been checked, but it does not itself compute a new invariant or remove a
residual bucket.

The next module may still be `FJ42`, but it should be governed by this audit:
Bieri (1976) verification is useful only if it sharpens a route decision.

## References

No new external references were used.

Internal references:

- `README.md`
- `PROJECT_CHARTER.md`
- `SCOPE_LEDGER.md`
- `ESTABLISHED_RESULTS.md`
- `OPEN_QUESTIONS.md`
- `NOTATION_LEDGER.md`
- `BIBLIOGRAPHY.md`
- `ledgers/known_classes.md`
- `ledgers/inheritance_properties.md`
- `ledgers/open_group_classes.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/theorem_dependencies.md`
- `reflections/cycle_001_reflection.md`
- `reflections/cycle_002_reflection.md`
- `modules/cycle_001/`
- `modules/cycle_002/`
