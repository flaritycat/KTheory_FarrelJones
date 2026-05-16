# Module FJ83. K0 Cohen--Lyndon Payload Verification

## Status

Completed

## Module type

Source-payload verification / Weaker K0 consequence / Gate exit

## Problem

`FJ82` placed the project in `C5-PAUSE-001`: no numbered module may start
until an accepted payload is recorded. The accepted payload
`PAY-T001-K0-CL-2025-001` names a specific weaker \(K_0\) /
Cohen--Lyndon source for `T-001`.

FJ83 must verify the source statement, hypotheses, and formulation level
without promoting the payload to full Farrell--Jones, coefficient K-theory
FJC, `FJCw`, `FICwF`, or a residual subtraction for `T-001`.

## Input

- `ledgers/payload_intake_protocol.md`
- `OPEN_QUESTIONS.md`, especially `OQ-081` and `OQ-104`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `ledgers/source_status.md`
- `ledgers/theorem_dependencies.md`
- `BIBLIOGRAPHY.md`
- accepted payload `PAY-T001-K0-CL-2025-001`
- Jaikin-Zapirain, Linton, and Sanchez-Peralta (2025)

## Output target

FJ83 should:

- record the accepted payload as the exit object for `C5-PAUSE-001`;
- complete `OBL-C5-003` for this payload-instantiated module;
- verify the source metadata and theorem-level payload at first pass;
- update `OQ-081` from "no exact source payload available" to a checked
  weaker \(K_0\) / Cohen--Lyndon source-payload status;
- resolve `OQ-104` by identifying FJ83 as the payload-instantiated module;
- record that no full `T-001` result and no residual subtraction follows;
- stop after the source-hypothesis audit and ledger updates.

## Definitions

**Definition.** A *weaker \(K_0\)-level Farrell--Jones payload* is a
source-checked statement about the projective class group \(K_0(RG)\) or a
closely related \(K_0\)-map. It is not, by itself, coefficient K-theory FJC,
full \(\mathcal{FJ}\), `FJCw`, or `FICwF`.

**Definition.** A *Cohen--Lyndon source payload* is a source theorem or
source-defined theorem package using a Cohen--Lyndon presentation or
Cohen--Lyndon group pair with recorded hypotheses and a project object
changed.

**Warning.** In this module, "Farrell--Jones Conjecture for \(K_0\)" means
the source's \(K_0(R)\to K_0(RG)\) formulation for torsion-free groups and
regular rings. It is not promoted here to the project's coefficient
K-theory assembly formulation from `FJ02`.

## Main work

### Payload intake

| Field | FJ83 record |
| --- | --- |
| Payload ID | `PAY-T001-K0-CL-2025-001` |
| Payload type | `PAY-T001-BRIDGE` |
| Target gates | `OBL-C5-003`, `OBL-T001-013`, and the inactive weaker \(K_0\) / Cohen--Lyndon lane from `OQ-081` and `OBL-T001-007` |
| Source | Jaikin-Zapirain, Linton, and Sanchez-Peralta (2025) |
| Formulation level | weaker \(K_0\)-level / projective-class-group formulation only |
| Accepted? | Yes, for FJ83 source-payload verification only |
| Stop condition | Stop after source-hypothesis audit and ledger updates; do not create `FJ84` without a new accepted payload. |

### Source metadata check

The arXiv record for `arXiv:2510.23518` lists:

- title: *Group pairs, coherence and Farrell--Jones Conjecture for \(K_0\)*;
- authors: Andrei Jaikin-Zapirain, Marco Linton, and Pablo
  Sanchez-Peralta;
- version checked: `v2`;
- DOI: `10.48550/arXiv.2510.23518`;
- subject area: group theory.

The user's payload used the author initial `P.`; the arXiv metadata gives
the given name `Pablo`. The bibliography should therefore use the initial
`P.` and the source metadata spelling.

### Source statement audit

| Source item | FJ83 first-pass verification | Project status |
| --- | --- | --- |
| Conjecture 1 | The source formulates the \(K_0\)-level conjecture for a torsion-free group \(G\) and a regular ring \(R\): the inclusion \(R\to RG\) induces an isomorphism \(K_0(R)\to K_0(RG)\). | Verified as the source's weaker \(K_0\)-level formulation; not the project's full coefficient FJC. |
| Introductory K0 theorem, Theorem 1.7 in the paper's numbering | For a group pair \(\mathcal P=(G,X)\) satisfying the Cohen--Lyndon property, with each stabilizer \(G_x\) equal to its normalizer in \(G\), with \(R\) regular, \(\mathrm{cd}_R(G)<\infty\), and \(RG\) coherent, the source gives a natural surjectivity statement \(K_0(RG)\to K_0(R[G/\langle G_x:x\in X\rangle])\). | Verified as an exact source payload. It is a surjectivity theorem under hypotheses, not a direct project proof for all torsion-free one-relator groups. |
| Section theorem labeled `teoK_0` | The source proves a group-pair theorem: if \(\mathcal P=(G,X)\) satisfies the Cohen--Lyndon property over \(R\), \(G\) has finite \(R\)-cohomological dimension with coherent \(RG\), and the normalizer quotients \(N_G(G_x)/G_x\) have finite \(R\)-cohomological dimension with coherent group rings, then a natural map from \(K_0(RG)\) plus normalizer-quotient summands to \(K_0(R[\pi(\mathcal P)])\) is surjective. | Verified as the technical theorem behind the payload. Future use must preserve the extra hypotheses and summands. |
| Abstract-level claim | The source states that groups admitting a Cohen--Lyndon presentation satisfy the \(K_0\) Farrell--Jones formulation. | Recorded as source-level motivation. Project use still requires the theorem-hypothesis bridge for a candidate or family. |

