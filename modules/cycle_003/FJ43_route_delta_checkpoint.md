# Module FJ43. Route-Delta Checkpoint for the Normal-Subgroup Source Cluster

## Status

Completed

## Module type

Attack surface / Reflection / Theorem map

## Problem

`FJ38` selected the BNS/Bieri--Renz/Bieri/Karrass--Solitar source cluster for
`RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\). The
strategic audit after cycle 002 requires a decision checkpoint after this
kind of source work, because source verification without route movement can
start imitating progress.

The problem is to decide whether the current source cluster should continue
immediately, pause, or pivot after `FJ39`--`FJ42`.

## Input

- `reflections/strategic_audit_after_cycle_002.md`;
- `FJ39`, Karrass--Solitar finitely presented normal-subgroup bridge;
- `FJ40`, finitely presented-kernel candidate audit;
- `FJ41`, direct BNS finite-generation theorem verification;
- `FJ42`, Bieri source-access and route-delta check;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `OQ-064`.

## Output target

Record a route decision for `RB-004`:

- continue the current source cluster;
- pause the current source cluster and select another attack packet;
- or pivot to another residual bucket.

## Definitions

**Definition.** In this module, a `route-delta checkpoint` is a module whose
main output is a decision about whether previous source work has changed the
active attack surface enough to justify continuing.

**Definition.** A `source-only continuation` is another source-verification
module whose input is not tied to a concrete candidate, a missing hypothesis
for a selected bridge, or a named residual subtraction.

**Definition.** A `candidate-ready` route is a route for which the repository
has a specific group or family, the relevant hypotheses to check, and a clear
stop condition.

## Main work

### Source-cluster ledger

| Source-cluster item | Verified route gain | Missing input | Checkpoint decision |
|---|---|---|---|
| Brown route | Computable two-generator one-relator criterion already used in `FJ30`--`FJ36` | no beyond-Brown expansion recorded | do not repeat Brown computations without a new attack packet |
| Karrass--Solitar bridge | Source-verified in `FJ39` for nontrivial finitely presented normal subgroups of infinite index | no new source-ready finitely presented kernel by `FJ40` | keep as cleanup bridge; do not make it the next module by itself |
| Direct BNS theorem | Source-verified in `FJ41` for finite generation through \(S(G,N)\subseteq\Sigma(G)\) | no \(\Sigma(G)\)-membership computation for a new family | keep as active theorem map; do not continue without a candidate or computation source |
| Bieri (1976) | Metadata/source-access checked in `FJ42`; primary theorem text not source-verified | theorem text and exact hypotheses remain unavailable | do not use as theorem input |
| Bieri--Renz (1988) | Metadata/secondary-context role recorded in `FJ38` and `FJ39` | no concrete \(\mathrm{FP}_2\), finite-presentation, or higher-finiteness need attached to a candidate | do not verify next as an automatic source-only continuation |

### Route-delta table

| Question | Required answer |
|---|---|
| What theorem was checked? | No new theorem is checked in `FJ43`; it audits theorem-use status from `FJ39`--`FJ42`. |
| What route does it affect? | `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\). |
| What does it enable? | A governance decision: pause the automatic source-cluster sequence and require a candidate-ready route before further Bieri--Renz/BNS verification. |
| What does it not enable? | No Farrell--Jones route subtraction, no Bieri theorem use, no Bieri--Renz theorem use, and no new finite-rank free-kernel bridge. |
| What is the next decision? | Compare residual buckets and select an attack packet or no-candidate artifact in `FJ44`. |

### Decision

**Route decision.** The current BNS/Bieri--Renz/Bieri/Karrass--Solitar
source cluster should pause as an automatic source-reading sequence.

This is not an abandonment of `RB-004`. The Brown route, the direct BNS
theorem map, and the Karrass--Solitar cleanup bridge remain available.
However, the repository currently lacks:

- a new beyond-Brown one-relator candidate;
- a source-ready finitely presented normal kernel outside already removed
  examples;
- a BNS-invariant computation for a new family;
- a direct Bieri theorem-use row;
- a candidate-specific need for Bieri--Renz.

Therefore the next module should not be another abstract source check inside
the same cluster. It should compare the remaining residual buckets and select
either a concrete attack packet or a documented no-candidate/pivot artifact.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ43` produces no new `T-001` residual subtraction.

**Proposition.** `FJ43` first-pass resolves `OQ-064` by pausing automatic
continuation of the current source cluster until a candidate-ready route is
identified.

## Proof or verification

The first proposition follows from the ledger audit. `FJ43` checks no new
external theorem and verifies no new group-specific bridge into the known
Farrell--Jones classes already recorded in `FJ23`--`FJ27`.

The second proposition is a project-governance conclusion from the strategic
audit rule that source modules must produce route delta. The source cluster
has produced useful boundaries:

- `FJ39` supplies a verified finitely presented normal-subgroup cleanup
  theorem, but not a candidate generator;
- `FJ40` finds no new source-ready finitely presented-kernel example in the
  repository;
- `FJ41` verifies direct BNS finite-generation theorem use, but no
  \(\Sigma(G)\)-membership computation;
- `FJ42` keeps Bieri (1976) outside source-verified theorem use and records
  finite-presentation/type-\(VFP\) bottlenecks from comparison sources.

Those outputs sharpen the boundary of `RB-004`, but they do not justify a
fourth consecutive source-only continuation. The project should now force an
attack-packet decision.

## References

No new external source was checked in this module. The following external
sources are inherited through `FJ39`--`FJ42` and the project bibliography:

- Bieri, R. (1976). Normal subgroups in duality groups and in groups of
  cohomological dimension 2. *Journal of Pure and Applied Algebra, 7*(1),
  35--51. https://doi.org/10.1016/0022-4049(76)90065-7
- Bieri, R., Neumann, W. D., & Strebel, R. (1987). A geometric invariant of
  discrete groups. *Inventiones Mathematicae, 90*, 451--478.
  https://doi.org/10.1007/BF01389175
- Bieri, R., & Renz, B. (1988). Valuations on free resolutions and higher
  geometric invariants of groups. *Commentarii Mathematici Helvetici, 63*(3),
  464--497. https://doi.org/10.1007/BF02566775
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222. https://doi.org/10.1090/S0002-9939-1978-0466323-3

Internal references:

- `reflections/strategic_audit_after_cycle_002.md`
- `modules/cycle_003/FJ41_direct_bns_theorem_verification.md`
- `modules/cycle_003/FJ42_bieri_source_access_route_delta.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ39`;
- `FJ40`;
- `FJ41`;
- `FJ42`;
- `OQ-064`;
- `reflections/strategic_audit_after_cycle_002.md`.

## Results produced

This module produced:

- no established result number;
- a route decision pausing automatic source-cluster continuation for `RB-004`;
- a requirement that later Bieri--Renz/BNS work be attached to a concrete
  candidate, missing bridge, or named residual subtraction;
- a new next target: `FJ44`, residual-bucket comparison and attack-packet
  selection.

## Open questions generated

- `OQ-065`: Which residual bucket or attack packet should replace the paused
  automatic `RB-004` source-cluster continuation?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for the new current target;
- `SCOPE_LEDGER.md` for the `OQ-064` decision and `OQ-065`;
- `OPEN_QUESTIONS.md` for `OQ-064` and `OQ-065`;
- `ledgers/t001_residual.md` and `ledgers/t001_kernel_recognition.md` for the
  route pause;
- `ledgers/theorem_dependencies.md` for `FJ43` and `FJ44`.
