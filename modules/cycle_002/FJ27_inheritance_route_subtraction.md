# Module FJ27. Inheritance-route subtraction for T-001

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

Continue the route-subtraction pass for `T-001`, the torsion-free
one-relator residual gap analysis.

`FJ23`--`FJ26` subtract the named routes through hyperbolic groups,
finite-dimensional CAT(0)-groups, virtually solvable groups, and
hyperbolic-by-cyclic/free-by-cyclic groups. The next question is what can be
removed by inheritance properties already recorded in `FJ12` and
`ledgers/inheritance_properties.md`.

The delicate point is version control. The inheritance ledger contains
coefficient K-theory rows, K-theory assembly rows with source-specific target
notation, and survey-level full \(\mathcal{FJ}\) rows. These should not be
merged into one unlabeled closure principle.

## Input

This module uses:

- `ER-010` and `FJ12`, the first inheritance-properties ledger;
- `ledgers/inheritance_properties.md`;
- `ER-012` and `FJ19`, the one-relator status ledger;
- `FJ23`, `FJ24`, `FJ25`, and `FJ26`, the completed named route
  subtractions;
- `OQ-037`;
- Bartels--Reich for coefficient pullback and subgroup inheritance;
- Bartels--Echterhoff--Lueck for K-theory directed-colimit inheritance;
- Lueck's 2025 survey for full \(\mathcal{FJ}\) inheritance rows.

## Output target

A first-pass inheritance-route subtraction table for `T-001`:

- which inheritance rows can be used as coefficient K-theory routes;
- which rows remain source-level full \(\mathcal{FJ}\) routes;
- which rows need extra bridge data before they remove any one-relator case;
- which rows are deferred because primary-source tracing or formulation
  reconciliation is still missing.

## Definitions

**Definition.** An inheritance-route subtraction is a project bookkeeping
step: a torsion-free one-relator group is removed from the active `T-001`
residual once the project has a source-verified inheritance row whose exact
hypotheses and version match the intended claim.

**Definition.** A coefficient K-theory inheritance route is an inheritance
route using a source statement for the K-theoretic Farrell--Jones conjecture
with coefficients in additive categories.

**Definition.** A full \(\mathcal{FJ}\) inheritance route is an inheritance
route using Lueck's source-specific class of groups satisfying the Full
Farrell--Jones Conjecture.

**Definition.** An inheritance bridge is a source-verified statement, or an
internal elementary proof, showing that a torsion-free one-relator group fits
the exact input pattern of an inheritance row.

**Warning.** An inheritance row is not a recognition theorem. For example,
the finite-index overgroup row can be used only after a finite-index subgroup
and its source-level Farrell--Jones status have been recorded.

**Warning.** Full \(\mathcal{FJ}\) rows are not silently converted into the
project's simplified ring-coefficient K-theory formulation. They may be
stronger source-level information, but this module keeps the source
formulation visible because `FJ02` is still deferred.

## Main work

### Route principle

**Source-verified claim.** Bartels and Reich prove pullback and subgroup
inheritance for the K-theoretic Farrell--Jones conjecture with coefficients
in additive categories. `FJ12` records the exact source flags and the
pullback-family notation (Bartels & Reich, 2007).

**Source-verified claim.** Bartels, Echterhoff, and Lueck prove
directed-colimit inheritance for the K-theoretic assembly statement in their
source convention, with different hypotheses for arbitrary directed systems
and injective directed systems. `FJ12` records these distinctions (Bartels et
al., 2007).

**Literature claim.** Lueck's survey records closure properties for the full
class \(\mathcal{FJ}\), including subgroups, finite direct products,
extensions, directed colimits, free products, finite-index overgroups, graph
products, and special extension rows with virtually torsion-free hyperbolic
or countable free kernels. `FJ12` records these as source-verified survey
statements with full-formulation flags (Lueck, 2025).

**Route principle.** Therefore, for `T-001`, an inheritance row subtracts a
remaining torsion-free one-relator group only when:

1. the group fits the exact source hypotheses;
2. the source status is recorded in the repository;
3. the version flag is preserved in the conclusion.

### Subtraction table

