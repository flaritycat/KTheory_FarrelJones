# Module FJ56. Kernel-Control Candidate Inventory

## Status

Completed

## Module type

Candidate inventory / Attack surface / Obstruction record

## Problem

`FJ55` recorded that hierarchy / primitive-extension data is not a direct
Farrell--Jones route in the current repository. The selected `RB-003` +
`RB-004`/`RB-008` hybrid packet must therefore become candidate-level:
identify which repository-supported candidate rows have epimorphisms to
\(\mathbb Z\), recorded kernel type, and a route-compatible extension
theorem candidate.

This module must not fabricate a new one-relator family. Its task is to
audit the candidate rows already present in `ledgers/t001_candidate_inventory.md`
and decide whether any row remains active for a proof attempt.

## Input

- `FJ30`, Brown/BNS kernel-recognition verification;
- `FJ31`, Brown calibration example;
- `FJ33`, worked Brown test for \(G_{2,3}\);
- `FJ36`, Bass--Serre bridge for the \(G_{p,q}\)-family;
- `FJ41`, direct BNS theorem verification;
- `FJ54`, residual-bucket checkpoint after `RB-006`;
- `FJ55`, hierarchy-to-FJ bridge test;
- `OQ-077`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`.

## Output target

A kernel-control inventory decision:

- attach explicit kernel-control status to all repository-supported candidate
  rows;
- separate route-ready rows from already-routed rows;
- identify whether a live non-routed candidate exists for `FJ57`;
- record a proof obligation if no such candidate is present.

## Definitions

**Definition.** Kernel-control data for a candidate row means the recorded
status of:

- an epimorphism \(\chi\colon G\to\mathbb Z\), if present;
- Brown/BNS data for \([\chi]\) and \([-\chi]\), if applicable;
- the kernel type, such as finite-rank free, hyperbolic, countable free, or
  unknown;
- the extension theorem candidate, such as the `FJ26` finite-rank
  free-by-cyclic route;
- formulation safety for coefficient FJ, full \(\mathcal{FJ}\), `FJCw`, or
  finite-index use.

**Definition.** A route-exhausted candidate row is a row whose kernel-control
data already places it in a recorded route, or whose role is only calibration.
Such a row may remain useful as a test example, but it is not an active
residual subtraction target.

**Definition.** A live kernel-control candidate is a repository-supported
candidate row whose route output is named but not yet proved, blocked, or
already exhausted.

**Warning.** A BNS finite-generation theorem is not a kernel computation.
`FJ41` makes direct BNS theorem use available, but a candidate still needs
\(\Sigma(G)\)-membership data and a freeness, hyperbolicity, or inheritance
bridge before any Farrell--Jones route can be invoked.

## Main work

### Candidate kernel-control audit

| Candidate ID | Kernel-control data now recorded | Route-output decision | Active for `FJ57`? |
|---|---|---|---|
| `CAND-T001-001` | The commutator calibration example has an epimorphism \(\chi(x)=1,\chi(y)=0\). `FJ31` records the Brown-positive check and \(\ker(\chi)\cong F_1\). | It has an `FJ26` finite-rank free-by-cyclic output, but this is redundant because the example is already covered by the virtually solvable route. | No. Calibration only. Stop if proposed as novelty. |
| `CAND-T001-002` | \(G_{2,3}\) has \(\chi(x)=3,\chi(y)=2\). `FJ33` records the Brown-positive check, \(\ker(\chi)\cong F_2\), and \(G_{2,3}\cong F_2\rtimes\mathbb Z\). | It is already removed through the `FJ26` finite-rank free-by-cyclic route. | No. Already routed. |
| `CAND-T001-003` | \(G_{p,q}\) has \(\chi_{p,q}(x)=q,\chi_{p,q}(y)=p\). `FJ34` records Brown-positive finite generation, and `FJ36` records Bass--Serre freeness, so \(K_{p,q}\cong F_n\) for finite \(n\). | It is already removed through the `FJ26` finite-rank free-by-cyclic route. Exact rank is not needed for route use. | No. Already routed as a family. |
| `TPL-RB003-004-008` | No presentation, epimorphism, BNS data, kernel type, or route output is recorded. | Not a mathematical candidate. | No. Placeholder only. |

### BNS-only lane check

`FJ41` verifies the original BNS finite-generation theorem for normal
subgroups with abelian quotient. For the current inventory, this gives no new
live candidate:

- the concrete Brown rows already have stronger kernel-control data;
- no row records a new \(\Sigma(G)\)-membership computation;
- no row records a finitely generated but not yet free kernel needing a
  Bass--Serre, Karrass--Solitar, or inheritance bridge.

Thus direct BNS theorem use remains available, but inactive until a future
candidate row supplies computable BNS data outside the already exhausted Brown
examples.

### RB-008 extension-lane check

No current row has a countable-free kernel, a hyperbolic kernel without a
mapping-torus bridge, or another extension shape needing version-sensitive
inheritance. Therefore `RB-008` remains a live residual bucket, but it has no
candidate-ready row in the present inventory.

### Obstruction record

**Obstruction OBL-T001-003.** After `FJ56`, the repository has no live
kernel-control candidate for the selected `RB-003` + `RB-004`/`RB-008`
hybrid packet.

The only concrete candidate rows with kernel-control data are either
calibration-only or already removed by the `FJ26` finite-rank
free-by-cyclic route. The only remaining row is a template placeholder, not a
candidate.

### FJ57 handoff

`FJ57` should not repeat the kernel-control inventory. It should do one of
two things:

1. promote a repository-supported, non-routed candidate or candidate family
   into the inventory and attempt its route bridge; or
2. record the no-candidate obstruction precisely, including which missing
   input prevents the `RB-003` + `RB-004`/`RB-008` hybrid packet from
   advancing.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, every concrete candidate
row with explicit kernel-control data is route-exhausted.

**Proof.** `CAND-T001-001` is the commutator calibration example from
`FJ31`; its kernel is \(F_1\), but the row is already covered by the
virtually solvable route and is not residual. `CAND-T001-002` is the
\(G_{2,3}\) example from `FJ33`; it is \(F_2\rtimes\mathbb Z\) and is
already routed by `FJ26`. `CAND-T001-003` is the \(G_{p,q}\)-family from
`FJ36`; it is \(F_n\rtimes\mathbb Z\) for finite \(n\) and is already routed
by `FJ26`. The remaining template row has no presentation or kernel data.
Therefore no current concrete row remains live for a new kernel-control
subtraction.

**Route decision.** `FJ56` resolves `OQ-077` at first pass and sends the
project to `FJ57`, Candidate Family Proof Attempt or Obstruction Record.

**Warning.** This module does not prove a new Farrell--Jones case and does
not claim that `T-001` is solved.

## Proof or verification

Verification was internal to the repository:

1. `FJ30` was used for the Brown/BNS kernel-recognition theorem map.
2. `FJ31`, `FJ33`, and `FJ36` were used for the existing candidate rows.
3. `FJ41` was used to check whether direct BNS theorem use creates an
   additional live lane.
4. `FJ54` and `FJ55` were used for the hybrid-packet stop conditions.
5. No new external source was checked.

## References

No new external source was checked in this module.

Existing APA-style sources used through prior repository verification:

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell-Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904. https://doi.org/10.1093/imrn/rnac012
- Bieri, R., Neumann, W. D., & Strebel, R. (1987). A geometric invariant of
  discrete groups. *Inventiones Mathematicae, 90*, 451--478.
  https://doi.org/10.1007/BF01389175
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Serre, J.-P. (1980). Trees and amalgams. In *Trees* (pp. 1--68). Springer.
  https://doi.org/10.1007/978-3-642-61856-7_1

Internal references:

- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ31_first_brown_test_case.md`
- `modules/cycle_002/FJ33_worked_brown_test_g23.md`
- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`
- `modules/cycle_003/FJ41_direct_bns_theorem_verification.md`
- `modules/cycle_003/FJ54_residual_bucket_checkpoint_after_rb006.md`
- `modules/cycle_003/FJ55_primitive_extension_hierarchy_to_fj_bridge_test.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ30`;
- `FJ31`;
- `FJ33`;
- `FJ36`;
- `FJ41`;
- `FJ54`;
- `FJ55`;
- `OQ-077`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-077`;
- explicit kernel-control audit status for all repository-supported
  candidate rows;
- `OBL-T001-003`, the no-live-kernel-control-candidate obstruction;
- a decision to continue with `FJ57`, Candidate Family Proof Attempt or
  Obstruction Record;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-078`: Can `FJ57` promote a repository-supported, non-routed candidate
  family into the inventory, or should it record the no-candidate obstruction
  as the current endpoint of the hybrid packet?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ56` and next `FJ57`;
- `SCOPE_LEDGER.md` for the `OQ-077` resolution and new `OQ-078`;
- `OPEN_QUESTIONS.md` for `OQ-077` and `OQ-078`;
- `NOTATION_LEDGER.md` for kernel-control and `OBL-T001-003`;
- `ledgers/t001_candidate_inventory.md` for the kernel-control audit;
- `ledgers/t001_kernel_recognition.md`, `ledgers/t001_residual.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ56` source-use
  notes;
- `references/papers_to_read.md` for the next task.
