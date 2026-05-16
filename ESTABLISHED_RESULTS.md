# Established Results

## ER-001. Trivial group case of the simplified K-theoretic Farrell--Jones assembly map

### Status

Proposition, proved inside project.

### Statement

Let \(R\) be an associative unital ring and let \(G=1\) be the trivial group. In the simplified ring-coefficient formulation of module `FJ01`, the assembly map

\[
H_n^1(E_{\mathcal{VCyc}}1;\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R)
\cong K_n(R)
\]

is the identity map on \(K_n(R)\) for every \(n\in\mathbb Z\), assuming the black-box normalization of the equivariant homology theory used in `FJ01`.

### Proof locations

`modules/cycle_001/FJ01_minimal_statement.md`

Standalone expansion:

`modules/cycle_001/FJ05_trivial_group_example.md`

### Assumptions

- \(R\) is an associative unital ring.
- \(G=1\) is the trivial discrete group.
- \(H_n^G(-;\mathbf K_R)\) is normalized so that \(H_n^G(G/H;\mathbf K_R)\cong K_n(R[H])\).
- The point is used as a model for \(E_{\mathcal{VCyc}}1\).

### Source status

The proof is internal once the black-box equivariant homology normalization is accepted. The normalization itself remains a source-to-verify item for later modules.

## ER-002. Existence and homotopy characterization of classifying spaces for families

### Status

Source-verified theorem for project use.

### Statement

Let \(G\) be a discrete group and let \(\mathcal F\) be a project-style family of subgroups of \(G\), meaning that \(\mathcal F\) is closed under conjugation and passage to subgroups.

There exists a model for \(E_{\mathcal F}G\). It is unique up to \(G\)-homotopy equivalence in the sense that it is terminal in the \(G\)-homotopy category of \(G\)-CW complexes whose isotropy groups belong to \(\mathcal F\). If \(\mathcal F_0\subseteq\mathcal F_1\), then there is, up to \(G\)-homotopy, precisely one \(G\)-map

\[
E_{\mathcal F_0}G\longrightarrow E_{\mathcal F_1}G.
\]

In Lueck's source formulation, a \(G\)-CW complex \(X\) is a model for \(E_{\mathcal F}G\) if and only if all isotropy groups of \(X\) belong to \(\mathcal F\) and \(X^H\) is weakly contractible for each \(H\in\mathcal F\). Module `FJ74` records the project convention `FND-CONV-001`: the contractible/empty fixed-point formulation is a strict readable model convention, while this weakly contractible plus isotropy formulation remains the source-level criterion.

### Proof location

`modules/cycle_001/FJ03_classifying_spaces_for_families.md`

### Assumptions

- \(G\) is a discrete group.
- \(\mathcal F\) is closed under conjugation and passage to subgroups.
- The source theorem is applied in the \(G\)-CW setting.

### Source status

Source-verified from Lueck, *Survey on Classifying Spaces for Families of Subgroups*, Definition 1.8 and Theorem 1.9. The module records the source's weak-contractibility formulation rather than silently replacing it with a stronger contractibility claim.

## ER-003. The virtually cyclic subgroups form a family

### Status

Proposition, proved inside project, using source-verified structure for context.

### Statement

For every group \(G\), the collection

\[
\mathcal{VCyc}(G)=\{V\leq G:V\text{ is virtually cyclic}\}
\]

is closed under conjugation and passage to subgroups. Hence \(\mathcal{VCyc}(G)\) is a family of subgroups in the project sense.

The same module records the source-verified dichotomy that an infinite virtually cyclic group maps with finite kernel either onto \(\mathbb Z\) or onto \(D_\infty=\mathbb Z/2 * \mathbb Z/2\).

### Proof location

`modules/cycle_001/FJ04_virtually_cyclic_groups.md`

### Assumptions

- \(G\) is a discrete group.
- Virtually cyclic means finite or containing an infinite cyclic subgroup of finite index.

### Source status

The family property is proved internally. The infinite virtually cyclic dichotomy is source-verified from Lueck--Reich, with the original proof source Farrell--Jones 1995 still marked `to verify`.

## ER-004. Infinite cyclic group case of the simplified assembly map

### Status

Proposition, proved inside project.

### Statement

Let \(R\) be an associative unital ring and let \(G=\mathbb Z\). In the simplified ring-coefficient formulation of module `FJ01`, the assembly map

\[
H_n^{\mathbb Z}(E_{\mathcal{VCyc}}\mathbb Z;\mathbf K_R)
\longrightarrow
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R)
\cong K_n(R[\mathbb Z])
\]

