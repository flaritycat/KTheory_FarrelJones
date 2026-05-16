# Module FJ47. FJCw Finite-Index Bridge Source Selection

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

`FJ02` supplied the additive-category source convention needed before
`RB-005` could resume. The remaining finite-index problem from `FJ45` is
whether the project has a version-compatible passage from a finite-index
subgroup to its ambient group.

The problem is to select the strongest source-verified bridge now available
without collapsing:

- plain coefficient K-theory FJC;
- coefficient K-theory FJC with finite wreath products (`FJCw`);
- full \(\mathcal{FJ}\);
- CAT(0)-route language;
- `FICwF`.

## Input

- `FJ02`, additive-category formulation and source-convention policy;
- `FJ12`, inheritance-properties ledger;
- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ27`, version-aware inheritance-route subtraction;
- `FJ45`, finite-index formulation bridge checkpoint;
- `FJ46`, source-convention decision;
- `OQ-032`, `OQ-060`, and `OQ-068`;
- Bartels--Lueck--Reich--Rueping (2014), especially Remark 6.2;
- Wang (2015), especially Theorems A and C;
- Reich--Varisco (2018), especially Theorem 27 and its proof discussion.

## Output target

A source-selection decision for `RB-005`:

- identify the finite-index bridge that is now usable;
- state its exact formulation and hypotheses;
- state which finite-index bridge remains unavailable;
- decide whether any `T-001` residual subtraction follows immediately;
- select the next bounded project move.

## Definitions

**Definition.** A plain coefficient finite-index overgroup bridge would say:
if \(H\leq G\) has finite index and \(H\) satisfies the K-theoretic
Farrell--Jones conjecture with coefficients in additive categories, then
\(G\) satisfies the same coefficient K-theory statement.

**Definition.** A finite-wreath finite-index overgroup bridge says: if
\(H\leq G\) has finite index and \(H\) satisfies the K-theoretic
Farrell--Jones conjecture with coefficients in additive categories and
finite wreath products, then \(G\) satisfies that same finite-wreath-product
version, and hence satisfies the coefficient K-theory statement after
forgetting the finite-wreath-product strengthening.

**Definition.** In this module, `FJCw bridge` means the finite-wreath
finite-index overgroup bridge above.

## Main work

### Plain coefficient bridge check

**Source-verified warning.** Wang treats finite-index overgroup closure for
the Farrell--Jones conjecture with coefficients in additive categories as a
problem, not as an unconditional theorem. The introduction asks whether, for
\(H<G\) of finite index, coefficient FJC for \(H\) implies coefficient FJC
for \(G\). Theorem A gives a conditional result depending on a separate
K- and L-theoretic induction problem. Theorem C reduces K-theoretic
finite-index overgroup closure to semidirect products by finite
hyperelementary groups (Wang, 2015).

**Route decision.** `FJ47` does not authorize the plain coefficient
finite-index overgroup bridge. Inside this project, that bridge remains
unavailable unless a later source proves it directly or supplies the missing
semidirect-product/reduction input.

### FJCw bridge check

**Source-verified claim.** Bartels--Lueck--Reich--Rueping record that the
Farrell--Jones conjecture with finite wreath products passes to finite-index
overgroups. Their proof uses the normal core \(N\) of the finite-index
subgroup and an embedding of the overgroup into a wreath product
\(N\wr(G/N)\), together with inheritance properties for the finite-wreath
version (Bartels et al., 2014, Remark 6.2).

**Source-verified claim.** Reich and Varisco summarize the state of the art
by saying that the inheritance properties in their theorem require the
version with coefficients in additive categories and finite wreath products;
their proof discussion points to Bartels--Lueck--Reich--Rueping, Section 6,
for the finite-wreath-product extensions (Reich & Varisco, 2018,
Theorem 27).

### Bridge table

| Candidate bridge | Source result | FJ47 decision | Route consequence |
|---|---|---|---|
| Plain coefficient finite-index overgroup bridge | Wang treats this as a problem/reduction; no unconditional theorem is imported. | Not usable. | A group with a finite-index coefficient-FJC subgroup may not be promoted by this bridge alone. |
| `FJCw` finite-index overgroup bridge | Bartels--Lueck--Reich--Rueping Remark 6.2 verifies finite-index overgroup passage for the finite-wreath-product version. | Usable, with the `FJCw` flag visible. | If a finite-index subgroup is recorded with `FJCw`, the ambient group may be recorded with `FJCw`, hence with coefficient K-theory FJC. |
| Full \(\mathcal{FJ}\) finite-index bridge | Already recorded from Lueck's survey and used in `FJ45`. | Still usable only in the full \(\mathcal{FJ}\) lane. | Do not identify it with the `FJCw` bridge unless a comparison source is checked. |
| Direct CAT(0) finite-extension bridge | Not checked in this module. | Not usable here. | A CAT(0)-route statement still needs either an `FJCw` known-case input or a direct finite-extension recognition source. |

### Consequence for RB-005

`FJ47` partially unblocks `RB-005`: finite-index overgroup passage is now
available for source rows that carry `FJCw`. It does not automatically apply
to every coefficient K-theory known case already in the repository.

The immediate next task is therefore not another abstract source-convention
module. It is an application audit: check which `RB-005` cases have
finite-index subgroups with `FJCw` already source-verified, and which still
only have plain coefficient K-theory or CAT(0)-route labels.

## Proposition / Theorem / Conjecture / Example

**Source-verified claim.** `FJCw` passes from finite-index subgroups to
finite-index overgroups, in the source sense of Bartels--Lueck--Reich--
Rueping.

**Route proposition.** Under the `FJ02` convention, `FJ47` authorizes the
following route and no stronger one:

If \(H\leq G\) has finite index and \(H\) is recorded as satisfying
K-theoretic Farrell--Jones with coefficients in additive categories and
finite wreath products, then \(G\) may be recorded as satisfying the same
finite-wreath-product version. Consequently \(G\) may also be used for the
plain coefficient K-theory route, with the stronger source label preserved.

**Proposition.** `FJ47` produces no new `T-001` residual subtraction by
itself.

## Proof or verification

The source-verified claim follows from Bartels--Lueck--Reich--Rueping
Remark 6.2. The cited argument takes a finite-index inclusion \(G\subseteq
G'\), forms the finite-index normal core \(N\), embeds \(G'\) in a wreath
product \(N\wr(G'/N)\), and then uses the inheritance properties of the
finite-wreath-product formulation.

The route proposition follows by combining that finite-wreath bridge with
the `FJ02` source convention: `FJCw` includes a coefficient K-theory
statement for the group itself, but the finite-wreath-product hypothesis must
remain visible in the ledger.

The no-subtraction proposition holds because this module checks a bridge
formulation only. It does not verify that any particular `RB-005` subgroup
has the needed `FJCw` input, and it does not prove a direct CAT(0)
finite-extension recognition statement.

## References

- Bartels, A., Lueck, W., Reich, H., & Rueping, H. (2014). K- and L-theory
  of group rings over \(GL_n(\mathbb Z)\). *Publications Mathematiques de
  l'IHES, 119*, 97--125. https://doi.org/10.1007/s10240-013-0055-0
- Reich, H., & Varisco, M. (2018). Algebraic K-theory, assembly maps,
  controlled algebra, and trace methods: A primer and a survey of the
  Farrell--Jones conjecture. In J. Bruening & M. Staudacher (Eds.),
  *Space--Time--Matter: Analytic and Geometric Structures* (pp. 1--50).
  De Gruyter. https://doi.org/10.1515/9783110452150-001
- Wang, K. (2015). *On passage to over-groups of finite indices of the
  Farrell-Jones conjecture* (arXiv:1512.01704). arXiv.
  https://arxiv.org/abs/1512.01704

Internal references:

- `modules/cycle_001/FJ02_additive_categories.md`
- `modules/cycle_003/FJ45_finite_index_formulation_bridge_checkpoint.md`
- `modules/cycle_003/FJ46_source_convention_decision_for_rb005.md`
- `ledgers/inheritance_properties.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ02`;
- `FJ12`;
- `FJ24`;
- `FJ27`;
- `FJ45`;
- `FJ46`;
- `OQ-032`;
- `OQ-060`;
- `OQ-068`.

## Results produced

This module produced:

- `ER-014. Source-verified FJCw finite-index overgroup bridge`;
- a first-pass resolution of `OQ-068`;
- a new route-use rule for `RB-005`: finite-index passage is now usable for
  `FJCw` inputs, not for plain coefficient-only inputs;
- a next target, `FJ48`, to audit which `RB-005` cases actually have
  `FJCw` input.

## Open questions generated

- `OQ-069`: Which `RB-005` cases have source-verified `FJCw` finite-index
  subgroup input, so that the `FJ47` bridge can be applied?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ47` and next
  `FJ48`;
- `SCOPE_LEDGER.md` for `ER-014`, `OQ-068`, and `OQ-069`;
- `NOTATION_LEDGER.md` for the `FJCw` finite-index bridge;
- `ESTABLISHED_RESULTS.md` for `ER-014`;
- `OPEN_QUESTIONS.md` for `OQ-068` and `OQ-069`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for the new sources;
- `ledgers/inheritance_properties.md` for the source-verified bridge;
- `ledgers/t001_residual.md`, `ledgers/theorem_dependencies.md`, and
  `ledgers/open_group_classes.md` for the return to `RB-005`;
- `references/papers_to_read.md` for the next task.
