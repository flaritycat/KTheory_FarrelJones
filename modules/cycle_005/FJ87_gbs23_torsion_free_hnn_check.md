# Module FJ87. G_BS23 Torsion-Free HNN Check

## Status

Completed

## Module type

Candidate-status verification / Bridge check / Payload-instantiated module

## Problem

After `FJ86`, the candidate row `CAND-T001-004` for
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle
\]
was concrete but blocked. One of the missing items was torsion-free / HNN
status.

The user request "Continue with FJ87 by checking whether G_BS23 is
torsion-free" supplies a bounded payload: check only the torsion-free status
of `CAND-T001-004`, update the ledgers, and stop without claiming a
Farrell--Jones route.

## Input

- `FJ86`;
- `OQ-108`;
- `OBL-C5-007`;
- `OBL-T001-016`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`;
- accepted payload `PAY-T001-BS23-TF-HNN-2026-001`.

## Output target

FJ87 should:

- record the accepted payload as the exit object for `OQ-108` and
  `OBL-C5-007`;
- verify whether \(G_{BS23}\) is torsion-free at first pass;
- update `CAND-T001-004` accordingly;
- leave kernel control, route output, and prior-art comparison unresolved;
- make no full `T-001`, coefficient FJC, `FJCw`, `FICwF`, full
  \(\mathcal{FJ}\), or residual-subtraction claim.

## Definitions

**Definition.** Let
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle.
\]
Equivalently,
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}=a^3\rangle.
\]

**Definition.** Let \(A=\langle a\rangle\cong\mathbb Z\),
\(C=\langle a^2\rangle\leq A\), \(D=\langle a^3\rangle\leq A\), and
\[
\phi:C\to D,\qquad \phi(a^{2k})=a^{3k}.
\]
Then \(G_{BS23}\) is the HNN extension of \(A\) with stable letter \(t\) and
associated-subgroup isomorphism \(\phi\).

**Warning.** Verifying torsion-free status does not give a Farrell--Jones
route. The kernel of \(\chi(t)=1,\chi(a)=0\) remains uncontrolled in this
module.

## Main work

### Accepted payload

| Field | FJ87 record |
| --- | --- |
| Payload ID | `PAY-T001-BS23-TF-HNN-2026-001` |
| Payload type | `PAY-T001-BRIDGE` |
| Target gates | `OQ-108`, `OBL-C5-007`, and `OBL-T001-016` |
| Object | Torsion-free / HNN status check for `CAND-T001-004`, \(G_{BS23}\). |
| Repository objects changed | `ledgers/payload_intake_protocol.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; `README.md`; `PROJECT_CHARTER.md`; `NOTATION_LEDGER.md`; `ledgers/open_group_classes.md`; `BIBLIOGRAPHY.md`; `ledgers/source_status.md`. |
| Stop condition | Stop after torsion-free / HNN status and ledger update. Do not compute the kernel, audit prior art, or claim a Farrell--Jones route. |

### HNN form

The relator \(t a^2t^{-1}a^{-3}\) is equivalent to
\[
t a^2t^{-1}=a^3.
\]
Thus the presentation has the form
\[
\langle A,t\mid tct^{-1}=\phi(c),\ c\in C\rangle
\]
with \(A=\langle a\rangle\cong\mathbb Z\), \(C=\langle a^2\rangle\),
\(D=\langle a^3\rangle\), and \(\phi(a^{2k})=a^{3k}\).

The associated-subgroup map is an isomorphism \(C\cong D\), since both are
infinite cyclic and \(a^{2k}\mapsto a^{3k}\) preserves the exponent \(k\).

### Bass--Serre tree

`FJ36` records the Bass--Serre framework used in the project: a graph-of-
groups or HNN decomposition has an associated Bass--Serre tree, and vertex
stabilizers are conjugates of the vertex group. The source anchor recorded
there is Serre's *Trees*, with Carrasco--Mackay as an accessible stabilizer
formulation citing Serre (Carrasco & Mackay, 2022; Serre, 1980).