is the identity map after choosing \(\mathrm{pt}\) as a model for \(E_{\mathcal{VCyc}}\mathbb Z\). After choosing a generator \(t\) of \(\mathbb Z\), the standard identification

\[
R[\mathbb Z]\cong R[t,t^{-1}],
\]

identifies the target with \(K_n(R[t,t^{-1}])\).

### Proof location

`modules/cycle_001/FJ06_infinite_cyclic_group_example.md`

### Assumptions

- \(R\) is an associative unital ring.
- \(G=\mathbb Z\).
- \(H_n^G(-;\mathbf K_R)\) is normalized so that \(H_n^G(G/H;\mathbf K_R)\cong K_n(R[H])\).
- The all-degree statement uses the same nonconnective \(K\)-theory convention as `FJ01`.

### Source status

The proof is internal once the black-box equivariant homology normalization is accepted. This result does not invoke Bass--Heller--Swan.

## ER-005. Bass--Heller--Swan decomposition for the infinite cyclic group-ring target

### Status

Source-verified theorem for project use, not proved inside project.

### Statement

Let \(R\) be an associative unital ring and choose a generator \(t\) of \(\mathbb Z\). For every \(n\) in the \(K\)-theory conventions used by Weibel, the Bass--Heller--Swan fundamental theorem gives

\[
K_n(R[\mathbb Z])
\cong
K_n(R)\oplus K_{n-1}(R)\oplus NK_n(R)\oplus NK_n(R),
\]

where

\[
NK_n(R)=\operatorname{coker}\bigl(K_n(R)\to K_n(R[t])\bigr).
\]

The two \(NK_n(R)\)-summands correspond to the positive and negative Laurent directions.

### Proof location

`modules/cycle_001/FJ07_bass_heller_swan_nil_terms.md`

### Assumptions

- \(R\) is an associative unital ring.
- \(R[\mathbb Z]\) is identified with \(R[t,t^{-1}]\) after choosing a generator of \(\mathbb Z\).
- The \(K\)-theory convention is the one used in Weibel's Chapter V, Section 8.

### Source status

Source-verified from Weibel, C. A. (2013). *The K-book: An introduction to algebraic K-theory*, Chapter V, Theorems 8.1 and 8.2. Lueck and Reich (2004), Remark 1.15 and Subsection 2.2.5, are used for the Farrell--Jones interpretation of Nil-terms.

## ER-006. Conditional Whitehead-group vanishing from Farrell--Jones

### Status

Source-verified theorem map, conditional on the relevant K-theoretic Farrell--Jones statement.

### Statement

Let \(G\) be torsion free and let \(R\) be regular. Assume the K-theoretic Farrell--Jones assembly statement in the torsion-free regular-ring form used by Lueck and Reich. Then

\[
\mathrm{Wh}_0^R(G)=0
\qquad\text{and}\qquad
\mathrm{Wh}_1^R(G)=0.
\]

In particular, for \(R=\mathbb Z\),

\[
\widetilde K_0(\mathbb Z[G])=0
\qquad\text{and}\qquad
\mathrm{Wh}(G)=0.
\]

### Proof location

`modules/cycle_001/FJ08_whitehead_group_consequence.md`

### Assumptions

- \(G\) is torsion free.
- \(R\) is regular in the sense used by Lueck--Reich.
- The relevant K-theoretic Farrell--Jones statement holds for \(G\) and \(R\).
- The definitions of \(A_0\), \(A_1\), \(\mathrm{Wh}_0^R(G)\), and \(\mathrm{Wh}_1^R(G)\) are those used in Lueck--Reich.

### Source status

Source-verified from Lueck, W., and Reich, H. (2004), Section 1.1, Section 1.3, Proposition 2.10, and Corollary 2.11.

## ER-007. Conditional projective class group and finiteness-obstruction consequence

### Status

Source-verified theorem map, conditional on the relevant K-theoretic Farrell--Jones statement.

### Statement

Let \(G\) be torsion free. Assume the K-theoretic Farrell--Jones assembly statement in the torsion-free regular-ring form used by Lueck and Reich for \(R=\mathbb Z\). Then

\[
\widetilde K_0(\mathbb Z[G])=0.
\]

If, in addition, \(G\) is finitely presented, then every finitely dominated CW complex \(X\) with \(\pi_1(X)\cong G\) is homotopy equivalent to a finite CW complex.

### Proof location

`modules/cycle_001/FJ09_projective_class_group_consequence.md`

### Assumptions

