# Module FJ38. RB-004 beyond-Brown source selection

## Status

Completed

## Module type

Source selection / Attack surface / Literature verification

## Problem

`FJ37` selected `OQ-044` as the next active target: identify a source or
source cluster for `RB-004` cases outside Brown's checked two-generator
one-relator criterion.

Brown (1987) remains useful, but `FJ30` deliberately records it as a limited
route: its explicit one-relator computation is best understood in the project
for compatible two-generator one-relator presentations. The next source move
must widen the source toolkit without pretending that an unverified theorem
has already been proved or imported.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ29`, the selection of `RB-004`;
- `FJ30`, the Brown/BNS kernel-recognition theorem map;
- `FJ37`, the post-\(G_{p,q}\) residual audit;
- `ledgers/t001_kernel_recognition.md`;
- `references/papers_to_read.md`;
- `OQ-043`, `OQ-044`, and `OQ-056`;
- bibliographic checks for candidate sources.

## Output target

Produce:

- a selected source cluster for `RB-004` beyond Brown's checked
  two-generator criterion;
- a warning about what the selected cluster does not yet prove;
- a next module target for source verification;
- bibliography and source-status updates with APA-style citations.

## Definitions

**Definition.** A normal-subgroup bridge source is a source that may connect
normal-subgroup finiteness hypotheses in a one-relator or cohomological
dimension \(2\) setting to freeness, finite rank, or cyclic-extension
structure.

**Definition.** The `RB-004` source cluster selected in this module is a set
of sources to verify together because the route needs both finiteness
recognition and a one-relator normal-subgroup structure bridge.

**Warning.** Source selection is not theorem use. No source selected in this
module is available for route subtraction until a later module checks exact
statements and hypotheses.

## Main work

### What the next source must do

For a torsion-free one-relator group and a map
\[
G\to \mathbb Z,
\]
the `FJ26` route needs a bridge of the form
\[
1\to F_n\to G\to \mathbb Z\to 1,\qquad n<\infty.
\]

Outside Brown's checked two-generator criterion, this splits into two source
questions:

1. How can the project recognize that the kernel is finitely generated, or
   satisfies a stronger finiteness property?
2. Once such a normal subgroup is known to be finite enough, which
   one-relator or cohomological dimension source turns that into a free or
   free-by-cyclic bridge?

`FJ38` therefore selects a source cluster rather than a single paper.

### Candidate source audit

| Candidate source | Metadata check | Selection decision | Reason |
|---|---|---|---|
| Bieri--Neumann--Strebel (1987) | EuDML record checked. | Selected as foundational finite-generation source. | It is the original BNS source behind Brown's invariant and is directly relevant to finitely generated kernels of abelian quotients. |
| Bieri--Renz (1988) | EuDML record checked. | Selected as secondary finiteness source. | It records higher geometric invariants and is relevant if the normal-subgroup bridge requires \(\mathrm{FP}_n\), finite presentation, or higher finiteness hypotheses. |
| Bieri (1976) | ScienceDirect metadata checked. | Selected as normal-subgroup bridge source. | It is explicitly about normal subgroups in duality groups and groups of cohomological dimension \(2\), a context adjacent to torsion-free one-relator groups. Exact hypotheses must be verified before use. |
| Karrass--Solitar (1978) | AMS metadata and abstract checked. | Selected as one-relator normal-subgroup comparator. | The AMS abstract states that it classifies one-relator groups with a finitely presented normal subgroup of infinite index. Exact theorem form must be checked before use. |
| Friedl--Tillmann (2020) | Annales de l'Institut Fourier metadata and abstract checked. | Background, not the immediate beyond-Brown source. | It modernizes BNS computations for two-generator one-relator groups, so it is Brown-adjacent rather than genuinely beyond the checked two-generator setting. |
| Kielak (2020) | arXiv and Inventiones metadata checked. | Background/possible later source. | It connects BNS invariants with Newton polytopes for several classes, including deficiency-one/agrarian contexts; the hypotheses are too specialized for immediate route use without later verification. |

### Selected source cluster

**Selection.** The next source cluster is:

1. Bieri--Neumann--Strebel (1987), for the direct BNS normal-subgroup
   finiteness theorem rather than Brown's restatement;
2. Bieri--Renz (1988), for higher finiteness invariant context if finite
   presentation or \(\mathrm{FP}_2\)-type hypotheses become necessary;
3. Bieri (1976), for normal subgroups in groups of cohomological dimension
   \(2\);
4. Karrass--Solitar (1978), for the one-relator-specific finitely presented
   normal-subgroup classification.

This cluster is selected because `RB-004` outside Brown needs more than a
new computation. It needs a route skeleton:

\[
\text{kernel finiteness} \quad+\quad
\text{one-relator normal-subgroup structure}
\quad\Longrightarrow\quad
\text{possible finite-rank free-by-cyclic bridge}.
\]

**Warning.** This implication is a route skeleton, not a theorem recorded by
the project. The later source-verification module must check every arrow and
every hypothesis.

### Next module target

The next module should be:

```text
FJ39. Normal-subgroup bridge source verification for RB-004
```

It should verify:

- whether BNS (1987) supplies the finite-generation criterion needed beyond
  Brown's checked two-generator criterion;
- whether Bieri--Renz (1988) is needed for stronger finiteness properties;
- whether Bieri (1976) or Karrass--Solitar (1978) supplies a usable
  one-relator/CD2 bridge from a finite-enough normal subgroup of infinite
  index to a free or free-by-cyclic structure;
- exactly whether the needed hypothesis is finitely generated, finitely
  presented, \(\mathrm{FP}_2\), or something else.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ38` selects the BNS/Bieri--Renz/Bieri/Karrass--Solitar
