# Module FJ19. Torsion-free one-relator groups dossier

## Status

Completed

## Module type

Attack surface / Literature verification

## Problem

Determine what the project can responsibly say about the Farrell--Jones
status of torsion-free one-relator groups after the first-pass known-cases
and inheritance ledgers.

The main constraint is that this module must not turn a useful structural
property of one-relator groups into a Farrell--Jones theorem. In particular,
local indicability is important structure, but it is not by itself a
Farrell--Jones proof route in the current project.

## Input

This module uses:

- `FJ11` and `ER-009` for hyperbolic groups, finite-dimensional CAT(0)-groups,
  and virtually solvable groups;
- `FJ12` and `ER-010` for inheritance rows, especially the survey-level full
  \(\mathcal{FJ}\) row for extensions with countable free kernel;
- Lueck's 2025 survey for the current open-status warning about the Full
  Farrell--Jones Conjecture;
- Bestvina--Fujiwara--Wigglesworth for hyperbolic-by-cyclic groups;
- Howie/Brodskii for local indicability of torsion-free one-relator groups;
- Newman only as background for the torsion one-relator contrast.

## Output target

A reusable status table separating:

- known Farrell--Jones routes that apply to one-relator subclasses;
- structural facts that do not solve Farrell--Jones;
- global open or unverified status for torsion-free one-relator groups;
- plausible next target-selection questions for `FJ20`.

## Definitions

**Definition.** A one-relator group is a group admitting a presentation
\[
G\cong \langle X\mid r\rangle
\]
with one defining relator. When \(X\) is finite, this is a finitely generated
one-relator group.

**Definition.** In this module, a torsion-free one-relator group means a
one-relator group with no nontrivial elements of finite order.

**Definition.** A group is locally indicable if every nontrivial finitely
generated subgroup admits a surjection onto \(\mathbb Z\).

**Definition.** If \(\Phi\colon H\to H\) is an automorphism, the mapping torus
or \(H\)-by-cyclic group is
\[
H_\Phi=H\rtimes_\Phi \mathbb Z.
\]
If \(H\) is a free group, this is a free-by-cyclic group.

**Warning.** A one-relator group with torsion is often written in the form
\(\langle X\mid w^m\rangle\) with \(m\geq 2\). Such groups are useful contrast
cases, but they are not the target class of this module.

## Main work

### Source-verified status table

| Class or route | Farrell--Jones status in this project | Source status | Use in this module |
|---|---|---|---|
| All torsion-free one-relator groups | Not recorded as solved. Lueck lists torsion-free one-relator groups among classes for which the Full Farrell--Jones Conjecture is open in general. | Source-verified open-status warning from Lueck (2025). | Keeps the global class as an active target rather than a known case. |
| Torsion-free one-relator groups as locally indicable groups | Howie records a short proof of Brodskii's theorem that torsion-free one-relator groups are locally indicable. Lueck also lists locally indicable groups as open in general for Full Farrell--Jones. | Source-verified structural fact plus source-verified open-status warning. | Local indicability may guide reductions, but it is not a completed FJ proof route here. |
| Hyperbolic one-relator groups | Covered whenever the group is independently known to be hyperbolic. | Follows from `ER-009`, using Bartels--Lueck--Reich and Bartels--Lueck. | Known subclass route. |
| Finite-dimensional CAT(0) one-relator groups | Covered whenever the group is independently known to act properly, cocompactly, and isometrically on a finite-dimensional CAT(0)-space. | Follows from `ER-009`, using Wegner and Bartels--Lueck. | Known subclass route. |
| Virtually solvable one-relator groups | Covered whenever the group is independently known to be virtually solvable. | Follows from `ER-009`, using Wegner. | Known subclass route. |
| Hyperbolic-by-cyclic groups \(H\rtimes_\Phi\mathbb Z\), with \(H\) virtually torsion-free hyperbolic | Bestvina, Fujiwara, and Wigglesworth prove the K- and L-theoretic Farrell--Jones conjectures in the source formulation with coefficients in additive categories. | Source-verified for `FJ19`. | Covers finite-rank free-by-cyclic groups, and any one-relator group independently identified as such. |
| Extensions with countable free kernel and quotient in Lueck's \(\mathcal{FJ}\) | Lueck's survey-level theorem records this as a full \(\mathcal{FJ}\) inheritance row. | Source-verified survey statement in `FJ12`; primary proof source not traced here. | Useful reduction route, but proof-sensitive use requires primary-source tracing. |
| One-relator groups with torsion | Background contrast only. Newman supplies the classical spelling theorem context; a full route from the torsion one-relator presentation to the project's FJ ledger should be checked before theorem use. | Background source found; not promoted to a new project theorem here. | Prevents confusing the torsion case with the torsion-free target. |

### Interpretation