- \(G\) is torsion free.
- \(R=\mathbb Z\), which is regular in the sense used by Lueck--Reich.
- The relevant K-theoretic Farrell--Jones statement holds for \(G\).
- The geometric finiteness-obstruction consequence also assumes \(G\) is finitely presented.

### Source status

Source-verified from Lueck, W., and Reich, H. (2004), Section 1.1, Theorem 1.8, and Consequence 1.9. The proof uses ER-006 for the algebraic Farrell--Jones implication.

## ER-008. Conditional Borel consequence from K-theory vanishing and L-theory assembly

### Status

Source-verified theorem map, conditional on low-dimensional K-theory vanishing and the \(L^{\langle -\infty\rangle}\)-theory assembly isomorphism.

### Statement

Let \(G\) be torsion free. Assume:

- \(\mathrm{Wh}(G)=0\);
- \(\widetilde K_0(\mathbb Z[G])=0\);
- \(K_{-i}(\mathbb Z[G])=0\) for all \(i\geq 1\);
- the assembly map

\[
H_n(BG;\mathbf L^{\langle -\infty\rangle}(\mathbb Z))
\longrightarrow
L_n^{\langle -\infty\rangle}(\mathbb ZG)
\]

is an isomorphism for every \(n\in\mathbb Z\).

Then the Borel conjecture holds for all orientable closed aspherical topological manifolds of dimension at least \(5\) with fundamental group \(G\).

### Proof location

`modules/cycle_001/FJ10_borel_conjecture_consequence.md`

### Assumptions

- \(G\) is torsion free.
- The low-dimensional K-theory vanishing hypotheses above hold.
- The \(L^{\langle -\infty\rangle}\)-theory assembly map is an isomorphism in all degrees.
- The manifold is orientable, closed, aspherical, topological, and of dimension at least \(5\).

### Source status

Source-verified from Lueck, W., and Reich, H. (2004), Conjecture 1.19, Conjecture 1.27, Proposition 1.23, and Theorem 1.28. This is not a K-theory-only result.

## ER-009. First source-verified known Farrell--Jones classes

### Status

Source-verified literature theorem ledger.

### Statement

The following group classes are recorded as known Farrell--Jones cases in
the versions stated:

- Hyperbolic groups satisfy the K-theoretic Farrell--Jones conjecture
  with coefficients in additive categories in all degrees. They also
  satisfy the L-theoretic Farrell--Jones assembly theorem with
  coefficients via Bartels--Lueck's class \(\mathcal B\).
- Finite-dimensional CAT(0)-groups satisfy the K-theoretic
  Farrell--Jones conjecture with coefficients in additive categories in
  all degrees. They also satisfy the L-theoretic Farrell--Jones assembly
  theorem with coefficients via Bartels--Lueck's class \(\mathcal B\).
- Virtually solvable groups satisfy the K- and L-theoretic
  Farrell--Jones conjecture with coefficients in additive categories with
  respect to the family of virtually cyclic subgroups.

### Proof location

`modules/cycle_001/FJ11_known_classes_ledger.md`

Proof-skeleton expansion:

`modules/cycle_001/FJ13_hyperbolic_groups_case.md`

CAT(0)-group proof-route expansion:

`modules/cycle_001/FJ14_cat0_groups_case.md`

Ledger table:

`ledgers/known_classes.md`

### Assumptions

- "With coefficients" is used in the source sense of coefficients in
  additive categories; `FJ02` now records the project's first-pass
  additive-category source convention.
- "Finite-dimensional CAT(0)-group" means a group admitting a proper,
  cocompact, isometric action on a finite-dimensional CAT(0)-space.
- The table is not exhaustive.

### Source status

Source-verified from Bartels, Lueck, and Reich (2008), main theorem;
Bartels and Lueck (2012), definition of the class \(\mathcal B\) and
Theorem B; Wegner (2012), main theorem, strong-transfer-reducibility
route, and CAT(0)-group theorem; and Wegner (2015), main theorem.

## ER-010. First source-verified inheritance-properties ledger

### Status

Source-verified literature theorem ledger.

### Statement

The project records the following first-pass inheritance information:

- the K-theoretic Farrell--Jones conjecture with coefficients in
  additive categories inherits injectivity and surjectivity separately
  along pullback families under arbitrary group homomorphisms;
- in particular, the coefficient K-theoretic formulation inherits to
  subgroups;
- directed colimits are inherited in the source-verified sense of
  Bartels--Echterhoff--Lueck, with the source's \(R\rtimes H\) target
  convention and with separate hypotheses for arbitrary structure maps
  and injective structure maps;
