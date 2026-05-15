# Cycle 002 Reflection. One-relator residual routes and kernel recognition

## Status

Completed

## Reflection type

Cycle reflection

## Scope

This reflection closes the second twenty-module cycle:

- `FJ21`--`FJ40`;
- the target `T-001`, torsion-free one-relator residual gap analysis;
- the active residual bucket `RB-004`, finite-rank free-kernel recognition
  over \(\mathbb Z\).

It does not add a new mathematical theorem, source-verified claim, or
established-result number.

## Inputs

Internal repository inputs:

- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ESTABLISHED_RESULTS.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `references/papers_to_read.md`;
- `modules/cycle_002/`.

No new external source is used in this reflection.

## Cycle summary

### Structure source and vocabulary

`FJ21` and `FJ22` gave `T-001` a source-disciplined one-relator vocabulary.
The cycle selected Linton's one-relator hierarchy work as the modern
structure spine, kept Linton's hyperbolic one-relator paper as a bridge
source, and recorded classical one-relator sources as verification targets
instead of silently importing them.

**Warning.** The hierarchy vocabulary is not itself a Farrell--Jones route.
It becomes useful only when paired with a source-verified bridge to a known
class, an inheritance row, or a controlled kernel-recognition statement.

### Route subtractions

`FJ23`--`FJ27` converted the broad one-relator target into route-specific
bookkeeping. The cycle recorded conservative subtraction rules for:

- word-hyperbolic cases;
- finite-dimensional CAT(0) cases;
- virtually solvable cases;
- hyperbolic-by-cyclic and finite-rank free-by-cyclic cases;
- exact source-verified inheritance routes.

**Remark.** These subtractions are project-state route rules, not negative
results about anything left over. A case remains in the residual only because
the repository has not yet recorded the needed bridge.

### Residual ledger

`FJ28` assembled the first `T-001` residual ledger. The most useful outcome
was the separation between a mathematical open class and a repository-state
missing bridge.

The cycle then selected:

```text
RB-004: epimorphisms to Z or HNN splittings with unknown kernel control
```

as the first concrete residual attack surface.

### Brown route

`FJ29`--`FJ34` selected and applied Brown's kernel-recognition technology in
a limited, checked way.

The Brown portion produced:

- a verified first-pass Brown/BNS kernel-recognition ledger;
- a calibration example using the commutator presentation;
- a worked nonabelian example \(G_{2,3}\cong F_2\rtimes\mathbb Z\);
- a Brown-positive finite-generation statement for the family
  \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\).

**Warning.** Brown's checked route remains a limited two-generator
one-relator criterion in the repository. It is not a global theorem that
every one-relator epimorphism to \(\mathbb Z\) has finitely generated kernel.

### Bass--Serre bridge

`FJ35` and `FJ36` supplied the missing bridge for the \(G_{p,q}\)-family.
The key route was:

- Brown gives finite generation of \(K_{p,q}=\ker(\chi_{p,q})\);
- the cyclic-amalgam presentation gives a Bass--Serre tree;
- \(K_{p,q}\) acts freely on that tree;
- a source-verified free-action bridge gives that \(K_{p,q}\) is free;
- finite generation makes it finite-rank free;
- the family enters the `FJ26` finite-rank free-by-cyclic route.

This was the strongest concrete cycle-002 gain: a family was actually removed
from the active residual by a recorded route bridge.

### Beyond Brown

`FJ37`--`FJ40` audited what remained after the \(G_{p,q}\)-family and selected
a beyond-Brown source cluster:

- Bieri--Neumann--Strebel (1987);
- Bieri--Renz (1988);
- Bieri (1976);
- Karrass--Solitar (1978).

`FJ39` verified Karrass--Solitar as a narrow bridge for one-relator groups
with a nontrivial finitely presented normal subgroup of infinite index.
`FJ40` then checked whether the repository already contains a new non-Brown
source-ready finitely presented-kernel test case. It does not.

**Warning.** Karrass--Solitar is a cleanup theorem for a finite-presentation
input. It is not an example generator.

## What worked

Cycle 002 successfully turned a broad target into a route ledger with real
selection pressure. The project now distinguishes:

- known route subtractions;
- missing bridge buckets;
- source-selection tasks;
- worked Brown examples;
- a family-level route subtraction;
- cleanup theorems that are useful only after their inputs are recorded.

