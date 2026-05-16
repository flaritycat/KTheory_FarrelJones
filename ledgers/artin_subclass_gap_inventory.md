# Artin Subclass-Gap Inventory

## Status

Created by `FJ69`.

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
| `ART-GAP-003` | Possible Wu clique-reduction target not already covered by `FJ18` | `OQ-023` asks for this route, but no concrete noncovered graph/subclass is currently isolated. | likely `FJCw` if the source route applies; otherwise unknown. | candidate-filter row | Sharpens `OQ-023`: the next task is a candidate filter, not a source summary. | `FJ70` must either name a candidate from existing records or record no current Wu-filter candidate. |
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

## Next update

Begin `FJ70`, Wu Clique-Reduction Candidate Filter for Artin Gap Rows.
