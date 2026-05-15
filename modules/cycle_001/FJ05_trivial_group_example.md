# Module FJ05. Trivial group example

## Status

Completed, standalone expansion

## Module type

Example / Proof

## Problem

Verify the simplified K-theoretic Farrell--Jones assembly map for the
trivial group \(G=1\) as a standalone toy example.

This module expands the minimal proof already recorded in `FJ01` as
ER-001. It does not introduce a new established result number; it gives
ER-001 a reusable worked-example artifact.

## Input

- `FJ01`, for the simplified group-ring formulation and the black-box
  equivariant homology normalization.
- `FJ03`, for classifying spaces for families.
- `FJ04`, for the fact that \(\mathcal{VCyc}(G)\) is a family.
- The standing assumptions that \(R\) is an associative unital ring and
  \(G\) is a discrete group.

## Output target

A standalone proof that \(E_{\mathcal{VCyc}}1\) is modeled by
\(\mathrm{pt}\), and that the simplified assembly map

\[
H_n^1(E_{\mathcal{VCyc}}1;\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R)
\cong K_n(R)
\]

is the identity map on \(K_n(R)\).

## Definitions

### Definition: The trivial group

The **trivial group** is the group with one element. In this project it
is denoted by \(1\).

It has exactly one subgroup, namely \(1\) itself.

### Definition: The point as a \(1\)-space

Let \(\mathrm{pt}\) denote the one-point space. The action of the
trivial group \(1\) on \(\mathrm{pt}\) is unique.

As a \(1\)-space,

\[
\mathrm{pt}\cong 1/1.
\]

### Definition: Assembly map in this example

For \(G=1\), the simplified assembly map from `FJ01` is induced by the
unique \(1\)-map

\[
E_{\mathcal{VCyc}}1\longrightarrow \mathrm{pt}.
\]

After applying the black-box equivariant homology theory, it becomes

\[
A_{1,R,n}\colon
H_n^1(E_{\mathcal{VCyc}}1;\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R).
\]

## Main work

There are three checks:

1. identify \(\mathcal{VCyc}(1)\);
2. identify a model for \(E_{\mathcal{VCyc}}1\);
3. identify the induced assembly map.

Since the trivial group has no nontrivial subgroup data, all three
checks collapse to the point.

## Proposition / Theorem / Conjecture / Example

### Proposition: Trivial group example

Let \(R\) be an associative unital ring and let \(G=1\). In the
simplified group-ring formulation of `FJ01`, the assembly map

\[
A_{1,R,n}\colon
H_n^1(E_{\mathcal{VCyc}}1;\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R)
\cong K_n(R)
\]

is the identity map on \(K_n(R)\) for every \(n\in\mathbb Z\), assuming
the black-box normalization

\[
H_n^G(G/H;\mathbf K_R)\cong K_n(R[H]).
\]

## Proof or verification

The group \(1\) has exactly one subgroup, \(1\). This subgroup is
finite, hence virtually cyclic. Therefore

\[
\mathcal{VCyc}(1)=\{1\}.
\]

Consider the one-point \(1\)-space \(\mathrm{pt}\). Its fixed-point
space under the only subgroup is

\[
\mathrm{pt}^{\,1}=\mathrm{pt},
\]

which is contractible. There are no subgroups of \(1\) outside
\(\mathcal{VCyc}(1)\), so the empty fixed-point condition for subgroups
outside the family is vacuous. Hence \(\mathrm{pt}\) is a model for
\(E_{\mathcal{VCyc}}1\).

The terminal map

\[
E_{\mathcal{VCyc}}1\longrightarrow \mathrm{pt}
\]

is therefore represented by the identity map

\[
\mathrm{pt}\longrightarrow \mathrm{pt}.
\]

Applying \(H_n^1(-;\mathbf K_R)\) gives the identity endomorphism of

\[
H_n^1(\mathrm{pt};\mathbf K_R).
\]

Since \(\mathrm{pt}\cong 1/1\), the normalization from `FJ01` gives

\[
H_n^1(\mathrm{pt};\mathbf K_R)
\cong
H_n^1(1/1;\mathbf K_R)
\cong
K_n(R[1]).
\]

The group ring \(R[1]\) is canonically isomorphic to \(R\). Explicitly,
if \(e\) is the unique element of \(1\), the map

\[
R[1]\longrightarrow R,\qquad re\longmapsto r
\]

is a ring isomorphism. Therefore

\[
K_n(R[1])\cong K_n(R).
\]

Under this identification, the assembly map is the identity map on
\(K_n(R)\).

## References

- `FJ01`, for the simplified assembly map and ER-001.
- `FJ03`, for classifying spaces for families.
- `FJ04`, for \(\mathcal{VCyc}(G)\) as a family.

No new external source is used in this module.

## Dependencies

This module depends on:

- `FJ01`, especially the black-box normalization of
  \(H_n^G(-;\mathbf K_R)\);
- `FJ03`, for the fixed-point test defining \(E_{\mathcal F}G\);
- `FJ04`, for the family \(\mathcal{VCyc}(G)\).

## Results produced

This module produced:

- A standalone worked example for the trivial group.
- A second proof-location artifact for ER-001.
- No new established result number.

## Open questions generated

- None.

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: updated to record completion of `FJ05` and the
  next move to `FJ06`.
- `ESTABLISHED_RESULTS.md`: updated so ER-001 points to this standalone
  proof artifact as well as `FJ01`.
- `ledgers/theorem_dependencies.md`: updated so `FJ05` is marked
  completed and `FJ06` is listed as the next module.
