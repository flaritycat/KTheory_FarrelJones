# Module FJ71. Artin Branch Checkpoint After Wu Filter

## Status

Completed

## Module type

Attack surface / Governance checkpoint / Branch decision

## Problem

`FJ70` records no current Wu-filter candidate from the existing Artin gap
rows. The next step must not become another Artin source-summary module.

The module must make one branch decision for the active Artin packet:

- pause the active Artin packet until an exact source payload appears;
- select a bounded exact source-payload acquisition task with a named graph
  or subclass;
- return to target-pivot comparison using the `FJ67` criteria;
- identify a concrete repository object that changes the Artin inventory.

## Input

- `FJ18`, Artin Groups Dossier;
- `FJ68`, Target-Pivot Candidate Matrix;
- `FJ69`, Artin Subclass-Gap Inventory After FJ18;
- `FJ70`, Wu Clique-Reduction Candidate Filter for Artin Gap Rows;
- `OQ-023`;
- `OQ-092`;
- `OQ-093`;
- `OBL-ARTIN-003`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/source_status.md`;
- `AGENTS.md`.

## Output target

A branch checkpoint that:

- resolves `OQ-093` for the current repository state;
- pauses the active Artin proof/source lane as an immediate target sequence;
- keeps the global all-Artin status unresolved inside the project;
- records a reactivation gate for future Artin work;
- records a pivot obligation after the Artin pause;
- selects `FJ72`, Target-Pivot Refresh After Artin Pause;
- makes no global all-Artin theorem claim.

## Definitions

**Definition.** An Artin pause is a project-state decision that Artin groups
remain important and unresolved, but no immediate Artin proof attempt or
source-verification lane should continue without a named payload that changes
a project object.

**Definition.** An Artin reactivation payload is a named finite graph, graph
family, Artin subclass, exact source theorem, or concrete bridge object with
recorded hypotheses, formulation label, prior-art overlap, and the project
ledger row it changes.

**Definition.** A target-pivot refresh is a bounded comparison after a target
pause. It applies the `FJ67` criteria again to currently available target
inputs rather than selecting a new target by inertia.

**Warning.** Pausing the active Artin lane is not a theorem about Artin
groups. It does not claim that all Artin groups are outside the
Farrell--Jones known cases, and it does not claim that no Artin subclass can
be made candidate-ready later.

## Main work

### Branch table

| Branch option | Current repository support | Decision | Reason |
|---|---|---|---|
| Continue the Wu lane immediately | not supported | reject | `FJ70` records no current graph, graph family, subclass, or clique-subgroup data outside already covered rows. |
| Select a bounded Artin source-payload acquisition task | not supported | reject for now | No named graph, subclass, source theorem, or Artin inventory row is recorded as the acquisition target. |
| Continue through a concrete repository object | not supported | reject for now | The current Artin inventory has no new object beyond covered rows, global placeholders, and the no-current-candidate Wu row. |
| Pause the active Artin lane | supported | select | This satisfies `OBL-ARTIN-003` without fabricating a candidate or source payload. |
| Return to target-pivot comparison | supported | select as next step | After both dormant `T-001` and paused Artin lanes, the project needs a refreshed comparison under `FJ67` criteria. |

### Branch decision

`FJ71` pauses the active Artin lane as an immediate proof/source sequence.

The pause has the following meaning:

- `ART-GAP-001`, all Artin groups, remains unresolved inside the project;
- `ART-GAP-002`, unnamed subclasses outside the `FJ18` rows, remains inactive
  until a subclass is named;
- `ART-GAP-003`, the possible Wu clique-reduction target, remains inactive
  until the `FJ70` payload is supplied;
- no module should continue Artin source reading unless it changes an Artin
  inventory row, source-status row, open question, proof obligation, or
  prior-art blocker.

### New obligations

**Obligation OBL-ARTIN-004.** After `FJ71`, the active Artin lane is paused.
Future Artin modules may reactivate it only with an Artin reactivation
payload: a named graph, graph family, subclass, source theorem, bridge
object, formulation label, prior-art-overlap note, and project object changed.

**Obligation OBL-PIVOT-002.** After the Artin pause, the project must run a
target-pivot refresh before selecting another active mathematical target. The
refresh should compare only inputs with currently recorded repository objects
or should record that no target is ready.

### Next module selection

`FJ71` selects:

```text
FJ72. Target-Pivot Refresh After Artin Pause
```

Goal: compare the available post-pause target inputs using the `FJ67`
criteria and decide whether a new bounded packet is legitimate.

Required input:

- `FJ66`, `FJ67`, and `FJ68`;
- `FJ69`, `FJ70`, and `FJ71`;
- `ledgers/open_group_classes.md`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/t001_candidate_inventory.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `AGENTS.md`.

Success criterion:

- select one bounded next packet with a concrete repository object, or record
  that no target is ready.

Failure criterion:

- choose a target by preference alone, or open another source-summary lane
  without a named source payload and changed project object.

Expected output:

- updated target-pivot status;
- updated open questions and proof obligations;
- no theorem claim unless an exact source or internal proof is supplied.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, the active Artin packet
should be paused and the project should proceed to a target-pivot refresh.

## Proof or verification

**Proof.** `FJ70` records no current Wu-filter candidate and supplies the
minimum payload required before reactivating the Wu lane. The Artin inventory
contains covered rows, formulation rows, the global all-Artin gap row, the
unnamed-subclass gap row, and the no-current-candidate Wu row. It does not
contain a named graph, subclass, source theorem, bridge object, or changed
project row that could support a bounded Artin source-payload acquisition
module.

Continuing the Artin lane would therefore either repeat the already rejected
Wu filter or begin source accumulation without an exact payload. Pausing the
lane satisfies `OBL-ARTIN-003` and preserves the unresolved Artin status
without overclaiming. Since `T-001` is already dormant and the Artin lane is
now paused, the next legitimate governance step is a target-pivot refresh
using the `FJ67` criteria.

No external source was checked for this verification.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_004/FJ68_target_pivot_candidate_matrix.md`
- `modules/cycle_004/FJ69_artin_subclass_gap_inventory_after_fj18.md`
- `modules/cycle_004/FJ70_wu_clique_reduction_candidate_filter_artin_gap_rows.md`
- `ledgers/artin_subclass_gap_inventory.md`
- `ledgers/open_group_classes.md`
- `ledgers/source_status.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ18`;
- `FJ68`;
- `FJ69`;
- `FJ70`;
- `OQ-023`;
- `OQ-092`;
- `OQ-093`;
- `OBL-ARTIN-003`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/open_group_classes.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-093`;
- the Artin pause decision;
- `OBL-ARTIN-004`, the Artin reactivation gate;
- `OBL-PIVOT-002`, the post-Artin-pause target-pivot obligation;
- `A-004`, target-pivot refresh after Artin pause;
- selection of `FJ72`, Target-Pivot Refresh After Artin Pause;
- no new `ER-*` result;
- no global all-Artin theorem claim.

## Open questions generated

- `OQ-094`: Which target-pivot input should follow the Artin pause?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ71` and next `FJ72`;
- `SCOPE_LEDGER.md` for the `OQ-093` resolution, `OQ-094`, `A-004`, and
  `OBL-PIVOT-002`;
- `OPEN_QUESTIONS.md` for `OQ-093` and `OQ-094`;
- `NOTATION_LEDGER.md` for `A-004`, Artin pause, `OBL-ARTIN-004`, and
  `OBL-PIVOT-002`;
- `ledgers/artin_subclass_gap_inventory.md` for the Artin pause;
- `ledgers/open_group_classes.md` for the paused Artin lane;
- `ledgers/theorem_dependencies.md` for completed `FJ71` and pending `FJ72`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
