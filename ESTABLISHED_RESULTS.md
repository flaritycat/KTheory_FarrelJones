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