**Source-verified claim.** The current project should not claim that the
Farrell--Jones conjecture is known for every torsion-free one-relator group.
Lueck (2025) explicitly lists torsion-free one-relator groups among the groups
for which the Full Farrell--Jones Conjecture is open in general.

**Source-verified claim.** Torsion-free one-relator groups are locally
indicable by Brodskii's theorem as presented by Howie (2000). This is
structural information, not a Farrell--Jones theorem.

**Source-verified claim.** The project now has verified positive routes for
one-relator subclasses that are hyperbolic, finite-dimensional CAT(0),
virtually solvable, or hyperbolic-by-cyclic under the exact hypotheses above.

**Warning.** The phrase "one-relator group" is too coarse for target selection.
For `FJ20`, the useful question is not whether one-relator groups are
interesting. The useful question is which remaining torsion-free one-relator
groups survive after subtracting the verified routes.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group. If \(G\) is
known independently to lie in one of the following source-verified classes,
then the corresponding Farrell--Jones statement recorded in the project holds
for \(G\):

1. hyperbolic groups;
2. finite-dimensional CAT(0)-groups;
3. virtually solvable groups;
4. groups \(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free
   hyperbolic, in the Bestvina--Fujiwara--Wigglesworth source formulation.

**Proof.** The first three cases are direct applications of `ER-009`. The
fourth case is the main theorem of Bestvina, Fujiwara, and Wigglesworth
(2023), whose source formulation uses coefficients in additive categories and
the family of virtually cyclic subgroups. This proposition does not assert
that every torsion-free one-relator group belongs to one of these classes.

**Open problem.** Determine whether there is a source-verified global
K-theoretic Farrell--Jones theorem for all torsion-free one-relator groups in
a weaker formulation than Lueck's Full Farrell--Jones Conjecture, and if so,
record its exact hypotheses.

## Proof or verification

Verification steps completed in this module:

- Checked Lueck (2025) for the source-specific definition of a
  Farrell--Jones group, the status theorem for known full \(\mathcal{FJ}\)
  classes and inheritance properties, and the later list of groups for which
  Full Farrell--Jones is open in general; that list includes torsion-free
  one-relator groups and locally indicable groups.
- Checked Bestvina, Fujiwara, and Wigglesworth (2023) for the main
  hyperbolic-by-cyclic theorem, its K- and L-theoretic scope, and its
  additive-category coefficient convention.
- Checked Howie (2000) as a source for Brodskii's theorem that torsion-free
  one-relator groups are locally indicable.
- Recorded Newman (1968) only as a background source for the torsion
  one-relator contrast; this module does not use the torsion case as a proof
  input.

## References

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell--Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904. https://doi.org/10.1093/imrn/rnac012
- Howie, J. (2000). A short proof of a theorem of Brodskii. *Publicacions
  Matematiques, 44*(2), 613--647. http://eudml.org/doc/41412
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337
- Newman, B. B. (1968). Some results on one-relator groups. *Bulletin of the
  American Mathematical Society, 74*, 568--571.
  https://www.ams.org/bull/1968-74-03/S0002-9904-1968-12012-9/

Prior project references used through `ER-009` and `ER-010`:

- Bartels--Lueck--Reich (2008), Bartels--Lueck (2012), Wegner (2012), and
  Wegner (2015).

## Dependencies

This module depends on:

- `FJ11` and `ledgers/known_classes.md`;
- `FJ12` and `ledgers/inheritance_properties.md`;
- `FJ18` only as a comparison dossier for target selection;
- source-status updates in `BIBLIOGRAPHY.md` and `ledgers/source_status.md`.

## Results produced

This module produced:

- `ER-012`: first source-verified one-relator-group Farrell--Jones status
  ledger.

## Open questions generated

- `OQ-024`: Is there a source-verified global K-theoretic Farrell--Jones theorem
  for all torsion-free one-relator groups in a weaker formulation than Full
  Farrell--Jones?
- `OQ-025`: Which one-relator structure theorem should become the canonical
  reduction tool for this project: Magnus hierarchy, Brodskii--Howie local
  indicability, HNN splittings, or another modern hierarchy?
- `OQ-026`: Which torsion-free one-relator groups remain after subtracting the
  hyperbolic, finite-dimensional CAT(0), virtually solvable, and
  hyperbolic-by-cyclic routes?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for `ER-012` and new open questions;
- `NOTATION_LEDGER.md` for one-relator, locally indicable, and mapping-torus
  notation;
- `ESTABLISHED_RESULTS.md` for `ER-012`;
- `OPEN_QUESTIONS.md` for `OQ-024`--`OQ-026`;
- `BIBLIOGRAPHY.md` for the new one-relator and hyperbolic-by-cyclic sources;
- `ledgers/source_status.md` for source status changes;
- `ledgers/known_classes.md`, `ledgers/open_group_classes.md`, and
  `ledgers/theorem_dependencies.md` for the new status rows.
