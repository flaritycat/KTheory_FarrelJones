# Module FJ39. Normal-subgroup bridge source verification for RB-004

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

`FJ38` selected a normal-subgroup source cluster for `RB-004`, the problem of
turning epimorphisms to \(\mathbb Z\) or HNN data into finite-rank
free-by-cyclic route bridges. The next task is to check what the selected
sources actually provide, without converting source-selection hope into a
route theorem.

## Input

This module uses:

- `FJ30`, Brown/BNS kernel-recognition verification;
- `FJ38`, beyond-Brown source selection;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `OQ-043`, `OQ-044`, `OQ-057`, and `OQ-058`;
- Karrass--Solitar (1978), directly checked from the article PDF;
- Bieri--Neumann--Strebel (1987), checked only at orientation level here;
- Bieri--Renz (1988), bibliographic and source-role checked only here;
- Bieri (1976), not directly checked from the primary article in this module.

## Output target

Produce:

- the exact usable hypothesis from the checked Karrass--Solitar bridge;
- a warning about what this does not yet prove for `RB-004`;
- a status update for BNS, Bieri--Renz, and Bieri;
- the next module target.

## Definitions

**Definition.** A finitely presented normal-subgroup bridge is a source-verified
statement that starts with a one-relator group \(G\) and a nontrivial finitely
presented normal subgroup \(H\trianglelefteq G\) of infinite index, then
concludes structural information strong enough to look for a finite-rank
free-by-cyclic or virtually free-by-cyclic route.

**Warning.** Finitely generated is weaker than finitely presented. `FJ39`
does not replace Brown's finite-generation criterion by a global one-relator
finite-rank kernel theorem.

## Main work

### Karrass--Solitar verification

**Source-verified claim.** Karrass and Solitar (1978) prove the following
one-relator normal-subgroup theorem in the form needed for this project:

If \(G\) is a one-relator group with a nontrivial finitely presented normal
subgroup \(H\) of infinite index, then \(G\) is torsion-free, has two
generators, and is either an infinite cyclic or an infinite dihedral extension
of a finitely generated free group \(N\). The theorem further specifies how
\(H\) relates to \(N\): in the noncyclic case \(H\) may be chosen inside
\(N\), while in the cyclic case \(H\cap N\) is trivial.

This statement is directly relevant to `RB-004`, but its input is finite
presentation of the normal subgroup, not mere finite generation.

### Bieri dependency status

Karrass--Solitar's proof explicitly invokes Bieri's cohomological-dimension
machinery, including Bieri (1976). In this module, Bieri (1976) is therefore
verified only as a dependency cited by the checked Karrass--Solitar proof, not
as an independently checked theorem source. The exact Bieri theorem and
corollary hypotheses remain unavailable for direct project use until the
primary text is checked.

### BNS and Bieri--Renz status

Bieri--Neumann--Strebel (1987) remains selected for direct verification.
The article introduction confirms the intended subject: an invariant for
finitely generated groups that records finite-generation information for
kernels of abelian quotients. `FJ39` does not verify the exact normal-subgroup
theorem statement from the original paper.

Bieri--Renz (1988) remains selected only as secondary finiteness-property
context. This module does not verify a direct `RB-004` theorem from
Bieri--Renz, and does not use \(\mathrm{FP}_2\) or higher \(\mathrm{FP}_m\)
criteria as route input.

### Consequence for RB-004

The project now has a checked bridge with the following narrow input:

\[
\text{one-relator }G
\quad+\quad
1\ne H\trianglelefteq G
\quad+\quad
H\text{ finitely presented}
\quad+\quad
[G:H]=\infty.
\]

The output is structural: \(G\) is virtually an extension of a finite-rank
free group by a virtually cyclic group. This is close to the `FJ26`
finite-rank free-by-cyclic route, but not automatically identical to it. If
the quotient is infinite cyclic, the bridge is directly aligned with `FJ26`.
If the quotient is infinite dihedral, a finite-index passage would have to be
handled with the version-aware inheritance discipline from `FJ27`.

No new residual bucket is removed by this module.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ39` verifies Karrass--Solitar (1978) as a usable
normal-subgroup bridge source only under the hypothesis that the normal
subgroup is nontrivial, finitely presented, and of infinite index.

**Proof.** The checked Karrass--Solitar article states the theorem with those
hypotheses and concludes that the ambient one-relator group is torsion-free,
two-generator, and an infinite cyclic or infinite dihedral extension of a
finitely generated free group. This supplies a genuine bridge source, but it
does not apply to kernels known only to be finitely generated. Therefore it is
usable only for a finitely presented-kernel subroute of `RB-004`.

**Remark.** This is a source-verified bridge theorem map, not an internal
proof and not an `ER-*` result.

## Proof or verification

Verification completed:

1. Checked the Karrass--Solitar PDF directly and extracted the theorem
   hypotheses and conclusion.
2. Checked that the theorem input is finitely presented normal subgroup of
   infinite index, not merely finitely generated normal subgroup.
3. Checked that the Karrass--Solitar proof cites Bieri's cohomological
   dimension results, but did not independently verify Bieri (1976).
4. Checked BNS only at orientation level for finite-generation information
   about kernels of abelian quotients.
5. Left Bieri--Renz as selected higher-finiteness context, with no route use.

## References

- Bieri, R. (1976). Normal subgroups in duality groups and in groups of
  cohomological dimension 2. *Journal of Pure and Applied Algebra, 7*(1),
  35--51. https://doi.org/10.1016/0022-4049(76)90065-7
- Bieri, R., Neumann, W. D., & Strebel, R. (1987). A geometric invariant of
  discrete groups. *Inventiones Mathematicae, 90*, 451--478.
  https://doi.org/10.1007/BF01389175
- Bieri, R., & Renz, B. (1988). Valuations on free resolutions and higher
  geometric invariants of groups. *Commentarii Mathematici Helvetici, 63*(3),
  464--497. https://doi.org/10.1007/BF02566775
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222.
  https://doi.org/10.1090/S0002-9939-1978-0466323-3

Internal references:

- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ38_rb004_beyond_brown_source_selection.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ30`;
- `FJ38`;
- `OQ-043`;
- `OQ-044`;
- `OQ-057`;
- `OQ-058`;
- Karrass--Solitar (1978), directly checked;
- Bieri (1976), only as a cited dependency inside Karrass--Solitar;
- Bieri--Neumann--Strebel (1987), orientation only;
- Bieri--Renz (1988), orientation only.

## Results produced

This module produced:

- a first-pass partial resolution of `OQ-057`: the checked bridge requires a
  finitely presented normal subgroup;
- a warning that BNS finite-generation use remains unverified directly;
- a new finitely presented-kernel subroute inside `RB-004`;
- no new `ER-*` result;
- no residual subtraction.

## Open questions generated

- Which concrete `RB-004` example has a nontrivial finitely presented kernel
  of infinite index, if any?
- Can the infinite-dihedral alternative in Karrass--Solitar be routed through
  existing finite-index inheritance rows without changing formulations?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ39` and next `FJ40`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for `OQ-057` and new bridge questions;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
