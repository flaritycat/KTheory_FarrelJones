# Module FJ95. CAND-T001-005 Branch Checkpoint After FJ94

## Status

Completed

## Module type

Project governance / Branch checkpoint / Payload-instantiated module

## Problem

Prompt 013 in `next_prompts.md` asks for a branch checkpoint for
`CAND-T001-005` after the bounded torsion-free, kernel-control, prior-art,
and FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis audits recorded in
`FJ91`--`FJ94`.

The task is not to add new mathematics. It is to decide how the repository
should classify the row at the project-management level:

- keep it as a live proof target;
- route it;
- demote it to blocked;
- convert it into a calibration or prior-art example;
- close it as non-actionable.

## Input

- `FJ90`, the candidate-intake audit for `CAND-T001-005`;
- `FJ91`, the torsion-free source check;
- `FJ92`, the Brown/BNS kernel-control computation;
- `FJ93`, the known-route / prior-art blocker audit;
- `FJ94`, the FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis audit;
- `next_prompts.md`, Prompt 013;
- `OQ-116`;
- `OBL-C5-015`;
- `OBL-T001-022`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/theorem_dependencies.md`.

## Output target

Record a branch decision and the next gate.

The output must not:

- add a new source;
- add a new theorem;
- add a new computation;
- add a new candidate;
- claim full Farrell--Jones for `CAND-T001-005`;
- claim coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, or
  `FICwF`;
- claim a weaker \(K_0\) consequence;
- claim a residual-bucket subtraction;
- create a route or prior-art blocker not already recorded.

## Definitions

**Definition.** A row is a live proof target if the repository records a
concrete candidate together with a currently actionable proof obligation that
can be advanced by existing recorded data without adding a new payload.

**Definition.** A row is blocked / inactive if the repository retains it as a
concrete object, but no currently recorded route, source package, computation,
or prior-art comparison is sufficient to advance it.

**Warning.** Demoting a row to blocked / inactive is not a mathematical
negative result. It means only that the current repository has exhausted the
accepted bounded audits for that row.

## Main work

### Accepted payload

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND005-BRANCH-2026-001` |
| Payload type | `PAY-GOV` |
| Target gate | Active post-`FJ94` gate, `OQ-116`, `OBL-C5-015`, and `OBL-T001-022` |
| Object | Decide whether `CAND-T001-005` should remain live, be routed, be demoted to blocked, be converted to calibration/prior-art, or be closed as non-actionable. |
| Source-status label | No new external source checked; internal ledger audit only. |
| Stop condition | Stop after branch decision and ledger update. |

### Recorded state before the checkpoint

| Item | Repository status before `FJ95` |
| --- | --- |
| Concrete candidate row | Recorded in `FJ90`. |
| Proper-power status | First-pass non-proper-power check recorded in `FJ90`. |
| Torsion-free status | First-pass source-checked in `FJ91`. |
| Epimorphism to \(\mathbb Z\) | \(\chi(a)=0,\chi(b)=1\) recorded in `FJ90`. |
| Brown/BNS data | `FJ92` records Brown-positive finite generation of \(\ker(\chi)\). |
| Finite-rank free kernel | Not recorded. |
| Named route or prior-art blocker | None recorded by `FJ93`. |
| FJ83 weaker \(K_0\) / Cohen--Lyndon eligibility | Not eligible from current repository data by `FJ94`. |
| Residual subtraction | None recorded. |

### Branch table

| Branch option | FJ95 decision | Reason |
| --- | --- | --- |
| Keep as live proof target | Reject for now | The row has no current finite-rank free-kernel bridge, route bridge, prior-art blocker, or FJ83 application package. |
| Route the row | Reject | `FJ93` records no known repository route, and `FJ94` records no weaker \(K_0\) application. |
| Demote to blocked / inactive | Select | This preserves the concrete row while preventing further module drift around an exhausted candidate audit. |
| Convert to calibration / prior-art example | Reject | The row is not already routed or source-identified as prior art. |
| Close as non-actionable | Reject | The row is still concrete and may become useful if a later payload supplies finite-rank freeness, another route, new FJ83 data, or a prior-art object. |

### Branch decision

`CAND-T001-005` is demoted to blocked / inactive proof-target status.

It remains recorded as a concrete torsion-free one-relator candidate object,
but it is not live for further proof work until a future accepted payload
adds at least one exact changed object:

- finite-rank free-kernel identification;
- source-verified route bridge;
- new FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis data;
- formulation comparison tied to a named route;
- prior-art object;
- explicit reopening decision with a changed proof obligation.

## Proposition

**Proposition.** In the current repository state, `CAND-T001-005` should be
classified as a blocked / inactive candidate row, not as a live proof target,
routed example, prior-art example, calibration example, or closed row.

This is a project-ledger proposition, not a theorem about the group.

## Proof or verification

The proof is by internal ledger audit.

`FJ90` supplies the concrete row. `FJ91` supplies first-pass torsion-free
status. `FJ92` supplies Brown-positive finite generation of one kernel, but
does not identify the kernel as finite-rank free. `FJ93` checks the named
repository routes and records no route or prior-art blocker. `FJ94` checks
the FJ83 weaker \(K_0\) / Cohen--Lyndon source-hypothesis package and records
that the row is not eligible from current repository data.

Therefore the row is too concrete to delete or close, but too under-bridged
to continue as a live proof target. The conservative branch is blocked /
inactive.

## References

No new external source was checked in `FJ95`.

This module uses only internal repository records from `FJ90`--`FJ94` and the
listed ledgers.

## Dependencies

This module depends on:

- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `modules/cycle_005/FJ92_cand005_brown_bns_kernel_control.md`;
- `modules/cycle_005/FJ93_cand005_known_route_prior_art_audit.md`;
- `modules/cycle_005/FJ94_cand005_k0_cohen_lyndon_hypothesis_audit.md`;
- `next_prompts.md`, Prompt 013;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND005-BRANCH-2026-001`;
- completion of Prompt 013 in `next_prompts.md`;
- resolution of `OQ-116`;
- completion of `OBL-C5-015`;
- completion of `OBL-T001-022` by branch decision;
- new payload gate `OBL-C5-016`;
- new branch/reopening obligation `OBL-T001-023`;
- new open question `OQ-117`;
- candidate-status update for `CAND-T001-005`: blocked / inactive proof
  target, retained as a concrete row;
- no new established Farrell--Jones result;
- no weaker \(K_0\) consequence;
- no residual-bucket subtraction.

## Open questions generated

- `OQ-117`: Does any live non-routed `T-001` candidate row remain after the
  `FJ95` demotion of `CAND-T001-005`?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the post-`FJ95` project posture;
- `NOTATION_LEDGER.md` for the new payload, module status, open question,
  and proof obligations;
- `OPEN_QUESTIONS.md` for `OQ-116` and `OQ-117`;
- `ledgers/t001_candidate_inventory.md` for `CAND-T001-005`;
- `ledgers/t001_residual.md` for the non-subtractive branch effect;
- `ledgers/t001_kernel_recognition.md` for the unchanged kernel blocker;
- `ledgers/payload_intake_protocol.md` for the accepted payload record;
- `ledgers/theorem_dependencies.md` for the FJ95 dependency row;
- `AGENTS.md` for the active post-`FJ95` gate;
- `README.md` and `PROJECT_CHARTER.md` for the current project status.
