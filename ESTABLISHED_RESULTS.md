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

In Lueck's source formulation, a \(G\)-CW complex \(X\) is a model for \(E_{\mathcal F}G\) if and only if all isotropy groups of \(X\) belong to \(\mathcal F\) and \(X^H\) is weakly contractible for each \(H\in\mathcal F\).

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