| Inheritance input | Version | FJ27 action |
|---|---|---|
| \(G\leq K\), where \(K\) has a source-verified coefficient K-theory Farrell--Jones statement over \(\mathcal{VCyc}\) | coefficient K-theory | Subtract \(G\) by subgroup inheritance, with the coefficient version flag. |
| \(G\) is obtained by a directed colimit satisfying the Bartels--Echterhoff--Lueck hypotheses | K-theory assembly in source convention | Subtract only after the directed system and the source hypotheses have been recorded. |
| \(G\) has a finite-index subgroup \(H\in\mathcal{FJ}\) | full \(\mathcal{FJ}\) survey row | Record a full \(\mathcal{FJ}\)-level subtraction by the finite-index overgroup row; do not relabel it as a coefficient K-theory proof without another source. |
| \(G\) fits \(1\to K\to G\to Q\to 1\), with \(K\) countable free and \(Q\in\mathcal{FJ}\) | full \(\mathcal{FJ}\) survey row | Record a full \(\mathcal{FJ}\)-level subtraction if the exact sequence and quotient status are source-verified. |
| \(G\) fits \(1\to K\to G\to Q\to 1\), with \(K\) virtually torsion-free hyperbolic and \(Q\in\mathcal{FJ}\) | full \(\mathcal{FJ}\) survey row | Record a full \(\mathcal{FJ}\)-level subtraction if the exact sequence and quotient status are source-verified. |
| \(G\) fits the general full \(\mathcal{FJ}\) extension row, including the preimage condition for infinite cyclic subgroups of \(Q\) | full \(\mathcal{FJ}\) survey row | Subtract only after the preimage condition is checked. |
| \(G\) is a free product, graph product, or finite direct product of known full \(\mathcal{FJ}\) groups | full \(\mathcal{FJ}\) survey row | Subtract only after the decomposition and factor statuses are source-verified. |
| \(G\) is merely related to a known class by analogy, hierarchy language, or an informal extension picture | no verified inheritance bridge | Do not subtract. |

### Interpretation for the T-001 residual

`FJ27` removes only torsion-free one-relator groups whose inheritance bridge is
actually recorded.

It does not remove:

- every subgroup mentioned in one-relator hierarchy sources;
- every virtually compact special group at the coefficient K-theory level;
- every HNN extension;
- every group with a countable free kernel unless the exact extension row and
  quotient status are recorded;
- every group suggested by closure-property analogy.

**Warning.** The residual after `FJ27` is not a class closed under failure of
inheritance. It is the class not yet removed by the project-recorded named
routes or inheritance routes.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group. If
\(G\leq K\) and the project has recorded the coefficient K-theoretic
Farrell--Jones statement for \(K\) with coefficients in additive categories
over \(\mathcal{VCyc}\), then \(G\) is removed from the `T-001` residual at
the coefficient K-theory level.

**Proof.** This is the subgroup inheritance row recorded in `FJ12` from
Bartels and Reich. The row says that the corresponding coefficient
K-theoretic assembly statement passes from \(K\) to every subgroup
\(G\leq K\). Thus \(G\) is covered at the same coefficient K-theory version
level and should not remain in the active residual for that version.

**Proposition.** Let \(G\) be a torsion-free one-relator group. If the project
has recorded a finite-index subgroup \(H\leq G\) with \(H\in\mathcal{FJ}\),
then \(G\) is removed from the `T-001` residual at the source-level full
\(\mathcal{FJ}\) version.

**Proof.** This is the finite-index overgroup row recorded in `FJ12` from
Lueck's survey. Since \(H\leq G\) has finite index and \(H\in\mathcal{FJ}\),
the survey row gives \(G\in\mathcal{FJ}\). The conclusion is deliberately
kept at the full \(\mathcal{FJ}\) source level.

**Warning.** The second proposition is useful for virtual routes such as
virtually compact special data, but it does not replace a coefficient
K-theory finite-index-overgroup theorem unless such a theorem is later
source-verified.

## Proof or verification

This module composes inheritance rows already recorded in the repository.

1. `FJ12` verified Bartels--Reich pullback and subgroup inheritance for the
   coefficient K-theory formulation.
2. `FJ12` verified Bartels--Echterhoff--Lueck directed-colimit inheritance
   with the source's distinction between arbitrary and injective directed
   systems.
3. `FJ12` recorded Lueck's survey list of full \(\mathcal{FJ}\) inheritance
   properties as source-verified survey statements.
4. `FJ27` does not trace the survey-level full \(\mathcal{FJ}\) rows back to
   primary proof sources. That remains `OQ-015`.

## References

- Bartels, A., Echterhoff, S., & Lueck, W. (2007). *Inheritance of
  isomorphism conjectures under colimits* (arXiv:math/0702460). arXiv.
  https://arxiv.org/abs/math/0702460
- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

## Dependencies

This module depends on:

- `ER-010` and `FJ12`;
- `ledgers/inheritance_properties.md`;
- `ER-012` and `FJ19`;
- `FJ23`;
- `FJ24`;
- `FJ25`;
- `FJ26`;
- `OQ-037`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-037`;
- a version-aware inheritance-route subtraction table for `T-001`;
- a warning that survey-level full \(\mathcal{FJ}\) rows remain labeled by
  source formulation;
- no new `ER-*` result.

## Open questions generated

- What is the residual `T-001` ledger after subtracting the named routes and
  version-aware inheritance routes?
- Which concrete surviving one-relator subclasses should become the next
  attack surface?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ27` status and next `FJ28`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the inheritance-route subtraction and next residual
  ledger question;
- `NOTATION_LEDGER.md` for inheritance-route terms;
- `OPEN_QUESTIONS.md` to mark `OQ-037` first-pass resolved and add the next
  residual question;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ27` source use;
- `ledgers/inheritance_properties.md` for `FJ27` route use;
- `ledgers/theorem_dependencies.md` for the completed `FJ27` row and next
  dependency row;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status.
