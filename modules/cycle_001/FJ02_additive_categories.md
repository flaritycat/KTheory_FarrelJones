# Module FJ02. Additive-Category Formulation and Source Conventions

## Status

Completed

## Module type

Definition / Literature verification / Theorem map

## Problem

`FJ01` introduced a simplified ring-coefficient K-theoretic
Farrell--Jones assembly map as a black box. Later modules repeatedly used
source-level phrases such as "with coefficients in additive categories",
`FJCw`, `FICwF`, and full \(\mathcal{FJ}\). `FJ46` determined that these
phrases had become proof-level inputs for `RB-005`.

The problem is to record a first-pass modern additive-category formulation
and a source-convention policy without pretending that all source labels are
interchangeable.

## Input

- `FJ01`, simplified ring-coefficient formulation;
- `FJ11`, known-classes source flags;
- `FJ12`, inheritance properties with coefficient and full
  \(\mathcal{FJ}\) rows;
- `FJ18`, `FJCw` and `FICwF` source-level Artin flags;
- `FJ45`, finite-index formulation bridge checkpoint;
- `FJ46`, source-convention interruption decision;
- Bartels--Reich (2007), especially Definitions 2.1 and 3.1,
  Conjecture 3.2, Remark 3.3, Corollary 4.3, Theorem 4.5, and
  Proposition 4.6.

## Output target

A first-pass project convention for:

- additive categories with group action;
- the category \(\mathcal A *_G T\);
- the Or\(G\)-spectrum \(K_{\mathcal A}\);
- the K-theoretic Farrell--Jones conjecture with coefficients;
- the relationship to the simplified ring-coefficient formulation;
- how source labels such as `FJCw`, `FICwF`, and full
  \(\mathcal{FJ}\) may be used inside the project.

## Definitions

**Definition.** An additive category with right \(G\)-action is an additive
category \(\mathcal A\) equipped with additive covariant functors
\[
g^*\colon \mathcal A\to\mathcal A
\]
for \(g\in G\), satisfying the identity and multiplication compatibility
specified in Bartels--Reich (2007, Definition 2.1).

**Definition.** If \(T\) is a left \(G\)-set and \(\mathcal A\) is an
additive category with right \(G\)-action, then
\(\mathcal A *_G T\) denotes the additive category from Bartels--Reich
(2007, Definition 2.1). Its objects are finitely supported \(T\)-indexed
families of objects of \(\mathcal A\), and its morphisms record the
group-action data needed to assemble over \(G\)-orbits.

**Definition.** The Or\(G\)-spectrum \(K_{\mathcal A}\) is defined by
\[
K_{\mathcal A}(T)=K^{-\infty}(\mathcal A *_G T),
\]
following Bartels--Reich (2007, Definition 3.1).

**Definition.** The K-theoretic Farrell--Jones conjecture with coefficients
in additive categories says: for every group \(G\), every additive category
\(\mathcal A\) with right \(G\)-action, and the family
\(\mathcal{VCyc}\) of virtually cyclic subgroups of \(G\), the assembly map
\[
H_*^G(E_{\mathcal{VCyc}}G;K_{\mathcal A})
\longrightarrow
H_*^G(\mathrm{pt};K_{\mathcal A})
\]
is an isomorphism (Bartels & Reich, 2007, Conjecture 3.2).

**Definition.** In this project, `coefficient K-theory FJC` means the
K-theoretic Farrell--Jones conjecture with coefficients in additive
categories in the preceding Bartels--Reich sense, unless a later module
records a different source convention explicitly.

## Main work

### Source-verified formulation

**Source-verified claim.** Bartels and Reich define the coefficient version
using additive categories with right group action, the category
\(\mathcal A *_G T\), the nonconnective K-theory spectrum
\(K_{\mathcal A}\), and the assembly map over
\(E_{\mathcal{VCyc}}G\) (Bartels & Reich, 2007).

**Source-verified claim.** Bartels and Reich state that when
\(\mathcal A=R^\oplus\), the resulting formulation recovers the usual
Farrell--Jones conjecture in the Davis--Lueck formulation, and hence it
supports the simplified ring-coefficient viewpoint used in `FJ01`, modulo
the black-box homology normalization already declared there (Bartels &
Reich, 2007, Remark 3.3).

**Source-verified claim.** The coefficient formulation has the inheritance
properties recorded earlier in `FJ12`: pullback along group homomorphisms,
subgroup inheritance, and separate inheritance of injectivity and
surjectivity (Bartels & Reich, 2007, Corollary 4.3 and Theorem 4.5).

### Source-convention policy

