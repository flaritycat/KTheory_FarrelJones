# Module FJ119. CAND-T001-C6-019 Candidate Intake

## Status

Completed candidate-intake audit.

## Ledger type

Numbered module / T-001 candidate intake / payload-gated cycle-006 callback.

## Problem

The callback queue row `PAY-T001-CAND-C6-019-2026-001` is the first row in
`ledgers/payload_execution_queue.md` marked `Ready for intake` after `FJ118`.
It supplies a concrete two-generator one-relator candidate and asks for a
bounded intake audit only.

This module consumes exactly that row. It does not act on earlier
`CAND-T001-C6-*` rows, does not compute Brown/BNS data, and does not audit
broad prior art.

## Payload intake record

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND-C6-019-2026-001` |
| Date recorded | 2026-05-17 |
| Payload type | `PAY-T001-CAND` |
| Target gate | `OQ-126` / `OBL-C6-003`, plus `OBL-T001-013` as the `T-001` reactivation gate and `OBL-T001-015` as a weaker-\(K_0\) / Cohen--Lyndon caution if that source package is later considered. |
| Candidate, source, bridge, computation, or blocker | Candidate `CAND-T001-C6-019`, \(G_{C6,019}=\langle a,b\mid a b^{21} a^{-1} b^{-41} a b^{42} a^{-1} b^{-21}\rangle\), with \(\chi(a)=1,\chi(b)=0\). |
| Exact statement or object | Run a bounded candidate-intake audit: verify relator/proper-power status from the supplied word, use only repository-recorded source status for torsion-free status, record epimorphism availability, known-route overlap, prior-art risk, residual-bucket target, and next proof obligation. |
| APA citation if external source is used | Putman, A. (n.d.). *One-relator groups*. University of Notre Dame. https://www3.nd.edu/~andyp/notes/OneRelator.pdf. |
| Source-status label | Internal candidate-generation payload. Torsion-free status uses only the existing repository row: Putman's notes are an active reference for `FJ91` and `FJ101`--`FJ119`; first-pass theorem text checked for the non-proper-power torsion-free corollary. No browsing and no new source check. |
| Hypotheses and formulation level | Torsion-free one-relator candidate-intake level only. No full Farrell--Jones, coefficient FJC, full `\mathcal{FJ}`, `FJCw`, `FICwF`, weaker \(K_0\), theorem promotion, prior-art claim, or residual subtraction is asserted. |
| Repository object changed | `ledgers/payload_intake_protocol.md`; `ledgers/payload_execution_queue.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `NOTATION_LEDGER.md`; `ledgers/theorem_dependencies.md`; `BIBLIOGRAPHY.md`; `ledgers/source_status.md`; `README.md`; `PROJECT_CHARTER.md`; `SCOPE_LEDGER.md`; `modules/cycle_006/FJ119_cand_t001_c6_019_candidate_intake.md`. |
| Success criterion | The selected row is repository-visibly classified as candidate-admissible, already routed, blocked, calibration-only, or obstruction-only, with exact next proof obligation and no route promotion. |
| Failure criterion | Stop without promotion if the row becomes a placeholder, the relator/proper-power check fails or is unresolved, torsion-free source status cannot be supported from repository records, the row is already routed without new information, no route-output target exists, or the run drifts into a broad one-relator survey. |
| Stop condition | Stop after this single candidate-intake audit and ledger updates. Do not compute Brown/BNS data, do not audit broad prior art, do not claim Farrell--Jones, and do not execute the next queue row in the same run. |
| Accepted? | Yes, for `FJ119` candidate-intake audit only. |
| Follow-up module if accepted | `modules/cycle_006/FJ119_cand_t001_c6_019_candidate_intake.md` |

## Candidate presentation

Let
\[
G_{C6,019}
= \langle a,b\mid r\rangle,
\qquad
r=a b^{21} a^{-1} b^{-41} a b^{42} a^{-1} b^{-21}.
\]

The queued epimorphism candidate is
\[
\chi(a)=1,\qquad \chi(b)=0.
\]

## Internal exponent-sum check

**Computation.** The total exponent sums in the relator are:
\[
\sigma_a(r)=1-1+1-1=0,
\]
and
\[
\sigma_b(r)=21-41+42-21=1.
\]

Thus the abelianization vector of the relator is \((0,1)\).

**Remark.** If a nontrivial reduced relator were a proper power \(u^d\) with
\(d>1\), its exponent-sum vector would be divisible by \(d\). Since
\((0,1)\) is primitive, this gives a first-pass internal check that the
supplied relator is not a proper power.

## Epimorphism check

The character \(\chi\colon F(a,b)\to\mathbb Z\) with \(\chi(a)=1\) and
\(\chi(b)=0\) sends
\[
\chi(r)=1+0-1+0+1+0-1+0=0.
\]

Therefore \(\chi\) descends to a homomorphism
\[
\bar\chi\colon G_{C6,019}\to\mathbb Z.
\]

Since \(\bar\chi(a)=1\), the homomorphism is surjective.

## Torsion-free status

**Source-verified claim, inherited at first-pass level.** The repository
already records Putman's notes as the checked source used in `FJ91` for the
Karrass--Magnus--Solitar one-relator torsion theorem and the corollary that
\(\langle S\mid r\rangle\) is torsion-free when \(r\in F(S)\) is not a
proper power (Putman, n.d., Sec. 4).

Combining that existing source-status row with the internal non-proper-power
check above gives:

`CAND-T001-C6-019` is torsion-free at first-pass candidate-ledger level.

