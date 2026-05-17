# Module FJ94. CAND-T001-005 K0 Cohen--Lyndon Hypothesis Audit

## Status

Completed

## Module type

Candidate/family hypothesis audit / Weaker K0 consequence /
Payload-instantiated module

## Problem

`FJ93` records that no named repository route or prior-art blocker currently
routes `CAND-T001-005`. Prompt 012 asks whether the same candidate has enough
recorded data to use the weaker \(K_0\) / Cohen--Lyndon source payload
verified in `FJ83`.

This module executes accepted prompt payload
`PAY-T001-CAND005-K0-CL-HYP-2026-001` and checks only whether
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
is FJ83-eligible from current repository records.

## Input

- `FJ83`, the weaker \(K_0\) / Cohen--Lyndon source-payload verification;
- `FJ84`, the earlier current-inventory FJ83 hypothesis audit;
- `FJ90`, the `CAND-T001-005` intake module;
- `FJ91`, the torsion-free source check for `CAND-T001-005`;
- `FJ92`, the Brown/BNS kernel-control computation for `CAND-T001-005`;
- `FJ93`, the known-route / prior-art blocker audit for `CAND-T001-005`;
- `next_prompts.md`, Prompt 012;
- `OQ-115`;
- `OBL-C5-014`;
- `OBL-T001-021`.

## Output target

Classify `CAND-T001-005` as one of:

- FJ83-eligible;
- partially eligible;
- not FJ83-eligible from current repository data.

The output must not:

- claim full Farrell--Jones for `CAND-T001-005`;
- claim coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, or
  `FICwF`;
- claim a weaker \(K_0\) consequence;
- claim a residual-bucket subtraction;
- reread or summarize the source broadly;
- create `FJ95`.

## Definitions

**Definition.** A row is FJ83-eligible if the repository records enough data
to match the FJ83 weaker \(K_0\) / Cohen--Lyndon source-hypothesis package.

For this module, the required package is the one recorded in `FJ83` and
restated in `FJ84`:

- concrete candidate or family row;
- torsion-free status;
- regular-ring \(K_0\)-level formulation;
- exact Cohen--Lyndon presentation or group pair;
- identified group-pair quotient matching the candidate;
- stabilizer-equals-normalizer condition, or the technical normalizer
  quotient package;
- finite cohomological dimension hypotheses at the required level;
- coherent group-ring hypotheses;
- formulation-safety note separating weaker \(K_0\), coefficient FJC, full
  \(\mathcal{FJ}\), `FJCw`, and `FICwF`;
- prior-art / route-overlap status.

**Warning.** Not FJ83-eligible from current repository data means only that
the current row lacks the recorded hypothesis package. It is not a theorem
that no Cohen--Lyndon package exists for the group.

## Main work

