# Module FJ92. CAND-T001-005 Brown/BNS Kernel-Control Computation

## Status

Completed

## Module type

Computation / Candidate-status verification / Payload-instantiated module

## Problem

`FJ91` verifies that `CAND-T001-005` is torsion-free at first-pass
candidate-ledger level, but the row still lacks kernel-control data.

This module executes accepted prompt payload
`PAY-T001-CAND005-BROWN-BNS-2026-001` and asks only whether the character
\[
\chi\colon G_{FJ90}\to \mathbb Z,\qquad \chi(a)=0,\quad \chi(b)=1
\]
has finitely generated kernel under the Brown/BNS framework already recorded
in `FJ30` and `ledgers/t001_kernel_recognition.md`.

## Input

- `FJ30`, especially the checked Brown two-generator one-relator criterion
  and Corollary 3.2;
- `FJ41`, as a direct BNS finite-generation comparison theorem;
- `FJ90`, which records the candidate presentation and epimorphism;
- `FJ91`, which source-checks torsion-free status;
- `next_prompts.md`, Prompt 010;
- `OQ-113`;
- `OBL-C5-012`;
- `OBL-T001-019`.

## Output target

Classify the \(\chi\)-kernel for `CAND-T001-005` as one of:

- finite-rank free;
- finitely generated but not identified;
- blocked;
- unsuitable for the `FJ26` route.

The output must not:

- claim full Farrell--Jones for `CAND-T001-005`;
- claim coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, or
  `FICwF`;
- claim a residual-bucket subtraction;
- run a broad Brown/BNS survey;
- create `FJ93`.

## Definitions

**Definition.** For this module, Brown-positive means that both \([\chi]\)
and \([-\chi]\) pass the relevant maximum-count test from the checked Brown
two-generator one-relator criterion recorded in `FJ30`.

**Definition.** Kernel-control status is the project ledger status recording
whether an epimorphism to \(\mathbb Z\) has a usable kernel description for
a route such as `FJ26`.

**Warning.** Brown-positive finite generation is not the same as a
finite-rank free-kernel bridge. `FJ26` requires a recorded finite-rank
free kernel or another checked mapping-torus/hyperbolic-by-cyclic bridge.

## Main work

