# Module FJ15. Controlled topology primer

## Status

Completed

## Module type

Technique / Literature verification / Vocabulary primer

## Problem

Extract the controlled-topology and controlled-algebra vocabulary needed to read the proof skeletons in `FJ13` and `FJ14` without pretending to reconstruct the full proof machinery inside this repository.

## Input

- `FJ13` for the hyperbolic-groups proof skeleton.
- `FJ14` for the CAT(0)-groups proof skeleton.
- Wegner's obstruction-category review in the CAT(0)-groups paper.

## Output target

A reusable primer explaining:

- why assembly proofs introduce control spaces;
- what the obstruction category is meant to measure;
- what "controlled morphism" means at a first-pass level;
- how replacing `\mathrm{pt}` by a metric control space creates room for transfers and contraction;
- which controlled-topology topics remain outside the active K-theory proof path.

## Definitions

### Definition. Control space

In the source setup used by Wegner, a control space is a metric space `(Y,d_Y)` with an isometric `G`-action. The obstruction category is built over

```text
G x X x Y x [1,infinity),
```

where `X` is a `G`-space and `Y` supplies metric control.

### Definition. Obstruction category

For a `G`-space `X`, a metric `G`-space `(Y,d_Y)`, and a small additive category `\mathcal A` with strict right `G`-action, Wegner defines an additive obstruction category

```text
\mathcal O^G(X,(Y,d_Y);\mathcal A).
```

Objects are locally finite families of objects of `\mathcal A` indexed by `G x X x Y x [1,infinity)`, satisfying support and equivariance conditions. Morphisms are matrices of morphisms in `\mathcal A` whose nonzero entries satisfy finiteness, equivariance, and control conditions.

### Definition. Controlled morphism

At the level needed here, a morphism in the obstruction category is controlled when its nonzero matrix entries are bounded in three source-visible ways:

- only finitely many group displacements `g^{-1}g'` may occur;
- the `Y`-distance between source and target indices is bounded;
- the `[1,\infty)` coordinate changes by a bounded amount.

There is also an equivariant continuous control condition in the `X x [1,\infty)` direction. This module records that condition as source-level proof technology and does not reproduce its full definition.

### Definition. Controlled map

Wegner records a functoriality condition for maps of control spaces: a `G`-equivariant map `f:Y\to Y'` induces a functor on obstruction categories if, for every `r>0`, there is an `R>0` such that

```text
d_Y(y_1,y_2)<r  implies  d_{Y'}(f(y_1),f(y_2))<R.
```

This is the first control convention FJ15 will use.

### Warning. Controlled topology versus controlled algebra

The project charter names this module "controlled topology primer." In the checked K-theory sources for `FJ13` and `FJ14`, the active mechanism is controlled algebra: additive categories, controlled morphisms, obstruction categories, transfers, and vanishing of obstruction-category K-groups. Controlled h-cobordisms and surgery-theoretic controlled topology are not introduced here.

## Main work

### The proof pattern

The controlled proof skeleton in `FJ13` and `FJ14` can be read as:

1. Start with the assembly map induced by `E_\mathcal F G\to\mathrm{pt}`.
2. Encode the obstruction to the assembly map being an isomorphism in the K-theory of an obstruction category.
3. Replace the one-point control space by a more useful metric space `Y`.
4. Use transfers to move objects into the larger controlled setting.
5. Use covers, contraction, and stability to gain control.
6. Prove the relevant obstruction-category K-groups vanish.

This is why the proof skeletons keep saying that one needs "room" for constructions. The point has no geometry. A compactified Rips complex, a large CAT(0) ball, or a sequence of metric spaces has geometry that can be exploited.

### Point control and metric control

The target obstruction category for assembly is

```text
\mathcal O^G(E_\mathcal F G,\mathrm{pt};\mathcal A).
```

Wegner records that vanishing of its K-groups in the relevant range implies the assembly map is an isomorphism in all degrees, citing the Bartels--Lueck--Reich obstruction-category proposition.

However, proofs rarely work directly over `\mathrm{pt}`. Wegner explicitly says the reason to study

```text
\mathcal O^G(E_\mathcal F G,(Y,d_Y);\mathcal A)
```

for nontrivial metric spaces `Y` is that such spaces give room for the constructions used to prove vanishing.

