# Module FJ32. Nontrivial Brown test-family selection for T-001

## Status

Completed

## Module type

Attack surface / Example selection / Theorem map

## Problem

After `FJ31`, the project has a Brown criterion calibration example, but the
example is abelian and already removed by the virtually solvable route.

This module chooses the next Brown-compatible test case or small test family
for `T-001`, with enough preliminary computation to justify why the next
module should spend a full worked example on it.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ30`, the Brown/BNS kernel-recognition theorem map;
- `FJ31`, the commutator-presentation calibration example;
- `ledgers/t001_kernel_recognition.md`;
- Brown's Theorem 4.3 and Corollary 3.2 as verified in `FJ30`.

## Output target

Produce:

- a selected nonabelian two-generator one-relator Brown test case;
- a preliminary Brown maximum-count computation;
- a route-overlap warning;
- exact follow-up questions for the next worked module.

## Definitions

**Definition.** The selected next Brown test case is
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle .
\]

**Definition.** The selected character is the epimorphism
\[
\chi\colon G_{2,3}\to\mathbb Z,\qquad \chi(x)=3,\quad \chi(y)=2.
\]

This is compatible with the defining relator because
\[
2\chi(x)-3\chi(y)=6-6=0.
\]
It is onto because \(2\) and \(3\) generate \(\mathbb Z\) as an ideal.

**Warning.** This module selects and prepares the test case. It does not yet
record a new `T-001` route subtraction. In particular, the project must still
verify the target-status bridge needed for `T-001` and the finite-rank
free-kernel bridge needed for `FJ26`.

## Main work

### Selection criteria

The next Brown test should satisfy the following project constraints:

1. It should be a two-generator one-relator presentation, so Brown's checked
   criterion from `FJ30` is directly applicable.
2. It should not be the abelian commutator calibration example from `FJ31`.
3. It should have a visible epimorphism to \(\mathbb Z\).
4. It should not be treated as removed by the virtually solvable route unless
   the repository records a virtual-solvability bridge.
5. It should be small enough for the next module to compute the Brown
   initial-segment sequence explicitly.

The presentation
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle
\]
meets these selection criteria at the project-bookkeeping level.

### Nonabelian check

There is a quotient map from \(G_{2,3}\) onto the nonabelian symmetric group
\(S_3\):
\[
x\mapsto (12),\qquad y\mapsto (123).
\]

The defining relation is respected because
\[
(12)^2=e=(123)^3.
\]
The two permutations \((12)\) and \((123)\) generate \(S_3\). Therefore
\(G_{2,3}\) is nonabelian.

This is an internal verification, not an external literature claim.

### Preliminary Brown computation

Use the cyclically reduced relator
\[
r=xxy^{-1}y^{-1}y^{-1}.
\]

The proper initial segments and \(\chi\)-values are:

| \(i\) | \(s_i\) | \(\chi(s_i)\) |
|---|---|---|
| 1 | \(1\) | 0 |
| 2 | \(x\) | 3 |
| 3 | \(x^2\) | 6 |
| 4 | \(x^2y^{-1}\) | 4 |
| 5 | \(x^2y^{-2}\) | 2 |

The maximum is \(6\), and it occurs exactly once.

For \(-\chi\), the values are:

| \(i\) | \(s_i\) | \(-\chi(s_i)\) |
|---|---|---|
| 1 | \(1\) | 0 |
| 2 | \(x\) | -3 |
| 3 | \(x^2\) | -6 |
| 4 | \(x^2y^{-1}\) | -4 |
| 5 | \(x^2y^{-2}\) | -2 |

The maximum is \(0\), and it occurs exactly once.

Since \(\chi(x)\) and \(\chi(y)\) are both nonzero, this is the
nonzero-on-both-generators case in Brown's Theorem 4.3 as recorded in
`FJ30`. The preliminary computation therefore indicates that both
\([\chi]\) and \([-\chi]\) should pass Brown's maximum-count test.

### Route status

This selected case is not yet a new Farrell--Jones-positive row inside the
project.

What the project has now:

- a nonabelian two-generator one-relator presentation;
- an epimorphism to \(\mathbb Z\);
- a preliminary Brown-positive computation for both directions;
- no recorded virtual-solvability bridge for this presentation;
- no completed finite-rank free-kernel identification for this presentation.

What the project still needs before using the `FJ26` route:

- a full `FJ33` Brown test record;
- a proof or citation that the kernel is finite-rank free, not merely
  finitely generated;
- a target-status check showing that the selected group belongs to the
  torsion-free one-relator setting used by `T-001`, or a warning that it is
  only a Brown-workflow example.

## Proposition / Theorem / Conjecture / Example

**Example.** The presentation
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle
\]
with \(\chi(x)=3\), \(\chi(y)=2\) is selected as the next Brown test case.
It is nonabelian, and the preliminary Brown maximum-count computation passes
for both \([\chi]\) and \([-\chi]\).

**Proof.** The relation is compatible with \(\chi\) because
\(2\chi(x)-3\chi(y)=0\), and \(\chi\) is onto since \(2\) and \(3\) are
coprime.

The quotient map to \(S_3\) described above proves that \(G_{2,3}\) is
nonabelian.

The relator \(xxy^{-1}y^{-1}y^{-1}\) gives the \(\chi\)-values
\[
0,\ 3,\ 6,\ 4,\ 2,
\]
whose maximum occurs exactly once. For \(-\chi\), the values are
\[
0,\ -3,\ -6,\ -4,\ -2,
\]
whose maximum again occurs exactly once. Since both \(\chi(x)\) and
\(\chi(y)\) are nonzero, this is the relevant maximum-count condition from
Brown's Theorem 4.3 as recorded in `FJ30`.

**Warning.** Brown's Corollary 3.2 gives finite generation of the kernel once
both directions pass, but the `FJ26` route needs a finite-rank free-kernel
bridge. This module does not yet supply that bridge.

## Proof or verification

Verification steps completed:

1. Checked that the chosen \(\chi\) respects the relator.
2. Verified that \(\chi\) is onto.
3. Verified nonabelianness by an explicit quotient to \(S_3\).
4. Computed the preliminary Brown initial-segment values for \(\chi\) and
   \(-\chi\).
5. Selected `FJ33` as the next full worked Brown test.

## References

- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ31_first_brown_test_case.md`
- `ledgers/t001_kernel_recognition.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ30`;
- `FJ31`;
- Brown (1987).

## Results produced

This module produced:

- a first-pass resolution of `OQ-045`;
- a first-pass resolution of `OQ-046`;
- the selected next Brown test case \(G_{2,3}\);
- no new `ER-*` result.

## Open questions generated

- Does \(G_{2,3}\) have a source-verified or internally proved target-status
  bridge for `T-001`?
- Can the Brown-positive kernel in \(G_{2,3}\to\mathbb Z\) be identified as a
  finite-rank free group?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ32` and next `FJ33`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the selected Brown test case and new open questions;
- `OPEN_QUESTIONS.md` to mark `OQ-045` and `OQ-046` first-pass resolved and
  add the next kernel-bridge questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Brown's `FJ32` use;
- `NOTATION_LEDGER.md` for \(G_{2,3}\);
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
