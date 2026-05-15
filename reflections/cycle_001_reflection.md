# Cycle 001 Reflection. Foundation, proof technology, and first target

## Status

Completed

## Reflection type

Cycle reflection

## Scope

This reflection closes the first twenty-module cycle:

- `FJ01`;
- `FJ03`--`FJ20`;
- the intentionally deferred `FJ02` boundary.

It does not add a new mathematical theorem, source-verified claim, or
established-result number.

## Inputs

Internal repository inputs:

- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ESTABLISHED_RESULTS.md`;
- `ledgers/known_classes.md`;
- `ledgers/inheritance_properties.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `modules/cycle_001/`.

No new external source is used in this reflection.

## Cycle summary

### Foundation

**Definition.** The project begins from the simplified group-ring
formulation of the K-theoretic Farrell--Jones conjecture, with \(R\) an
associative unital ring and \(G\) a discrete group.

**Warning.** This formulation is not the full additive-category formulation.
The additive-category module `FJ02` remains deferred, and source-level flags
such as `with coefficients`, `FJCw`, and `FICwF` must not be collapsed into
the simplified statement without a later source-conventions check.

The first foundation block produced:

- the minimal assembly-map statement in `FJ01`;
- classifying spaces for families in `FJ03`;
- virtually cyclic group conventions in `FJ04`;
- the trivial and infinite cyclic examples in `FJ05` and `FJ06`;
- the Bass--Heller--Swan and Nil-term warning in `FJ07`.

### Consequences

**Remark.** The consequence modules `FJ08`--`FJ10` are theorem maps, not
unconditional new proofs of major geometric rigidity statements.

They record:

- conditional Whitehead-group vanishing;
- conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\);
- the Borel theorem map requiring both low-dimensional K-theory vanishing and
  \(L^{\langle -\infty\rangle}\)-theory assembly.

### Known cases and inheritance

The first ledger pass in `FJ11` and `FJ12` established a usable but incomplete
working base:

- hyperbolic groups;
- finite-dimensional CAT(0)-groups;
- virtually solvable groups;
- pullback, subgroup, directed-colimit, and survey-level full
  \(\mathcal{FJ}\) inheritance rows.

**Warning.** Survey-level inheritance rows should not be used
proof-sensitively until the exact proof source and hypotheses have been
checked.

### Proof technology

The proof-technology primers `FJ13`--`FJ17` gave the project a vocabulary for:

- hyperbolic proof routes;
- CAT(0) proof routes;
- controlled topology and obstruction categories;
- flow spaces and long covers;
- transfers and projection identities.

**Warning.** These modules are proof-skeleton maps. They do not reconstruct
the full Bartels--Lueck--Reich, Bartels--Lueck, or Wegner arguments inside the
repository.

### Target selection

The target-selection block `FJ18`--`FJ20` compared Artin groups and
torsion-free one-relator groups.

**Selection.** The first serious target is:

```text
T-001: torsion-free one-relator residual gap analysis
```

**Warning.** This selection is not a theorem. It is a project-management
decision based on the repository's current source-verified ledgers.

## What worked

The cycle now has a clean separation between:

- internal proofs;
- source-verified theorem maps;
- source-verified literature ledgers;
- warnings;
- open questions;
- project-selection results.

The project also has enough infrastructure to avoid starting the next cycle
with a vague question such as "try one-relator groups." The target has a
specific task: subtract verified known routes and identify what remains.

## What remains fragile

1. `FJ02` is still missing. This is acceptable for the simplified first pass,
   but it becomes a blocker before using source-level coefficient statements
   or finite-wreath-product formulations as internal hypotheses.
2. The known-classes ledger is intentionally incomplete.
3. The one-relator target depends on a structure toolkit that has not yet been
   selected.
4. The inheritance ledger contains some survey-level rows that need
   proof-source tracing before proof-sensitive use.
