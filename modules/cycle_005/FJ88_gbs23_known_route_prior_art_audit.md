# Module FJ88. G_BS23 Known-Route and Prior-Art Blocker Audit

## Status

Completed

## Module type

Candidate-status verification / Literature verification / Prior-art blocker /
Payload-instantiated module

## Problem

After `FJ87`, the candidate row `CAND-T001-004` for
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle
\]
had first-pass torsion-free / HNN status, but it still lacked route overlap
and prior-art comparison.

The accepted payload `PAY-T001-BS23-ROUTE-PRIORART-2026-001` asks for a
bounded audit: decide whether this single candidate is already covered by a
known Farrell--Jones route or prior-art theorem, and stop without computing
Brown/BNS data or kernel control.

## Input

- `FJ86`;
- `FJ87`;
- `OQ-109`;
- `OBL-C5-008`;
- `OBL-T001-017`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- Gandini--Meinert--Rueping (2015).

## Output target

FJ88 should:

- record the accepted FJ88 payload;
- identify whether \(G_{BS23}\) is already covered by a source-verified
  known route;
- update `CAND-T001-004` accordingly;
- record exact source hypotheses and formulation level;
- avoid Brown/BNS or kernel-control work;
- make no global `T-001` theorem claim.

## Definitions

**Definition.** Let
\[
BS(p,q)=\langle x,t\mid t x^p t^{-1}=x^q\rangle.
\]
Then
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle
\]
is \(BS(2,3)\) after rewriting the relator as \(t a^2t^{-1}=a^3\).

**Definition.** In Gandini--Meinert--Rueping (2015), \(C\) denotes the class
of groups satisfying the K- and L-theoretic Farrell--Jones conjecture with
finite wreath products, with coefficients in additive categories, with
respect to the family of virtually cyclic subgroups.

**Warning.** A source-verified route for \(BS(2,3)\) is a prior-art blocker
for the candidate row `CAND-T001-004`. It is not a proof that all
torsion-free one-relator groups satisfy Farrell--Jones.

## Main work

### Accepted payload

