# Module FJ90. T-001 Candidate Intake After No-Live-Candidate Blocker

## Status

Completed

## Module type

Candidate-intake audit / Payload-instantiated module / Obstruction record

## Problem

After `FJ89`, the repository recorded no-live-candidate blocker
`NLC-T001-001`: no current `T-001` candidate-inventory row was live and
non-routed.

Accepted payload `PAY-T001-CAND-FJ90-2026-001` supplies a new concrete
one-relator candidate:
\[
CAND\text{-}T001\text{-}005
=
G_{FJ90}
=
\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle.
\]

FJ90 must run only a bounded candidate-intake audit. It must decide whether
the row is candidate-admissible for `T-001`, already routed, blocked by
missing data, or useful only as an obstruction record. It must not start a
broad one-relator survey, create `FJ91`, or claim any Farrell--Jones theorem.

## Input

- `FJ61`;
- `FJ82`;
- `FJ89`;
- `OQ-111`;
- `OBL-C5-010`;
- `NLC-T001-001`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- accepted payload `PAY-T001-CAND-FJ90-2026-001`.

## Output target

FJ90 should:

- record the accepted FJ90 payload;
- add or classify `CAND-T001-005`;
- check first-pass relator status and obvious current-route overlap;
- record the torsion-free status only at the level justified by current
  repository data;
- record any blocker preventing active proof use;
- stop after ledger updates.

## Definitions

**Definition.** In this module,
\[
w=a b a^{-1} b^2 a b^{-3}
\]
is the relator of the candidate
\[
G_{FJ90}=\langle a,b\mid w\rangle.
\]

**Definition.** A candidate-intake audit records whether a proposed
candidate has enough data to become an active proof object. It is not a
proof attempt and is not a residual subtraction.

**Warning.** A one-relator presentation with an epimorphism to
\(\mathbb Z\) is not a Farrell--Jones route by itself. It must still pass
through a recorded route output such as hyperbolicity, finite-dimensional
CAT(0), virtual solvability, finite-rank-free or hyperbolic kernel
extension, version-safe inheritance, exact weaker payload, or a documented
obstruction.

## Main work

### Accepted payload

