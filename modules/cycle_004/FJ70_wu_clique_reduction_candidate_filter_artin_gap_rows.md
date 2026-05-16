# Module FJ70. Wu Clique-Reduction Candidate Filter for Artin Gap Rows

## Status

Completed

## Module type

Attack surface / Candidate filter / Obstruction record

## Problem

`FJ69` records `OBL-ARTIN-002`: `FJ70` must run the Wu
clique-reduction candidate filter for `ART-GAP-003` without broad source
accumulation.

The module must decide whether the current repository already contains a
concrete noncovered Artin graph, graph family, or subclass whose clique
subgroups are recorded as Farrell--Jones-positive in the formulation needed
by the Wu row. If not, it must record a no-current-candidate note and a
precise reactivation requirement.

## Input

- `FJ18`, Artin Groups Dossier;
- `FJ68`, Target-Pivot Candidate Matrix;
- `FJ69`, Artin Subclass-Gap Inventory After FJ18;
- `OQ-023`;
- `OQ-092`;
- `ART-GAP-003`;
- `OBL-ARTIN-002`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/known_classes.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/source_status.md`;
- `AGENTS.md`.

## Output target

A bounded filter artifact that:

- resolves `OQ-092` for the current repository state;
- records whether `ART-GAP-003` has a concrete candidate;
- records the minimum source-payload requirement for reactivating the Wu
  candidate lane;
- completes `OBL-ARTIN-002`;
- records `OBL-ARTIN-003`;
- selects `FJ71`, Artin Branch Checkpoint After Wu Filter.

## Definitions

**Definition.** A Wu-filter candidate is a repository-supported Artin
graph, graph family, or subclass that satisfies all of the following
project-level intake requirements:

- it is not already covered by a row in `FJ18` or
  `ledgers/artin_subclass_gap_inventory.md`;
- it comes with the finite graph and positive even label hypotheses needed
  for the Wu row as recorded in `FJ18`;
- each relevant clique subgroup has a recorded `FJCw` source-status row or a
  precise source-payload requirement;
- the resulting conclusion would change an Artin gap row, proof obligation,
  or prior-art blocker;
- the formulation label remains `FJCw` unless a separate checked comparison
  permits another label.

**Definition.** A no-current-Wu-candidate note records that the current
repository has no candidate satisfying the above intake requirements. It is
not a theorem that no such Artin group or subclass exists.

**Warning.** `FJ70` does not re-check Wu's source and does not reconstruct
the clique-reduction theorem. It uses only the source-verified Wu row already
recorded in `FJ18`.

## Main work

### Candidate filter

| Filter row | Input row | Concrete candidate object present? | Clique-subgroup data present? | Not-already-covered test | Outcome |
|---|---|---|---|---|---|
| `WU-FILT-001` | `ART-COV-005`, even Artin groups satisfying Wu's clique or join/tree criteria | yes, but only as already covered source rows | yes, within the already covered source hypotheses | fails: this is already a covered row | not a new candidate |
| `WU-FILT-002` | `ART-GAP-001`, all Artin groups | no finite graph, subclass, or graph-pattern object is specified | no clique inventory is recorded for the global class | cannot be tested; too broad | source payload required before use |
| `WU-FILT-003` | `ART-GAP-002`, named Artin subclasses outside `FJ18` rows | no named outside subclass is present in the repository | no clique-subgroup data is present | cannot be tested; no object | no current candidate |
| `WU-FILT-004` | `ART-GAP-003`, possible Wu clique-reduction target not already covered by `FJ18` | no concrete noncovered graph or subclass is isolated | no all-cliques-covered check can be run | cannot be tested in the current repository | no current Wu-filter candidate |

### Minimum reactivation payload

Future use of the Wu candidate lane must provide an exact payload before a
new source-summary module begins. The minimum payload is:

- a named finite Artin graph, graph family, or subclass;
- confirmation that the relevant source hypotheses are finite graph and
  positive even label hypotheses, or a checked correction of that statement;
- a clique list or clique-subgroup reduction statement;
- for every relevant clique subgroup, a recorded `FJCw` row or exact source
  theorem with APA citation, hypotheses, formulation level, and source
  status;
- an explanation of why the full graph or subclass is not already covered by
  `ART-COV-001`--`ART-COV-006`;
- a formulation-safety note comparing `FJCw` only with labels already
  licensed by `FJ02` and `FJ47`;
- a prior-art risk note explaining why the row is not merely a restatement
  of Wu's already recorded covered families.

### Candidate-filter decision

`FJ70` records no current Wu-filter candidate.

The obstruction is repository-state based: the available Artin records name
covered Wu cases and global or placeholder gap rows, but no concrete
noncovered graph, graph family, or subclass with clique-subgroup data.

### New proof obligation

**Obligation OBL-ARTIN-003.** After `FJ70`, no module may reactivate the Wu
clique-reduction lane unless it supplies the minimum reactivation payload
listed above or records a branch decision that pauses the Artin target lane.

Allowed outputs for the next module:

- pause the active Artin packet until an exact source payload appears;
- select a bounded exact source-payload acquisition task with a named graph
  or subclass;
- return to target-pivot comparison using the `FJ67` criteria;
- identify a concrete repository object that changes the Artin inventory.

Stop condition: do not continue Artin modules by summarizing additional
sources unless a named payload changes a candidate row, gap row, proof
obligation, or prior-art blocker.

### Next module selection

`FJ70` selects:

```text
FJ71. Artin Branch Checkpoint After Wu Filter
```

Goal: decide whether the active Artin lane should pause, select a named
source-payload acquisition packet, return to target-pivot comparison, or
continue through a concrete repository object.

Required input:

- `FJ18`;
- `FJ68`;
- `FJ69`;
- `FJ70`;
- `OQ-023`;
- `OQ-092`;
- `OQ-093`;
- `OBL-ARTIN-003`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/source_status.md`.