For this HNN extension, \(G_{BS23}\) acts without inversions on its
Bass--Serre tree \(T\), and every vertex stabilizer is conjugate to
\(A=\langle a\rangle\).

### Finite-order elements

Let \(g\in G_{BS23}\) have finite order. The cyclic group \(\langle g\rangle\)
has a finite orbit on \(T\). Let \(S\) be the finite subtree spanned by this
orbit. The action of \(\langle g\rangle\) preserves \(S\).

An automorphism of a finite tree fixes its center, which is either a vertex
or the midpoint of an edge. Since the Bass--Serre action is without
inversions, an edge-midpoint fixed point gives a fixed edge and hence fixed
vertices after passing to the action on the tree. Therefore \(g\) fixes a
vertex of \(T\).

Thus \(g\) lies in a vertex stabilizer, hence in a conjugate of
\(\langle a\rangle\cong\mathbb Z\). Since \(\mathbb Z\) is torsion-free, the
only finite-order element in any conjugate of \(\langle a\rangle\) is the
identity. Therefore \(g=1\).

### Candidate-status effect

FJ87 changes the `CAND-T001-004` row only in the torsion-free / HNN field:
\(G_{BS23}\) is now first-pass verified as torsion-free by the HNN /
Bass--Serre argument above.

FJ87 does not compute:

- the kernel of \(\chi(t)=1,\chi(a)=0\);
- Brown or BNS data;
- hyperbolicity;
- a CAT(0) or special-cube route;
- virtual solvability;
- finite-index / `FJCw` data;
- prior-art coverage.

## Proposition / Theorem / Conjecture / Example

**Proposition.** \(G_{BS23}\) is torsion-free.

This is a candidate-status proposition for `CAND-T001-004`, not a
Farrell--Jones theorem.

## Proof or verification

As above, write \(G_{BS23}\) as the HNN extension of
\(A=\langle a\rangle\cong\mathbb Z\) with associated subgroups
\(\langle a^2\rangle\) and \(\langle a^3\rangle\).

The Bass--Serre tree for this HNN extension has vertex stabilizers conjugate
to \(A\). If an element \(g\) has finite order, then \(\langle g\rangle\)
acts on the Bass--Serre tree with a finite orbit. The finite subtree spanned
by that orbit has a fixed center under \(\langle g\rangle\), and the
without-inversions condition gives a fixed vertex. Hence \(g\) is conjugate
into \(A\). Since \(A\cong\mathbb Z\) is torsion-free, \(g=1\).

Therefore every finite-order element of \(G_{BS23}\) is trivial.

## References

No new external source was checked in FJ87. The module uses the Bass--Serre
source package already recorded in `FJ36`.

- Carrasco, M., & Mackay, J. M. (2022). Conformal dimension of hyperbolic
  groups that split over elementary subgroups. *Inventiones Mathematicae,
  227*, 795--854. https://doi.org/10.1007/s00222-021-01074-w
- Serre, J.-P. (1980). Trees and amalgams. In *Trees* (pp. 1--68). Springer.
  https://doi.org/10.1007/978-3-642-61856-7_1

Internal references:

- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`;
- `modules/cycle_005/FJ86_t001_candidate_intake_audit.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Dependencies

This module depends on:

- `FJ36`;
- `FJ86`;
- `OQ-108`;
- `OBL-C5-007`;
- `OBL-T001-016`;
- Serre (1980), as already recorded in `FJ36`;
- Carrasco--Mackay (2022), as already recorded in `FJ36`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-BS23-TF-HNN-2026-001`;
- first-pass resolution of `OQ-108`;
- completion of `OBL-C5-007` for FJ87;
- first-pass torsion-free / HNN verification for `CAND-T001-004`;
- partial completion of `OBL-T001-016`, only for the torsion-free-status
  component;
- proof obligation `OBL-T001-017`;
- proof obligation `OBL-C5-008`;
- no new `ER-*` result;
- no Farrell--Jones route;
- no residual subtraction.

## Open questions generated

- `OQ-109`: Which accepted payload, if any, should instantiate `FJ88` after
  the FJ87 torsion-free / HNN check for \(G_{BS23}\)?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `NOTATION_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`.
