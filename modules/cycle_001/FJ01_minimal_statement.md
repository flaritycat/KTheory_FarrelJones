# Module FJ01. Minimal statement of the K-theoretic Farrell--Jones conjecture

## Status

Completed, first pass

## Module type

Definition / Conjecture / Example / Proof

## Problem

State the simplified \(K\)-theoretic Farrell--Jones conjecture for group rings and prove the trivial-group example.

This module deliberately avoids the stronger additive-category formulation. That formulation belongs to `FJ02`; dragging it in now would be mathematically possible and organizationally feral.

## Input

- Basic group theory.
- Basic ring theory.
- The project convention that \(R\) is an associative unital ring.
- The project convention that \(G\) is a discrete group.
- A black-box equivariant homology theory \(H_n^G(-;\mathbf K_R)\) associated to algebraic \(K\)-theory.

## Output target

A reusable first-pass statement of the simplified assembly map

\[
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_R)
\longrightarrow
K_n(R[G])
\]

and a proof that for \(G=1\) this map is the identity on \(K_n(R)\).

## Assumptions

- \(R\) is an associative unital ring.
- \(G\) is a discrete group.
- \(n\in\mathbb Z\).
- The notation \(K_n(-)\) is interpreted through a nonconnective algebraic \(K\)-theory model when negative degrees are included.
- The model of nonconnective \(K\)-theory is not chosen in this module.
- \(H_n^G(-;\mathbf K_R)\) is treated as a black-box equivariant homology theory normalized by

\[
H_n^G(G/H;\mathbf K_R)\cong K_n(R[H])
\]

for subgroups \(H\leq G\).

## Definitions

### Definition: Group ring

Let \(R\) be an associative unital ring and let \(G\) be a discrete group.

The **group ring** \(R[G]\) is the ring whose elements are finite formal sums

\[
\sum_{g\in G} r_g g,
\]

where \(r_g\in R\) and all but finitely many coefficients \(r_g\) are zero.

Addition is coefficientwise. Multiplication is determined by distributivity and by

\[
(rg)(sh)=(rs)(gh)
\]

for \(r,s\in R\) and \(g,h\in G\).

### Definition: Virtually cyclic group

A group \(V\) is **virtually cyclic** if it is finite or contains an infinite cyclic subgroup of finite index.

### Definition: The family \(\mathcal{VCyc}(G)\)

For a discrete group \(G\), let

\[
\mathcal{VCyc}(G)
\]

denote the collection of virtually cyclic subgroups of \(G\).

This is a family of subgroups: it is closed under conjugation and passage to subgroups.

### Definition: Family of subgroups

A **family of subgroups** \(\mathcal F\) of \(G\) is a collection of subgroups of \(G\) closed under:

1. conjugation in \(G\);
2. passage to subgroups.

### Definition: Classifying space for a family

Let \(\mathcal F\) be a family of subgroups of \(G\).

A \(G\)-CW complex \(E_{\mathcal F}G\) is a **classifying space for the family** \(\mathcal F\) if for every subgroup \(H\leq G\), the fixed-point space \((E_{\mathcal F}G)^H\) is:

\[
\begin{cases}
\text{contractible}, & H\in\mathcal F,\\
\varnothing, & H\notin\mathcal F.
\end{cases}
\]

Equivalently, all isotropy groups lie in \(\mathcal F\), and the fixed-point condition above holds.

In this module, the main family is \(\mathcal{VCyc}(G)\), so the relevant space is

\[
E_{\mathcal{VCyc}}G.
\]

### Definition: The black-box equivariant homology theory

For this first pass, \(H_n^G(-;\mathbf K_R)\) denotes an equivariant homology theory on \(G\)-CW complexes associated to algebraic \(K\)-theory of \(R\).

The key normalization used here is:

\[
H_n^G(G/H;\mathbf K_R)\cong K_n(R[H])
\]

for every subgroup \(H\leq G\).

In particular, since \(\mathrm{pt}\cong G/G\) as a \(G\)-space,

\[
H_n^G(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[G]).
\]

### Definition: Assembly map

The unique \(G\)-map

\[
E_{\mathcal{VCyc}}G\longrightarrow \mathrm{pt}
\]

induces a homomorphism

\[
A_{G,R,n}\colon
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_R)
\longrightarrow
H_n^G(\mathrm{pt};\mathbf K_R).
\]

Using the normalization

\[
H_n^G(\mathrm{pt};\mathbf K_R)
\cong K_n(R[G]),
\]

this is written as

\[
A_{G,R,n}\colon
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_R)
\longrightarrow
K_n(R[G]).
\]

This map is the **assembly map** in the simplified ring-coefficient formulation.

## Conjecture

### Conjecture: K-theoretic Farrell--Jones conjecture, simplified group-ring form

Let \(G\) be a discrete group and let \(R\) be an associative unital ring.

The **K-theoretic Farrell--Jones conjecture**, in the simplified ring-coefficient form used in this module, predicts that for every \(n\in\mathbb Z\), the assembly map

