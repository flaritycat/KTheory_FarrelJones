# Module FJ40. Finitely presented-kernel test selection for RB-004

## Status

Completed

## Module type

Attack surface / Literature verification / Reflection

## Problem

`FJ39` verifies Karrass--Solitar (1978) as a bridge for one-relator groups
with a nontrivial finitely presented normal subgroup of infinite index. The
next question is whether the repository already contains a concrete non-Brown
`RB-004` test case where that hypothesis is source-ready.

This module must not turn the Karrass--Solitar theorem into an example
generator. It can only select a test case if the finite-presentation input is
already recorded by an internal proof or by a checked source.

## Input

This module uses:

- `FJ30`, Brown/BNS kernel-recognition verification;
- `FJ33`, the worked \(G_{2,3}\) Brown test;
- `FJ36`, the \(G_{p,q}\)-family Bass--Serre bridge;
- `FJ37`, the post-\(G_{p,q}\) residual audit;
- `FJ39`, the Karrass--Solitar normal-subgroup bridge verification;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `OQ-056`, `OQ-059`, and `OQ-060`.

## Output target

Produce:

- a candidate audit for finitely presented kernels already in the repository;
- a decision about whether a non-Brown `RB-004` test case is source-ready;
- updates to the residual and kernel-recognition ledgers;
- the procedural handoff after the twentieth module of cycle 002.

## Definitions

**Definition.** A source-ready finitely presented-kernel test case is a
specific one-relator group \(G\), a specified nontrivial normal subgroup
\(H\trianglelefteq G\), and a recorded proof or source-verified claim that
\(H\) is finitely presented and has infinite index in \(G\).

**Definition.** A non-Brown `RB-004` test case is a source-ready
kernel-recognition case not already removed by the Brown two-generator route
or by the \(G_{p,q}\)-family Bass--Serre bridge recorded in `FJ36`.

**Warning.** A theorem saying that finite presentation of \(H\) implies strong
structure for \(G\) does not itself prove that any newly chosen \(H\) is
finitely presented.

## Main work

### Candidate audit

| Candidate | Finitely presented-kernel status | Route status | FJ40 decision |
|---|---|---|---|
| Commutator-presentation calibration from `FJ31` | The kernel is recorded as infinite cyclic. | Already calibration; also covered by elementary/virtually solvable considerations. | Not a non-Brown test case. |
| \(G_{2,3}\) from `FJ33` | The kernel is internally identified as \(F_2\). | Already removed through the `FJ26` finite-rank free-by-cyclic route. | Not a new test case. |
| \(G_{p,q}\), \(p,q\geq2\), \(\gcd(p,q)=1\), from `FJ36` | The kernel is finite-rank free by the Brown finite-generation input plus the Bass--Serre freeness bridge. | Already removed as a family through `FJ26`. | Not a new test case. |
| General beyond-Brown `RB-004` cases | No concrete normal subgroup with source-recorded finite presentation is currently present in the repository. | Still active residual territory. | No source-ready test case selected. |
| Karrass--Solitar infinite-dihedral alternative | No concrete example is selected; the alternative arises as a possible conclusion of the theorem. | Needs finite-index and version-aware inheritance handling before route use. | Deferred to a later module if needed. |

### Selection result

**Decision.** `FJ40` does not select a new non-Brown finitely
presented-kernel test case.

The reason is not that such examples cannot exist. The reason is narrower:
inside the current repository state, every source-ready finitely presented
kernel is already either a calibration case or routed through the
\(G_{p,q}\)-family bridge, while the beyond-Brown cases do not yet have a
recorded finite-presentation input.

### Consequence for RB-004

The Karrass--Solitar bridge remains useful as a cleanup route:

\[
\text{one-relator }G
\quad+\quad
1\ne H\trianglelefteq G
\quad+\quad
H\text{ finitely presented}
\quad+\quad
[G:H]=\infty
\]

is enough to route toward a finite-rank free-by-virtually-cyclic structure.
But the active obstruction is now clear: the project needs either

- a concrete source-ready finitely presented normal kernel; or
- direct verification of a broader BNS/Bieri/Bieri--Renz finite-generation or
  finite-presentation criterion.

No residual bucket is removed by `FJ40`.

### Cycle consequence

`FJ40` is the twentieth module of cycle 002. The next procedural step is not
`FJ41`. The next step is a cycle-002 reflection artifact that should summarize
what `FJ21`--`FJ40` established, what remains open in `T-001`, and whether the
next cycle should continue `RB-004`, switch to direct BNS verification, or
return to the deferred additive-category module `FJ02`.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, no new non-Brown
source-ready finitely presented-kernel test case for `RB-004` is selected.

**Proof.** The candidate audit above exhausts the finitely presented kernels
already recorded by the active `RB-004` ledgers. The commutator calibration,
\(G_{2,3}\), and the \(G_{p,q}\)-family are already routed or non-residual.
The beyond-Brown residual does not yet contain a concrete normal subgroup
whose finite presentation has been proved internally or verified from a
source. Therefore selecting a new test case would import an unverified
finite-presentation hypothesis, which is forbidden by the project rules.

**Remark.** This is a project-selection proposition, not a mathematical
nonexistence theorem and not an `ER-*` result.

## Proof or verification

Verification completed:

1. Checked the active kernel-recognition ledger for all currently recorded
   finite-rank free-kernel cases.
2. Checked the residual ledger for the post-\(G_{p,q}\) status of `RB-004`.
3. Checked `FJ39` for the exact Karrass--Solitar input hypothesis.
4. Distinguished already-routed finitely presented kernels from new
   beyond-Brown candidates.
5. Recorded that no new candidate is source-ready inside the current
   repository state.

## References

- Brown, K. S. (1987). Trees, valuations, and the Bieri--Neumann--Strebel
  invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222.
  https://doi.org/10.1090/S0002-9939-1978-0466323-3

Internal references:

- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ33_worked_brown_test_g23.md`
- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`
- `modules/cycle_002/FJ37_post_gpq_residual_audit.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ30`;
- `FJ33`;
- `FJ36`;
- `FJ37`;
- `FJ39`;
- `OQ-056`;
- `OQ-059`;
- `OQ-060`;
- Brown (1987), through the already checked Brown modules;
- Karrass--Solitar (1978), through `FJ39`.

## Results produced

This module produced:

- a negative selection result for `OQ-056` in the current repository state;
- a negative source-readiness result for `OQ-059` in the current repository
  state;
- a warning that the Karrass--Solitar bridge is a cleanup theorem, not an
  example generator;
- no new `ER-*` result;
- no residual subtraction;
- the procedural handoff to the cycle-002 reflection.

## Open questions generated

- Should the next cycle first verify a direct BNS/Bieri theorem, or first
  write a finite-index handling module for the Karrass--Solitar
  infinite-dihedral alternative?
- Should the deferred additive-category module `FJ02` interrupt the next
  cycle before more source-level theorem use is attempted?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ40` and the cycle-002 reflection
  handoff;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for `OQ-056`, `OQ-059`, and next procedural target;
- `OPEN_QUESTIONS.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` only if source statuses
  need to record `FJ40`.
