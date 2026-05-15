# Module FJ36. Bass--Serre source verification for Gpq

## Status

Completed

## Module type

Literature verification / Theorem map / Proof

## Problem

`FJ35` identified a conditional route for
\[
K_{p,q}=\ker(\chi_{p,q})
\]
where
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad
p,q\geq2,\quad \gcd(p,q)=1,
\]
and
\[
\chi_{p,q}(x)=q,\qquad \chi_{p,q}(y)=p.
\]

The missing step was source verification for the Bass--Serre freeness bridge:
if \(K_{p,q}\) acts freely on the Bass--Serre tree of the cyclic amalgam, then
\(K_{p,q}\) is free. Combined with Brown finite generation from `FJ34`, this
would give finite-rank freeness and therefore the `FJ26` route bridge.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ34`, the \(G_{p,q}\)-family Brown finite-generation computation;
- `FJ35`, the conditional Bass--Serre bridge map;
- Brown's Theorem 4.3 and Corollary 3.2 as already verified in `FJ30` and
  used in `FJ34`;
- Serre's *Trees* as the canonical Bass--Serre reference;
- auxiliary accessible source checks for the exact stabilizer and freeness
  statements.

## Output target

Produce:

- a source-verified Bass--Serre bridge for \(K_{p,q}\);
- a proof that \(K_{p,q}\) is finite-rank free;
- a finite-rank free-by-cyclic bridge for the \(G_{p,q}\)-family;
- a decision about `FJ26` route use for this family.

## Definitions

**Definition.** Let
\[
K_{p,q}=\ker(\chi_{p,q}).
\]

**Definition.** Let \(T_{p,q}\) denote the Bass--Serre tree associated to the
cyclic-amalgam presentation
\[
G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle,
\qquad z\mapsto x^p,\quad z\mapsto y^q.
\]

**Warning.** This module uses only the presentation-level amalgam and
Bass--Serre action. It does not use torus-knot groups, fibered knots, or a
geometric classification of \(G_{p,q}\).

## Main work

### Source verification

**Source-verified claim.** Serre's *Trees* is the canonical monograph source
for groups acting on trees. This module uses the Springer chapter record for
"Trees and amalgams" as the bibliographic anchor for the Bass--Serre
verification (Serre, 1980).

**Source-verified claim.** In the Bass--Serre setting, a graph-of-groups
decomposition has an associated Bass--Serre tree. For an action on such a
tree, the vertex groups are stabilizers of vertices in orbit representatives,
and stabilizers in the same orbit are conjugate. Carrasco and Mackay record
this formulation and cite Serre as a reference for Bass--Serre theory
(Carrasco & Mackay, 2022).

**Source-verified claim.** If a group acts freely on a tree, then it is a free
group. Margalit's chapter states this theorem explicitly, and Chiswell and
Mueller record the corresponding Bass--Serre consequence for free actions
without inversions on simplicial trees (Chiswell & Mueller, 2012; Margalit,
2017).

These claims verify the exact bridge needed in `FJ35`.

### Amalgam for G_{p,q}

The presentation
\[
G_{p,q}=\langle x,y\mid x^p=y^q\rangle
\]
is the cyclic amalgam
\[
\langle x\rangle *_{\langle z\rangle}\langle y\rangle,
\qquad z\mapsto x^p,\quad z\mapsto y^q.
\]
The maps from \(\langle z\rangle\) into \(\langle x\rangle\) and
\(\langle y\rangle\) are injective because \(x\) and \(y\) generate infinite
cyclic groups in the presentation-level factors.

By the source-verified Bass--Serre bridge, \(G_{p,q}\) acts without inversions
on \(T_{p,q}\), with vertex stabilizers conjugate to \(\langle x\rangle\) or
\(\langle y\rangle\).

### Free action of K_{p,q}

For any \(n\in\mathbb Z\),
\[
\chi_{p,q}(x^n)=nq.
\]
Since \(q\neq0\), the intersection
\[
K_{p,q}\cap \langle x\rangle
\]
is trivial. Likewise,
\[
\chi_{p,q}(y^m)=mp
\]
and \(p\neq0\), so
\[
K_{p,q}\cap \langle y\rangle
\]
is trivial.

If \(h\in K_{p,q}\cap g\langle x\rangle g^{-1}\), then
\[
h=gx^ng^{-1}
\]
for some \(n\), and
\[
0=\chi_{p,q}(h)=\chi_{p,q}(x^n)=nq.
\]
Thus \(n=0\), so \(h=1\). The same argument applies to conjugates of
\(\langle y\rangle\).

Therefore \(K_{p,q}\) has trivial intersection with every vertex stabilizer
of \(T_{p,q}\). Hence \(K_{p,q}\) acts freely on \(T_{p,q}\). By the
source-verified free-action theorem, \(K_{p,q}\) is free.

### Finite rank

`FJ34` already proves that \(K_{p,q}\) is finitely generated, using Brown's
finite-generation criterion. A finitely generated free group is free of finite
rank. Thus
\[
K_{p,q}\cong F_n
\]
for some finite \(n\). This module does not compute \(n\).

### Semidirect product

Since \(\gcd(p,q)=1\), choose integers \(a,b\) with
\[
aq+bp=1.
\]
Then
\[
\chi_{p,q}(x^a y^b)=1.
\]
The assignment \(1\mapsto x^a y^b\) splits
\[
G_{p,q}\xrightarrow{\chi_{p,q}}\mathbb Z.
\]
Therefore
\[
G_{p,q}\cong K_{p,q}\rtimes\mathbb Z
\]
with \(K_{p,q}\cong F_n\), \(n<\infty\).

### Target-status and FJ26 route

The presentation \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\) is a
one-relator presentation. The semidirect product
\[
F_n\rtimes\mathbb Z
\]
is torsion-free: if \((u,k)^m=(1,0)\), then \(mk=0\), so \(k=0\), and then
\(u^m=1\) in the free group \(F_n\), forcing \(u=1\).

Thus the \(G_{p,q}\)-family lies inside the active torsion-free one-relator
target and has a finite-rank free-by-cyclic bridge. By the `FJ26` route, the
family is removed from the active `T-001` residual.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(p,q\geq2\) with \(\gcd(p,q)=1\). For
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle
\]
and \(\chi_{p,q}(x)=q,\chi_{p,q}(y)=p\), the kernel
\[
K_{p,q}=\ker(\chi_{p,q})
\]
is a finite-rank free group.

**Proof.** `FJ34` proves that \(K_{p,q}\) is finitely generated. The
cyclic-amalgam form of \(G_{p,q}\) gives a Bass--Serre tree whose vertex
stabilizers are conjugates of \(\langle x\rangle\) and \(\langle y\rangle\).
The computation above shows that \(K_{p,q}\) intersects every such conjugate
trivially. Therefore \(K_{p,q}\) acts freely on the Bass--Serre tree. A group
acting freely on a tree is free, by the source-verified Bass--Serre freeness
bridge. Since \(K_{p,q}\) is also finitely generated, it is finite-rank free.

**Example.** The group \(G_{p,q}\) is removed from the active `T-001`
residual by the finite-rank free-by-cyclic route of `FJ26`.

**Proof.** The preceding proposition gives \(K_{p,q}\cong F_n\) for some
finite \(n\). The epimorphism \(\chi_{p,q}\colon G_{p,q}\to\mathbb Z\)
splits because \(\gcd(p,q)=1\), giving
\[
G_{p,q}\cong F_n\rtimes\mathbb Z.
\]
This is exactly the finite-rank free-by-cyclic bridge recorded in `FJ26`.

**Warning.** This route does not compute the rank \(n\). It records only the
finite-rank free-by-cyclic bridge needed by `FJ26`.

## Proof or verification

Verification steps completed:

1. Checked the Serre source location for the Bass--Serre chapters.
2. Checked an accessible graph-of-groups formulation recording vertex
   stabilizers as conjugates of vertex groups and citing Serre.
3. Checked an accessible free-action theorem statement for groups acting on
   trees.
4. Applied the Bass--Serre tree to the cyclic amalgam for \(G_{p,q}\).
5. Proved internally that \(K_{p,q}\) intersects all vertex stabilizer
   conjugates trivially.
6. Combined the free-action theorem with Brown finite generation from `FJ34`.
7. Recorded the finite-rank free-by-cyclic bridge through `FJ26`.

## References

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell-Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904.
  https://doi.org/10.1093/imrn/rnac012
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Carrasco, M., & Mackay, J. M. (2022). Conformal dimension of hyperbolic
  groups that split over elementary subgroups. *Inventiones Mathematicae,
  227*, 795--854. https://doi.org/10.1007/s00222-021-01074-w
- Chiswell, I., & Mueller, T. (2012). Free R-tree actions and universality.
  In *A universal construction for groups acting freely on real trees*
  (pp. 61--77). Cambridge University Press.
  https://doi.org/10.1017/CBO9781139176064.005
- Margalit, D. (2017). Office hour three: Groups acting on trees. In M. Clay
  & D. Margalit (Eds.), *Office hours with a geometric group theorist*
  (pp. 45--65). Princeton University Press.
  https://doi.org/10.23943/princeton/9780691158662.003.0003
- Serre, J.-P. (1980). Trees and amalgams. In *Trees* (pp. 1--68). Springer.
  https://doi.org/10.1007/978-3-642-61856-7_1

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ34_nearby_brown_family_generalization.md`
- `modules/cycle_002/FJ35_gpq_kernel_bridge_source_selection.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ34`;
- `FJ35`;
- Brown (1987);
- Serre (1980);
- Carrasco--Mackay (2022);
- Chiswell--Mueller (2012);
- Margalit (2017);
- Bestvina--Fujiwara--Wigglesworth (2023), through `FJ26`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-051`;
- a first-pass resolution of `OQ-053`;
- a finite-rank free-kernel bridge for \(K_{p,q}\);
- a finite-rank free-by-cyclic bridge for the \(G_{p,q}\)-family;
- a `T-001` route subtraction through `FJ26`;
- no new `ER-*` result.

## Open questions generated

- Which residual `RB-004` family or subgroup should be attacked after the
  \(G_{p,q}\)-family route bridge?
- Should the exact rank of \(K_{p,q}\) be computed later, or is finite rank
  sufficient for the route ledger?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ36` and next `FJ37`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the source-verified bridge and next residual question;
- `OPEN_QUESTIONS.md` for `OQ-051`, `OQ-053`, and new next-step questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for the Bass--Serre
  verification sources;
- `NOTATION_LEDGER.md` for \(T_{p,q}\) and the updated \(K_{p,q}\) status;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
