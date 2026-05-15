# Module FJ06. Infinite cyclic group example

## Status

Completed, first pass

## Module type

Example / Computation / Proof

## Problem

Analyze the simplified assembly map for \(G=\mathbb Z\), and explain
why the target is

\[
K_n(R[t,t^{-1}]).
\]

This module does not use the Bass--Heller--Swan decomposition. That
decomposition, and the Nil phenomena it reveals, belong to `FJ07`.

## Input

- `FJ01`, for the simplified assembly map and the black-box
  normalization of \(H_n^G(-;\mathbf K_R)\).
- `FJ03`, for \(E_{\mathcal F}G\), the example
  \(E_{\mathcal{All}}G\simeq \mathrm{pt}\), and the terminal map to
  \(\mathrm{pt}\).
- `FJ04`, for the fact that \(\mathbb Z\) is virtually cyclic and that
  \(\mathcal{VCyc}(G)\) is a family.
- The standing assumption that \(R\) is an associative unital ring.

## Output target

A worked explanation that, for \(G=\mathbb Z\), the simplified assembly
map is the identity map after choosing a generator \(t\) and using the
standard identification

\[
R[\mathbb Z]\cong R[t,t^{-1}].
\]

## Definitions

### Definition: Laurent polynomial ring

For an associative unital ring \(R\), the **Laurent polynomial ring**
\(R[t,t^{-1}]\) consists of finite sums

\[
\sum_{k\in\mathbb Z} r_k t^k,
\]

where \(r_k\in R\) and all but finitely many \(r_k\) are zero.

Multiplication is determined by distributivity and the rule

\[
(r t^i)(s t^j)=rs\,t^{i+j}.
\]

If \(R\) is noncommutative, the indeterminate \(t\) is treated here as
central in the ordinary group-ring identification with \(R[\mathbb Z]\).

### Definition: The infinite cyclic group as a multiplicative group

Write

\[
\mathbb Z=\langle t\rangle
\]

for the infinite cyclic group with generator \(t\). In this notation
the group elements are \(t^k\) for \(k\in\mathbb Z\).

This multiplicative notation is used only to match the group ring
\(R[\mathbb Z]\) with \(R[t,t^{-1}]\).

## Main work

The key point is that \(\mathbb Z\) itself is virtually cyclic. Hence
every subgroup of \(\mathbb Z\) is virtually cyclic, so

\[
\mathcal{VCyc}(\mathbb Z)=\mathcal{All}(\mathbb Z).
\]

By `FJ03`, the one-point \(\mathbb Z\)-space is a model for
\(E_{\mathcal{All}}\mathbb Z\). Therefore \(\mathrm{pt}\) is also a
model for \(E_{\mathcal{VCyc}}\mathbb Z\).

Thus, before any Bass--Heller--Swan decomposition is considered, the
simplified Farrell--Jones assembly map for \(G=\mathbb Z\) is already
the identity map on the target object:

\[
H_n^{\mathbb Z}(E_{\mathcal{VCyc}}\mathbb Z;\mathbf K_R)
\longrightarrow
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R).
\]

The target is identified by the normalization from `FJ01`:

\[
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[\mathbb Z]).
\]

Finally,

\[
R[\mathbb Z]\cong R[t,t^{-1}],
\]

so the target is \(K_n(R[t,t^{-1}])\).

## Proposition / Theorem / Conjecture / Example

### Proposition: Infinite cyclic group example

Let \(R\) be an associative unital ring and let \(G=\mathbb Z\). In the
simplified group-ring formulation of `FJ01`, the assembly map

\[
H_n^{\mathbb Z}(E_{\mathcal{VCyc}}\mathbb Z;\mathbf K_R)
\longrightarrow
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[\mathbb Z])
\]

is the identity map after choosing \(\mathrm{pt}\) as a model for
\(E_{\mathcal{VCyc}}\mathbb Z\). Under the standard group-ring
identification determined by the chosen generator
\(R[\mathbb Z]\cong R[t,t^{-1}]\), the target is

\[
K_n(R[t,t^{-1}]).
\]

This holds for every \(n\in\mathbb Z\), assuming the same black-box
normalization and nonconnective \(K\)-theory convention used in `FJ01`.

