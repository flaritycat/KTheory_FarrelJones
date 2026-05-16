# Module FJ69. Artin Subclass-Gap Inventory After FJ18

## Status

Completed

## Module type

Attack surface / Ledger inventory / Target refinement

## Problem

`FJ68` selects `A-001`, Artin subclass-gap inventory after `FJ18`, as the
bounded next target packet. It records `OBL-ARTIN-001`: `FJ69` must produce
an Artin subclass-gap inventory from existing repository records before any
new Artin source-summary lane begins.

`FJ69` must update `OQ-021`, sharpen `OQ-023`, and choose a bounded next
Artin packet or record that no Artin gap is ready.

## Input

- `FJ18`, Artin Groups Dossier;
- `FJ20`, First Target Selection;
- `FJ68`, Target-Pivot Candidate Matrix;
- `OQ-021`;
- `OQ-023`;
- `OQ-091`;
- `OBL-ARTIN-001`;
- `ledgers/known_classes.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/source_status.md`;
- `NOTATION_LEDGER.md`;
- `AGENTS.md`.

## Output target

A first-pass Artin subclass-gap inventory that:

- creates `ledgers/artin_subclass_gap_inventory.md`;
- separates covered, method, gap, and formulation-safety rows;
- resolves `OQ-091`;
- gives a first-pass current-repository answer to `OQ-021`;
- sharpens `OQ-023` into a candidate-filter task;
- records `OBL-ARTIN-002`;
- selects `FJ70`.

## Definitions

**Definition.** An Artin covered row is an Artin class or route already
recorded in `FJ18` under exact source hypotheses and formulation labels.

**Definition.** An Artin gap row is an Artin class or route not recorded as a
known Farrell--Jones case inside the current repository.

**Definition.** A method row is a theorem route such as normal
poly-freeness that can support Artin applications only after a separate
bridge identifies a given Artin class with the method's hypotheses.

**Definition.** A formulation-safety row records that source labels such as
`FJCw`, `FICwF`, full \(\mathcal{FJ}\), and coefficient K-theory are not
being identified.

## Main work

### Inventory created

`FJ69` creates:

```text
ledgers/artin_subclass_gap_inventory.md
```

The inventory contains:

- `ART-COV-001`: Artin groups of FC-type;
- `ART-COV-002`: weak Garside groups of finite type, including spherical
  Artin and braid examples listed in `FJ18`;
- `ART-COV-003`: even Artin groups of FC-type;
- `ART-METHOD-001`: normally poly-free groups as an Artin-relevant method
  row;
- `ART-COV-004`: right-angled Artin groups and finite-graph semidirect
  products \(A_\Gamma\rtimes_f\mathbb Z\);
- `ART-COV-005`: even Artin groups satisfying Wu's clique or join/tree
  criteria;
- `ART-COV-006`: Roushon's listed finite real, complex, and affine Artin
  types;
- `ART-GAP-001`: all Artin groups;
- `ART-GAP-002`: named Artin subclasses outside the `FJ18` rows, currently
  not named in the repository;
- `ART-GAP-003`: possible Wu clique-reduction target not already covered by
  `FJ18`;
- `ART-FORM-001`: formulation comparison and source-label safety.

### Known-classes normalization

`FJ69` also normalizes `ledgers/known_classes.md` by adding two explicit
rows already present in the `FJ18` source-verified table:

- weak Garside groups of finite type, including the listed spherical Artin
  and braid examples;
- right-angled Artin groups and finite-graph semidirect products
  \(A_\Gamma\rtimes_f\mathbb Z\).

No new source is checked by this normalization. It only makes the known-class
ledger match the source-verified rows already recorded in `FJ18`.

### OQ-021 inventory answer

`FJ69` gives a first-pass current-repository answer to `OQ-021`.

Inside the current repository, the only explicit Artin gap row is:

```text
ART-GAP-001: all Artin groups
```

The project also records a placeholder gap condition:

```text
ART-GAP-002: named Artin subclasses outside the FJ18 rows
```

No such additional subclass is named in the current repository. A future
module must name an exact subclass before source work begins.

### OQ-023 sharpening

`OQ-023` remains open but is sharpened.

The Wu clique-reduction route is already represented in `ART-COV-005` for
the source-verified cases recorded by `FJ18`. The open task is not to
summarize Wu again. The open task is:

```text
ART-GAP-003: possible Wu clique-reduction target not already covered by FJ18
```

The next module should test whether existing repository records contain a
noncovered Artin graph or subclass whose clique subgroups are already in
covered rows. If no such object is present, it should record a no-current
candidate note.

### New proof obligation

**Obligation OBL-ARTIN-002.** `FJ70` must run the Wu clique-reduction
candidate filter for Artin gap rows.

Allowed outcomes:

- name a concrete Artin subclass or graph-pattern row already present in the
  repository and attach its required clique-subgroup status;
