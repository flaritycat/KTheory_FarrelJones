# Module FJ04. Virtually cyclic groups

## Status

Completed, first pass

## Module type

Definition / Example / Proof / Literature verification

## Problem

Classify virtually cyclic groups enough for use in the early
Farrell--Jones modules.

This module is deliberately structural. It does not compute Nil-terms,
does not prove the Farrell--Jones conjecture for any new group, and does
not use controlled topology.

## Input

- `FJ01`, for the definition of \(\mathcal{VCyc}(G)\).
- `FJ03`, for classifying spaces for families and the role of
  \(E_{\mathcal{VCyc}}G\).
- Lueck--Reich, *The Baum-Connes and the Farrell-Jones Conjectures in
  K- and L-Theory*, for the definition of virtually cyclic groups, the
  family \(\mathcal{VCyc}\), the family \(\mathcal{VCyc}_I\), and the
  infinite virtually cyclic dichotomy.
- Lueck--Weiermann, *On the classifying space of the family of
  virtually cyclic subgroups*, for the type I/type II terminology and
  the later-use description of type I and type II groups in relative
  assembly terms.

## Output target

A usable structural lemma distinguishing finite and infinite virtually
cyclic groups, including type I/type II when appropriate.

## Definitions

### Definition: Virtually cyclic group

A group \(V\) is **virtually cyclic** if either:

1. \(V\) is finite; or
2. \(V\) contains an infinite cyclic subgroup of finite index.

This is the convention already used in `FJ01`. It matches the convention
recorded by Lueck--Reich in their subsection on families of subgroups.

### Definition: Infinite dihedral group

The **infinite dihedral group** is

\[
D_\infty=\mathbb Z/2 * \mathbb Z/2.
\]

Equivalently, it is the semidirect product

\[
\mathbb Z\rtimes \mathbb Z/2
\]

where the nontrivial element of \(\mathbb Z/2\) acts on \(\mathbb Z\)
by inversion.

### Definition: Type I / first kind

An infinite virtually cyclic group \(V\) is **of type I**, also called
**virtually cyclic of the first kind**, if there is an epimorphism

\[
V\longrightarrow \mathbb Z
\]

with finite kernel.

When this needs to be used as a family, write
\(\mathcal{VCyc}_I(G)\) for the collection consisting of the finite
subgroups of \(G\) together with the infinite virtually cyclic
subgroups of type I. This convention keeps the collection closed under
passage to subgroups.

### Definition: Type II / second kind

An infinite virtually cyclic group \(V\) is **of type II** if there is
an epimorphism

\[
V\longrightarrow D_\infty
\]

with finite kernel.

## Main work

The point of the family \(\mathcal{VCyc}(G)\) in the Farrell--Jones
conjecture is that it contains more than finite subgroups but remains
close to one-dimensional group theory. The infinite members split into
two standard forms:

- type I: finite-by-\(\mathbb Z\);
- type II: finite-by-\(D_\infty\).

This split is not cosmetic. Later algebraic \(K\)-theory modules will
meet different Nil-phenomena in the two cases. This module records only
the group-theoretic distinction.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim: Infinite virtually cyclic dichotomy

Let \(V\) be an infinite virtually cyclic group. Then \(V\) satisfies
one of the following alternatives:

1. \(V\) admits an epimorphism with finite kernel onto
   \(\mathbb Z\);
2. \(V\) admits an epimorphism with finite kernel onto
   \(D_\infty=\mathbb Z/2 * \mathbb Z/2\).

Source: Lueck--Reich, *The Baum-Connes and the Farrell-Jones
Conjectures in K- and L-Theory*, the lemma labeled `lem: virtually
cyclic` in the arXiv source. The proof there refers to Farrell--Jones,
*The lower algebraic K-theory of virtually infinite cyclic groups*,
Lemma 2.5.