5. The project has not yet identified an explicit surviving torsion-free
   one-relator subclass outside the recorded known routes.

## Next cycle plan

The next cycle should remain governed by `T-001`.

Provisional module sequence:

| Module | Provisional task | Purpose |
|---|---|---|
| `FJ21` | One-relator structure source selection | Choose the canonical source toolkit for the target. |
| `FJ22` | One-relator hierarchy vocabulary | Record definitions and exact hypotheses needed for reductions. |
| `FJ23` | Hyperbolic route subtraction | Identify one-relator cases already covered by hyperbolicity. |
| `FJ24` | CAT(0) route subtraction | Identify one-relator cases covered by finite-dimensional CAT(0) routes. |
| `FJ25` | Virtually solvable and elementary cases | Remove low-complexity covered examples. |
| `FJ26` | Hyperbolic-by-cyclic and free-by-cyclic route | Check when the recorded extension theorem applies. |
| `FJ27` | Inheritance audit for `T-001` | Trace only the inheritance rows needed for the target. |
| `FJ28` | Residual subclass table, first pass | List covered and surviving subclasses. |
| `FJ29` | Global weaker K-theory theorem search | Check whether a weaker global one-relator theorem exists in sources. |
| `FJ30` | Source-formulation reconciliation checkpoint | Decide whether `FJ02` or a supplement must interrupt the cycle. |
| `FJ31` | Survivor example dossier | Choose one explicit surviving family or explain why none is isolated. |
| `FJ32` | First reduction attempt | Attempt a conditional reduction only under recorded hypotheses. |
| `FJ33` | Failed-attempt ledger, if needed | Preserve dead ends with clear labels. |
| `FJ34` | Virtually cyclic and Nil-term caution for target examples | Check whether Nil phenomena affect the planned formulation. |
| `FJ35` | Source-status audit | Promote only actually checked sources. |
| `FJ36` | Known-classes ledger update | Add any one-relator-relevant known classes found. |
| `FJ37` | Open problem sharpening | Rewrite the surviving target as precise open questions. |
| `FJ38` | Dependency map | Draw the theorem-dependency route for the target. |
| `FJ39` | Target decision checkpoint | Decide theorem, conditional reduction, or abandonment. |
| `FJ40` | Cycle 002 closeout module | Prepare the second reflection. |

This table is provisional. The project may insert `FJ02` or a
source-conventions supplement earlier if source-formulation conflicts become
the active blocker.

## Decision

**Reflection decision.** Cycle 001 is closed. The next mathematical move is
`FJ21`: one-relator structure source selection for `T-001`.

## References

No new external references were used.

Internal references:

- `modules/cycle_001/FJ01_minimal_statement.md`
- `modules/cycle_001/FJ03_classifying_spaces_for_families.md`
- `modules/cycle_001/FJ04_virtually_cyclic_groups.md`
- `modules/cycle_001/FJ05_trivial_group_example.md`
- `modules/cycle_001/FJ06_infinite_cyclic_group_example.md`
- `modules/cycle_001/FJ07_bass_heller_swan_nil_terms.md`
- `modules/cycle_001/FJ08_whitehead_group_consequence.md`
- `modules/cycle_001/FJ09_projective_class_group_consequence.md`
- `modules/cycle_001/FJ10_borel_conjecture_consequence.md`
- `modules/cycle_001/FJ11_known_classes_ledger.md`
- `modules/cycle_001/FJ12_inheritance_properties_ledger.md`
- `modules/cycle_001/FJ13_hyperbolic_groups_case.md`
- `modules/cycle_001/FJ14_cat0_groups_case.md`
- `modules/cycle_001/FJ15_controlled_topology_primer.md`
- `modules/cycle_001/FJ16_flow_spaces_primer.md`
- `modules/cycle_001/FJ17_transfers_primer.md`
- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_001/FJ19_one_relator_groups_dossier.md`
- `modules/cycle_001/FJ20_first_target_selection.md`
