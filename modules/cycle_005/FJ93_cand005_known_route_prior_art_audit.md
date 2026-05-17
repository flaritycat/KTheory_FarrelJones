# Module FJ93. CAND-T001-005 Known-Route and Prior-Art Blocker Audit

## Status

Completed

## Module type

Candidate-status verification / Known-route audit / Prior-art blocker /
Payload-instantiated module

## Problem

`FJ92` verifies Brown-positive finite generation of the \(\chi\)-kernel for
`CAND-T001-005`, but it does not identify a finite-rank free kernel and does
not invoke the `FJ26` route.

This module executes accepted prompt payload
`PAY-T001-CAND005-ROUTE-PRIORART-2026-001` and asks only whether the current
repository already records a named Farrell--Jones route or prior-art blocker
for
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle.
\]

## Input

- `FJ23`, the hyperbolic route;
- `FJ24`, the CAT(0) / compact-special route;
- `FJ25`, the virtually solvable route;
- `FJ26`, the hyperbolic-by-cyclic / finite-rank free-by-cyclic route;
- `FJ27`, the inheritance-route ledger;
- `FJ83` and `FJ84`, the weaker \(K_0\) / Cohen--Lyndon payload and
  candidate-hypothesis audit;
- `FJ88`, the graph-of-abelian-groups prior-art route for \(G_{BS23}\);
- `FJ90`, `FJ91`, and `FJ92`, the current `CAND-T001-005` intake,
  torsion-free check, and Brown/BNS computation;
- `next_prompts.md`, Prompt 011;
- `OQ-114`;
- `OBL-C5-013`;
- `OBL-T001-020`.

## Output target

Classify `CAND-T001-005` as one of:

- already routed;
- prior-art blocked;
- still route-blocked;
- still live as a concrete non-routed candidate object.

The output must not:

- claim full Farrell--Jones for `CAND-T001-005`;
- claim coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, or
  `FICwF`;
- claim a weaker \(K_0\) consequence;
- claim a residual-bucket subtraction;
- start a broad one-relator, Brown/BNS, or prior-art survey;
- create `FJ94`.

## Definitions

**Definition.** A known-route blocker is a recorded source-verified theorem
or internal route bridge that already places a candidate in one of the
project's approved Farrell--Jones routes.

**Definition.** A prior-art blocker is a recorded external theorem that covers
the candidate directly enough that the row should not be treated as a new
residual proof target.

**Warning.** Absence of a recorded route in this module is not a negative
theorem about the group. It only records that the current repository has not
yet supplied a usable route or blocker.

## Main work