Post-`FJ75` source-access note: `FJ75` checked the Farrell--Jones 1995
DOI and metadata but did not access the primary text of Lemma 2.5. Thus
Farrell--Jones (1995) remains a located original proof source, not a
directly source-verified theorem source inside this repository. The
usable first-pass source for this claim remains Lueck--Reich.

### Proposition: Type I groups are finite-by-infinite-cyclic

Let \(V\) be an infinite virtually cyclic group of type I. Then there is
a finite group \(F\) and an action of \(\mathbb Z\) on \(F\) such that

\[
V\cong F\rtimes \mathbb Z.
\]

### Proof

By definition of type I, there is an exact sequence

\[
1\longrightarrow F\longrightarrow V\longrightarrow \mathbb Z
\longrightarrow 1
\]

with \(F\) finite. Since \(\mathbb Z\) is free on one generator, choose
an element \(t\in V\) mapping to a generator of \(\mathbb Z\). The
subgroup \(\langle t\rangle\) maps isomorphically onto \(\mathbb Z\),
so the extension splits. Conjugation by \(t\) gives an automorphism of
\(F\), and \(V\cong F\rtimes \mathbb Z\).

### Literature claim: Type II groups as finite amalgams

If \(V\) is an infinite virtually cyclic group of type II, then it can
be written in the form

\[
V_1 *_{V_0} V_2,
\]

where \(V_0,V_1,V_2\) are finite groups and \(V_0\) has index two in
both \(V_1\) and \(V_2\).

Source: Lueck--Weiermann, *On the classifying space of the family of
virtually cyclic subgroups*, Example in Section 6 discussing the
relative term for \(K\)-theory and infinite virtually cyclic groups.

This module records the statement for later orientation. It does not
prove the Bass--Serre-theoretic decomposition internally.

### Proposition: Subgroups of virtually cyclic groups are virtually cyclic

Let \(V\) be a virtually cyclic group and let \(H\leq V\). Then \(H\) is
virtually cyclic.

### Proof

If \(V\) is finite, then \(H\) is finite, hence virtually cyclic.

Assume \(V\) is infinite virtually cyclic. Choose an infinite cyclic
subgroup \(C\leq V\) of finite index. Then

\[
[H:H\cap C]\leq [V:C]<\infty.
\]

The subgroup \(H\cap C\) is a subgroup of the infinite cyclic group
\(C\), so it is either trivial or infinite cyclic. If \(H\cap C\) is
trivial, then \(H\) is finite. If \(H\cap C\) is infinite cyclic, then
\(H\) contains an infinite cyclic subgroup of finite index. In both
cases \(H\) is virtually cyclic.

### Corollary: \(\mathcal{VCyc}(G)\) is a family

For every group \(G\), the collection

\[
\mathcal{VCyc}(G)=\{V\leq G:V\text{ is virtually cyclic}\}
\]

is closed under conjugation and passage to subgroups. Hence it is a
family of subgroups in the project sense.

### Proof

Closure under subgroups is the preceding proposition. Closure under
conjugation follows because if \(V\leq G\) is virtually cyclic and
\(g\in G\), then \(gVg^{-1}\) is isomorphic to \(V\), and being
virtually cyclic is invariant under group isomorphism.

### Example: Finite groups

Every finite group is virtually cyclic by definition. Thus every finite
subgroup of \(G\) belongs to \(\mathcal{VCyc}(G)\), giving

\[
\mathcal{Fin}(G)\subseteq \mathcal{VCyc}(G).
\]

### Example: Infinite cyclic group

The group \(\mathbb Z\) is virtually cyclic of type I. The identity map

\[
\mathbb Z\longrightarrow \mathbb Z
\]

has finite kernel, namely the trivial group.

### Example: Finite-by-\(\mathbb Z\)

If \(F\) is finite and \(\alpha\colon \mathbb Z\to\operatorname{Aut}(F)\)
is an action, then

\[
F\rtimes_\alpha \mathbb Z
\]

is virtually cyclic of type I.

### Example: Infinite dihedral group

The group \(D_\infty\) is virtually cyclic of type II. It maps to itself
with finite kernel, and it contains an infinite cyclic subgroup of index
two.

