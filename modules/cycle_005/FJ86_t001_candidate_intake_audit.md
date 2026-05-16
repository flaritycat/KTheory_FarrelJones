# Module FJ86. T-001 Candidate Intake Audit for G_BS23

## Status

Completed

## Module type

Candidate-intake audit / Payload-instantiated module / Obstruction record

## Problem

After `FJ85`, no mathematical `FJ86` was selected. The project required a
new accepted payload naming an exact object, changed repository objects,
success criterion, failure criterion, and stop condition.

Accepted payload `PAY-T001-CAND-BS23-2026-001` supplies a concrete
Baumslag--Solitar-type one-relator candidate
\[
G_{BS23}=\langle a,t\mid t a^2 t^{-1}a^{-3}\rangle.
\]

FJ86 must decide whether this object is candidate-admissible for `T-001`,
already routed, blocked by missing data, or useful only as an obstruction
record.

## Input

- `FJ85`;
- `OQ-107`;
- `OBL-C5-006`;
- `OBL-T001-013`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/theorem_dependencies.md`;
- accepted payload `PAY-T001-CAND-BS23-2026-001`.

## Output target

FJ86 should:

- record the accepted payload as the exit object for `OQ-107` and
  `OBL-C5-006`;
- add or classify the concrete candidate row for \(G_{BS23}\);
- check only first-pass candidate-admissibility data;
- avoid a general Baumslag--Solitar or one-relator survey;
- make no full Farrell--Jones, coefficient FJC, `FJCw`, `FICwF`, or residual
  subtraction claim;
- stop after ledger updates.

## Definitions

**Definition.** In this module,
\[
G_{BS23}=\langle a,t\mid t a^2 t^{-1}a^{-3}\rangle
\]
is the concrete payload candidate.

**Definition.** A *candidate-intake audit* records whether a proposed
candidate has enough data to become an active proof object. It is not a
proof attempt and is not a residual subtraction.

**Warning.** A Baumslag--Solitar-type presentation is not a Farrell--Jones
route by itself. It must still pass through a recorded route output such as
hyperbolicity, finite-dimensional CAT(0), virtual solvability,
finite-rank-free or hyperbolic kernel extension, version-safe inheritance,
or an exact weaker payload.

## Main work

### Accepted payload

| Field | FJ86 record |
| --- | --- |
| Payload ID | `PAY-T001-CAND-BS23-2026-001` |
| Payload type | `PAY-T001-CAND` |
| Target gates | `OQ-107`, `OBL-C5-006`, and `OBL-T001-013` |
| Object | Candidate-intake audit for \(G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle\). |
| Repository objects changed | `ledgers/payload_intake_protocol.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; `README.md`; `PROJECT_CHARTER.md`; plus `NOTATION_LEDGER.md` and `ledgers/open_group_classes.md` for project-index consistency. |
| Stop condition | Stop after the candidate-admissibility audit and ledger update. Do not start a general Baumslag--Solitar or one-relator survey. |

### Candidate audit table

| Field | FJ86 audit status |
| --- | --- |
| Candidate ID | `CAND-T001-004` |
| Presentation | \(G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle\) |
| One-relator status | Yes, by presentation. |
| Relator proper-power status | First-pass internal check: no. The cyclically reduced relator has length \(7\); a proper power of a cyclically reduced word would have root length dividing \(7\), and the length-one possibility is incompatible with the letters appearing in the relator. |
| Torsion-free status | Not source-verified in FJ86. The row is blocked for proof use until a checked source or internal module verifies the torsion-free/HNN status. |
| Epimorphism to \(\mathbb Z\) | Yes: \(\chi(t)=1\), \(\chi(a)=0\). The relator has zero total \(\chi\)-value. |
| Kernel-control status | Unknown / uncontrolled. No finite-rank free, countable free, or hyperbolic kernel bridge is recorded. |
| Hyperbolicity route | Unknown from current project records. |
| CAT(0) / special route | Unknown from current project records. |
| Virtually solvable route | Unknown from current project records. |
| Finite-index / `FJCw` route | No finite-index or `FJCw` bridge is recorded. |
| FJ83 weaker \(K_0\) / Cohen--Lyndon route | Not eligible from current data. No Cohen--Lyndon group-pair, normalizer, finite cohomological dimension, or coherent group-ring package is recorded for this row. |
| Prior-art risk | High / unchecked. Baumslag--Solitar-type groups have substantial prior literature, but no exact prior-art blocker or route source is checked in this module. |
| FJ86 decision | Add as a concrete blocked intake row, not as an active proof-success row. |