**Route policy.** A source theorem stated as `coefficient K-theory FJC` may
be used as a project K-theory route only with the additive-category
coefficient flag preserved.

**Route policy.** A source theorem stated as `FJCw` may be used only with
its finite-wreath-product and additive-category flags preserved, unless a
later module checks that the source explicitly implies the desired weaker
project statement.

**Route policy.** A source theorem stated as `FICwF` remains a source-level
flag. It is not automatically identified with `FJCw`, full
\(\mathcal{FJ}\), or the simplified ring-coefficient statement. If a later
module needs it proof-sensitively, it must check the source's exact K-, L-,
A-theory, coefficient, and finite-wreath-product conventions.

**Route policy.** A source theorem stated for full \(\mathcal{FJ}\) remains
in that source-level full-formulation lane. It is not automatically
converted into a coefficient K-theory theorem, or conversely, without a
checked comparison source.

**Route policy.** The simplified ring-coefficient formulation from `FJ01`
is now treated as a specialization target of the coefficient formulation.
When a source theorem proves coefficient K-theory FJC for a group, the
project may use it for the simplified ring-coefficient K-theory route, while
recording that the source result is stronger and additive-category-level.

### Consequence for RB-005

`FJ02` removes the main source-convention obstruction identified in `FJ46`,
but it does not by itself supply a coefficient finite-index overgroup
theorem.

Therefore `RB-005` should resume with a narrower task: select or verify a
source for coefficient K-theory finite-index overgroup passage, or record
that only the full \(\mathcal{FJ}\) finite-index row remains available.

## Proposition / Theorem / Conjecture / Example

**Source-verified claim.** The project adopts Bartels--Reich Conjecture 3.2
as its first-pass canonical K-theoretic Farrell--Jones formulation with
coefficients in additive categories.

**Proposition.** Under the `FJ02` convention, source labels are not
automatically collapsed: coefficient K-theory FJC, full \(\mathcal{FJ}\),
`FJCw`, `FICwF`, and simplified ring-coefficient FJ remain separate route
labels unless a source comparison is checked.

## Proof or verification

The source-verified claim follows from Bartels--Reich Definitions 2.1 and
3.1 and Conjecture 3.2. Those source passages define the additive
coefficient category, the Or\(G\)-spectrum \(K_{\mathcal A}\), and the
assembly map over \(E_{\mathcal{VCyc}}G\).

The proposition is a project bookkeeping rule forced by the source checks.
Bartels--Reich supplies a precise coefficient K-theory formulation and
states its relationship to the ordinary conjecture in the case
\(\mathcal A=R^\oplus\). `FJ18`, however, records `FJCw` and `FICwF` as
source-level labels from different articles, and `FJ45` records full
\(\mathcal{FJ}\) as a survey-level source class. Therefore these labels
must remain visible until a later source comparison is checked.

## References

- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004

Internal references:

- `modules/cycle_001/FJ01_minimal_statement.md`
- `modules/cycle_001/FJ11_known_classes_ledger.md`
- `modules/cycle_001/FJ12_inheritance_properties_ledger.md`
- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_003/FJ45_finite_index_formulation_bridge_checkpoint.md`
- `modules/cycle_003/FJ46_source_convention_decision_for_rb005.md`
- `ledgers/inheritance_properties.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ01`;
- `FJ11`;
- `FJ12`;
- `FJ18`;
- `FJ45`;
- `FJ46`;
- `OQ-002`;
- `OQ-003`;
- `OQ-022`;
- `OQ-067`.

## Results produced

This module produced:

- `ER-013. Source-verified additive-category K-theory formulation and
  source-convention policy`;
- a first-pass resolution of `OQ-002`;
- a first-pass resolution of `OQ-022`;
- a partial resolution of `OQ-003`;
- a return path from the `FJ02` interruption to `RB-005`.

## Open questions generated

- `OQ-068`: Which source verifies a coefficient K-theory finite-index
  overgroup bridge under the `FJ02` convention?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for the completed `FJ02`;
- `SCOPE_LEDGER.md` for `ER-013`, `OQ-002`, `OQ-003`, `OQ-022`, and
  `OQ-068`;
- `NOTATION_LEDGER.md` for additive-category formulation notation;
- `ESTABLISHED_RESULTS.md` for `ER-013`;
- `OPEN_QUESTIONS.md` for resolved and generated questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for source status;
- `ledgers/inheritance_properties.md` and `ledgers/known_classes.md` for the
  now-active convention;
- `ledgers/t001_residual.md`, `ledgers/theorem_dependencies.md`, and
  `ledgers/open_group_classes.md` for the return to `RB-005`;
- `references/papers_to_read.md` for the next task.