| Field | FJ88 record |
| --- | --- |
| Payload ID | `PAY-T001-BS23-ROUTE-PRIORART-2026-001` |
| Payload type | `PAY-T001-BLOCKER` |
| Target gates | `OQ-109`, `OBL-C5-008`, and `OBL-T001-017` |
| Object | Known-route / prior-art blocker audit for `CAND-T001-004`, \(G_{BS23}\). |
| Repository objects changed | `modules/cycle_005/FJ88_gbs23_known_route_prior_art_audit.md`; `ledgers/payload_intake_protocol.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; `README.md`; `PROJECT_CHARTER.md`; `BIBLIOGRAPHY.md`; `ledgers/source_status.md`; `ESTABLISHED_RESULTS.md`; `SCOPE_LEDGER.md`; `NOTATION_LEDGER.md`; `ledgers/known_classes.md`; `ledgers/open_group_classes.md`. |
| Stop condition | Stop after the known-route / prior-art blocker audit and ledger update. Do not compute Brown/BNS data or kernel control. Do not create `FJ89`. |

### Candidate identification

The FJ87 presentation
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle
\]
is equivalent to
\[
\langle a,t\mid t a^2t^{-1}=a^3\rangle.
\]
Thus \(G_{BS23}=BS(2,3)\) in the Baumslag--Solitar convention used by
Gandini--Meinert--Rueping.

Gandini--Meinert--Rueping give the explicit graph-of-groups model for
\(BS(p,q)\): one vertex and one edge, with vertex and edge group infinite
cyclic and edge maps sending the cyclic generator to the \(p\)-th and
\(q\)-th powers. For \(p=2\) and \(q=3\), this places \(G_{BS23}\) inside the
class of fundamental groups of finite graphs of infinite cyclic groups.

### Source theorem and formulation level

**Source-verified claim.** Gandini--Meinert--Rueping prove that the
fundamental group of any graph of abelian groups lies in their class \(C\).
They also state that all generalized Baumslag--Solitar groups, and in
particular all Baumslag--Solitar groups, lie in \(C\).

The relevant source hypotheses are:

- a graph of groups;
- abelian vertex groups;
- no finiteness or countability restriction is needed for the main theorem;
- \(BS(2,3)\) is covered by the finite graph of infinite cyclic groups
  example.

The formulation level is stronger than the project needs for the candidate
audit: K- and L-theoretic Farrell--Jones with finite wreath products and
coefficients in additive categories. Under the `FJ02` source-convention
policy, the finite-wreath-product label must remain visible; this route
does not collapse into full \(\mathcal{FJ}\) or `FICwF` without separate
comparison.

### Route audit table

| Route checked | FJ88 status for `CAND-T001-004` | Reason |
|---|---|---|
| Graph of abelian groups / generalized Baumslag--Solitar | source-verified route found | \(G_{BS23}=BS(2,3)\) is the fundamental group of a finite graph of infinite cyclic groups, hence a graph of abelian groups; Gandini--Meinert--Rueping route it through \(C\). |
| Direct Baumslag--Solitar prior art | prior-art blocker found | Gandini--Meinert--Rueping explicitly record Baumslag--Solitar groups as a corollary of their theorem. |
| Hyperbolic route | not used | No hyperbolicity bridge for \(G_{BS23}\) is checked in FJ88. |
| CAT(0) / compact-special route | not used | No CAT(0), cubical, or specialness recognition source is checked in FJ88. |
| Virtually solvable route | not used | No virtual-solvability bridge is checked in FJ88, and the graph-of-abelian route already resolves the candidate route status. |
| Finite-index / `FJCw` bridge | not needed | The candidate receives a direct finite-wreath-product source route; no finite-index passage is required. |
| Free-by-cyclic / hyperbolic-by-cyclic route | not used | FJ88 does not compute the kernel of \(\chi(t)=1,\chi(a)=0\). |
| FJ83 weaker \(K_0\) / Cohen--Lyndon route | not used | The stronger graph-of-abelian source route is enough for this candidate; no Cohen--Lyndon hypothesis audit is performed. |

### Candidate-status effect

`CAND-T001-004` is no longer a live non-routed residual candidate. It is a
source-routed and prior-art-blocked candidate row:

- the row remains useful as a calibration example for payload discipline;
- kernel control remains uncomputed, but is no longer needed to route this
  candidate;
- the route is not a new residual subtraction method for `T-001`, because it
  is an external prior-art theorem covering Baumslag--Solitar groups;
- the global class of torsion-free one-relator groups remains unresolved.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The candidate \(G_{BS23}\) is already covered by the
Gandini--Meinert--Rueping graph-of-abelian-groups Farrell--Jones route.

This is a candidate-status route proposition for `CAND-T001-004`, not a
new theorem about all torsion-free one-relator groups.

## Proof or verification

The relation in \(G_{BS23}\) rewrites as \(t a^2t^{-1}=a^3\), so
\[
G_{BS23}=BS(2,3).
\]
Gandini--Meinert--Rueping model \(BS(p,q)\) as the fundamental group of a
graph of groups with one infinite cyclic vertex group, one infinite cyclic
edge group, and edge maps \(x\mapsto x^p\) and \(x\mapsto x^q\). Thus
\(G_{BS23}\) is the fundamental group of a finite graph of abelian groups.

By the main theorem of Gandini--Meinert--Rueping, the fundamental group of a
graph of abelian groups lies in \(C\), where \(C\) is their finite-wreath-
product, additive-category K- and L-theoretic Farrell--Jones class. Their
Corollary 1.1 explicitly includes all Baumslag--Solitar groups.

Therefore \(G_{BS23}\) is already covered by a source-verified
Farrell--Jones route at the formulation level recorded above.

## References

- Gandini, G., Meinert, S., & Rueping, H. (2015). The Farrell-Jones
  conjecture for fundamental groups of graphs of abelian groups. *Groups,
  Geometry, and Dynamics, 9*(3), 783--792.
  https://doi.org/10.4171/GGD/327

Internal references:

- `modules/cycle_005/FJ86_t001_candidate_intake_audit.md`;
- `modules/cycle_005/FJ87_gbs23_torsion_free_hnn_check.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`.

## Dependencies

This module depends on:

- `FJ02`;
- `FJ86`;
- `FJ87`;
- `OQ-109`;
- `OBL-C5-008`;
- `OBL-T001-017`;
- Gandini--Meinert--Rueping (2015).

## Results produced

This module produced:

- accepted payload record `PAY-T001-BS23-ROUTE-PRIORART-2026-001`;
- first-pass resolution of `OQ-109`;
- completion of `OBL-C5-008` for FJ88;
- completion of `OBL-T001-017` for the known-route / prior-art audit;
- a source-verified route status for `CAND-T001-004`;
- prior-art blocker status for `CAND-T001-004`;
- `ER-015`, the graph-of-abelian-groups / Baumslag--Solitar source route;
- proof obligation `OBL-C5-009`;
- no Brown/BNS computation;
- no kernel-control result;
- no global `T-001` theorem.

## Open questions generated

- `OQ-110`: Which accepted payload, if any, should instantiate `FJ89` after
  the FJ88 closure of the \(G_{BS23}\) candidate route audit?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ESTABLISHED_RESULTS.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/known_classes.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`.