\[
A_{G,R,n}\colon
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_R)
\longrightarrow
H_n^G(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[G])
\]

is an isomorphism.

## Warning

This is not the strongest modern formulation.

The stronger formulation uses coefficients in additive \(G\)-categories, and sometimes appears in fibered or inheritance-friendly forms. This module does not state that version. It is reserved for `FJ02`, where the exact hypotheses and source references must be checked.

Also, the all-degrees statement \(n\in\mathbb Z\) requires a nonconnective algebraic \(K\)-theory model. This module records that requirement but does not choose the model.

## Heuristic

The conjecture says, informally, that the algebraic \(K\)-theory of the group ring \(R[G]\) is assembled from information coming from virtually cyclic subgroups \(V\leq G\).

Symbolically, and only heuristically,

\[
K_n(R[G])
\quad\text{is controlled by}\quad
\{K_n(R[V]) : V\in\mathcal{VCyc}(G)\}.
\]

## Warning

The heuristic above is not a formal statement. The formal statement is the assembly-map isomorphism.

## Example / Proposition

### Proposition: Trivial group case

Let \(R\) be an associative unital ring and let \(G=1\) be the trivial group. Then \(\mathrm{pt}\) is a model for \(E_{\mathcal{VCyc}}1\), and the simplified assembly map

\[
H_n^1(E_{\mathcal{VCyc}}1;\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R)
\cong
K_n(R)
\]

is the identity map on \(K_n(R)\) for all \(n\in\mathbb Z\).

## Proof

The group \(1\) has exactly one subgroup, namely \(1\) itself. This subgroup is finite, hence virtually cyclic. Therefore

\[
\mathcal{VCyc}(1)=\{1\}.
\]

Consider the one-point space \(\mathrm{pt}\) with the trivial action of \(1\). Its only fixed-point space is

\[
\mathrm{pt}^1=\mathrm{pt},
\]

which is contractible. There are no subgroups outside \(\mathcal{VCyc}(1)\), so the empty fixed-point condition is vacuous. Hence \(\mathrm{pt}\) is a model for \(E_{\mathcal{VCyc}}1\).

The map

\[
E_{\mathcal{VCyc}}1\longrightarrow \mathrm{pt}
\]

is therefore represented by the identity map

\[
\mathrm{pt}\longrightarrow \mathrm{pt}.
\]

Applying the functor \(H_n^1(-;\mathbf K_R)\) gives the identity map

\[
H_n^1(\mathrm{pt};\mathbf K_R)
\longrightarrow
H_n^1(\mathrm{pt};\mathbf K_R).
\]

By the normalization of the black-box equivariant homology theory,

\[
H_n^1(\mathrm{pt};\mathbf K_R)
\cong
K_n(R[1]).
\]

Finally, the group ring \(R[1]\) is canonically isomorphic to \(R\), since a finite formal sum over the one-element group is just one coefficient in \(R\). Thus

\[
K_n(R[1])\cong K_n(R).
\]

Under this identification, the assembly map is the identity map on \(K_n(R)\).

## References

- Farrell, F. T.; Jones, L. E. *Isomorphism conjectures in algebraic K-theory*. Journal of the American Mathematical Society 6 (1993), 249--297. Status: `to verify`; original source located but not checked in this module.
- Lück, W.; Reich, H. *The Baum-Connes and the Farrell-Jones Conjectures in K- and L-Theory*. arXiv:math/0402405. Status: `partially read`; used as a survey-level reference for the assembly-map perspective.
- Davis, J. F.; Lück, W. *Spaces over a category and assembly maps in isomorphism conjectures in K- and L-theory*. K-Theory 15 (1998), 201--252. Status: `to verify`; candidate source for the assembly formalism.

## Dependencies

This module depends on:

- no previous project modules;
- the project charter assumptions about \(R\), \(G\), and source discipline.

## Results produced

This module produced:

- A first-pass definition of \(R[G]\).
- A first-pass definition of \(\mathcal{VCyc}(G)\).
- A first-pass definition of \(E_{\mathcal F}G\).
- A black-box definition of \(H_n^G(-;\mathbf K_R)\).
- The simplified K-theoretic Farrell--Jones conjecture for group rings.
- ER-001: proof of the trivial group case.

## Open questions generated

- Which source should be treated as authoritative for the modern additive-category formulation?
- Which model of nonconnective algebraic \(K\)-theory should be fixed for the all-integers statement?
- At what point should the black-box equivariant homology theory be unpacked into spectra or orbit-category machinery?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: updated to record the active simplified scope and ER-001.
- `NOTATION_LEDGER.md`: updated with \(R[G]\), \(\mathcal{VCyc}(G)\), \(E_{\mathcal F}G\), \(\mathbf K_R\), and \(H_n^G(-;\mathbf K_R)\).
- `ESTABLISHED_RESULTS.md`: updated with ER-001.
- `OPEN_QUESTIONS.md`: updated with source/model questions.
- `BIBLIOGRAPHY.md`: updated with initial sources.
- `ledgers/source_status.md`: updated with source-status entries.