normal-subgroup source cluster as the next `RB-004` beyond-Brown source
cluster, with `FJ39` assigned to verify exact theorem statements and
hypotheses.

**Proof.** `FJ30` records that Brown's explicit one-relator computation is
limited to compatible two-generator one-relator presentations. `FJ37`
selects `OQ-044`, the beyond-Brown source question. The selected cluster
matches the two pieces missing outside Brown: BNS and Bieri--Renz address
geometric invariant and finiteness-property tools, while Bieri and
Karrass--Solitar are directly about normal subgroups in cohomological
dimension \(2\) or one-relator settings. Bibliographic metadata has been
checked for all four selected sources. Therefore this cluster is the next
bounded source-verification target.

**Remark.** This proposition is a project-selection result. It is not a
mathematical theorem about one-relator groups and should not receive an
`ER-*` number.

## Proof or verification

Verification steps completed:

1. Checked the existing Brown limitations in `FJ30` and
   `ledgers/t001_kernel_recognition.md`.
2. Checked the EuDML record for Bieri--Neumann--Strebel (1987).
3. Checked the EuDML record for Bieri--Renz (1988).
4. Checked the ScienceDirect metadata for Bieri (1976).
5. Checked the AMS metadata and abstract for Karrass--Solitar (1978).
6. Checked Brown-adjacent modern candidates Friedl--Tillmann (2020) and
   Kielak (2020), but did not select them as the immediate beyond-Brown route.

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
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Friedl, S., & Tillmann, S. (2020). Two-generator one-relator groups and
  marked polytopes. *Annales de l'Institut Fourier, 70*(2), 831--879.
  https://doi.org/10.5802/aif.3325
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222.
  https://doi.org/10.1090/S0002-9939-1978-0466323-3
- Kielak, D. (2020). The Bieri--Neumann--Strebel invariants via Newton
  polytopes. *Inventiones Mathematicae, 219*(3), 1009--1068.
  https://doi.org/10.1007/s00222-019-00919-9

Internal references:

- `modules/cycle_002/FJ29_residual_attack_surface_selection.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ37_post_gpq_residual_audit.md`
- `ledgers/t001_kernel_recognition.md`
- `references/papers_to_read.md`

## Dependencies

This module depends on:

- `FJ29`;
- `FJ30`;
- `FJ37`;
- `OQ-043`;
- `OQ-044`;
- `OQ-056`;
- Brown (1987), as the already verified limited route;
- Bieri--Neumann--Strebel (1987), selected for direct verification;
- Bieri--Renz (1988), selected as secondary finiteness context;
- Bieri (1976), selected for normal-subgroup bridge verification;
- Karrass--Solitar (1978), selected for one-relator comparison.

## Results produced

This module produced:

- a first-pass resolution of `OQ-044`;
- a selected beyond-Brown `RB-004` source cluster;
- the next module target `FJ39`;
- no new `ER-*` result.

## Open questions generated

- Which exact hypotheses in Bieri (1976) and Karrass--Solitar (1978) are
  needed: finitely generated, finitely presented, \(\mathrm{FP}_2\), or a
  different finiteness condition?
- Does BNS (1987), without Brown's two-generator computation, give a usable
  finite-generation criterion for any concrete `RB-004` family already in the
  repository?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ38` and next `FJ39`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for `OQ-044` and new source-verification questions;
- `OPEN_QUESTIONS.md` for `OQ-043`, `OQ-044`, `OQ-056`, and new questions;
- `NOTATION_LEDGER.md` for the normal-subgroup bridge source cluster;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for selected and
  background sources;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
