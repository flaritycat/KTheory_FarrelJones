# Module FJ91. CAND-T001-005 Torsion-Free Source Check

## Status

Completed

## Module type

Candidate-status verification / Literature verification /
Payload-instantiated module

## Problem

`FJ90` added the concrete one-relator candidate
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
as `CAND-T001-005`, but it did not source-check torsion-free status.

This module executes accepted payload `PAY-T001-CAND005-TF-2026-001` and asks
only whether the non-proper-power check from `FJ90` combines with a checked
one-relator torsion theorem to promote the row's torsion-free status.

## Input

- `FJ90`, especially the internal non-proper-power check for
  \(w=a b a^{-1} b^2 a b^{-3}\);
- `next_prompts.md`, Prompt 009;
- `OQ-112`;
- `OBL-C5-011`;
- `OBL-T001-018`;
- Putman's notes on one-relator groups, used as the accessible checked source
  for the Karrass--Magnus--Solitar torsion theorem and its torsion-free
  corollary.

## Output target

Decide whether `CAND-T001-005` has source-checked torsion-free status at the
candidate-ledger level.

The output must not:

- compute Brown/BNS data;
- identify a kernel type;
- audit known Farrell--Jones routes or prior art;
- claim full `T-001`;
- claim coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, or `FICwF`;
- subtract a residual bucket;
- create `FJ92`.

## Definitions

**Definition.** For this module, source-checked torsion-free status means:
there is a checked source theorem whose hypotheses apply to the exact
presentation defining the candidate, and whose conclusion is that the group
has no nontrivial finite-order elements.

**Definition.** A word \(w\in F(S)\) is a proper power if
\(w=v^n\) in the free group \(F(S)\) for some \(v\in F(S)\) and integer
\(n>1\).

**Warning.** Torsion-free status is a target-status input for `T-001`; it is
not a Farrell--Jones route by itself.

## Main work

### Accepted payload

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND005-TF-2026-001` |
| Payload type | `PAY-T001-BRIDGE` |
| Target gate | `OQ-112`, `OBL-C5-011`, and `OBL-T001-018` |
| Candidate | `CAND-T001-005`, \(G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle\) |
| Object | Check whether the `FJ90` non-proper-power verification combines with a source-checked one-relator torsion theorem to promote torsion-free status. |
| Stop condition | Stop after torsion-free source-check and ledger update; do not create `FJ92`. |

### FJ90 internal input

`FJ90` records the relator
\[
w=a b a^{-1} b^2 a b^{-3}.
\]

In abelianization, the exponent vector is
\[
([a]\text{-exponent},[b]\text{-exponent})=(1,0).
\]

If \(w=v^n\) in the free group for some \(n>1\), then the abelianization
vector of \(w\) would be \(n\) times the abelianization vector of \(v\).  The
vector \((1,0)\) is primitive and is not divisible by any \(n>1\).  Thus the
`FJ90` check rules out \(w\) being a proper power.

### Source theorem checked

**Source-verified claim.** Putman's notes state the Karrass--Magnus--Solitar
torsion theorem for one-relator groups and record the immediate corollary
that if \(G=\langle S\mid r\rangle\) and \(r\in F(S)\) is not a proper power,
then \(G\) is torsion-free (Putman, n.d., Sec. 4).

Exact hypotheses used here:

- \(G\) has a one-relator presentation \(\langle S\mid r\rangle\);
- \(r\) is a word in the free group \(F(S)\);
- \(r\) is not a proper power in \(F(S)\).

Conclusion used here:

- \(G\) is torsion-free.

Source-status caution:

- Putman's notes are the checked accessible source for this module.
- The notes attribute the underlying torsion theorem to Karrass, Magnus, and
  Solitar (1960), but `FJ91` does not independently check the original paper.

### Application to CAND-T001-005

For `CAND-T001-005`, take \(S=\{a,b\}\) and
\[
r=w=a b a^{-1} b^2 a b^{-3}.
\]

The presentation is a one-relator presentation, and the `FJ90`
abelianization check records that \(w\) is not a proper power. Therefore the
checked torsion-free corollary applies to \(G_{FJ90}\).

### Candidate-status effect

The torsion-free-status blocker for `CAND-T001-005` is cleared at first-pass
candidate-ledger level.

The following remain unresolved:

- Brown/BNS data;
- kernel type for \(\chi(a)=0,\chi(b)=1\);
- known-route overlap;
- prior-art comparison;
- any full Farrell--Jones, coefficient FJC, full \(\mathcal{FJ}\), `FJCw`,
  `FICwF`, or weaker \(K_0\) promotion.

## Proposition

**Proposition.** `CAND-T001-005` is torsion-free at first-pass
candidate-status level.

## Proof or verification

By `FJ90`, the relator \(w=a b a^{-1} b^2 a b^{-3}\) is not a proper power
in \(F(a,b)\), using the primitive abelianization vector \((1,0)\). Putman's
checked one-relator torsion corollary says that a one-relator group
\(\langle S\mid r\rangle\) with \(r\) not a proper power is torsion-free.
Applying this with \(S=\{a,b\}\) and \(r=w\) gives that
\(G_{FJ90}\) is torsion-free.

This verifies only torsion-free target status. It does not identify any
Farrell--Jones route.

## References

Putman, A. (n.d.). *One-relator groups*. University of Notre Dame.
https://www3.nd.edu/~andyp/notes/OneRelator.pdf

Karrass, A., Magnus, W., & Solitar, D. (1960). Elements of finite order in
groups with a single defining relation. *Communications on Pure and Applied
Mathematics, 13*, 57--66. Cited in Putman (n.d.); original paper not
independently checked in `FJ91`.

## Dependencies

This module depends on:

- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `next_prompts.md`, Prompt 009;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND005-TF-2026-001`;
- completed Prompt 009 in `next_prompts.md`;
- resolution of `OQ-112`;
- completion of `OBL-C5-011`;
- partial completion of `OBL-T001-018` for torsion-free status;
- candidate-status promotion of `CAND-T001-005` from
  "blocked / not source-verified" to "torsion-free at first-pass
  candidate-status level";
- new active route-promotion blocker `OBL-T001-019`;
- new payload gate `OBL-C5-012`;
- new open question `OQ-113`;
- no new established Farrell--Jones result;
- no residual-bucket subtraction.

## Open questions generated

- `OQ-113`: Which accepted payload, if any, should instantiate `FJ92` after
  the `FJ91` torsion-free source check?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the post-`FJ91` project posture;
- `NOTATION_LEDGER.md` for the new payload, module status, open question,
  and proof obligations;
- `OPEN_QUESTIONS.md` for `OQ-112` and `OQ-113`;
- `BIBLIOGRAPHY.md` for Putman and the Karrass--Magnus--Solitar citation
  status;
- `ledgers/source_status.md` for the source-use label;
- `ledgers/t001_candidate_inventory.md` for `CAND-T001-005`;
- `ledgers/t001_residual.md` for the non-subtractive residual effect;
- `ledgers/payload_intake_protocol.md` for the accepted payload record;
- `ledgers/theorem_dependencies.md` for the FJ91 dependency row.