### Accepted payload

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND005-K0-CL-HYP-2026-001` |
| Payload type | `PAY-T001-BRIDGE` |
| Target gate | Active post-`FJ93` gate plus `OBL-T001-021` |
| Object | Check whether `CAND-T001-005` has enough recorded data to satisfy the FJ83 source-hypothesis package. |
| Stop condition | Stop after candidate-hypothesis audit and ledger update. |

### Candidate state before the audit

The repository records:

- a concrete one-relator candidate row in `FJ90`;
- first-pass non-proper-power status in `FJ90`;
- first-pass torsion-free status in `FJ91`;
- the epimorphism \(\chi(a)=0,\chi(b)=1\);
- Brown-positive finite generation of \(\ker(\chi)\) in `FJ92`;
- no named route or prior-art blocker in `FJ93`.

The repository does not record:

- a Cohen--Lyndon presentation for the candidate;
- a Cohen--Lyndon group pair whose quotient is \(G_{FJ90}\);
- stabilizer/normalizer data;
- normalizer quotient data;
- finite cohomological dimension data for the FJ83 theorem;
- coherent group-ring hypotheses;
- a completed weaker \(K_0\)-level formulation comparison for this row.

### FJ83 hypothesis audit table

| FJ83 hypothesis item | Current data for `CAND-T001-005` | FJ94 decision |
| --- | --- | --- |
| Concrete candidate row | Present from `FJ90`. | Satisfied. |
| Torsion-free status | Present at first-pass candidate-ledger level from `FJ91`. | Satisfied for this audit. |
| Regular-ring \(K_0\)-level formulation | Present only as the FJ83 source formulation. No candidate-specific application statement is recorded. | Not enough by itself. |
| Cohen--Lyndon presentation or group pair | Not recorded. | Missing. |
| Group-pair quotient matching the candidate | Not recorded. | Missing. |
| Stabilizer equals normalizer, or normalizer quotient package | Not recorded. | Missing. |
| Finite cohomological dimension hypotheses | Not recorded. | Missing. |
| Coherent group-ring hypotheses | Not recorded. | Missing. |
| Normalizer-quotient finite cohomological dimension and coherence data | Not recorded. | Missing. |
| Formulation-safety note | Recorded as caution in `FJ83`, `FJ84`, `FJ93`, and the candidate inventory. | Present as a warning, not as an application bridge. |
| Prior-art / route-overlap status | `FJ93` records no known route or prior-art blocker. | Present as route-audit data, not enough for FJ83 eligibility. |

### Audit result

`CAND-T001-005` is not FJ83-eligible from current repository data.

The row has a concrete presentation and first-pass torsion-free status, but
the Cohen--Lyndon/group-pair, normalizer, finite cohomological dimension, and
coherence hypotheses are not recorded. Therefore the FJ83 weaker \(K_0\)
payload cannot be applied to this row in the current project state.

## Proposition

**Proposition.** `CAND-T001-005` is not FJ83-eligible from current repository
records.

This is a project-ledger proposition. It is not a mathematical theorem about
the group and does not assert that the Jaikin-Zapirain--Linton--Sanchez-
Peralta source cannot apply after additional data are supplied.

## Proof or verification

FJ83 and FJ84 record the minimum hypothesis package required before the
weaker \(K_0\) / Cohen--Lyndon source can be used on a candidate row.

For `CAND-T001-005`, the repository records concrete candidate data and
torsion-free status. It also records Brown-positive finite generation of one
kernel and the absence of a named route or prior-art blocker. None of these
items supplies the Cohen--Lyndon presentation or group-pair data, the
matching quotient, normalizer data, finite cohomological dimension
hypotheses, or coherent group-ring hypotheses required by the FJ83 package.

Thus the source-payload application is blocked at the candidate-hypothesis
level. The audit stops here.

## References

Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs,
coherence and Farrell-Jones Conjecture for K0* (arXiv:2510.23518v2). arXiv.
https://arxiv.org/abs/2510.23518. https://doi.org/10.48550/arXiv.2510.23518.

Source-status note: no new external source was checked in `FJ94`; this module
uses the source package already verified in `FJ83`.

## Dependencies

This module depends on:

- `modules/cycle_005/FJ83_k0_cohen_lyndon_payload_verification.md`;
- `modules/cycle_005/FJ84_k0_cohen_lyndon_candidate_hypothesis_audit.md`;
- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `modules/cycle_005/FJ92_cand005_brown_bns_kernel_control.md`;
- `modules/cycle_005/FJ93_cand005_known_route_prior_art_audit.md`;
- `next_prompts.md`, Prompt 012;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND005-K0-CL-HYP-2026-001`;
- completion of Prompt 012 in `next_prompts.md`;
- resolution of `OQ-115`;
- completion of `OBL-C5-014`;
- completion of the FJ83-hypothesis-audit part of `OBL-T001-021`;
- new route-promotion / branch blocker `OBL-T001-022`;
- new payload gate `OBL-C5-015`;
- new open question `OQ-116`;
- candidate-status update for `CAND-T001-005`: not FJ83-eligible from current
  repository data;
- no new established Farrell--Jones result;
- no weaker \(K_0\) consequence;
- no residual-bucket subtraction.

## Open questions generated

- `OQ-116`: Which accepted payload, if any, should instantiate `FJ95` after
  the `FJ94` FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis audit?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the post-`FJ94` project posture;
- `NOTATION_LEDGER.md` for the new payload, module status, open question,
  and proof obligations;
- `OPEN_QUESTIONS.md` for `OQ-115` and `OQ-116`;
- `ledgers/t001_candidate_inventory.md` for `CAND-T001-005`;
- `ledgers/t001_residual.md` for the non-subtractive residual effect;
- `ledgers/t001_kernel_recognition.md` for the unchanged but still active
  kernel-recognition blocker;
- `ledgers/payload_intake_protocol.md` for the accepted payload record;
- `ledgers/theorem_dependencies.md` for the FJ94 dependency row;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` to mark FJ94 as reuse of
  the already checked FJ83 source package;
- `AGENTS.md` for the active post-`FJ94` gate.
