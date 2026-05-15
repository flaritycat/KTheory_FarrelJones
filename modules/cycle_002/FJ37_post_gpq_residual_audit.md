# Module FJ37. Post-Gpq residual audit and next target selection

## Status

Completed

## Module type

Attack surface / Reflection / Source selection

## Problem

`FJ36` removed the family
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad
p,q\geq2,\quad \gcd(p,q)=1,
\]
from the active `T-001` residual by verifying
\[
G_{p,q}\cong F_n\rtimes \mathbb Z
\]
for some finite \(n\). The project now needs to audit what remains, decide
whether the exact rank of \(K_{p,q}\) is worth computing, and select the next
bounded residual problem without turning the \(G_{p,q}\)-family bridge into a
global theorem for torsion-free one-relator groups.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ28`, the conservative `T-001` residual ledger;
- `FJ29`, the selection of `RB-004` as the first residual attack surface;
- `FJ30`, the first-pass Brown/BNS source verification;
- `FJ36`, the \(G_{p,q}\)-family Bass--Serre route bridge;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `OQ-044`, `OQ-054`, and `OQ-055`.

## Output target

Produce:

- a post-\(G_{p,q}\) audit of the active residual;
- a decision on whether exact rank computation for \(K_{p,q}\) is currently
  route-critical;
- the next module target after `FJ37`;
- ledger updates that preserve the distinction between a family route bridge
  and a global theorem.

## Definitions

**Definition.** A post-route residual audit is a project bookkeeping step
performed after a route subtraction, checking which open questions have been
resolved, which are merely deferred, and which residual bucket should be
attacked next.

**Definition.** A method-exhaustion warning records that a successful method
on one example or family has not been proved to cover all cases in the
ambient target.

**Definition.** The beyond-Brown `RB-004` source-selection target is the
problem of finding or verifying a kernel-recognition source for cases not
covered by the Brown two-generator one-relator criterion already checked in
`FJ30`.

## Main work

### Audit after FJ36

The current `RB-004` ledger has three different statuses that must not be
merged.

| Item | Status after `FJ36` | Interpretation |
|---|---|---|
| \(G_{2,3}\) | Removed by `FJ33` through \(F_2\rtimes\mathbb Z\). | A single worked example. |
| \(G_{p,q}\), \(p,q\geq2\), \(\gcd(p,q)=1\) | Removed by `FJ36` through \(F_n\rtimes\mathbb Z\), \(n<\infty\). | A family bridge, with rank not computed. |
| General `RB-004` | Still active. | Brown's checked route is limited; the project has no global kernel-control theorem. |

**Warning.** The \(G_{p,q}\)-family result is not a theorem that every
torsion-free one-relator epimorphism to \(\mathbb Z\) has finite-rank free
kernel.

### Rank computation decision

`FJ36` proves \(K_{p,q}\cong F_n\) for some finite \(n\). The `FJ26` route
requires finite rank, not the exact numerical value of \(n\). Therefore the
exact rank computation is not route-critical at this stage.

**Decision.** Defer exact rank computation for \(K_{p,q}\). Keep it as a
possible later calibration or exposition task, but do not spend the next
module on it.

### Candidate next targets

| Candidate | Decision | Reason |
|---|---|---|
| Compute the exact rank of \(K_{p,q}\). | Deferred. | Finite rank is already enough for the route ledger. |
| Search for another example inside the same \(G_{p,q}\)-style family. | Deferred. | `FJ36` already covers the family at the level needed by `FJ26`. |
| Verify the original Bieri--Neumann--Strebel normal-subgroup theorem. | Deferred as a standalone target. | Useful if the project needs abelian quotients beyond \(\mathbb Z\), but not the most direct next obstruction. |
| Source-select beyond Brown's two-generator criterion. | Selected. | `OQ-044` remains the cleanest unresolved `RB-004` source problem after the \(G_{p,q}\) bridge. |
| Switch to finite-index or virtual-special handling. | Deferred. | Important, but it would leave the current kernel-recognition thread before resolving its next explicit source gap. |

### Selected next module

**Selection.** The next module is:

```text
FJ38. RB-004 beyond-Brown source selection
```

Its task should be to identify the next source or source cluster for
kernel-recognition cases outside Brown's checked two-generator criterion.
It should begin from the repository's existing source queue:

- the original Bieri--Neumann--Strebel paper, already located but not checked
  directly;
- the one-relator structure sources from `FJ21`--`FJ22`;
- any additional kernel-recognition source only after bibliographic and
  hypothesis checks.

**Warning.** `FJ38` should not use a theorem from an unverified source. Its
first job is source selection and exact-hypothesis triage, not theorem use.

## Proposition / Theorem / Conjecture / Example

**Proposition.** After `FJ36`, the exact rank of \(K_{p,q}\) is not needed for
the active `FJ26` route, and the next bounded residual target is `OQ-044`,
source selection for `RB-004` cases outside Brown's checked two-generator
criterion.

**Proof.** `FJ36` proves \(K_{p,q}\cong F_n\) with \(n<\infty\), which is
exactly the finite-rank input required by the free-by-cyclic route in `FJ26`.
Computing \(n\) would refine the example but would not unlock a new route.
Meanwhile, `ledgers/t001_kernel_recognition.md` states that Brown's currently
checked route is best understood for compatible two-generator one-relator
presentations. `OQ-044` asks for the source handling cases outside that
criterion. Since `RB-004` remains the selected attack surface and `OQ-044` is
the next source gap inside it, `FJ38` should select or verify the next source
for beyond-Brown kernel recognition.

**Remark.** This is a project-selection result, not an `ER-*` theorem.

## Proof or verification

Verification steps completed:

1. Checked `ledgers/t001_residual.md` after the `FJ36` route subtraction.
2. Checked `ledgers/t001_kernel_recognition.md` for the remaining limitation
   of Brown's checked two-generator criterion.
3. Checked `OQ-054` and `OQ-055`.
4. Decided that exact rank computation is deferred because it is not
   route-critical.
5. Selected `OQ-044` as the next active source-selection target.

## References

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell-Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904.
  https://doi.org/10.1093/imrn/rnac012
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ28_residual_ledger_after_route_subtractions.md`
- `modules/cycle_002/FJ29_residual_attack_surface_selection.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ28`;
- `FJ29`;
- `FJ30`;
- `FJ36`;
- `OQ-044`;
- `OQ-054`;
- `OQ-055`;
- Brown (1987), as already verified in `FJ30`;
- Bestvina--Fujiwara--Wigglesworth (2023), through `FJ26`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-054`;
- a deferral decision for `OQ-055`;
- the selection of `OQ-044` as the next active target;
- the next module target `FJ38`;
- no new `ER-*` result.

## Open questions generated

- Which concrete non-Brown `RB-004` test case should be used after `FJ38`
  selects or verifies a broader source?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ37` and next `FJ38`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the `OQ-054` resolution, `OQ-055` deferral, and
  selected `OQ-044` target;
- `OPEN_QUESTIONS.md` for `OQ-044`, `OQ-054`, `OQ-055`, and the new concrete
  case-selection question;
- `NOTATION_LEDGER.md` for the beyond-Brown source-selection target;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` only to record that `FJ37`
  used Brown and Bestvina--Fujiwara--Wigglesworth through existing route
  ledgers, without new theorem verification.