- Lueck's full class \(\mathcal{FJ}\) has the survey-level closure
  properties recorded in `ledgers/inheritance_properties.md`, including
  subgroups, finite direct products, directed colimits, certain
  extensions, free products, finite-index overgroups, and graph
  products.

### Proof location

`modules/cycle_001/FJ12_inheritance_properties_ledger.md`

Ledger table:

`ledgers/inheritance_properties.md`

### Assumptions

- "With coefficients" means coefficients in additive categories in the
  source sense; `FJ02` now records the project's first-pass internal
  convention for this source formulation.
- Lueck's \(\mathcal{FJ}\) denotes the source-specific full
  Farrell--Jones class, not merely the simplified ring-coefficient
  statement from `FJ01`.
- Survey-level closure rows should not be used as primary-proof inputs
  until their proof sources have been traced if proof-sensitive use is
  required.

### Source status

Source-verified from Bartels and Reich (2007), Section 4; Bartels,
Echterhoff, and Lueck (2007), Theorem "Inheritance under colimits"; and
Lueck (2025), Theorem "Status of the Full Farrell-Jones Conjecture."

## ER-011. First source-verified Artin-group Farrell--Jones subclass ledger

### Status

Source-verified literature theorem ledger.

### Statement

The project records the following first-pass Artin-group Farrell--Jones
subclasses and method rows:

- Artin groups of FC-type satisfy the Farrell--Jones conjecture with
  finite wreath products in the source formulation of Huang and Osajda.
- Weak Garside groups of finite type satisfy the Farrell--Jones
  conjecture with finite wreath products in the same source
  formulation; this includes spherical Artin groups and braid-group
  examples listed by Huang and Osajda.
- Normally poly-free groups satisfy the K- and L-theoretic
  Farrell--Jones conjecture with finite wreath products and coefficients
  in additive categories in the source formulation of Brueck, Kielak,
  and Wu.
- Even Artin groups of FC-type satisfy the K- and L-theoretic FJCw by
  Brueck--Kielak--Wu's normally-poly-free route.
- For a finite simplicial graph \(\Gamma\), right-angled Artin groups
  \(A_\Gamma\) satisfy FJCw by the CAT(0) route already recorded in
  the project, and groups \(A_\Gamma\rtimes_f\mathbb Z\) satisfy
  K- and L-theoretic FJCw by Brueck--Kielak--Wu.
- The even Artin groups covered by Wu's clique criterion and join/tree
  construction satisfy FJCw under the exact finite-graph and edge-label
  hypotheses recorded in `FJ18`.
- Roushon's listed finite real, complex, and affine Artin types satisfy
  `FICwF` in K-, L-, and A-theories with coefficients and finite wreath
  products, for subgroups of the listed Artin groups, using the 2024
  corrigendum for the \(\widetilde B_n\) route.

The global class of all Artin groups is not recorded as a known
Farrell--Jones case by this result.

### Proof location

`modules/cycle_001/FJ18_artin_groups_dossier.md`

Ledger table:

`ledgers/known_classes.md`

### Assumptions

- "FJCw" and "FICwF" are source-level flags. `FJ02` supplies a first-pass
  policy: do not identify them with the project's simplified
  ring-coefficient statement, coefficient K-theory FJC, or full
  \(\mathcal{FJ}\) without a checked comparison.
- Each row is usable only under the exact hypotheses recorded in
  `FJ18`.
- The project has not reconstructed the Helly-group, normally
  poly-free, or Roushon proof routes internally.

### Source status

Source-verified from Huang and Osajda (2021), Brueck, Kielak, and Wu
(2021), Wu (2022), Roushon (2021), Roushon's erratum (2022), and
Roushon's corrigendum (2024), as recorded in `FJ18`,
`BIBLIOGRAPHY.md`, and `ledgers/source_status.md`.

## ER-012. First source-verified one-relator-group Farrell--Jones status ledger

### Status

Source-verified literature status ledger.

### Statement

The project records the following first-pass one-relator-group status
information:

- The global class of torsion-free one-relator groups is not recorded as
  a known Farrell--Jones case in this project. Lueck (2025) lists
  torsion-free one-relator groups among classes for which the Full
  Farrell--Jones Conjecture is open in general.
- Torsion-free one-relator groups are locally indicable by Brodskii's
  theorem as presented by Howie (2000). This is a structural theorem,
  not a Farrell--Jones theorem.
- A one-relator group that is independently known to be hyperbolic,
  finite-dimensional CAT(0), or virtually solvable is covered by the
  corresponding rows of `ER-009`.
