# Module FJ42. Bieri Source Access and Route Delta

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

`FJ38` selected Bieri (1976) as part of the beyond-Brown normal-subgroup
source cluster for `RB-004`. `FJ39` used Bieri only as a cited dependency
inside Karrass--Solitar, and `FJ41` verified direct BNS finite-generation
theorem use without producing a finite-rank free-kernel bridge.

The problem is to decide whether Bieri (1976) gives the project an actionable
normal-subgroup bridge, and under which finiteness hypothesis, without
importing a cohomological-dimension theorem from memory.

## Input

- `FJ38`, beyond-Brown `RB-004` source selection;
- `FJ39`, Karrass--Solitar finitely presented normal-subgroup bridge;
- `FJ41`, direct Bieri--Neumann--Strebel finite-generation verification;
- `reflections/strategic_audit_after_cycle_002.md`;
- `OQ-057` and `OQ-063`;
- Bieri (1976), with ScienceDirect/Elsevier metadata checked;
- Osajda (2021) and Margolis (2026) as comparison sources only.

## Output target

Record whether Bieri (1976) can be used as a source-verified theorem input
for `RB-004`, and record the route change forced by the exact source-status
boundary.

## Definitions

**Definition.** In this module, \(\operatorname{cd}(G)\) denotes the
cohomological dimension of a group \(G\), used only at source level.

**Definition.** A group is of type \(VFP\) if it has a finite-index subgroup
whose trivial integral module has a finite projective resolution by finitely
generated modules. This is the convention stated in Margolis (2026).

**Warning.** This module distinguishes three statuses:

- `Source-verified claim`: checked directly in the source being used.
- `Literature claim`: reported in a later source, but not directly checked in
  the original cited source here.
- `Route decision`: a project-management consequence that follows from the
  current source statuses, not a new mathematical theorem.

## Main work

### Source access result

**Source-verified claim.** The Bieri article metadata was checked through the
ScienceDirect/Elsevier record: Bieri's article is "Normal subgroups in duality
groups and in groups of cohomological dimension 2," published in *Journal of
Pure and Applied Algebra*, volume 7, issue 1, pages 35--51, with DOI
`10.1016/0022-4049(76)90065-7` (Bieri, 1976).

**Warning.** The primary theorem text of Bieri (1976) was not directly
extracted in this run. The ScienceDirect page and API metadata were reachable,
but the direct PDF/full-text endpoint was not usable from this environment.
Therefore this module does not upgrade any theorem from Bieri (1976) to
`Source-verified claim`.

### Comparison-source evidence

**Literature claim.** Osajda (2021) reports that Bieri (1976), Theorem B,
gives the following kind of statement: a finitely presented normal subgroup of
a group with cohomological dimension at most \(2\) is forced into the
free-or-finite-index alternative. This is useful evidence about the relevant
finiteness hypothesis, but it is not a direct check of Bieri's paper in this
repository.

**Literature claim.** Margolis (2026) reports that Bieri (1976), Theorem A,
concerns a normal subgroup \(H\) of type \(VFP\) inside a duality group \(G\),
with both \(H\) and \(G/H\) becoming duality groups. Margolis also records a
modern commensurated-subgroup analogue and a one-relator consequence under a
finitely presented subgroup hypothesis.

**Warning.** The comparison sources point toward finite presentation or type
\(VFP\), not mere finite generation. They do not by themselves authorize a
Bieri theorem-use row in this project.

### Route-delta table

| Possible bridge | Current verification status | Visible finiteness hypothesis | Route delta |
|---|---|---|---|
| Bieri (1976), CD \(\leq 2\) normal-subgroup theorem | literature claim only in this module | finitely presented normal subgroup | reinforces the finite-presentation bottleneck; no residual subtraction |
| Bieri (1976), duality-group theorem | literature claim only in this module | type \(VFP\) normal subgroup | not an immediate `RB-004` free-kernel bridge |
| Karrass--Solitar (1978) | source-verified in `FJ39` | nontrivial finitely presented normal subgroup of infinite index | remains the usable one-relator bridge, but still needs a matching example |
| BNS Theorem B1 | source-verified in `FJ41` | finite generation plus BNS membership data | still needs a \(\Sigma(G)\) computation before route use |

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ42` produces no new `T-001` residual subtraction.

## Proof or verification

The only directly verified Bieri input in this run is bibliographic and
access-status information. The theorem text itself was not available for
primary-source inspection, so a Bieri theorem cannot be imported under the
project's source rules.

The comparison sources nevertheless sharpen the route decision. Both the
CD-\(2\) comparison and the duality-group comparison point to stronger
finiteness hypotheses than finite generation. Thus `FJ42` confirms that the
current source cluster has not escaped the finite-presentation/type-\(VFP\)
bottleneck already seen in `FJ39`. A later module may still verify Bieri
directly, but the next project move should be a route-delta checkpoint rather
than an automatic jump to more source bookkeeping.

## References

- Bieri, R. (1976). Normal subgroups in duality groups and in groups of
  cohomological dimension 2. *Journal of Pure and Applied Algebra, 7*(1),
  35--51. https://doi.org/10.1016/0022-4049(76)90065-7
- Margolis, A. J. (2026). Groups of cohomological codimension one. *Annales
  de l'Institut Fourier*, Online first. https://doi.org/10.5802/aif.3766
- Osajda, D. (2021). *Normal subgroups of SimpHAtic groups*
  (arXiv:1501.00951v2). arXiv. https://arxiv.org/abs/1501.00951

## Dependencies

This module depends on:

- `FJ38`;
- `FJ39`;
- `FJ41`;
- `OQ-057`;
- `OQ-063`;
- Bieri (1976);
- Karrass--Solitar (1978), as the currently source-verified comparison
  bridge.

## Results produced

This module produced:

- no established result number;
- a source-status correction for Bieri (1976);
- a route-delta decision: continue to `FJ43`, a checkpoint on whether the
  BNS/Bieri/Karrass--Solitar source cluster is still mathematically advancing
  `RB-004`.

## Open questions generated

- `OQ-064`: Should `RB-004` continue through Bieri--Renz/BNS source
  verification, or should the project pivot because the current source cluster
  has not produced a new concrete route?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for `OQ-057`, `OQ-063`, and the new route checkpoint;
- `NOTATION_LEDGER.md` for \(\operatorname{cd}(G)\), \(VFP\), and
  \(\operatorname{vcd}(G)\);
- `OPEN_QUESTIONS.md` for `OQ-057`, `OQ-063`, and `OQ-064`;
- `BIBLIOGRAPHY.md` for Bieri source status and the comparison sources;
- `ledgers/source_status.md` for source statuses;
- `ledgers/t001_kernel_recognition.md` and `ledgers/t001_residual.md` for the
  route-delta decision;
- `README.md` and `PROJECT_CHARTER.md` for the new current target.
