# Module FJ84. K0 Cohen--Lyndon Candidate Hypothesis Audit

## Status

Completed

## Module type

Candidate/family hypothesis audit / Weaker K0 consequence / Payload-instantiated module

## Problem

`FJ83` verifies Jaikin-Zapirain--Linton--Sanchez-Peralta (2025) as a weaker
\(K_0\) / Cohen--Lyndon source payload, but it does not apply the source to a
specific `T-001` candidate or family.

Accepted payload `PAY-T001-K0-CL-HYP-2026-001` asks FJ84 to test whether any
currently recorded `T-001` candidate or family satisfies the FJ83 source
hypotheses, or to record that no current row is eligible.

## Input

- `modules/cycle_005/FJ83_k0_cohen_lyndon_payload_verification.md`
- `ledgers/payload_intake_protocol.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `OPEN_QUESTIONS.md`, especially `OQ-105`
- `ledgers/theorem_dependencies.md`
- `OBL-C5-004`
- `OBL-T001-014`
- accepted payload `PAY-T001-K0-CL-HYP-2026-001`

## Output target

FJ84 should:

- record the accepted payload as the exit object for `OQ-105` and
  `OBL-C5-004`;
- audit only currently recorded `T-001` candidate/family rows;
- decide whether any current row satisfies the FJ83 source hypotheses;
- update candidate and residual ledgers without creating a residual
  subtraction;
- stop after the candidate/family hypothesis audit.

## Definitions

**Definition.** A row is *FJ83-eligible* if the repository currently records
enough data to match the FJ83 weaker \(K_0\) / Cohen--Lyndon source
hypotheses for that row.

For this audit, the minimum FJ83-eligibility data are:

- a concrete candidate or family row;
- torsion-free status;
- regular-ring formulation level;
- an exact Cohen--Lyndon presentation or group pair;
- an identified group-pair quotient matching the candidate/family;
- the stabilizer-equals-normalizer condition, or the relevant normalizer
  quotient data from the technical theorem;
- finite cohomological dimension hypotheses at the required level;
- coherent group-ring hypotheses;
- formulation-safety note excluding coefficient FJC, full \(\mathcal{FJ}\),
  `FJCw`, and `FICwF`;
- prior-art / route-overlap status.

**Warning.** FJ83-eligibility is a project-use threshold, not a claim that
the source theorem is false for a row whose data are missing. Missing data in
this audit means "not currently usable from repository records."

## Main work

### Accepted payload

| Field | FJ84 record |
| --- | --- |
| Payload ID | `PAY-T001-K0-CL-HYP-2026-001` |
| Payload type | `PAY-T001-BRIDGE` |
| Target gates | `OQ-105`, `OBL-C5-004`, `OBL-T001-014` |
| Object | Use the FJ83 source payload to run a candidate/family-level hypothesis audit. |
| Repository objects changed | `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; plus protocol, source-status, bibliography, and handoff ledgers needed for consistency. |
| Stop condition | Stop after the candidate/family hypothesis audit; do not claim full Farrell--Jones, coefficient FJC, `FJCw`, `FICwF`, or a residual subtraction. |

### Candidate/family audit table

| Row | Current repository status | FJ83 hypothesis data present? | FJ84 decision |
| --- | --- | --- | --- |
| `CAND-T001-001` | Calibration example from `FJ31`; already non-residual through virtually solvable overlap. | Not enough for FJ83 use. The row does not record an exact Cohen--Lyndon group pair, stabilizer/normalizer data, finite cohomological dimension data for the source theorem, or coherent group-ring hypotheses. | Not FJ83-eligible. Keep as calibration only. |
| `CAND-T001-002` | \(G_{2,3}\) row; already removed through the `FJ26` finite-rank free-by-cyclic route. | Not enough for FJ83 use. The row records Brown/free-kernel route data, not the FJ83 Cohen--Lyndon group-pair, normalizer, cohomological-dimension, and coherent group-ring package. | Not FJ83-eligible. Keep as already routed. |
| `CAND-T001-003` | \(G_{p,q}\)-family row; already removed through the `FJ26` finite-rank free-by-cyclic route. | Not enough for FJ83 use. The row records Brown/Bass--Serre/free-kernel route data, not the FJ83 Cohen--Lyndon group-pair, normalizer, cohomological-dimension, and coherent group-ring package. | Not FJ83-eligible. Keep as already routed. |
| `TPL-RB003-004-008` | Template placeholder only. | No. The row has no concrete group or family data. | Not a mathematical candidate. |

### Audit result

No currently recorded `T-001` candidate or family is FJ83-eligible.

This is a successful candidate/family-level audit because the current rows
were checked against the FJ83 hypothesis list. The obstruction is not lack of
source text; it is lack of row-level hypothesis data in the existing
candidate inventory.

## Proposition / Theorem / Conjecture / Example

**Proposition.** No currently recorded `T-001` candidate/family row is
eligible for project use of the FJ83 weaker \(K_0\) / Cohen--Lyndon payload.

This is a project-ledger proposition. It is not a mathematical theorem about
the groups themselves and does not assert that the source theorem fails for
any listed row.

## Proof or verification

The only current concrete `T-001` rows are `CAND-T001-001`,
`CAND-T001-002`, and `CAND-T001-003`. The candidate inventory records them as
calibration or already-routed rows. The template row is explicitly not a
mathematical candidate.

FJ83 records that future source use needs exact Cohen--Lyndon presentation or
group-pair data, normalizer data, finite cohomological dimension data,
coherent group-ring hypotheses, formulation safety, and prior-art overlap
control. None of the current rows records that package. Therefore none is
eligible for FJ83-based promotion from current repository data.

The audit stops here. It does not start a new one-relator survey and does
not import a new theorem.

## References

No new external source was checked in FJ84. The audit uses the source
statement already verified in `FJ83`:

Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs,
coherence and Farrell-Jones Conjecture for K0* (arXiv:2510.23518v2). arXiv.
https://arxiv.org/abs/2510.23518. https://doi.org/10.48550/arXiv.2510.23518.

## Dependencies

This module depends on:

- `FJ83`;
- `OQ-105`;
- `OBL-C5-004`;
- `OBL-T001-014`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-K0-CL-HYP-2026-001`;
- first-pass resolution of `OQ-105`;
- completion of `OBL-C5-004` for FJ84;
- completion of `OBL-T001-014` for the current candidate inventory only;
- new proof obligation `OBL-T001-015`: future FJ83-payload use requires a
  new or amended candidate row recording the full FJ83 hypothesis package;
- new proof obligation `OBL-C5-005`: no `FJ85` may be created without a new
  accepted payload.

No established mathematical result was produced.

## Open questions generated

- `OQ-106`: Which accepted payload, if any, should instantiate `FJ85` after
  the FJ84 no-eligible-current-candidate audit?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `BIBLIOGRAPHY.md`;
- `AGENTS.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/source_status.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