- A one-relator group that is independently known to be of the form
  \(H\rtimes_\Phi\mathbb Z\), with \(H\) virtually torsion-free
  hyperbolic, is covered by Bestvina--Fujiwara--Wigglesworth's
  hyperbolic-by-cyclic theorem in its source formulation.

### Proof location

`modules/cycle_001/FJ19_one_relator_groups_dossier.md`

Ledger tables:

`ledgers/known_classes.md`

`ledgers/open_group_classes.md`

### Assumptions

- "Full Farrell--Jones" and \(\mathcal{FJ}\) are used in Lueck's
  source-specific sense; this is stronger than the simplified
  ring-coefficient formulation in `FJ01`.
- The project has not reconciled all source-level coefficient and finite
  wreath product conventions with its internal simplified formulation;
  see `OQ-022`.
- The conditional subclass routes require independent verification that
  the group under study belongs to the relevant class.

### Source status

Source-verified from Lueck (2025), Bestvina, Fujiwara, and Wigglesworth
(2023), and Howie (2000). Newman (1968) is recorded as background for
the torsion one-relator contrast, not as a Farrell--Jones theorem source.

## ER-013. Source-verified additive-category K-theory formulation and source-convention policy

### Status

Source-verified formulation and project source-convention policy.

### Statement

The project adopts Bartels--Reich Conjecture 3.2 as its first-pass
canonical K-theoretic Farrell--Jones formulation with coefficients in
additive categories:

- \(\mathcal A\) is an additive category with right \(G\)-action;
- \(T\) is a left \(G\)-set;
- \(\mathcal A *_G T\) is the associated additive category from
  Bartels--Reich Definition 2.1;
- \(K_{\mathcal A}(T)=K^{-\infty}(\mathcal A *_G T)\) is the Or\(G\)-
  spectrum from Bartels--Reich Definition 3.1;
- the coefficient K-theory Farrell--Jones conjecture asks that
  \[
  H_*^G(E_{\mathcal{VCyc}}G;K_{\mathcal A})
  \longrightarrow
  H_*^G(\mathrm{pt};K_{\mathcal A})
  \]
  be an isomorphism for every additive category \(\mathcal A\) with
  right \(G\)-action.

The source-convention policy is that coefficient K-theory FJC, full
\(\mathcal{FJ}\), `FJCw`, `FICwF`, and the simplified ring-coefficient
formulation remain separate source labels unless a comparison is checked.

### Proof location

`modules/cycle_001/FJ02_additive_categories.md`

### Assumptions

- This is a formulation result, not a proof of the conjecture for all
  groups.
- The simplified ring-coefficient formulation from `FJ01` is treated as a
  specialization target of the additive-category formulation, subject to
  the black-box homology normalization in `FJ01`.
- `FJCw` and `FICwF` remain source-level flags with finite-wreath-product
  and source-specific theory content.

### Source status

Source-verified from Bartels and Reich (2007), especially Definitions 2.1
and 3.1, Conjecture 3.2, Remark 3.3, Corollary 4.3, Theorem 4.5, and
Proposition 4.6, as recorded in `FJ02`, `BIBLIOGRAPHY.md`, and
`ledgers/source_status.md`.

## ER-014. Source-verified FJCw finite-index overgroup bridge

### Status

Source-verified inheritance route.

### Statement

Let \(H\leq G\) be a subgroup of finite index. If \(H\) satisfies the
K-theoretic Farrell--Jones conjecture with coefficients in additive
categories and finite wreath products (`FJCw` in the project source-label
sense), then \(G\) satisfies the same finite-wreath-product version.

Consequently, \(G\) also satisfies the K-theoretic Farrell--Jones conjecture
with coefficients in additive categories under the `FJ02` convention, but the
stronger `FJCw` source label must remain visible.

### Proof location

`modules/cycle_003/FJ47_fjcw_finite_index_bridge_source_selection.md`

### Assumptions

- The finite-index subgroup must carry the finite-wreath-product version,
  not merely plain coefficient K-theory FJC.
- This result does not identify `FJCw` with full \(\mathcal{FJ}\),
  `FICwF`, or a direct CAT(0)-route statement.
- This result does not by itself remove any `T-001` residual case.

### Source status

Source-verified from Bartels, Lueck, Reich, and Rueping (2014), especially
Remark 6.2. Reich and Varisco (2018), Theorem 27, is recorded as a survey
cross-check pointing to the finite-wreath-product version for the listed
inheritance properties. Wang (2015), Theorems A and C, is recorded as a
warning that plain coefficient finite-index closure is not imported here as
an unconditional theorem.