- identify an exact source payload required before such a row can be tested;
- record that no current repository object supports a Wu-filter candidate.

Stop condition: `FJ70` must not become a broad Artin literature summary and
must not claim a global all-Artin theorem.

### Next module selection

`FJ69` selects:

```text
FJ70. Wu Clique-Reduction Candidate Filter for Artin Gap Rows
```

Goal: decide whether `ART-GAP-003` can produce a bounded candidate from
existing records, or whether it must be marked no-current-candidate until an
exact source payload or subclass name is supplied.

Required input:

- `FJ18`;
- `FJ69`;
- `OQ-023`;
- `ART-GAP-003`;
- `OBL-ARTIN-002`;
- `ledgers/artin_subclass_gap_inventory.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`.

Success criterion:

- produce a candidate filter row with exact clique-subgroup obligations; or
- record a no-current-Wu-candidate obstruction.

Failure criterion:

- begin general Artin source accumulation without a candidate row, exact
  source payload, or changed project object.

Expected output:

- update `OQ-023`;
- update `ledgers/artin_subclass_gap_inventory.md`;
- either select a bounded `FJ71` Artin packet or record that the Artin lane
  needs an exact source payload before continuing.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, the Artin subclass-gap
inventory can be produced from existing records, and the only bounded next
Artin task is the Wu clique-reduction candidate filter.

**Proof.** `FJ18` already records source-verified Artin rows and warns that
no global all-Artin theorem is imported. `ledgers/known_classes.md` records
several of those rows and, after `FJ69`, is normalized for two additional
`FJ18` rows. `OPEN_QUESTIONS.md` records `OQ-021` and `OQ-023` as the
relevant Artin questions. No current repository row names an additional
Artin subclass outside `FJ18` with a ready source payload. The only bounded
route object already named is Wu's clique-reduction question. Therefore the
inventory can be completed internally, and the next bounded Artin task is a
candidate filter for `ART-GAP-003`.

**Route decision.** `FJ69` resolves `OQ-091`, gives a first-pass
current-repository answer to `OQ-021`, sharpens `OQ-023`, completes
`OBL-ARTIN-001`, records `OBL-ARTIN-002`, and selects `FJ70`.

**Warning.** `FJ69` proves no new Farrell--Jones case and does not claim the
Farrell--Jones conjecture for all Artin groups.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ18` for the source-verified Artin table and global warning.
2. Checked `FJ68` for `A-001` and `OBL-ARTIN-001`.
3. Checked `ledgers/known_classes.md` for Artin rows already mirrored there.
4. Checked `ledgers/source_status.md` for active Artin source-status rows.
5. Checked `OPEN_QUESTIONS.md` for `OQ-021`, `OQ-023`, and `OQ-091`.
6. No new external source was checked.

## References

No new external source was used in this module.

External source names appearing in the inventory are inherited from the
source-verified `FJ18` rows and their existing bibliography entries.

Internal references:

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_001/FJ20_first_target_selection.md`
- `modules/cycle_004/FJ68_target_pivot_candidate_matrix.md`
- `OPEN_QUESTIONS.md`
- `ledgers/known_classes.md`
- `ledgers/open_group_classes.md`
- `ledgers/source_status.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ18`;
- `FJ20`;
- `FJ68`;
- `OQ-021`;
- `OQ-023`;
- `OQ-091`;
- `OBL-ARTIN-001`.

## Results produced

This module produced:

- `ledgers/artin_subclass_gap_inventory.md`;
- a first-pass resolution of `OQ-091`;
- a first-pass current-repository answer to `OQ-021`;
- a sharpened `OQ-023`;
- completion of `OBL-ARTIN-001`;
- `OBL-ARTIN-002`, the Wu clique-reduction candidate-filter obligation;
- selection of `FJ70`, Wu Clique-Reduction Candidate Filter for Artin Gap
  Rows;
- no new `ER-*` result;
- no new global Artin theorem claim.

## Open questions generated

- `OQ-092`: Can `FJ70` produce a Wu clique-reduction candidate from existing
  Artin gap rows, or must it record no current candidate?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ69` and next `FJ70`;
- `SCOPE_LEDGER.md` for the `OQ-091` resolution and new `OQ-092`;
- `OPEN_QUESTIONS.md` for `OQ-021`, `OQ-023`, `OQ-091`, and `OQ-092`;
- `NOTATION_LEDGER.md` for Artin inventory row labels and `OBL-ARTIN-002`;
- `ledgers/known_classes.md` for normalized `FJ18` rows;
- `ledgers/open_group_classes.md` for the Artin next action;
- `ledgers/source_status.md` to mark that `FJ69` uses only existing `FJ18`
  Artin source rows;
- `ledgers/theorem_dependencies.md` for completed `FJ69` and pending `FJ70`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
