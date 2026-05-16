# Module FJ75. Virtually Cyclic Dichotomy Source-Payload Check

## Status

Completed

## Module type

Literature verification / Source-access audit / Governance checkpoint

## Problem

`FJ74` selected `OQ-006`, the direct original-source check for the
virtually cyclic dichotomy used in `FJ04`.

The exact payload is Farrell--Jones (1995), Lemma 2.5, cited in the
current `FJ04` dependency chain as the proof source for the dichotomy that
an infinite virtually cyclic group maps with finite kernel either onto
\(\mathbb Z\) or onto \(D_\infty\).

The problem is to decide whether this source can now be promoted from
`to verify` to direct theorem-use status.

## Input

- `FJ04`, Virtually Cyclic Groups;
- `FJ74`, Fixed-Point Convention Cleanup for Classifying Spaces;
- `OQ-006`;
- `ER-003`;
- `OBL-FND-003`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/theorem_dependencies.md`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `AGENTS.md`.

## Output target

A bounded source-payload decision:

- promote Farrell--Jones (1995), Lemma 2.5, if the primary text is directly
  accessible and the exact hypotheses can be checked; or
- record no-promotion status if only metadata or secondary citations are
  available.

## Definitions

**Definition.** A **source-payload promotion** means that a source is moved
from bibliographic or secondary-citation status to direct theorem-use status,
with exact theorem location and hypotheses recorded.

**Definition.** A **no-promotion source-access result** means that the
source has been located bibliographically, but the theorem text has not been
checked. Such a source may remain in the bibliography, but it must not be
used as a direct theorem source.

## Main work

### Source-access log

The following access checks were made.

| Object | Result | Project consequence |
|---|---|---|
| DOI `10.1007/BF00965457` | Crossref metadata confirms Farrell and Jones, title, journal `K-Theory`, volume 9, issue 1, pages 13--30, 1995, DOI. | Bibliographic metadata can be upgraded from "URL/DOI: to verify" to DOI-checked. |
| OpenAlex DOI record | Records the work as closed access, with no open-access URL and no repository full text. | No direct text access from this metadata route. |
| Springer DOI/landing page | The environment received a client-challenge page rather than article text. | The primary source was not readable through this route. |
| Direct Springer PDF endpoint | The endpoint did not provide a PDF article text in this environment. | The primary Lemma 2.5 text was not checked. |
| Web search for exact Lemma 2.5 text | No primary text of Lemma 2.5 was recovered. Secondary references to the lemma were found, but they are not the requested source payload. | No direct theorem promotion. |

### Source-payload decision

`FJ75` records a no-promotion result.

Farrell--Jones (1995) is now DOI- and metadata-checked, but Lemma 2.5 was
not directly read. Therefore the repository must not cite Farrell--Jones
(1995), Lemma 2.5, as a direct source-verified theorem.

The usable first-pass source for the `FJ04` dichotomy remains the already
checked Lueck--Reich survey lemma. Farrell--Jones (1995) remains the cited
original proof source, but with source-access status:

```text
metadata checked; primary Lemma 2.5 text not accessed; do not use directly
```

### Consequence for `OQ-006`

`OQ-006` is resolved negatively for the current project state:

- the original source was located and DOI-checked;
- the primary lemma text was not available in this environment;
- no exact hypotheses from Lemma 2.5 were imported;
- no source-verified Farrell--Jones 1995 row is promoted;
- the `FJ04` statement remains supported through Lueck--Reich as before.

### New proof obligation

**Obligation OBL-FND-004.** `FJ76` must decide whether the foundational
source queue contains another exact, bounded source payload ready for action,
or whether the foundational queue should pause and return to target-pivot
comparison. It must not launch a broad foundations or bibliography survey.

### Next module selection

`FJ75` selects:

```text
FJ76. Foundational Source-Queue Checkpoint After OQ-006 No-Promotion
```

Goal: decide whether another exact foundational source-payload item is ready
after the `OQ-006` no-promotion result.

Required input:

- `FJ73`;
- `FJ74`;
- `FJ75`;
- current foundational open questions;
- `ledgers/theorem_dependencies.md`;
- `ledgers/source_status.md`;
- `AGENTS.md`.

Success criterion:

- select at most one exact source-payload item with a project object changed,
  or pause the foundational source queue.

Failure criterion:

- the module becomes a broad literature triage or source-summary exercise.

Expected output:

- one bounded next packet, or a pause-and-pivot recommendation;
- updated open-question and dependency ledgers;
- no new group-class Farrell--Jones theorem claim.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Farrell--Jones (1995), Lemma 2.5, should not be promoted to
direct theorem-use status in the current repository state.

## Proof or verification

**Proof.** The module located the DOI and bibliographic metadata for the
article, but did not obtain readable primary text for Lemma 2.5. Crossref
confirms the article metadata, while OpenAlex records the article as closed
access with no open-access URL and no repository full text. The Springer
routes checked in this run did not expose article text.

The project's source discipline requires exact theorem source and exact
hypotheses before promoting an external theorem. Since the primary lemma text
was not checked, the source cannot be promoted. The current `FJ04` row must
therefore remain dependent on the already checked Lueck--Reich survey
statement, while Farrell--Jones (1995) remains located but not directly
usable.

## References

- Crossref. (n.d.). *The lower algebraic K-theory of virtually infinite
  cyclic groups* [Metadata record for DOI 10.1007/BF00965457]. Retrieved
  May 16, 2026, from
  https://api.crossref.org/works/10.1007/BF00965457
- Farrell, F. T., & Jones, L. E. (1995). The lower algebraic K-theory of
  virtually infinite cyclic groups. *K-Theory, 9*(1), 13--30.
  https://doi.org/10.1007/BF00965457
- Lueck, W., & Reich, H. (2004). *The Baum-Connes and the Farrell-Jones
  conjectures in K- and L-theory* (arXiv:math/0402405). arXiv.
  https://arxiv.org/abs/math/0402405
- OpenAlex. (n.d.). *The lower algebraicK-theory of virtually infinite
  cyclic groups* [Work metadata record]. Retrieved May 16, 2026, from
  https://api.openalex.org/works/doi:10.1007/BF00965457

## Dependencies

This module depends on:

- `FJ04`;
- `FJ74`;
- `OQ-006`;
- `ER-003`;
- `OBL-FND-003`;
- Crossref metadata for DOI `10.1007/BF00965457`;
- OpenAlex metadata for access status.

## Results produced

This module produced:

- no-promotion status for Farrell--Jones (1995), Lemma 2.5;
- DOI-checked bibliography metadata for Farrell--Jones (1995);
- first-pass negative resolution of `OQ-006`;
- completion of `OBL-FND-003`;
- `FND-SRC-001`, the source-access no-promotion status for Farrell--Jones
  (1995), Lemma 2.5;
- `OBL-FND-004`, the foundational source-queue checkpoint obligation;
- selection of `FND-004`, foundational source-queue checkpoint after
  `OQ-006` no-promotion;
- selection of `FJ76`, Foundational Source-Queue Checkpoint After `OQ-006`
  No-Promotion;
- no new `ER-*` result;
- no group-class Farrell--Jones theorem claim.

## Open questions generated

- `OQ-096`: Which foundational source-payload item, if any, should follow
  the `OQ-006` no-promotion result?

## Update to ledgers

After completion, update:

- `modules/cycle_001/FJ04_virtually_cyclic_groups.md` with the post-`FJ75`
  source-access note;
- `README.md` and `PROJECT_CHARTER.md` for completed `FJ75` and next
  `FJ76`;
- `SCOPE_LEDGER.md` for `OQ-006`, `OQ-096`, `FND-SRC-001`, `FND-004`, and
  `OBL-FND-004`;
- `OPEN_QUESTIONS.md` for `OQ-006` and new `OQ-096`;
- `NOTATION_LEDGER.md` for completed `FND-003`, completed `OBL-FND-003`,
  `FND-SRC-001`, `FND-004`, and `OBL-FND-004`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for DOI-checked but
  no-promotion Farrell--Jones (1995) status;
- `ledgers/theorem_dependencies.md` for completed `FJ75` and pending `FJ76`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
