# Module FJ55. Primitive-Extension / Hierarchy-to-FJ Bridge Test

## Status

Completed

## Module type

Attack surface / Theorem map / Obstruction record

## Problem

`FJ54` selected the `RB-003` + `RB-004`/`RB-008` hybrid attack packet:
primitive-extension / hierarchy framework combined with explicit
kernel-control testing for concrete torsion-free one-relator candidate
families.

The first task is to decide whether the hierarchy / primitive-extension side
already gives an FJ route, a candidate family, a bridge lemma, or a documented
obstruction. This module must not become another source summary.

## Input

- `FJ22`, one-relator hierarchy vocabulary;
- `FJ23`, hyperbolic-route subtraction;
- `FJ24`, finite-dimensional CAT(0)-route subtraction;
- `FJ26`, hyperbolic-by-cyclic/free-by-cyclic route subtraction;
- `FJ27`, version-aware inheritance-route subtraction;
- `FJ28`, conservative `T-001` residual ledger;
- `FJ54`, residual-bucket checkpoint and hybrid-packet selection;
- `OQ-076`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_kernel_recognition.md`.

## Output target

A bridge-test decision:

- identify which hierarchy outputs already route through existing known-case
  machinery;
- identify which hierarchy outputs do not route;
- record the missing bridge as a proof obligation;
- decide whether `FJ56` should continue with kernel-control candidate
  inventory.

## Definitions

**Definition.** A hierarchy-to-FJ bridge is a source-verified or internally
proved implication from one-relator hierarchy data to one of the project's
approved route targets:

- word-hyperbolicity, for `FJ23`;
- finite-dimensional CAT(0) or compact finite-dimensional special input, for
  `FJ24`;
- virtual solvability, for `FJ25`;
- finite-rank free-by-cyclic or hyperbolic-by-cyclic structure, for `FJ26`;
- a version-safe inheritance configuration, for `FJ27`.

**Definition.** In this module, primitive-extension data is only project
shorthand for hierarchy / extension structure selected by `FJ54`. No theorem
under the name "primitive-extension bridge" is source-verified in the
repository.

**Warning.** The existence of a one-relator hierarchy is not itself a
Farrell--Jones theorem, an FJ route, or a residual subtraction.

## Main work

### Bridge test table

| Recorded hierarchy or extension datum | Existing route if hypotheses are verified | FJ55 decision | Next proof obligation |
|---|---|---|---|
| Existence of a finite one-relator hierarchy | None by itself | Not a route. This remains `RB-003` structure only. | Add a bridge to hyperbolicity, CAT(0), virtual solvability, kernel control, or inheritance. |
| Acylindrical hierarchy | `FJ23`, through the Linton hyperbolicity bridge recorded in `FJ22` and used in `FJ23` | Route exists only after acylindricity is verified for a concrete candidate. It is not new residual subtraction beyond the hyperbolic route. | Candidate row must record the acylindricity source or computation. |
| \(\mathbb Z\)-stable hierarchy with no Baumslag--Solitar subgroup | `FJ23`, through the Linton main-equivalence bridge recorded in `FJ22` | Route exists only after both hypotheses are verified. It is hyperbolic-route overlap. | Candidate row must record both \(\mathbb Z\)-stability and Baumslag--Solitar exclusion. |
| Negative immersions / \(\pi(w)>2\) input | `FJ23`, via `FJ22`, `FJ52`, and WIP / provisional `FJ53` | Demoted as `RB-006` progress; usable only as hyperbolic-route overlap. | Do not reactivate `RB-006` without a non-hyperbolic bridge. |
| Virtual specialness bundled with hyperbolicity | Usually already hyperbolic-route overlap in the current Linton rows | Not an independent `RB-005` or `RB-006` subtraction. | Needs a concrete finite-index / `FJCw` or CAT(0)-route formulation bridge before use beyond `FJ23`. |
| HNN splitting or epimorphism to \(\mathbb Z\) from hierarchy data | Possible `FJ26` route after kernel control | Not a route by itself. This is the live `RB-004`/`RB-008` interface. | Candidate row must record epimorphism, kernel type, and extension theorem candidate. |
| Countable free or otherwise uncontrolled kernel | Possible inheritance route only with exact source-version data | Not currently routable. | Candidate row must record exact sequence, quotient status, and formulation safety. |

### Obstruction record

**Obstruction OBL-T001-001.** Current repository data contains no direct
hierarchy-to-FJ bridge.

The only licensed hierarchy uses are route-through outputs:

- hyperbolicity, hence `FJ23`;
- finite-dimensional CAT(0) or compact special input, hence `FJ24` or a
  formulation-sensitive finite-index lane;
- finite-rank free or hyperbolic kernel extension data, hence `FJ26`;
- exact version-safe inheritance data, hence `FJ27`.

Thus `RB-003` cannot advance as a standalone source lane. It must be paired
with candidate-level kernel-control or extension data.

### Candidate-inventory effect

`FJ55` does not add a fabricated group candidate. It adds a proof-obligation
section to `ledgers/t001_candidate_inventory.md`:

- `OBL-T001-001`: no direct hierarchy-to-FJ bridge currently recorded;
- `OBL-T001-002`: every future hybrid candidate must state which route output
  it seeks before source work begins.

## Proposition / Theorem / Conjecture / Example

**Proposition.** With the current repository data, one-relator hierarchy
existence alone does not remove any case from the `T-001` residual.

**Route decision.** `FJ55` resolves `OQ-076` at first pass by recording
`OBL-T001-001` and sending the project to `FJ56`, Kernel-Control Candidate
Inventory.

**Warning.** This module does not claim that hierarchy methods cannot lead to
a future Farrell--Jones route. It records only that no such direct route is
currently available inside the repository.

## Proof or verification

`FJ22` records Linton's hierarchy theorem and downstream route vocabulary as
group-theoretic source data, while warning that it is not a Farrell--Jones
theorem. `FJ23` records the precise use of hierarchy data when it supplies
hyperbolicity. `FJ24`, `FJ26`, and `FJ27` record the other approved route
targets and their required hypotheses. None of these modules licenses bare
hierarchy existence, HNN splitting, or epimorphism to \(\mathbb Z\) as an FJ
route.

Therefore hierarchy data becomes useful only after it produces one of the
approved route outputs. The only live route-output interface for the selected
hybrid packet is kernel-control / extension testing, so the next module should
be `FJ56`.

## References

No new external source was checked in this module.

Existing APA-style sources used through prior repository verification:

- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic Farrell-Jones
  conjecture for hyperbolic groups. *Inventiones Mathematicae, 172*(1),
  29--70. https://doi.org/10.1007/s00222-007-0093-7
- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell-Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904. https://doi.org/10.1093/imrn/rnac012
- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324

Internal references:

- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`
- `modules/cycle_002/FJ28_residual_ledger_after_route_subtractions.md`
- `modules/cycle_003/FJ54_residual_bucket_checkpoint_after_rb006.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ22`;
- `FJ23`;
- `FJ24`;
- `FJ26`;
- `FJ27`;
- `FJ28`;
- `FJ54`;
- `OQ-076`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-076`;
- `OBL-T001-001`, the direct hierarchy-to-FJ bridge obstruction;
- `OBL-T001-002`, the required route-output declaration for future hybrid
  candidates;
- a decision to continue with `FJ56`, Kernel-Control Candidate Inventory;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-077`: Which repository-supported candidate rows can receive explicit
  kernel-control data for the `RB-003` + `RB-004`/`RB-008` hybrid packet?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ55` and next `FJ56`;
- `SCOPE_LEDGER.md` for the `OQ-076` resolution and new `OQ-077`;
- `OPEN_QUESTIONS.md` for `OQ-076` and `OQ-077`;
- `NOTATION_LEDGER.md` for the bridge-test and proof-obligation terms;
- `ledgers/t001_candidate_inventory.md` for `OBL-T001-001` and
  `OBL-T001-002`;
- `ledgers/t001_residual.md`, `ledgers/theorem_dependencies.md`, and
  `ledgers/open_group_classes.md` for the current target update;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ55` source-use
  notes;
- `references/papers_to_read.md` for the next task.