### Hypothesis checklist

| Hypothesis or formulation item | FJ83 status | Consequence |
| --- | --- | --- |
| torsion-free group \(G\) | Required by Conjecture 1 and by the source-level implication to the \(K_0\)-formulation. | Not checked for any new `T-001` candidate in FJ83. |
| regular ring \(R\) | Explicit in Conjecture 1 and the K0 group-pair theorem. | Keep the result at regular-ring \(K_0\)-level. |
| Cohen--Lyndon presentation / group pair | Explicit source condition. | Future project use must identify the exact pair or presentation. |
| group-pair quotient \(\pi(\mathcal P)\) | Explicit source object in the theorem. | Must be matched to a concrete group before any application. |
| stabilizer equals normalizer | Required in the introductory K0 theorem. | Cannot be assumed for a candidate without verification. |
| normalizer quotient hypotheses | Present in the technical theorem through \(N_G(G_x)/G_x\). | Future use must check finite \(R\)-cohomological dimension and coherent group rings for the quotients. |
| finite cohomological dimension | Required in the K0 group-pair theorem. | Not supplied by `T-001` in general inside this module. |
| coherent group ring | Required for \(RG\) and, in the technical theorem, for the normalizer-quotient group rings. | This is a major bridge obligation before any candidate-level promotion. |
| full FJ / coefficient FJC / `FJCw` / `FICwF` | Not provided by this payload. | No residual subtraction and no full `T-001` theorem. |

### Project decision

FJ83 accepts the payload as a valid source-payload verification module. This
exits `C5-PAUSE-001` only for the bounded FJ83 task.

`OQ-081` changes from no exact weaker \(K_0\) / Cohen--Lyndon source payload
available to exact source payload located and first-pass verified at the
statement/hypothesis level.

The verification is not enough to promote an established result. It does not
prove the Farrell--Jones conjecture for all torsion-free one-relator groups.
It does not provide a coefficient K-theory route, `FJCw`, `FICwF`, full
\(\mathcal{FJ}\), or a `T-001` residual subtraction.

## Proposition / Theorem / Conjecture / Example

**Proposition.** `PAY-T001-K0-CL-2025-001` is an accepted payload sufficient
to instantiate `FJ83`, and its source gives a first-pass verified weaker
\(K_0\) / Cohen--Lyndon theorem package.

This is a repository-source-status proposition, not a new mathematical
theorem of the project.

## Proof or verification

The payload satisfies the `FJ82` protocol because it records a payload ID,
payload type, target gates, a specific source, an exact statement object,
APA-style citation data, source-status label, hypotheses and formulation
level, changed repository objects, success criterion, failure criterion, and
stop condition.

The arXiv page and TeX source identify the paper, authors, DOI, and version.
The source's introduction states Conjecture 1 as the \(K_0(R)\to K_0(RG)\)
isomorphism for torsion-free groups and regular rings. The same section
states the introductory K0 theorem giving a surjectivity map under the
Cohen--Lyndon, normalizer, finite cohomological dimension, and coherent
group-ring hypotheses. The final section states the more general group-pair
surjectivity theorem with normalizer-quotient summands.

Thus the payload is verified at source-statement level. The missing project
bridge is application to a concrete `T-001` candidate or family satisfying
the source hypotheses.

## References

Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs,
coherence and Farrell-Jones Conjecture for K0* (arXiv:2510.23518v2). arXiv.
https://arxiv.org/abs/2510.23518. https://doi.org/10.48550/arXiv.2510.23518.

## Dependencies

This module depends on:

- `FJ08`;
- `FJ09`;
- `FJ19`;
- `FJ59`;
- `FJ60`;
- `FJ82`;
- `OQ-081`;
- `OQ-104`;
- `OBL-T001-007`;
- `OBL-T001-013`;
- `OBL-C5-003`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-K0-CL-2025-001`;
- completion of `OBL-C5-003` for FJ83;
- first-pass resolution of `OQ-104`;
- updated first-pass status for `OQ-081`;
- source-status entry for Jaikin-Zapirain, Linton, and Sanchez-Peralta
  (2025);
- proof obligation `OBL-T001-014`: future use of this \(K_0\) /
  Cohen--Lyndon payload must map the exact source hypotheses to a concrete
  `T-001` candidate or family before any promotion;
- proof obligation `OBL-C5-004`: no `FJ84` may be created without a new
  accepted payload.

No established mathematical result was produced.

## Open questions generated

- `OQ-105`: Which accepted payload, if any, should instantiate `FJ84` after
  FJ83?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `AGENTS.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/source_status.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