The \(G_{p,q}\)-family bridge is the main positive artifact of the cycle.
It gives a concrete example of the charter's intended rhythm: identify a
bucket, attack a narrow bridge, and then reflect before broadening the claim.

## What remains fragile

1. Direct BNS theorem use is still open. The repository has Brown's checked
   restatement and orientation-level BNS status, but not a verified original
   BNS theorem suitable for beyond-Brown `RB-004`.
2. Bieri (1976) remains only a cited dependency inside Karrass--Solitar, not
   an independently checked source.
3. Bieri--Renz (1988) remains higher-finiteness context, with no theorem
   imported.
4. The Karrass--Solitar infinite-dihedral alternative still needs
   finite-index and version-aware inheritance handling before route use.
5. `FJ02` remains deferred. This is acceptable for the next group-theoretic
   BNS source check, but it becomes urgent before source-level coefficient,
   finite-wreath-product, `FJCw`, or `FICwF` claims are used as internal proof
   hypotheses.

## Next cycle plan

The next cycle should remain governed by `T-001`, with the first move focused
on direct BNS verification rather than a new example search.

Provisional module sequence:

| Module | Provisional task | Purpose |
|---|---|---|
| `FJ41` | Direct BNS theorem verification for `RB-004` | Check the exact Bieri--Neumann--Strebel statement and whether it yields a usable beyond-Brown kernel criterion. |
| `FJ42` | Bieri (1976) primary-source verification | Determine the exact normal-subgroup hypotheses cited through Karrass--Solitar. |
| `FJ43` | Bieri--Renz finiteness-property checkpoint | Decide whether \(\mathrm{FP}_2\) or higher finiteness invariants are needed. |
| `FJ44` | Karrass--Solitar dihedral alternative handling | Check finite-index and inheritance requirements before route use. |
| `FJ45` | Beyond-Brown candidate selection, second pass | Select a concrete candidate only after `FJ41`--`FJ44` clarify hypotheses. |
| `FJ46` | Source-conventions checkpoint | Decide whether `FJ02` must interrupt before further theorem-use. |
| `FJ47` | `RB-004` dependency map refresh | Update the kernel-recognition and residual ledgers after the source checks. |
| `FJ48` | Failed-attempt or no-candidate ledger | Preserve any source routes that fail, with hypotheses stated. |
| `FJ49` | One-relator known-route audit | Check whether new source work changes any route-subtraction rows. |
| `FJ50` | Mid-cycle decision checkpoint | Decide whether to continue `RB-004` or switch residual buckets. |
| `FJ51`--`FJ59` | Reserved bounded modules | Fill only after the `FJ41`--`FJ50` evidence is recorded. |
| `FJ60` | Cycle 003 closeout module | Prepare the third reflection. |

This plan is provisional. If `FJ41` shows that direct BNS verification is not
the right next bridge, the cycle should pivot immediately and record the
reason.

## Decision

**Reflection decision.** Cycle 002 is closed. The next mathematical move is:

```text
FJ41. Direct BNS theorem verification for RB-004
```

The goal of `FJ41` is not to use BNS as a slogan. It is to check the original
source statement, exact hypotheses, and whether it supplies any route input
that is not already covered by Brown's checked two-generator criterion.

## References

No new external references were used.

Internal references:

- `modules/cycle_002/FJ21_one_relator_structure_source_selection.md`
- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ25_virtually_solvable_route_subtraction.md`
- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`
- `modules/cycle_002/FJ28_residual_ledger_after_route_subtractions.md`
- `modules/cycle_002/FJ29_residual_attack_surface_selection.md`
- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ31_first_brown_test_case.md`
- `modules/cycle_002/FJ32_nontrivial_brown_test_family_selection.md`
- `modules/cycle_002/FJ33_worked_brown_test_g23.md`
- `modules/cycle_002/FJ34_nearby_brown_family_generalization.md`
- `modules/cycle_002/FJ35_gpq_kernel_bridge_source_selection.md`
- `modules/cycle_002/FJ36_bass_serre_source_verification_gpq.md`
- `modules/cycle_002/FJ37_post_gpq_residual_audit.md`
- `modules/cycle_002/FJ38_rb004_beyond_brown_source_selection.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_002/FJ40_finitely_presented_kernel_test_selection.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`
