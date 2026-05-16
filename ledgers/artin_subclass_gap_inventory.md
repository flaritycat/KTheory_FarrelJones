# Artin Subclass-Gap Inventory

## Status

Created by `FJ69`; updated by `FJ70`, `FJ71`, `FJ72`, `FJ77`, and `FJ81`.

This ledger is an internal inventory extracted from existing repository
records. No new external source was checked for this ledger.

## Use rules

- Do not claim Farrell--Jones for all Artin groups from this ledger.
- Preserve formulation labels: `FJCw`, `FICwF`, full \(\mathcal{FJ}\),
  coefficient K-theory, and simplified ring-coefficient statements are not
  interchangeable.
- Treat a row as usable only under its source-recorded hypotheses.
- Do not begin a new Artin source-summary lane unless a row below identifies
  an exact source payload and project object changed.

## Source anchors inside the repository

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_004/FJ68_target_pivot_candidate_matrix.md`
- `ledgers/known_classes.md`
- `ledgers/source_status.md`
- `OPEN_QUESTIONS.md`

## Inventory table

| Inventory ID | Artin class or route | Current source-verified status | Formulation label | Coverage classification | Relation to open questions | Next obligation or stop condition |
|---|---|---|---|---|---|---|
| `ART-COV-001` | Artin groups of FC-type | Source-verified in `FJ18` and `ledgers/known_classes.md` under the Huang--Osajda row. | Farrell--Jones with finite wreath products, source-level label. | covered under exact source hypotheses | Helps answer `OQ-021`: FC-type is not an uncovered gap row. | Do not use as a global all-Artin theorem. |
| `ART-COV-002` | Weak Garside groups of finite type, including spherical Artin and braid examples listed in `FJ18` | Source-verified in `FJ18`; normalized into `ledgers/known_classes.md` by `FJ69`. | Farrell--Jones with finite wreath products, source-level label. | covered under exact source hypotheses; ledger-normalization row | Helps answer `OQ-021`: spherical/braid examples listed in `FJ18` are covered as source-level examples, not as a global Artin theorem. | Use only under the weak finite-type Garside/source hypotheses recorded in `FJ18`. |
| `ART-COV-003` | Even Artin groups of FC-type | Source-verified in `FJ18` and `ledgers/known_classes.md` under the Brueck--Kielak--Wu row. | `FJCw`; K- and L-theoretic with additive categories and finite wreath products. | covered under exact source hypotheses; overlaps `ART-COV-001` by a different route | Helps answer `OQ-021`: even FC-type is not an uncovered gap row. | Preserve the `FJCw` formulation label. |
| `ART-METHOD-001` | Normally poly-free groups | Source-verified in `FJ18` and `ledgers/known_classes.md` as a method row. | `FJCw`; K- and L-theoretic with additive categories and finite wreath products. | method route, not only an Artin subclass | Supports `OQ-021` only when a specific Artin subclass is recorded as normally poly-free. | Do not apply to an Artin class without a recorded normally poly-free bridge. |
| `ART-COV-004` | Right-angled Artin groups and finite-graph semidirect products \(A_\Gamma\rtimes_f\mathbb Z\) | Source-verified in `FJ18`; normalized into `ledgers/known_classes.md` by `FJ69`. | RAAGs: source route through CAT(0)/known-class rows; semidirect products: source-level `FJCw`. | covered under exact source hypotheses; ledger-normalization row | Helps answer `OQ-021`: finite-graph RAAG and recorded RAAG-by-cyclic rows are not uncovered gap rows. | Do not extend to arbitrary Artin semidirect products. |
| `ART-COV-005` | Even Artin groups satisfying Wu's clique or join/tree criteria | Source-verified in `FJ18` and `ledgers/known_classes.md`. | `FJCw`; additive categories and finite wreath products. | covered under exact finite-graph, positive-even-label, clique/join/tree hypotheses | Central to `OQ-023`: current Wu rows are covered when the source hypotheses are met. | `FJ70` should test whether any currently recorded noncovered Artin row can be filtered through this route. |
| `ART-COV-006` | Roushon's listed finite real, complex, and affine Artin types | Source-verified in `FJ18` and `ledgers/known_classes.md` with erratum/corrigendum caution. | `FICwF`; K-, L-, and A-theory with coefficients and finite wreath products. | covered under exact listed types and correction status | Helps answer `OQ-021`: the listed finite real, complex, and affine types are not uncovered gap rows. | Use the corrected \(\widetilde B_n\) route; preserve `FICwF`. |
| `ART-GAP-001` | All Artin groups | Explicitly not established by `FJ18` or `ledgers/known_classes.md`. | unknown / not recorded as known. | global gap row | Main residual answer to `OQ-021`: global all-Artin status remains unresolved inside the project. | Do not promote without an exact global source payload and formulation-safe theorem statement. |
| `ART-GAP-002` | Named Artin subclasses outside `FJ18` rows | No specific subclass name is currently recorded in the repository beyond broad placeholders. | unknown. | no-current-name gap row | First-pass answer to `OQ-021`: no additional named outside subclass is ready inside the current repository. | A future module must name an exact subclass before source work begins. |
| `ART-GAP-003` | Possible Wu clique-reduction target not already covered by `FJ18` | `OQ-023` asks for this route, but no concrete noncovered graph/subclass is currently isolated. `FJ70` confirms that no current repository row supplies the required graph/subclass and clique-subgroup data. `FJ71` pauses the active Artin lane rather than continuing without a named payload. | likely `FJCw` if the source route applies; otherwise unknown. | candidate-filter row; no-current-candidate after `FJ70`; paused after `FJ71` | Sharpens `OQ-023`: the Wu route is inactive until a named payload appears. | Future use must satisfy `OBL-ARTIN-004`; otherwise use this row only as a paused pivot-comparison input. |
| `ART-FORM-001` | Formulation comparison between `FJCw`, `FICwF`, full \(\mathcal{FJ}\), and coefficient K-theory | First-pass policy supplied by `FJ02`; finite-index `FJCw` bridge supplied by `FJ47`. | formulation policy, not a group class. | formulation-safety row | Applies to both `OQ-021` and `OQ-023`. | Do not collapse source labels without a checked comparison. |

## FJ69 decision

`FJ69` completes the first-pass inventory required by `OBL-ARTIN-001`.

For the current repository state:

- `OQ-021` is first-pass resolved as an inventory question: the only
  recorded global gap is all Artin groups, and no additional named Artin
  subclass outside the `FJ18` rows is currently candidate-ready.
- `OQ-023` remains open but is sharpened: the next useful task is a Wu
  clique-reduction candidate filter, not a broad Artin source survey.
- The active bounded follow-up packet is `A-002`, Wu clique-reduction
  candidate filter for Artin gap rows.

## FJ70 candidate-filter decision

`FJ70` runs the Wu candidate filter against the current inventory and records
no current Wu-filter candidate.

| Filter row | Input row | Current status | Output |
|---|---|---|---|
| `WU-FILT-001` | `ART-COV-005` | already covered under the Wu source hypotheses recorded in `FJ18` | not a new candidate |
| `WU-FILT-002` | `ART-GAP-001` | global all-Artin row has no finite graph/subclass or clique inventory | exact source payload required before testing |
| `WU-FILT-003` | `ART-GAP-002` | no named outside subclass is recorded | no current candidate |
| `WU-FILT-004` | `ART-GAP-003` | no concrete noncovered graph/subclass with clique-subgroup data is isolated | no current Wu-filter candidate |

Minimum reactivation payload for the Wu lane:

- a named finite Artin graph, graph family, or subclass;
- the exact finite graph and positive even label hypotheses, or a checked
  correction of that hypothesis record;
- a clique list or clique-subgroup reduction statement;
- `FJCw` status, source payload, or source-status requirement for every
  relevant clique subgroup;
- an explanation that the full graph or subclass is not already covered by
  `ART-COV-001`--`ART-COV-006`;
- formulation-safety and prior-art-overlap notes.

`FJ70` completes `OBL-ARTIN-002` and records `OBL-ARTIN-003`: do not
reactivate the Wu clique-reduction lane without the payload above, or a
branch decision pausing/redirecting the active Artin packet.

## FJ71 branch decision

`FJ71` records the branch decision required by `OBL-ARTIN-003`.

For the current repository state, the active Artin proof/source lane is
paused. The repository does not contain a named noncovered Artin graph, graph
family, subclass, source theorem, bridge object, or changed project row that
would justify continuing the lane.

This pause does not resolve the global all-Artin gap. It records a stop
condition: future Artin modules may reactivate the lane only by satisfying
`OBL-ARTIN-004`, the Artin reactivation gate.

Minimum reactivation data after `FJ71`:

- a named finite Artin graph, graph family, subclass, source theorem, or
  bridge object;
- exact hypotheses and formulation label;
- the project row or open question changed;
- a prior-art-overlap note;
- source-status and APA citation data if a new external theorem is used.

## FJ72 pivot-refresh status

`FJ72` uses this ledger as an input to the target-pivot refresh and keeps the
Artin lane paused.

No row in this ledger currently supplies the `OBL-ARTIN-004` reactivation
payload. The covered rows remain usable only under their exact source
hypotheses; the global all-Artin row remains unresolved; the unnamed-subclass
and Wu candidate rows remain inactive until named payload data appears.

## FJ77 target-pivot readiness status

`FJ77` uses this ledger as an input after the foundational source-queue pause
and again keeps the Artin lane paused.

No named graph, graph family, subclass, source theorem, bridge object,
formulation label, prior-art-overlap note, or changed project object has
appeared since `FJ72`. Therefore `OBL-ARTIN-004` remains unsatisfied.

## FJ81 reactivation gate audit status

`FJ81` checks this ledger against `OBL-ARTIN-004` at the start of cycle 005.

No named graph, graph family, subclass, source theorem, bridge object,
formulation label, prior-art-overlap note, or changed project object has
appeared since the `FJ71` pause and later `FJ77` readiness check.

Therefore `OBL-ARTIN-004` remains unsatisfied. No active Artin update is
scheduled by `FJ81`; the Artin lane remains paused.

## Next update

No active Artin update is scheduled. Reactivate only through
`OBL-ARTIN-004`.