### Accepted payload

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-CAND005-ROUTE-PRIORART-2026-001` |
| Payload type | `PAY-T001-BLOCKER` |
| Target gate | Active post-`FJ92` gate plus `OBL-T001-020` |
| Candidate | `CAND-T001-005`, \(G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle\) |
| Object | Audit whether the candidate is already removed by a named repository route or prior-art theorem. |
| Stop condition | Stop after known-route / prior-art blocker audit and ledger update. |

### Candidate state before the audit

The repository records the following current data for `CAND-T001-005`:

- `FJ90`: the relator is first-pass checked as not a proper power and the
  epimorphism \(\chi(a)=0,\chi(b)=1\) is recorded;
- `FJ91`: torsion-free status is first-pass source-verified via Putman's
  statement of the Karrass--Magnus--Solitar one-relator torsion theorem;
- `FJ92`: Brown's recorded maximum-count test verifies finite generation of
  \(\ker(\chi)\);
- no finite-rank free-kernel identification is recorded;
- no hyperbolic, CAT(0), virtually solvable, finite-index, graph-of-abelian,
  or weaker \(K_0\) / Cohen--Lyndon route is recorded for this row.

### Route audit table

| Route or blocker checked | Required recorded bridge | FJ93 status | Reason |
| --- | --- | --- | --- |
| Hyperbolic route (`FJ23`) | Source-verified hyperbolicity bridge for the exact candidate or a family containing it | not routed | No hyperbolicity bridge for \(G_{FJ90}\) is recorded in the current candidate row. |
| CAT(0) / compact-special route (`FJ24`) | Source-verified finite-dimensional CAT(0) action, or compact finite-dimensional special cube complex bridge with formulation-safe passage | not routed | No CAT(0), cubical, or compact-special bridge is recorded for this presentation. |
| Virtually solvable route (`FJ25`) | Source-verified or internally proved virtual-solvability bridge | not routed | Torsion-free status, abelianization data, and an epimorphism to \(\mathbb Z\) do not establish virtual solvability. No virtual-solvability recognition bridge is recorded. |
| Finite-index / `FJCw` route (`FJ27`, `FJ47`) | Finite-index subgroup or overgroup data with the correct formulation flag | not routed | No finite-index subgroup, overgroup, or `FJCw` input is recorded for the candidate. |
| Finite-rank free-by-cyclic route (`FJ26`) | Exact sequence \(1\to F_n\to G\to\mathbb Z\to 1\) with \(n<\infty\), or equivalent finite-rank free-kernel bridge | not routed | `FJ92` gives finite generation of \(\ker(\chi)\), but does not identify it as finite-rank free. |
| Hyperbolic-by-cyclic route (`FJ26`) | Semidirect-product bridge \(H\rtimes\mathbb Z\) with \(H\) virtually torsion-free hyperbolic | not routed | The kernel is not identified as virtually torsion-free hyperbolic, and no mapping-torus theorem input is recorded. |
| Graph-of-abelian-groups route (`FJ88`) | Graph-of-abelian-groups model or generalized Baumslag--Solitar identification for this candidate | not routed | `FJ88` routes \(G_{BS23}\), not \(G_{FJ90}\). No graph-of-abelian-groups model is recorded for `CAND-T001-005`. |
| Weaker \(K_0\) / Cohen--Lyndon route (`FJ83`, `FJ84`) | Full source-hypothesis package: Cohen--Lyndon or group-pair data, torsion-free status, regular-ring formulation, normalizer, finite cohomological dimension, coherent group-ring hypotheses, and prior-art safety | not eligible from current data | The candidate row records torsion-free status but no Cohen--Lyndon/group-pair package, normalizer data, finite cohomological dimension, coherent group-ring input, or formulation comparison. |
| Other inheritance routes (`FJ12`, `FJ27`) | Exact inheritance source, version flag, and verified group-extension or colimit data | not routed | No inheritance-safe exact sequence or colimit object is recorded beyond the epimorphism to \(\mathbb Z\), and its kernel type remains insufficient. |

## Proposition

**Proposition.** In the current repository state, `FJ93` finds no recorded
known-route bridge or prior-art blocker that routes `CAND-T001-005`.

## Proof or verification

The verification is by bounded route comparison.

The hyperbolic, CAT(0), virtually solvable, finite-index, and inheritance
routes each require a source-verified bridge recorded on the candidate row or
in a family containing it. No such bridge is currently recorded for
`CAND-T001-005`.

The `FJ26` route is also unavailable. `FJ92` records finite generation of
\(\ker(\chi)\), but the approved finite-rank free-by-cyclic route requires a
finite-rank free-kernel bridge or an equivalent mapping-torus /
hyperbolic-by-cyclic input.

The graph-of-abelian-groups route from `FJ88` applies to \(G_{BS23}\), not to
this presentation. No graph-of-abelian-groups model for \(G_{FJ90}\) is
recorded.

The weaker \(K_0\) / Cohen--Lyndon lane from `FJ83` and `FJ84` is not
eligible from current candidate data, because the required source-hypothesis
package is not recorded for `CAND-T001-005`.

Therefore the candidate is not already routed in the present repository. It
remains a concrete torsion-free one-relator candidate object with
Brown-positive finite generation of one kernel, but it is still
route-blocked and not residual-subtractive.

## References

Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell--Jones
conjecture for hyperbolic-by-cyclic groups. *International Mathematics
Research Notices, 2023*(7), 5887--5904.
https://doi.org/10.1093/imrn/rnac012

Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic Farrell--Jones
conjecture for hyperbolic groups. *Inventiones Mathematicae, 172*(1), 29--70.
https://doi.org/10.1007/s00222-007-0093-7

Gandini, G., Meinert, S., & Rueping, H. (2015). The Farrell-Jones conjecture
for fundamental groups of graphs of abelian groups. *Groups, Geometry, and
Dynamics, 9*(3), 783--792. https://doi.org/10.4171/GGD/327

Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs,
coherence and Farrell-Jones Conjecture for K0* (arXiv:2510.23518v2). arXiv.
https://doi.org/10.48550/arXiv.2510.23518

Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for CAT(0)-groups.
*Proceedings of the American Mathematical Society, 140*(3), 779--793.
https://doi.org/10.1090/S0002-9939-2011-11150-X

Wegner, C. (2015). The Farrell-Jones conjecture for virtually solvable groups.
*Journal of Topology, 8*(4), 975--1016. https://doi.org/10.1112/jtopol/jtv026

Source-status note: no new external source was checked in `FJ93`; the module
uses route sources and source-status labels already recorded in earlier
modules and ledgers.

## Dependencies

This module depends on:

- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`;
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`;
- `modules/cycle_002/FJ25_virtually_solvable_route_subtraction.md`;
- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`;
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`;
- `modules/cycle_005/FJ83_k0_cohen_lyndon_payload_verification.md`;
- `modules/cycle_005/FJ84_k0_cohen_lyndon_candidate_hypothesis_audit.md`;
- `modules/cycle_005/FJ88_gbs23_known_route_prior_art_audit.md`;
- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `modules/cycle_005/FJ92_cand005_brown_bns_kernel_control.md`;
- `next_prompts.md`, Prompt 011;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-CAND005-ROUTE-PRIORART-2026-001`;
- completion of Prompt 011 in `next_prompts.md`;
- resolution of `OQ-114`;
- completion of `OBL-C5-013`;
- completion of the route/prior-art-audit part of `OBL-T001-020`;
- new route-promotion blocker `OBL-T001-021`;
- new payload gate `OBL-C5-014`;
- new open question `OQ-115`;
- candidate-status update for `CAND-T001-005`: concrete torsion-free
  one-relator row, Brown-positive finite generation recorded, no known route
  or prior-art blocker recorded, still route-blocked;
- no new established Farrell--Jones result;
- no residual-bucket subtraction.

## Open questions generated

- `OQ-115`: Which accepted payload, if any, should instantiate `FJ94` after
  the `FJ93` known-route / prior-art blocker audit?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the post-`FJ93` project posture;
- `NOTATION_LEDGER.md` for the new payload, module status, open question,
  and proof obligations;
- `OPEN_QUESTIONS.md` for `OQ-114` and `OQ-115`;
- `ledgers/t001_candidate_inventory.md` for `CAND-T001-005`;
- `ledgers/t001_residual.md` for the non-subtractive residual effect;
- `ledgers/payload_intake_protocol.md` for the accepted payload record;
- `ledgers/theorem_dependencies.md` for the FJ93 dependency row;
- `AGENTS.md` for the active post-`FJ93` gate.