### Corollary: Torsion-free virtually cyclic groups

If \(V\) is torsion-free and virtually cyclic, then \(V\) is either
trivial or infinite cyclic.

### Proof

If \(V\) is finite and torsion-free, then \(V\) is trivial. If \(V\) is
infinite, use the source-verified dichotomy.

In the type I case, \(V\cong F\rtimes\mathbb Z\) with \(F\) finite. The
torsion-free hypothesis forces \(F=1\), so \(V\cong\mathbb Z\).

In the type II case, \(V\) admits an epimorphism onto \(D_\infty\) with
finite kernel. The preimage of either order-two factor in
\(D_\infty=\mathbb Z/2 * \mathbb Z/2\) is a finite subgroup of \(V\)
mapping nontrivially to \(\mathbb Z/2\), which contradicts
torsion-freeness. Thus the type II case cannot occur.

## Proof or verification

The infinite virtually cyclic dichotomy is not proved from scratch in
this module. It is source-verified from Lueck--Reich. The source states
the dichotomy for an infinite virtually cyclic group and identifies the
two quotients \(\mathbb Z\) and \(\mathbb Z/2 * \mathbb Z/2\), with
finite kernels.

The semidirect-product statement for type I is proved internally from
the source-verified epimorphism to \(\mathbb Z\).

The type II amalgamated-product statement is recorded as a literature
claim from Lueck--Weiermann and left unproved here. It will matter later
only when Nil-terms or Bass--Serre decompositions are explicitly under
discussion.

## References

- Lueck, W.; Reich, H. *The Baum-Connes and the Farrell-Jones
  Conjectures in K- and L-Theory*. arXiv:math/0402405, 2004. Status:
  `active reference`; used for the definition of virtually cyclic
  groups, \(\mathcal{VCyc}_I\), and the infinite virtually cyclic
  dichotomy.
- Lueck, W.; Weiermann, M. *On the classifying space of the family of
  virtually cyclic subgroups*. arXiv:math/0702646, version 2, 2009.
  Status: `partially read`; used for type I/type II terminology and the
  type II amalgam orientation.
- Farrell, F. T.; Jones, L. E. *The lower algebraic K-theory of
  virtually infinite cyclic groups*. K-Theory 9 (1995), 13--30.
  DOI: 10.1007/BF00965457. Status: `metadata checked; primary Lemma 2.5
  text not accessed`; cited by Lueck--Reich as the proof source for the
  dichotomy, but not directly checked in this module or promoted by
  `FJ75`.

## Dependencies

This module depends on:

- `FJ01`, for the first definition of \(\mathcal{VCyc}(G)\).
- `FJ03`, for families of subgroups and \(E_{\mathcal F}G\).
- Lueck--Reich's virtually cyclic dichotomy.

## Results produced

This module produced:

- A first-pass structural description of finite and infinite virtually
  cyclic groups.
- The type I/type II terminology needed for later modules.
- An internal proof that subgroups of virtually cyclic groups are
  virtually cyclic.
- ER-003: \(\mathcal{VCyc}(G)\) is a family of subgroups.
- A reminder that type II groups are associated to finite amalgams,
  source-recorded but not internally proved here.

## Open questions generated

- Should the project directly verify Farrell--Jones 1995, Lemma 2.5,
  before using the type I/type II dichotomy in a proof-sensitive way?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: updated to record completion of `FJ04` and the
  next move to `FJ05`.
- `NOTATION_LEDGER.md`: updated with \(\mathbb Z\),
  \(D_\infty\), and \(\mathcal{VCyc}_I(G)\).
- `ESTABLISHED_RESULTS.md`: updated with ER-003.
- `OPEN_QUESTIONS.md`: updated with the direct-source verification
  question for Farrell--Jones 1995.
- `BIBLIOGRAPHY.md`: updated with Lueck--Weiermann and Farrell--Jones
  1995.
- `ledgers/source_status.md`: updated with FJ04 source status.