Success criterion:

- record a branch decision with one of the allowed outputs above.

Failure criterion:

- begin another Artin source-summary module without a named source payload
  and changed project object.

Expected output:

- update the Artin inventory;
- update `OPEN_QUESTIONS.md`;
- update the active target packet or pause status;
- make no global all-Artin theorem claim.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, `ART-GAP-003` does not
contain a Wu-filter candidate.

**Proof.** The current Artin inventory records the Wu route as
`ART-COV-005`, already covered under the source hypotheses recorded in
`FJ18`. The remaining Artin gap rows are `ART-GAP-001`, the global class of
all Artin groups; `ART-GAP-002`, unnamed subclasses outside `FJ18`; and
`ART-GAP-003`, a possible Wu clique-reduction target. None of these rows
names a finite graph, graph family, or subclass with recorded clique-subgroup
data. Therefore the Wu filter cannot produce a candidate from current
repository records. The appropriate output is a no-current-candidate note
and a reactivation payload requirement.

**Route decision.** `FJ70` resolves `OQ-092`, updates `OQ-023`, completes
`OBL-ARTIN-002`, records `OBL-ARTIN-003`, selects `FJ71`, and makes no new
Farrell--Jones theorem claim.

**Warning.** This is not a negative mathematical theorem about Wu's method
or about Artin groups. It records only that the current repository does not
contain the candidate data required for a bounded Wu-filter proof attempt.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ18` for the source-verified Wu rows and global all-Artin
   warning.
2. Checked `FJ69` and `ledgers/artin_subclass_gap_inventory.md` for
   `ART-COV-*`, `ART-GAP-*`, and `ART-FORM-*` rows.
3. Checked `ledgers/known_classes.md` for already covered Artin rows.
4. Checked `ledgers/open_group_classes.md` for active Artin target status.
5. Checked `OPEN_QUESTIONS.md` for `OQ-023` and `OQ-092`.
6. Ran a targeted repository search for Wu, clique, Artin graph, even Artin,
   and `ART-GAP-003` references.
7. No new external source was checked.

## References

No new external source was used in this module.

External source names appearing here are inherited from the source-verified
`FJ18` rows and their existing APA entries.

Internal references:

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_004/FJ68_target_pivot_candidate_matrix.md`
- `modules/cycle_004/FJ69_artin_subclass_gap_inventory_after_fj18.md`
- `OPEN_QUESTIONS.md`
- `ledgers/artin_subclass_gap_inventory.md`
- `ledgers/known_classes.md`
- `ledgers/open_group_classes.md`
- `ledgers/source_status.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ18`;
- `FJ68`;
- `FJ69`;
- `OQ-023`;
- `OQ-092`;
- `ART-GAP-003`;
- `OBL-ARTIN-002`;
- `ledgers/artin_subclass_gap_inventory.md`.

## Results produced

This module produced:

- a first-pass current-repository resolution of `OQ-092`;
- a no-current-Wu-candidate note for `ART-GAP-003`;
- a minimum reactivation payload for the Wu clique-reduction lane;
- completion of `OBL-ARTIN-002`;
- `OBL-ARTIN-003`, the Artin/Wu reactivation or branch obligation;
- selection of `FJ71`, Artin Branch Checkpoint After Wu Filter;
- no new `ER-*` result;
- no global all-Artin theorem claim.

## Open questions generated

- `OQ-093`: Should `FJ71` pause the active Artin packet, select a named
  source-payload acquisition task, return to target-pivot comparison, or
  continue through a concrete repository object after the no-current-Wu-
  candidate note?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ70` and next `FJ71`;
- `SCOPE_LEDGER.md` for the `OQ-092` resolution and new `OQ-093`;
- `OPEN_QUESTIONS.md` for `OQ-023`, `OQ-092`, and `OQ-093`;
- `NOTATION_LEDGER.md` for `WU-FILT-*`, `A-003`, and `OBL-ARTIN-003`;
- `ledgers/artin_subclass_gap_inventory.md` for the no-current-candidate
  decision;
- `ledgers/open_group_classes.md` for the active Artin branch checkpoint;
- `ledgers/source_status.md` to record that `FJ70` used only existing `FJ18`
  Artin source rows;
- `ledgers/theorem_dependencies.md` for completed `FJ70` and pending `FJ71`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
