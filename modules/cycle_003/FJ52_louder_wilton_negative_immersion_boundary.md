# Module FJ52. Louder--Wilton Negative-Immersion Boundary Check

## Status

Completed

## Module type

Literature verification / Attack surface / Theorem map

## Problem

`FJ51` selected Louder--Wilton (2022) as a bounded `RB-006` source-boundary
check. The project needs to decide whether this source gives a compact
special or direct CAT(0) route delta beyond the hyperbolic route, or whether
its useful output belongs to the `FJ23` hyperbolic route.

## Input

- `FJ22`, one-relator hierarchy vocabulary;
- `FJ23`, hyperbolic-route subtraction;
- `FJ24`, CAT(0)-route subtraction and compact-special bridge;
- `FJ51`, `RB-006` source-selection attack packet;
- `OQ-073`;
- Louder--Wilton (2022), checked through the arXiv abstract, UCL repository
  record, and Cambridge repository text snippets;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Output target

A boundary decision:

- record what Louder--Wilton actually supplies;
- decide whether it gives an `RB-006` compact-special/CAT(0) route delta;
- decide whether its useful project role is hyperbolic-route overlap;
- select the next bounded project move.

## Definitions

**Definition.** The primitivity rank \(\pi(w)\) of a word \(w\in F\), in the
Louder--Wilton setting, is the smallest rank of a subgroup of \(F\) containing
\(w\) as an imprimitive element, with the source's stated conventions for
primitive and trivial words.

**Definition.** For this module, a Louder--Wilton negative-immersion input is
the source-verified condition \(\pi(w)>2\), which Louder--Wilton identify
with negative immersions of the natural presentation complex for
\(F/\langle\langle w\rangle\rangle\).

**Warning.** Louder--Wilton (2022) is not used here as a source for
hyperbolicity, virtual specialness, compact specialness, or a CAT(0) action.
The paper records hyperbolicity of negative-immersion one-relator groups as a
conjecture, not as a theorem. Hyperbolicity/virtual-special consequences are
handled in the repository through Linton's source row from `FJ22` and the
route rules in `FJ23`/`FJ24`.

## Main work

### Source check

**Source-verified claim.** Louder--Wilton define negative immersions for
compact 2-complexes in terms of compact connected complexes immersing into
the given complex: the alternative is negative Euler characteristic or
Nielsen reduction to a graph.

**Source-verified claim.** Louder--Wilton's Theorem 1.3 states that the
presentation complex of \(F/\langle\langle w\rangle\rangle\) has negative
immersions exactly when \(\pi(w)>2\) (Louder & Wilton, 2022).

**Source-verified claim.** Louder--Wilton's Theorem 1.5 gives a low-rank
subgroup theorem: for \(\pi(w)>1\), finitely generated subgroups of rank less
than \(\pi(w)\) are free, and rank-\(\pi(w)\) subgroups are controlled by a
finite list of one-relator subgroups, up to the alternatives stated in the
source (Louder & Wilton, 2022).

**Source-verified claim.** Louder--Wilton record that if a one-relator group
has negative immersions, then it has no Baumslag--Solitar subgroup and its
finitely generated abelian subgroups are cyclic. In the same introduction,
they state the hyperbolicity of one-relator groups with negative immersions
as a conjecture, not as a theorem (Louder & Wilton, 2022).

### RB-006 boundary decision

Louder--Wilton supplies a useful one-relator recognition input for the
negative-immersion condition, but it does not by itself supply a compact
special, virtually compact special, or direct finite-dimensional CAT(0)
recognition theorem.

The source therefore does not produce an `RB-006` route delta. Its immediate
Farrell--Jones relevance is only through already separate routes:

- with Linton's later negative-immersion theorem recorded in `FJ22`, the
  condition \(\pi(w)>2\) may become hyperbolic-route input;
- once hyperbolicity is available, the Farrell--Jones subtraction belongs to
  `FJ23`;
- virtual specialness attached to the same hyperbolic package is not counted
  as a new CAT(0) or compact-special subtraction in `RB-006`;
- no direct CAT(0) or compact-special theorem is imported from
  Louder--Wilton.

### Route delta

| Question | FJ52 answer |
|---|---|
| What source was checked? | Louder--Wilton (2022), *Negative immersions for one-relator groups*. |
| What theorem package was found? | \(\pi(w)>2\) characterizes negative immersions for the presentation complex; low-rank subgroup freeness and no-Baumslag--Solitar consequences are recorded. |
| Does it supply compact-special/CAT(0) route delta? | No. |
| Does it supply hyperbolic-route overlap? | Yes, when paired with the Linton negative-immersion-to-hyperbolicity row already recorded in `FJ22`. |
| Does this remove a residual case in FJ52? | No; this module is a boundary check and records no subtraction. |
| Next decision | Write a hyperbolic-overlap checkpoint deciding whether to record the \(\pi(w)>2\) route through `FJ23`, or close this path as already absorbed. |

## Proposition / Theorem / Conjecture / Example

**Source-verified warning.** Louder--Wilton (2022) does not provide the
compact-special or direct finite-dimensional CAT(0) route sought by `RB-006`.

**Proposition.** `FJ52` produces no new `T-001` residual subtraction.

**Route decision.** `FJ52` resolves `OQ-073`: Louder--Wilton gives
negative-immersion and subgroup-structure input, but no independent
`RB-006` compact-special/CAT(0) route delta. Its possible project use is a
hyperbolic-route overlap through `FJ23`.

## Proof or verification

The source-verified warning follows from the checked source statements. The
Louder--Wilton theorem package characterizes negative immersions by
primitivity rank and gives subgroup-structure consequences. It does not state
that the group is compact special, finite-dimensional CAT(0), or
Farrell--Jones.

The no-subtraction proposition follows because this module does not combine
the Louder--Wilton input with Linton's negative-immersion-to-hyperbolicity
theorem as a formal route subtraction. It only checks the `RB-006` boundary.
Any later subtraction must be recorded explicitly as a hyperbolic-route
overlap and must keep the source chain visible.

## References

- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Louder, L., & Wilton, H. (2022). Negative immersions for one-relator groups.
  *Duke Mathematical Journal, 171*(3), 547--594.
  https://doi.org/10.1215/00127094-2021-0024

Internal references:

- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_003/FJ51_rb006_source_selection_attack_packet.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ22`;
- `FJ23`;
- `FJ24`;
- `FJ51`;
- `OQ-073`;
- Louder--Wilton (2022);
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-073`;
- a source-verified warning that Louder--Wilton does not supply an
  independent compact-special/CAT(0) route delta for `RB-006`;
- a possible hyperbolic-overlap follow-up through `FJ23`;
- no new `ER-*` result;
- no residual subtraction.

## Open questions generated

- `OQ-074`: Should the project record the \(\pi(w)>2\) negative-immersion
  condition as a hyperbolic-route overlap through `FJ23`, or treat it as
  already absorbed by the existing negative-immersion route marker?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ52` and next
  `FJ53`;
- `SCOPE_LEDGER.md` for the `OQ-073` resolution and new `OQ-074`;
- `OPEN_QUESTIONS.md` for `OQ-072`, `OQ-073`, and `OQ-074`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Louder--Wilton's
  active boundary-check status;
- `ledgers/t001_residual.md`, `ledgers/theorem_dependencies.md`, and
  `ledgers/open_group_classes.md` for the current target update;
- `references/papers_to_read.md` for the next task.