### Route status

The candidate has a useful `RB-004` / `RB-008` shape: it has an epimorphism
to \(\mathbb Z\), but its kernel is not controlled in the repository. This
is exactly the kind of object the project requested before continuing
candidate-level work.

However, FJ86 does not verify the torsion-free status, does not compute BNS
or Brown data, does not prove a kernel theorem, and does not identify an
approved Farrell--Jones route. Therefore the candidate is not removed from
the residual.

### New proof obligation

**Obligation OBL-T001-016.** The row `CAND-T001-004` cannot be promoted to a
route result or residual subtraction until a later accepted payload supplies
at least one of:

- a source-checked torsion-free / HNN verification sufficient for `T-001`;
- a Brown/BNS/kernel-control computation;
- a source-checked hyperbolic, CAT(0), virtually solvable, finite-index, or
  inheritance bridge;
- a prior-art blocker showing that the candidate is already covered or not
  useful.

Stop condition: do not treat \(G_{BS23}\) as a solved Farrell--Jones case or
as a residual subtraction from this audit alone.

### Next gate

FJ86 completes `OBL-C5-006` for the accepted payload
`PAY-T001-CAND-BS23-2026-001`. It records the next cycle gate:

**Obligation OBL-C5-007.** No `FJ87` module may be created until a new
accepted payload is recorded under `ledgers/payload_intake_protocol.md` or in
an equivalent target ledger row.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The payload `PAY-T001-CAND-BS23-2026-001` is sufficient to
instantiate FJ86 as a candidate-intake audit, but it is not sufficient to
promote \(G_{BS23}\) to a route result or residual subtraction.

This is a project-ledger proposition, not a mathematical Farrell--Jones
theorem.

## Proof or verification

The payload names a concrete one-relator presentation, target gates, changed
repository objects, success criterion, failure criterion, and stop condition.
It therefore satisfies the payload protocol at the level needed to instantiate
FJ86.

The audit then checks the candidate-intake fields. The presentation is
concrete. The relator is not a proper power by the elementary length check
recorded above. The map \(\chi(t)=1\), \(\chi(a)=0\) gives an epimorphism to
\(\mathbb Z\).

The remaining route data are absent from the repository. FJ86 does not check
an external torsion theorem, Bass--Serre normal-form theorem, Brown/BNS
criterion, hyperbolicity theorem, CAT(0) bridge, virtual-solvability source,
finite-index formulation bridge, or prior-art comparison for this candidate.
Thus the correct project action is to record a concrete blocked intake row
and a next proof obligation, not to make a theorem claim.

## References

No new external source was checked in FJ86.

Internal references:

- `FJ23`;
- `FJ24`;
- `FJ25`;
- `FJ26`;
- `FJ27`;
- `FJ61`;
- `FJ82`;
- `FJ85`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Dependencies

This module depends on:

- `FJ85`;
- `OQ-107`;
- `OBL-C5-006`;
- `OBL-T001-013`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND-BS23-2026-001`;
- first-pass resolution of `OQ-107`;
- completion of `OBL-C5-006` for FJ86;
- candidate intake row `CAND-T001-004`;
- proof obligation `OBL-T001-016`;
- proof obligation `OBL-C5-007`;
- no new `ER-*` result;
- no residual subtraction.

## Open questions generated

- `OQ-108`: Which accepted payload, if any, should instantiate `FJ87` after
  the FJ86 \(G_{BS23}\) candidate-intake audit?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `NOTATION_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/theorem_dependencies.md`.
