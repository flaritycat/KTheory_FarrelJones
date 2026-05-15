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

### Proof location

`modules/cycle_001/FJ01_minimal_statement.md`

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