This is not a Farrell--Jones route, not a kernel-control theorem, not a
prior-art blocker, and not a residual subtraction.

## Known-route status

No known route is claimed in this module.

High-level comparison against recorded route classes:

| Route class | FJ119 status |
| --- | --- |
| Hyperbolic route | unresolved; no hyperbolicity bridge is recorded for this row |
| Finite-dimensional CAT(0) / special route | unresolved; no CAT(0), compact-special, or virtual-special bridge is recorded |
| Virtually solvable route | unresolved; no virtual-solvability bridge is recorded |
| Finite-index / `FJCw` route | unresolved; no finite-index package is recorded |
| Finite-rank free-by-cyclic / hyperbolic-by-cyclic route | unresolved; \(\chi\) is recorded but no kernel type is computed |
| Graph-of-abelian-groups route | unresolved; no graph-of-abelian-groups structure is recorded |
| Weaker \(K_0\) / Cohen--Lyndon lane | not applied; no Cohen--Lyndon or group-pair hypothesis package is recorded |

## Candidate classification

Classification: candidate-admissible at first-pass intake level, but
route-unresolved and not residual-subtractive.

Reason:

- the row supplies a concrete two-generator one-relator presentation;
- the relator is first-pass checked as not a proper power;
- the torsion-free status is supported at the same first-pass level as
  `FJ91` and `FJ101`--`FJ119` by the existing Putman source-status row;
- the epimorphism \(\bar\chi\colon G_{C6,019}\to\mathbb Z\) is recorded;
- no known route, prior-art blocker, kernel type, or formulation-safe
  Farrell--Jones bridge is recorded.

Residual-bucket target: `RB-004` / `RB-008` only as a kernel-control and
extension-inheritance uncertainty. No bucket is subtracted.

## Next proof obligation

`OBL-C6-022`: no later module may promote, route, or subtract
`CAND-T001-C6-019` unless a new accepted payload supplies one of:

- a bounded Brown/BNS or kernel-control computation for \(\bar\chi\);
- a source-verified known-route or prior-art blocker audit;
- a source-verified route bridge with exact formulation level;
- a formulation-comparison object tied to a named route;
- an explicit branch decision for the row.

## Formulation safety

This module claims none of the following:

- full Farrell--Jones for the candidate;
- coefficient K-theory FJC;
- full `\mathcal{FJ}`;
- `FJCw`;
- `FICwF`;
- weaker \(K_0\) consequence;
- finite-index inheritance;
- target theorem;
- residual subtraction.

## Stop condition

Stop after this candidate-intake audit and ledger updates. Do not compute
Brown/BNS data in `FJ119`. Do not execute queue row `020` in this run.

## References

Putman, A. (n.d.). *One-relator groups*. University of Notre Dame.
https://www3.nd.edu/~andyp/notes/OneRelator.pdf

## Dependencies

This module depends on:

- `ledgers/payload_execution_queue.md`;
- `ledgers/payload_intake_protocol.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `modules/cycle_006/FJ101_cand_t001_c6_001_candidate_intake.md`;
- `modules/cycle_006/FJ102_cand_t001_c6_002_candidate_intake.md`;
- `modules/cycle_006/FJ103_cand_t001_c6_003_candidate_intake.md`;
- `modules/cycle_006/FJ104_cand_t001_c6_004_candidate_intake.md`;
- `modules/cycle_006/FJ105_cand_t001_c6_005_candidate_intake.md`;
- `modules/cycle_006/FJ106_cand_t001_c6_006_candidate_intake.md`;
- `modules/cycle_006/FJ107_cand_t001_c6_007_candidate_intake.md`;
- `modules/cycle_006/FJ108_cand_t001_c6_008_candidate_intake.md`;
- `modules/cycle_006/FJ109_cand_t001_c6_009_candidate_intake.md`;
- `modules/cycle_006/FJ110_cand_t001_c6_010_candidate_intake.md`;
- `modules/cycle_006/FJ111_cand_t001_c6_011_candidate_intake.md`;
- `modules/cycle_006/FJ112_cand_t001_c6_012_candidate_intake.md`;
- `modules/cycle_006/FJ113_cand_t001_c6_013_candidate_intake.md`;
- `modules/cycle_006/FJ114_cand_t001_c6_014_candidate_intake.md`;
- `modules/cycle_006/FJ115_cand_t001_c6_015_candidate_intake.md`;
- `modules/cycle_006/FJ116_cand_t001_c6_016_candidate_intake.md`;
- `modules/cycle_006/FJ117_cand_t001_c6_017_candidate_intake.md`;
- `modules/cycle_006/FJ118_cand_t001_c6_018_candidate_intake.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- accepted intake of `PAY-T001-CAND-C6-019-2026-001` for `FJ119` only;
- candidate row `CAND-T001-C6-019`;
- first-pass non-proper-power check by exponent-sum vector \((0,1)\);
- first-pass torsion-free candidate status using the existing `FJ91` and
  `FJ101`--`FJ119` source status for Putman;
- epimorphism \(\bar\chi\colon G_{C6,019}\to\mathbb Z\);
- proof obligation `OBL-C6-022`.

No established result number is produced.

## Open questions generated

- `OQ-145`: Which accepted payload, if any, should act on
  `CAND-T001-C6-019` after the `FJ119` candidate-intake audit?

## Update to ledgers

After completion, update:

- `ledgers/payload_execution_queue.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `ledgers/theorem_dependencies.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`.
