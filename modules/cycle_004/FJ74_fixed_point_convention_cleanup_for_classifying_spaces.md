# Module FJ74. Fixed-Point Convention Cleanup for Classifying Spaces

## Status

Completed

## Module type

Definition / Literature verification / Governance checkpoint

## Problem

`FJ73` selected `OQ-005`, the weakly contractible versus contractible
fixed-point formulation issue, as the first bounded foundational blocker
after the current group-class target pauses.

`FJ03` gives a readable definition of a model for \(E_{\mathcal F}G\) using
contractible fixed-point spaces for subgroups in \(\mathcal F\) and empty
fixed-point spaces outside \(\mathcal F\). The same module records that
Lueck's Theorem 1.9 uses weakly contractible fixed-point spaces for
subgroups in \(\mathcal F\), together with the isotropy condition.

The problem is to turn this into a project convention without replacing the
source formulation by a stronger-looking statement.

## Input

- `FJ03`, Classifying Spaces for Families;
- `FJ73`, Foundational Open-Question Triage After Target Pauses;
- `OQ-005`;
- `ER-002`;
- `OBL-FND-002`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `ESTABLISHED_RESULTS.md`;
- `ledgers/theorem_dependencies.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `AGENTS.md`.

## Output target

A project convention that:

- keeps the contractible/empty formulation as a strict, readable model
  convention for examples and exposition;
- keeps Lueck's weakly contractible plus isotropy formulation as the
  source-level characterization behind `ER-002`;
- prevents later modules from silently upgrading weak contractibility to
  contractibility in theorem claims;
- resolves `OQ-005` at first pass;
- completes `OBL-FND-002`;
- selects the next bounded module without reopening a broad foundations
  survey.

## Definitions

**Definition.** A **strict fixed-point model** for \(E_{\mathcal F}G\) is a
\(G\)-CW complex \(X\) such that, for every subgroup \(H\leq G\),

\[
X^H\simeq *
\quad\text{if }H\in\mathcal F,
\qquad
X^H=\varnothing
\quad\text{if }H\notin\mathcal F.
\]

Here \(X^H\simeq *\) means contractible. This is the readable convention
used in `FJ03` for examples and first-pass exposition.

**Definition.** A **source-level model criterion** for \(E_{\mathcal F}G\)
is the criterion recorded in `FJ03` from Lueck (2004): a \(G\)-CW complex
\(X\) represents the classifying space if its isotropy groups lie in
\(\mathcal F\) and \(X^H\) is weakly contractible for every
\(H\in\mathcal F\).

**Warning.** In this project, "strict fixed-point model" is a sufficient
expository convention. It is not a replacement for the source-level theorem
when citing existence, uniqueness, or terminality.

## Main work

### Convention decision

The project will use a two-layer convention.

| Use case | Required wording |
|---|---|
| Concrete examples such as \(\mathrm{pt}\), \(EG\), or introductory \(E_{\mathcal F}G\) descriptions | It is acceptable to use the strict contractible/empty fixed-point formulation once the fixed-point spaces are checked directly. |
| Source-level existence, uniqueness, and terminality claims | Cite `ER-002` and preserve the weakly contractible plus isotropy formulation recorded from Lueck (2004). |
| General recognition of a \(G\)-CW complex as a model | State the weakly contractible plus isotropy criterion, unless a strict contractible/empty verification is actually supplied. |
| Assembly-map notation \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\) | Either model convention is harmless after passing to the \(G\)-homotopy type, but theorem-sensitive wording should cite `ER-002`. |

Thus `FJ03` remains usable, but its contractible/empty definition should be
read as the strict readable model convention. The source theorem behind the
project remains the weaker homotopy characterization already recorded in
`ER-002`.

### Resolution of `OQ-005`

`OQ-005` is resolved at first pass by adopting this convention.

The resolution is not a new theorem. It is a wording and dependency rule:
later modules may use the strict definition for transparent examples, but
must use the source-level criterion when making general or source-dependent
claims.

### Completed proof obligation

`OBL-FND-002` is completed by the following rule.

**Rule FND-CONV-001.** Do not silently replace weakly contractible
fixed-point spaces by contractible fixed-point spaces in source-verified
claims about \(E_{\mathcal F}G\). When using the strict
contractible/empty condition, label it as a strict fixed-point model or
verify it directly in the example.

### Next module selection

After this cleanup, the next bounded foundational item is `OQ-006`, the
original-source check for the virtually cyclic dichotomy used in `FJ04`.
This is selected because it is exact, source-payload bounded, and tied to an
existing dependency row.

**Obligation OBL-FND-003.** `FJ75` must check the original Farrell--Jones
(1995) virtually cyclic dichotomy source payload, specifically Lemma 2.5 as
cited by the current dependency chain, or record no-promotion status. It
must not broaden into a survey of virtually cyclic groups or lower algebraic
\(K\)-theory.

`FJ74` selects:

```text
FJ75. Virtually Cyclic Dichotomy Source-Payload Check
```

Goal: check Farrell--Jones (1995), Lemma 2.5, or record that the source
payload is unavailable or insufficient for promotion.

Required input:

- `FJ04`;
- `OQ-006`;
- `ER-003`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/theorem_dependencies.md`.