### What "gain control" means here

**Heuristic.** A proof gains control when it replaces a problem about arbitrary algebraic data by a problem where nonzero morphisms are forced to stay close with respect to chosen geometric coordinates.

In the source proof architecture, the gain-control mechanism is not just a slogan. It is implemented by:

- choosing control spaces with enough geometry;
- imposing boundedness conditions on morphism matrices;
- constructing transfers into larger controlled categories;
- using open covers and contracting maps to make images small;
- applying a stability or vanishing theorem to the obstruction category.

### Hyperbolic and CAT(0) comparison

| Role | Hyperbolic proof skeleton | CAT(0) proof skeleton |
| --- | --- | --- |
| Control space with geometry | Compactified Rips complex `\overline X`. | Large closed CAT(0) balls and related metric spaces. |
| Cover source | Wide covers for hyperbolic groups. | Flow-space covers for CAT(0)-groups. |
| Transfer issue | Uses the equivariant setup from the hyperbolic proof. | Requires strong homotopy actions because closed CAT(0) balls are not generally `G`-spaces. |
| Obstruction target | Vanishing of `K_*(\mathcal O^G(E_\mathcal F G,\mathrm{pt};\mathcal A))`. | Same obstruction-category target, with different transfer geometry. |
| Deferred details | Wide covers, stability, transfer construction. | Flow spaces, strong homotopy actions, transfer construction. |

### What FJ15 does not establish

FJ15 does not prove an assembly theorem, a stability theorem, or a vanishing theorem. It also does not define controlled h-cobordisms, because no checked h-cobordism source is active in the K-theory proof path at this point.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim. Obstruction-category reduction

Wegner records that if

```text
K_m(\mathcal O^G(E_\mathcal F G,\mathrm{pt};\mathcal A)) = 0
```

for all sufficiently large `m` and all additive `G`-categories `\mathcal A`, then the corresponding assembly map is an isomorphism in all degrees. Wegner cites Bartels--Lueck--Reich for this proposition.

### Heuristic. Geometry creates control

The controlled proof strategy replaces the point by a metric control space because metric geometry can force morphisms into bounded or contracting patterns. This is a heuristic summary of the source proof architecture, not an independent theorem.

## Proof or verification

This module checked the following source locations in Wegner:

- the introduction, where the obstruction category is identified as the K-theoretic homotopy-fiber mechanism for assembly;
- the statement that transfers replace the one-point space by suitable metric spaces;
- the obstruction-category definition over `G x X x Y x [1,\infty)`;
- the control conditions on morphisms in that category;
- the functoriality condition for maps of metric control spaces;
- the proposition that vanishing of the obstruction category implies the assembly isomorphism, cited there to Bartels--Lueck--Reich;
- the statement that nontrivial metric spaces are studied because they give room for constructions.

**Warning.** The Bartels--Lueck--Reich proposition cited by Wegner has not been reverified directly in FJ15. This remains part of OQ-016.

## References

- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic Farrell-Jones conjecture for hyperbolic groups. *Inventiones Mathematicae, 172*(1), 29--70. https://doi.org/10.1007/s00222-007-0093-7
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3), 779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

## Dependencies

This module depends on:

- `FJ01`: assembly-map target and nonconnective K-theory convention.
- `FJ03`: classifying spaces for families.
- `FJ13`: hyperbolic proof skeleton and obstruction-category boundary.
- `FJ14`: CAT(0) proof skeleton and transfer/control boundary.

## Results produced

This module produced:

- A first controlled-algebra vocabulary bridge for reading `FJ13`, `FJ14`, `FJ16`, and `FJ17`.
- A warning that controlled h-cobordism is not yet active.
- A source-tracked obstruction-category reduction note.

## Open questions generated

- OQ-018. Which primary source should be adopted as the canonical project reference for obstruction categories and continuous-control conditions before `FJ17` uses them proof-sensitively?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` to mark FJ15 complete and set FJ16 as next.
- `README.md` to show progress through FJ15.
- `SCOPE_LEDGER.md` to record the controlled-algebra primer and next scope.
- `NOTATION_LEDGER.md` for the general obstruction-category and control-space notation.
- `OPEN_QUESTIONS.md` for OQ-018.
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Wegner's obstruction-category review.