## Proof or verification

The group \(\mathbb Z\) is infinite cyclic, hence virtually cyclic.
Every subgroup of a virtually cyclic group is virtually cyclic by
`FJ04`. Therefore every subgroup of \(\mathbb Z\) belongs to
\(\mathcal{VCyc}(\mathbb Z)\). Hence

\[
\mathcal{VCyc}(\mathbb Z)=\mathcal{All}(\mathbb Z).
\]

By `FJ03`, \(\mathrm{pt}\) is a model for
\(E_{\mathcal{All}}\mathbb Z\). Therefore \(\mathrm{pt}\) is a model
for \(E_{\mathcal{VCyc}}\mathbb Z\).

The assembly map is induced by the terminal \(\mathbb Z\)-map

\[
E_{\mathcal{VCyc}}\mathbb Z\longrightarrow \mathrm{pt}.
\]

Using the point model, this map is represented by

\[
\mathrm{pt}\longrightarrow \mathrm{pt},
\]

the identity map. Applying \(H_n^{\mathbb Z}(-;\mathbf K_R)\) gives the
identity endomorphism of

\[
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R).
\]

The black-box normalization gives

\[
H_n^{\mathbb Z}(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[\mathbb Z]).
\]

Now write \(\mathbb Z=\langle t\rangle\). Define

\[
\Phi\colon R[\mathbb Z]\longrightarrow R[t,t^{-1}]
\]

by

\[
\Phi\left(\sum_{k\in\mathbb Z} r_k t^k\right)
=
\sum_{k\in\mathbb Z} r_k t^k.
\]

On the left, \(t^k\) denotes the group element in \(\mathbb Z\); on the
right, \(t^k\) denotes the Laurent monomial. Both sums are finite.
Coefficientwise addition is preserved. Multiplication is preserved
because in the group ring

\[
(r_i t^i)(s_j t^j)=r_i s_j t^{i+j},
\]

which is exactly the multiplication rule in \(R[t,t^{-1}]\). Thus
\(\Phi\) is a ring isomorphism. Consequently

\[
K_n(R[\mathbb Z])\cong K_n(R[t,t^{-1}]).
\]

Combining these identifications, the simplified assembly map for
\(G=\mathbb Z\) is the identity map on
\(K_n(R[t,t^{-1}])\).

## Warning

This does not compute \(K_n(R[t,t^{-1}])\) in terms of \(K_n(R)\).

The computation of \(K_n(R[t,t^{-1}])\) relative to \(K_n(R)\) is where
the Bass--Heller--Swan decomposition and Nil-terms enter. That is the
purpose of `FJ07`.

## References

- `FJ01`, for the simplified assembly map and black-box normalization.
- `FJ03`, for \(E_{\mathcal{All}}G\simeq\mathrm{pt}\) and the assembly
  map as the map induced by \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\).
- `FJ04`, for the fact that \(\mathbb Z\) is virtually cyclic and that
  subgroups of virtually cyclic groups are virtually cyclic.

No new external source is used in this module.

## Dependencies

This module depends on:

- `FJ01`, for the assembly map and homology normalization;
- `FJ03`, for classifying spaces for families;
- `FJ04`, for virtually cyclic group structure.

## Results produced

This module produced:

- A standalone worked example for \(G=\mathbb Z\).
- The chosen-generator identification
  \(R[\mathbb Z]\cong R[t,t^{-1}]\).
- ER-004: the simplified assembly map for \(G=\mathbb Z\) is the
  identity under the point model, with target \(K_n(R[t,t^{-1}])\).

## Open questions generated

- Which APA-formatted source should be used in `FJ07` for the
  Bass--Heller--Swan decomposition and Nil-terms?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: updated to record completion of `FJ06` and the
  next move to `FJ07`.
- `NOTATION_LEDGER.md`: updated with \(R[t,t^{-1}]\) and the generator
  \(t\) of \(\mathbb Z\).
- `ESTABLISHED_RESULTS.md`: updated with ER-004.
- `OPEN_QUESTIONS.md`: updated with a source-selection question for
  Bass--Heller--Swan.
- `ledgers/theorem_dependencies.md`: updated so `FJ06` is completed
  and `FJ07` is listed as the next module.
