# Module FJ35. Gpq kernel bridge source selection

## Status

Completed

## Module type

Theorem map / Source selection / Attack surface

## Problem

`FJ34` proves that, for
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad p,q\geq2,\quad
\gcd(p,q)=1,
\]
the epimorphism
\[
\chi_{p,q}(x)=q,\qquad \chi_{p,q}(y)=p
\]
has finitely generated kernel. The `FJ26` finite-rank free-by-cyclic route
requires more: the kernel must be identified as a finite-rank free group.

This module decides whether to attack that gap by a direct
Reidemeister--Schreier calculation or by selecting a source-verified structural
bridge.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ30`, the Brown/BNS kernel-recognition theorem map;
- `FJ34`, the \(G_{p,q}\)-family Brown finite-generation computation;
- `ledgers/t001_kernel_recognition.md`;
- Brown's finite-generation result as already recorded in `FJ34`;
- Serre's *Trees* as a newly selected source to verify for the relevant
  Bass--Serre freeness bridge.

## Output target

Produce:

- a precise candidate bridge from Brown finite generation to finite-rank
  freeness;
- a decision about whether torus-knot or fibered-knot sources are needed for
  the next step;
- a source-verification target for the next module.

## Definitions

**Definition.** Let
\[
K_{p,q}=\ker(\chi_{p,q}).
\]

**Definition.** The candidate Bass--Serre freeness bridge for this project is
the following source-to-verify statement: if a group \(G=A*_C B\) acts on its
Bass--Serre tree with vertex stabilizers conjugate to \(A\) and \(B\), and a
subgroup \(H\leq G\) intersects every conjugate of \(A\) and \(B\) trivially,
then \(H\) acts freely on that tree; a group acting freely on a tree is free.

**Warning.** This module does not yet promote the Bass--Serre bridge to a
source-verified theorem inside the project. It selects the exact bridge to
verify next.

## Main work

### Amalgamated-product shape

The presentation
\[
G_{p,q}=\langle x,y\mid x^p=y^q\rangle
\]
has the formal shape of the cyclic amalgam
\[
\langle x\rangle *_{\langle z\rangle} \langle y\rangle,
\qquad z\mapsto x^p,\quad z\mapsto y^q.
\]

This observation is purely presentation-level bookkeeping. To use it as a
kernel-freeness theorem, the project still needs the Bass--Serre source check
specified below.

### Trivial vertex-stabilizer intersections

Assume the Bass--Serre action for the above amalgam has been source-verified.
Then vertex stabilizers are conjugates of \(\langle x\rangle\) and
\(\langle y\rangle\).

For \(n\in\mathbb Z\),
\[
\chi_{p,q}(x^n)=nq.
\]
Since \(q\neq0\), the only power of \(x\) in \(K_{p,q}\) is the identity.
Likewise,
\[
\chi_{p,q}(y^m)=mp,
\]
so the only power of \(y\) in \(K_{p,q}\) is the identity.

Because \(\chi_{p,q}\) is invariant under conjugation, \(K_{p,q}\) also
intersects every conjugate of \(\langle x\rangle\) and \(\langle y\rangle\)
trivially.

Therefore, once the Bass--Serre freeness bridge is source-verified,
\(K_{p,q}\) acts freely on the Bass--Serre tree and is free.

### Finite rank and splitting

`FJ34` already gives finite generation of \(K_{p,q}\) from Brown's checked
criterion. A finitely generated free group has finite rank. Thus the
source-verified Bass--Serre bridge would upgrade `FJ34` from finite
generation to finite-rank freeness.

The quotient map \(\chi_{p,q}\colon G_{p,q}\to\mathbb Z\) splits because
\(\mathbb Z\) is free cyclic and \(\chi_{p,q}\) is onto. Equivalently, choose
integers \(a,b\) with
\[
aq+bp=1
\]
and send \(1\in\mathbb Z\) to \(x^a y^b\). This gives
\[
G_{p,q}\cong K_{p,q}\rtimes\mathbb Z
\]
after the kernel-freeness bridge is verified.

### Decision

The next step should not be a torus-knot or fibered-knot theorem. The
immediate bridge can be made without such a classification if the
Bass--Serre freeness source check succeeds.

The selected next source is Serre's *Trees*, especially the chapter "Trees and
Amalgams" (Serre, 1980). The Springer page has been checked for bibliographic
metadata and chapter location; the exact theorem statement still needs to be
verified before theorem use.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Conditional on a source-verified Bass--Serre freeness bridge
in the form stated above, \(K_{p,q}\) is a finite-rank free group and
\[
G_{p,q}\cong K_{p,q}\rtimes\mathbb Z.
\]

**Proof.** `FJ34` gives finite generation of \(K_{p,q}\). The presentation of
\(G_{p,q}\) has the candidate cyclic-amalgam form
\[
\langle x\rangle *_{\langle z\rangle}\langle y\rangle.
\]
The character \(\chi_{p,q}\) is nonzero on every nontrivial element of
\(\langle x\rangle\) and every nontrivial element of \(\langle y\rangle\),
and the same remains true for their conjugates. Hence \(K_{p,q}\) has trivial
intersection with the candidate vertex stabilizers. A source-verified
Bass--Serre freeness bridge would imply that \(K_{p,q}\) is free. Since it is
already finitely generated, it is finite-rank free. The epimorphism to
\(\mathbb Z\) splits by choosing a lift of \(1\), giving the semidirect product
display.

**Warning.** This is a conditional theorem map, not a completed route bridge.
Do not invoke `FJ26` for the full \(G_{p,q}\)-family until the Bass--Serre
source verification is completed.

## Proof or verification

Verification steps completed:

1. Reused `FJ34` for finite generation of \(K_{p,q}\).
2. Identified the cyclic-amalgam candidate presentation.
3. Checked internally that \(K_{p,q}\) intersects all conjugates of
   \(\langle x\rangle\) and \(\langle y\rangle\) trivially.
4. Selected the Bass--Serre freeness bridge as the clean route to finite-rank
   freeness.
5. Selected Serre's *Trees* as the next source to verify.
6. Deferred torus-knot and fibered-knot sources because they are not needed
   for the immediate bridge.

## References

- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Serre, J.-P. (1980). Trees and amalgams. In *Trees* (pp. 1--68). Springer.
  https://doi.org/10.1007/978-3-642-61856-7_1

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ34_nearby_brown_family_generalization.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ30`;
- `FJ34`;
- Brown (1987);
- Serre (1980), as a selected source for next verification.

## Results produced

This module produced:

- a conditional Bass--Serre route map from Brown finite generation to
  finite-rank freeness for \(K_{p,q}\);
- a decision not to use torus-knot or fibered-knot sources for the immediate
  bridge;
- a selected next source-verification module, `FJ36`;
- no family-level `FJ26` route bridge yet;
- no new `ER-*` result.

## Open questions generated

- Can Serre's *Trees* be verified in the exact Bass--Serre form needed for
  the \(K_{p,q}\) freeness bridge?
- After that verification, should the project record the full
  \(G_{p,q}\)-family as removed through `FJ26`?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ35` and next `FJ36`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the conditional bridge and next question;
- `OPEN_QUESTIONS.md` for `OQ-051`, `OQ-052`, and the new Bass--Serre source
  question;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Serre's *Trees*;
- `NOTATION_LEDGER.md` for \(K_{p,q}\);
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
