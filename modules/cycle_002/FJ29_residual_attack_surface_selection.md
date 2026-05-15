# Module FJ29. Residual attack-surface selection for T-001

## Status

Completed

## Module type

Attack surface / Source selection / Reflection

## Problem

Choose one concrete residual bucket from the `FJ28` residual ledger for the
next source-verification or reduction attempt in `T-001`, the torsion-free
one-relator residual gap analysis.

The selection must be conservative. It should not assert a new
Farrell--Jones theorem, and it should not use an unverified one-relator
kernel theorem as if it had already been checked.

## Input

This module uses:

- `FJ20`, the selection of `T-001`;
- `FJ26`, the hyperbolic-by-cyclic/free-by-cyclic route subtraction;
- `FJ28`, the residual ledger after route subtractions;
- `ledgers/t001_residual.md`;
- `OQ-036`, `OQ-039`, and `OQ-040`;
- Brown's BNS-invariant paper as a found but still unverified source for
  kernel-recognition work;
- Bestvina--Fujiwara--Wigglesworth as already source-verified in `FJ19` and
  used in `FJ26`.

## Output target

Select:

- one residual bucket from `ledgers/t001_residual.md`;
- the first source to verify for that bucket;
- the next module task.

## Definitions

**Definition.** A selected residual attack surface is a residual bucket chosen
for the next bounded source-verification or reduction attempt. The selection
is project bookkeeping, not a mathematical theorem.

**Definition.** The kernel-recognition attack surface is residual bucket
`RB-004`: epimorphisms to \(\mathbb Z\), or HNN-splitting data, where the
missing bridge is control of the kernel, especially finite-rank free-kernel
control.

**Definition.** A first verification source is the first external source the
next module should check for exact statements, hypotheses, and proof-sensitive
usability.

**Warning.** Selecting `RB-004` does not prove that any epimorphism
\(G\to\mathbb Z\) from a torsion-free one-relator group has finitely
generated kernel. It only chooses that question as the next project target.

**Warning.** Brown's paper is selected here for verification. It is not
promoted here to an active theorem source.

## Main work

### Selection criteria

The following criteria guide the choice:

1. The bucket should connect directly to an existing Farrell--Jones route.
2. The first verification task should be bounded by a specific source or
   small source cluster.
3. A successful verification should update a route table rather than merely
   add more vocabulary.
4. A failed verification should still produce a useful failed-attempt or
   source-status artifact.

### Candidate comparison

| Candidate bucket | Selection decision | Reason |
|---|---|---|
| `RB-004`: epimorphisms to \(\mathbb Z\) or HNN splittings with unknown kernel control | Selected | A finite-rank free-kernel bridge feeds directly into the `FJ26` finite-rank free-by-cyclic route. Brown (1987) is already recorded as a found source to verify. |
| `RB-005`: virtually compact special or finite-index bridge cases | Deferred | Important, but it requires reconciling finite-index, CAT(0), coefficient K-theory, and full \(\mathcal{FJ}\) formulation issues. |
| `RB-006`: compact special or CAT(0)-looking one-relator cases beyond hyperbolicity | Deferred | This likely requires a wider cubulation/specialness source search before a single verification target is well-defined. |
| `RB-007`: virtually solvable-looking one-relator cases | Deferred | No preferred classification or recognition source has yet been selected. |
| `RB-003`: hierarchy-only data | Deferred | The bucket is too broad until a specific bridge from hierarchy data to a known Farrell--Jones route is chosen. |

### Selected attack surface

**Selection.** The next attack surface is `RB-004`, finite-rank
free-kernel recognition for one-relator epimorphisms to \(\mathbb Z\).

The working input shape for the next module is:

\[
G \xrightarrow{p} \mathbb Z
\]

where \(G\) is a torsion-free one-relator group and the project needs to know
whether \(\ker(p)\) is a free group of finite rank.

If a later module verifies a finite-rank free-kernel statement for a given
case, then `FJ26` already records the route:

\[
1\to F_n\to G\to \mathbb Z\to 1
\quad (n<\infty)
\]

splits and yields \(G\cong F_n\rtimes\mathbb Z\), placing \(G\) in the
finite-rank free-by-cyclic special case of the hyperbolic-by-cyclic route
recorded from Bestvina, Fujiwara, and Wigglesworth (2023).