### Accepted payload

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND005-BROWN-BNS-2026-001` |
| Payload type | `PAY-T001-COMPUTATION` |
| Target gate | `OQ-113`, `OBL-C5-012`, and `OBL-T001-019` |
| Candidate | `CAND-T001-005`, \(G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle\) |
| Character | \(\chi(a)=0,\ \chi(b)=1\) |
| Object | Compute bounded Brown/BNS data needed to decide whether \(\ker(\chi)\) is finitely generated or remains kernel-control blocked. |
| Stop condition | Stop after the kernel-control audit and ledger update; do not create the next module. |

### Candidate and character

Let
\[
G_{FJ90}=\langle a,b\mid w\rangle,
\qquad
w=a b a^{-1} b^2 a b^{-3}.
\]

The relator has total \(b\)-exponent zero, so the assignment
\(\chi(a)=0,\ \chi(b)=1\) defines a homomorphism
\(\chi\colon G_{FJ90}\to\mathbb Z\). Since \(b\) maps to \(1\), \(\chi\) is
surjective.

The word \(w\) is cyclically reduced for the purposes of the recorded Brown
test: there is no cancellation between adjacent displayed letters and no
cyclic cancellation between the first letter \(a\) and last letter \(b^{-1}\).

### Brown initial-segment computation for chi

Use the proper initial segments of the displayed cyclically reduced relator:

| Proper initial segment | \(\chi\)-value |
| --- | ---: |
| \(1\) | 0 |
| \(a\) | 0 |
| \(ab\) | 1 |
| \(aba^{-1}\) | 1 |
| \(aba^{-1}b\) | 2 |
| \(aba^{-1}b^2\) | 3 |
| \(aba^{-1}b^2a\) | 3 |
| \(aba^{-1}b^2ab^{-1}\) | 2 |
| \(aba^{-1}b^2ab^{-2}\) | 1 |

Here one generator, \(a\), has \(\chi(a)=0\). In the zero-on-one-generator
case recorded in `FJ30`, the relevant maximum must occur exactly twice. The
maximum value is \(3\), and it occurs exactly twice.

Therefore \([\chi]\) passes the recorded Brown maximum-count test.

### Brown initial-segment computation for negative chi

For \(-\chi\), the same initial segments give:

| Proper initial segment | \(-\chi\)-value |
| --- | ---: |
| \(1\) | 0 |
| \(a\) | 0 |
| \(ab\) | -1 |
| \(aba^{-1}\) | -1 |
| \(aba^{-1}b\) | -2 |
| \(aba^{-1}b^2\) | -3 |
| \(aba^{-1}b^2a\) | -3 |
| \(aba^{-1}b^2ab^{-1}\) | -2 |
| \(aba^{-1}b^2ab^{-2}\) | -1 |

The maximum value is \(0\), and it occurs exactly twice. Therefore
\([-\chi]\) also passes the recorded Brown maximum-count test.

### Kernel-control decision

By the Brown/BNS framework recorded in `FJ30`, Brown-positive status in both
directions gives finite generation of \(\ker(\chi)\).

This module does not identify \(\ker(\chi)\) as a finite-rank free group.
The current project route `FJ26` therefore remains unavailable for this row
until a later accepted payload supplies one of:

- a finite-rank free-kernel identification;
- a source-verified mapping-torus or hyperbolic-by-cyclic bridge;
- a known-route / prior-art blocker;
- another formulation-safe Farrell--Jones route.

Thus the classification is:

```text
CAND-T001-005 kernel status after FJ92:
finitely generated but not identified as finite-rank free.
```

## Proposition

**Proposition.** For
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
and \(\chi(a)=0,\chi(b)=1\), the recorded Brown two-generator one-relator
criterion verifies both \([\chi]\) and \([-\chi]\). Hence
\(\ker(\chi)\) is finitely generated.

## Proof or verification

The character \(\chi\) is a surjection because \(b\mapsto 1\), and it
respects the relator because the total \(b\)-exponent of
\(a b a^{-1} b^2 a b^{-3}\) is \(1+2-3=0\).

The proper-initial-segment computation for \(\chi\) gives the value sequence
\[
0,0,1,1,2,3,3,2,1.
\]
Since \(\chi(a)=0\), the zero-on-one-generator Brown case requires the
maximum to occur exactly twice. The maximum is \(3\), and it occurs twice.

The computation for \(-\chi\) gives
\[
0,0,-1,-1,-2,-3,-3,-2,-1.
\]
The maximum is \(0\), and it occurs twice.

Thus both \([\chi]\) and \([-\chi]\) pass the checked Brown criterion
recorded in `FJ30`. Brown's Corollary 3.2, as recorded there, gives finite
generation of \(\ker(\chi)\).

The verification stops at finite generation. No finite-rank free-kernel
bridge is recorded here.

## References

Brown, K. S. (1987). Trees, valuations, and the
Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
https://doi.org/10.1007/BF01389176

Source-status note: no new external source was checked in `FJ92`; this
module uses the Brown theorem package already checked in `FJ30`.

## Dependencies

This module depends on:

- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`;
- `modules/cycle_003/FJ41_direct_bns_theorem_verification.md`;
- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `next_prompts.md`, Prompt 010;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND005-BROWN-BNS-2026-001`;
- completed Prompt 010 in `next_prompts.md`;
- resolution of `OQ-113`;
- completion of `OBL-C5-012`;
- partial completion of `OBL-T001-019` for Brown-positive finite generation;
- new route-promotion blocker `OBL-T001-020`;
- new payload gate `OBL-C5-013`;
- new open question `OQ-114`;
- candidate-status update for `CAND-T001-005`: Brown-positive,
  finitely generated kernel, not identified as finite-rank free;
- no new established Farrell--Jones result;
- no residual-bucket subtraction.

## Open questions generated

- `OQ-114`: Which accepted payload, if any, should instantiate `FJ93` after
  the `FJ92` Brown/BNS kernel-control computation?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the post-`FJ92` project posture;
- `NOTATION_LEDGER.md` for the new payload, module status, open question,
  and proof obligations;
- `OPEN_QUESTIONS.md` for `OQ-113` and `OQ-114`;
- `ledgers/t001_candidate_inventory.md` for `CAND-T001-005`;
- `ledgers/t001_residual.md` for the non-subtractive residual effect;
- `ledgers/t001_kernel_recognition.md` for the Brown-positive finite
  generation computation;
- `ledgers/payload_intake_protocol.md` for the accepted payload record;
- `ledgers/theorem_dependencies.md` for the FJ92 dependency row.