| Field | FJ90 record |
| --- | --- |
| Payload ID | `PAY-T001-CAND-FJ90-2026-001` |
| Payload type | `PAY-T001-CAND` |
| Target gates | `OQ-111`, `OBL-C5-010`, and `NLC-T001-001` |
| Object | Candidate-intake audit for \(G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle\). |
| Source status | No new external source checked; candidate object supplied by payload. |
| Repository objects changed | `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`; `ledgers/payload_intake_protocol.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; `README.md`; `PROJECT_CHARTER.md`; `SCOPE_LEDGER.md`; `NOTATION_LEDGER.md`. |
| Stop condition | Stop after the candidate-admissibility audit and ledger update. Do not start a broad one-relator survey. Do not create `FJ91`. |

### Relator status

The relator is
\[
w=a b a^{-1} b^2 a b^{-3}.
\]
It is cyclically reduced: the first letter is \(a\), while the last letter
is \(b^{-1}\), so no cyclic cancellation occurs.

The exponent-sum vector of \(w\) in the abelianization of the free group
\(\langle a,b\rangle\) is
\[
(\sigma_a(w),\sigma_b(w))=(1,0).
\]
If \(w=v^n\) in the free group for some \(n>1\), then the abelianization
vector of \(w\) would be \(n\) times the abelianization vector of \(v\).
Since the first coordinate of \((1,0)\) is not divisible by any \(n>1\),
this is impossible.

Thus FJ90 records a first-pass internal check that the relator is not a
proper power.

### Candidate audit table

| Field | FJ90 audit status |
| --- | --- |
| Candidate ID | `CAND-T001-005` |
| Presentation | \(G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle\) |
| One-relator status | Yes, by presentation. |
| Relator proper-power status | First-pass internal check: no, because the free-abelian exponent vector is \((1,0)\), which is not divisible by any \(n>1\). |
| Torsion-free status | Blocked / not source-verified in FJ90. The proper-power check points to the classical one-relator torsion theorem as a possible next source check, but this module does not verify that theorem for promotion. |
| Epimorphism to \(\mathbb Z\) | Yes: \(\chi(a)=0\), \(\chi(b)=1\). The relator has total \(\chi\)-value \(0\). |
| Kernel-control status | Unknown / uncontrolled. No finite-rank free, countable free, or hyperbolic kernel bridge is recorded. |
| Hyperbolicity route | Unknown from current project records. |
| CAT(0) / special route | Unknown from current project records. |
| Virtually solvable route | Unknown from current project records. |
| Finite-index / `FJCw` route | No finite-index or `FJCw` bridge is recorded. |
| FJ83 weaker \(K_0\) / Cohen--Lyndon route | Not eligible from current data. No Cohen--Lyndon group-pair, normalizer, finite cohomological dimension, or coherent group-ring package is recorded for this row. |
| Prior-art risk | Unknown / unchecked. No prior-art comparison is performed in FJ90. |
| FJ90 decision | Add as a concrete blocked intake row, not as an active proof-success row and not as a residual subtraction. |

### Route status

The candidate has a plausible `RB-004` / `RB-008` shape because it has an
epimorphism to \(\mathbb Z\), but its kernel is not controlled in the
repository. No current route through `FJ23`--`FJ27`, `ER-015`, or the FJ83
weaker \(K_0\) lane is recorded for this row.

However, FJ90 does not source-verify torsion-free status, compute Brown/BNS
data, prove a kernel theorem, or identify a prior-art blocker. Therefore the
row is a concrete blocked intake row, not a live residual proof target.

### New proof obligation

**Obligation OBL-T001-018.** The row `CAND-T001-005` cannot be promoted to a
live `T-001` proof target, route result, or residual subtraction until a
later accepted payload supplies at least one of:

- a source-checked torsion-free verification, such as an exact one-relator
  torsion theorem with hypotheses and formulation status;
- a Brown/BNS/kernel-control computation;
- a source-checked hyperbolic, CAT(0), virtually solvable, finite-index, or
  inheritance bridge;
- a prior-art blocker showing that the candidate is already covered or not
  useful.

Stop condition: do not treat \(G_{FJ90}\) as a solved Farrell--Jones case or
as a residual subtraction from this audit alone.

### Next gate

FJ90 completes `OBL-C5-010` for the accepted payload
`PAY-T001-CAND-FJ90-2026-001`. It records the next cycle gate:

**Obligation OBL-C5-011.** No `FJ91` module may be created until a new
accepted payload is recorded under `ledgers/payload_intake_protocol.md` or in
an equivalent target ledger row.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The payload `PAY-T001-CAND-FJ90-2026-001` is sufficient to
instantiate FJ90 as a candidate-intake audit, but it is not sufficient to
promote \(G_{FJ90}\) to a live `T-001` proof target, route result, or
residual subtraction.

This is a project-ledger proposition, not a mathematical Farrell--Jones
theorem.

## Proof or verification

The payload names a concrete one-relator presentation, target gates, changed
repository objects, success criterion, failure criterion, and stop condition.
It therefore satisfies the payload protocol at the level needed to instantiate
FJ90.

The audit then checks the candidate-intake fields. The presentation is
concrete. The relator is not a proper power by the abelianization obstruction
recorded above. The map \(\chi(a)=0\), \(\chi(b)=1\) gives an epimorphism to
\(\mathbb Z\).

The remaining target and route data are absent from the repository. FJ90 does
not source-check a one-relator torsion theorem, Brown/BNS criterion,
hyperbolicity theorem, CAT(0) bridge, virtual-solvability source,
finite-index formulation bridge, or prior-art comparison for this candidate.
Thus the correct project action is to record a concrete blocked intake row
and a next proof obligation, not to make a theorem claim.

## References

No external source was used in FJ90.

Internal references:

- `FJ23`;
- `FJ24`;
- `FJ25`;
- `FJ26`;
- `FJ27`;
- `FJ61`;
- `FJ82`;
- `FJ89`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Dependencies

This module depends on:

- `FJ61`;
- `FJ82`;
- `FJ89`;
- `OQ-111`;
- `OBL-C5-010`;
- `NLC-T001-001`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND-FJ90-2026-001`;
- first-pass resolution of `OQ-111`;
- completion of `OBL-C5-010` for FJ90;
- candidate intake row `CAND-T001-005`;
- proof obligation `OBL-T001-018`;
- proof obligation `OBL-C5-011`;
- no new `ER-*` result;
- no external source check;
- no residual subtraction.

## Open questions generated

- `OQ-112`: Which accepted payload, if any, should instantiate `FJ91` after
  the FJ90 candidate-intake audit for `CAND-T001-005`?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/theorem_dependencies.md`.