### First source to verify

**Selection.** The first source to verify is:

Brown, K. S. (1987). *Trees, valuations, and the Bieri--Neumann--Strebel
invariant*.

The next module should check Brown for:

- exact one-relator hypotheses;
- whether the statements concern epimorphisms to \(\mathbb Z\), characters,
  or BNS invariant data;
- whether the conclusion is finite generation of the kernel, freeness,
  finite rank, or a weaker property;
- whether the result applies to all relevant torsion-free one-relator groups
  or only to special presentations/characters;
- how the statement connects to the finite-rank free-by-cyclic bridge from
  `FJ26`.

### Next module target

`FJ30` should be a source-verification module for Brown's kernel-recognition
results. It should either:

- extract an exact theorem with hypotheses usable by the project;
- determine that Brown alone is insufficient and identify the next source;
- or preserve a failed attempt if the expected bridge does not exist.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ29` selects `RB-004`, finite-rank free-kernel recognition
over \(\mathbb Z\), as the next concrete attack surface for `T-001`, and
selects Brown (1987) as the first source to verify.

**Proof.** `FJ28` lists `RB-004` as a residual bucket whose missing bridge is
kernel control for maps to \(\mathbb Z\) or HNN-splitting data. `FJ26`
records that a source-verified exact sequence
\[
1\to F_n\to G\to \mathbb Z\to 1
\]
with \(n<\infty\) gives a finite-rank free-by-cyclic bridge into the
Bestvina--Fujiwara--Wigglesworth route. Brown's BNS-invariant paper is already
recorded in the source ledger as a found source relevant to one-relator
kernels and free-by-cyclic recognition. Among the `FJ28` candidates, this is
the most bounded source-verification task with a direct connection to an
existing route. Therefore `RB-004` and Brown (1987) are selected.

**Remark.** This proposition is a project-selection result. It should not be
entered as an `ER-*` theorem.

## Proof or verification

Verification steps completed in this module:

1. Checked `FJ26` for the finite-rank free-by-cyclic route and its warnings.
2. Checked `FJ28` and `ledgers/t001_residual.md` for candidate residual
   buckets.
3. Checked `OPEN_QUESTIONS.md` for `OQ-036`, `OQ-039`, and `OQ-040`.
4. Checked the source-status and bibliography entries for Brown (1987).
5. Selected `RB-004` and Brown (1987) without upgrading Brown to theorem-use
   status.

## References

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell--Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904.
  https://doi.org/10.1093/imrn/rnac012
- Brown, K. S. (1987). Trees, valuations, and the Bieri--Neumann--Strebel
  invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ28_residual_ledger_after_route_subtractions.md`
- `ledgers/t001_residual.md`
- `OPEN_QUESTIONS.md`

## Dependencies

This module depends on:

- `FJ20`;
- `FJ26`;
- `FJ28`;
- `OQ-036`;
- `OQ-039`;
- `OQ-040`;
- Brown (1987), as a source selected for later verification.

## Results produced

This module produced:

- a first-pass resolution of `OQ-039`;
- a first-pass resolution of `OQ-040`;
- a selected residual attack surface: `RB-004`;
- a selected first verification source: Brown (1987);
- no new `ER-*` result.

## Open questions generated

- What exact theorem in Brown (1987), if any, gives a finite-generation or
  finite-rank free-kernel criterion for one-relator epimorphisms to
  \(\mathbb Z\)?
- If Brown (1987) is insufficient, which BNS or one-relator source should be
  checked next?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ29` status and next `FJ30`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the selected residual attack surface;
- `NOTATION_LEDGER.md` for selection terms;
- `OPEN_QUESTIONS.md` to mark `OQ-039` and `OQ-040` first-pass resolved and
  generate the Brown-verification question;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Brown's selected
  verification role;
- `ledgers/t001_residual.md` for the `FJ29` selection;
- `ledgers/open_group_classes.md` for the updated `T-001` next action;
- `ledgers/theorem_dependencies.md` for the completed `FJ29` row and next
  dependency row;
- `references/papers_to_read.md` for the `FJ30` reading task.