Success criterion:

- either directly verify the original virtually cyclic dichotomy source with
  exact hypotheses, or record a no-promotion note preserving the current
  Lueck--Reich/Lueck--Weiermann dependency status.

Failure criterion:

- the module expands into a broad history of virtually cyclic groups or lower
  algebraic \(K\)-theory.

Expected output:

- updated `OQ-006`;
- updated source-status and theorem-dependency rows;
- no new group-class Farrell--Jones theorem claim.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `OQ-005` can be resolved for first-pass project use by the
two-layer convention above.

## Proof or verification

**Proof.** `FJ03` already records both pieces needed for the convention. Its
definition section uses the contractible/empty fixed-point formulation as a
readable model definition. Its source-verified claim and proof-verification
section separately record Lueck's weakly contractible fixed-point
characterization together with the isotropy condition.

The two-layer convention preserves both statements: strict examples remain
available when directly checked, while source-dependent claims continue to
use the weakly contractible plus isotropy formulation recorded in `ER-002`.
Therefore the ambiguity in `OQ-005` is removed without adding a new theorem
or performing a new source survey.

No new external source was checked for this module. The citation to Lueck
(2004) is inherited from the verified `FJ03` source record.

## References

- Lueck, W. (2004). *Survey on classifying spaces for families of subgroups*
  (arXiv:math/0312378, Version 2). arXiv.
  https://arxiv.org/abs/math/0312378. Source status: active reference;
  Definition 1.8 and Theorem 1.9 checked in `FJ03`.

Internal references:

- `modules/cycle_001/FJ03_classifying_spaces_for_families.md`
- `modules/cycle_004/FJ73_foundational_open_question_triage_after_target_pauses.md`
- `OPEN_QUESTIONS.md`
- `SCOPE_LEDGER.md`
- `NOTATION_LEDGER.md`
- `ESTABLISHED_RESULTS.md`
- `ledgers/theorem_dependencies.md`
- `ledgers/source_status.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ03`;
- `FJ73`;
- `OQ-005`;
- `ER-002`;
- `OBL-FND-002`;
- Lueck (2004), Definition 1.8 and Theorem 1.9 as already recorded in
  `FJ03`.

## Results produced

This module produced:

- `FND-CONV-001`, the fixed-point convention rule for classifying spaces;
- first-pass resolution of `OQ-005`;
- completion of `OBL-FND-002`;
- `OBL-FND-003`, the virtually cyclic dichotomy source-payload obligation;
- completion of `FND-002`;
- selection of `FND-003`, virtually cyclic dichotomy source-payload check;
- selection of `FJ75`, Virtually Cyclic Dichotomy Source-Payload Check;
- no new `ER-*` result;
- no group-class Farrell--Jones theorem claim.

## Open questions generated

No new open question is generated. `FJ75` continues with existing `OQ-006`.

## Update to ledgers

After completion, update:

- `modules/cycle_001/FJ03_classifying_spaces_for_families.md` with the
  post-`FJ74` convention note;
- `README.md` and `PROJECT_CHARTER.md` for completed `FJ74` and next
  `FJ75`;
- `SCOPE_LEDGER.md` for the `OQ-005` resolution, `FND-CONV-001`,
  completion of `FND-002`, and next `FND-003`;
- `OPEN_QUESTIONS.md` for `OQ-005` and `OQ-006`;
- `NOTATION_LEDGER.md` for `FND-CONV-001`, completed `FND-002`, and next
  `FND-003`;
- `ESTABLISHED_RESULTS.md` to cross-reference the convention without
  changing `ER-002`;
- `ledgers/theorem_dependencies.md` for completed `FJ74` and pending `FJ75`;
- `BIBLIOGRAPHY.md`, `ledgers/source_status.md`, `references/papers_to_read.md`,
  and `AGENTS.md` for source-use and handoff status.
