# Module FJ34. Nearby Brown family generalization

## Status

Completed

## Module type

Theorem map / Example family / Attack surface

## Problem

`FJ33` proved a concrete finite-rank free-by-cyclic bridge for
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle .
\]

This module tests how much of that argument generalizes to nearby
presentations
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle
\]
without importing unverified torus-knot or one-relator classification claims.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ30`, the Brown/BNS kernel-recognition theorem map;
- `FJ33`, the worked \(G_{2,3}\) route bridge;
- `ledgers/t001_kernel_recognition.md`;
- Brown's Theorem 4.3 and Corollary 3.2 as verified in `FJ30`.

## Output target

Produce:

- a conservative family-level Brown computation for \(G_{p,q}\);
- a clear boundary between finite-generation information and the
  finite-rank free-kernel bridge needed by `FJ26`;
- the next module target.

## Definitions

**Definition.** For integers \(p,q\geq 2\) with \(\gcd(p,q)=1\), define
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle .
\]

**Definition.** Define
\[
\chi_{p,q}\colon G_{p,q}\to\mathbb Z,\qquad
\chi_{p,q}(x)=q,\quad \chi_{p,q}(y)=p.
\]

This is compatible with the relator because
\[
p\chi_{p,q}(x)-q\chi_{p,q}(y)=pq-qp=0.
\]
It is onto because \(\gcd(p,q)=1\).

**Warning.** This module does not claim the standard torus-knot group
interpretation of \(G_{p,q}\), does not claim a family-level fiberedness
theorem, and does not claim that \(\ker(\chi_{p,q})\) is free. It records only
the Brown-positive finite-generation part that follows from the already
checked Brown criterion.

## Main work

### Brown test for \([\chi_{p,q}]\)

Use the cyclically reduced relator
\[
r=x^p y^{-q}.
\]

The proper initial segments give the following \(\chi_{p,q}\)-values:
\[
0,\ q,\ 2q,\ \ldots,\ (p-1)q,\ pq,\ pq-p,\ pq-2p,\ \ldots,\ pq-(q-1)p.
\]

The maximum is \(pq\), and it occurs exactly once.

### Brown test for \([-\chi_{p,q}]\)

For \(-\chi_{p,q}\), the values are:
\[
0,\ -q,\ -2q,\ \ldots,\ -(p-1)q,\ -pq,\ -pq+p,\ -pq+2p,\ \ldots,\ -pq+(q-1)p.
\]

Since \(p,q\geq 2\), all entries after the first are negative. The final
entry is \(-p\). Therefore the maximum is \(0\), and it occurs exactly once.

### Brown conclusion

Since \(\chi_{p,q}(x)=q\) and \(\chi_{p,q}(y)=p\) are both nonzero, Brown's
Theorem 4.3 uses the maximum-occurs-once condition. Both directions pass.

By Brown's Corollary 3.2, \(\ker(\chi_{p,q})\) is finitely generated.

### What generalizes from FJ33

The following parts of the \(G_{2,3}\) proof generalize directly:

- the epimorphism \(\chi_{p,q}\);
- the Brown initial-segment computation;
- finite generation of \(\ker(\chi_{p,q})\) via Brown.

The following parts do not yet generalize inside the repository:

- the explicit braid-presentation change used in `FJ33`;
- the semidirect-product presentation with free kernel;
- the rank calculation for the kernel;
- the torsion-free target-status bridge for the whole family.

Therefore `FJ34` does not invoke the `FJ26` route for the whole
\(G_{p,q}\)-family.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(p,q\geq 2\) with \(\gcd(p,q)=1\). For
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle
\]
and \(\chi_{p,q}(x)=q,\chi_{p,q}(y)=p\), Brown's two-generator one-relator
criterion verifies both \([\chi_{p,q}]\) and \([-\chi_{p,q}]\). Consequently
\(\ker(\chi_{p,q})\) is finitely generated.

**Proof.** The Brown initial-segment values for \(\chi_{p,q}\) are listed
above; the maximum \(pq\) occurs exactly once. For \(-\chi_{p,q}\), all
values after the initial \(0\) are negative, so the maximum \(0\) occurs
exactly once. Since both generator values are nonzero, Brown's Theorem 4.3
applies in both directions. Brown's Corollary 3.2 then gives finite
generation of the kernel.

**Warning.** This proposition is not yet a finite-rank free-by-cyclic bridge.
The project still needs a proof or source identifying
\(\ker(\chi_{p,q})\) as a finite-rank free group before `FJ26` can be invoked
for the family.

## Proof or verification

Verification steps completed:

1. Defined the family \(G_{p,q}\) with \(p,q\geq 2\) and \(\gcd(p,q)=1\).
2. Checked that \(\chi_{p,q}\) respects the relator and is onto.
3. Computed the Brown initial-segment values for \(\chi_{p,q}\).
4. Computed the Brown initial-segment values for \(-\chi_{p,q}\).
5. Applied Brown's Theorem 4.3 and Corollary 3.2 as recorded in `FJ30`.
6. Marked the missing free-kernel and target-status bridges.

## References

- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ33_worked_brown_test_g23.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ30`;
- `FJ33`;
- Brown (1987).

## Results produced

This module produced:

- a first-pass resolution of `OQ-049`;
- a first-pass resolution of `OQ-050`;
- a Brown-positive finite-generation result for the \(G_{p,q}\)-family;
- no family-level `FJ26` route bridge;
- no new `ER-*` result.

## Open questions generated

- Can \(\ker(\chi_{p,q})\) be identified as a finite-rank free group by an
  internal Reidemeister--Schreier computation?
- Which source, if any, should be used before the project records a
  family-level torus-knot or fibered-kernel theorem?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ34` and next `FJ35`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the family Brown computation and next questions;
- `OPEN_QUESTIONS.md` to mark `OQ-049` and `OQ-050` first-pass resolved;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Brown's `FJ34` use;
- `NOTATION_LEDGER.md` for \(G_{p,q}\) and \(\chi_{p,q}\);
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
