# T-001 Candidate Inventory

## Status

Created by `FJ54` as the candidate ledger for the `RB-003` +
`RB-004`/`RB-008` hybrid attack packet.

This file is not a list of new examples. It records only candidate families
already present in the repository, plus clearly marked template placeholders
for future modules.

## Active attack packet

Primary packet:

`RB-003` + `RB-004`/`RB-008` hybrid: primitive-extension / hierarchy
framework combined with explicit kernel-control testing for concrete
torsion-free one-relator candidate families.

Guiding question:

Can Linton-style hierarchy / primitive-extension data be converted into an
FJ route, a candidate family, a bridge lemma, or a documented obstruction?

## Candidate inventory table

| Candidate ID | Presentation | Relator status: proper power? yes/no/unknown | Torsion-free status | \(\pi(w)\) status if relevant | Hyperbolicity route: known / blocked / unknown | CAT(0) / special route: known / blocked / unknown | BNS / Brown data | Epimorphism to \(\mathbb Z\) available? | Kernel type: finite-rank free / countable free / hyperbolic / unknown | Extension theorem candidate | `FJCw`/full-FJ formulation safety | Prior-art risk | Next proof obligation | Stop condition |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `CAND-T001-001` | \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) | unknown in this inventory | Recorded as calibration example in `FJ31`; already non-residual | not used | known route overlap via virtually solvable status, not a new hyperbolic subtraction | not needed | Brown maximum-count test recorded in `FJ31`; \(\ker(\chi)\cong F_1\) | yes, \(\chi(x)=1,\chi(y)=0\) | finite-rank free | `FJ26` route available but redundant; `FJ25` already covers it | no new finite-index or `FJCw` use | high risk of double-counting as novelty | none; calibration only | stop if proposed as a new residual subtraction |
| `CAND-T001-002` | \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) | unknown in this inventory | Internally verified in `FJ33` | not used | not needed for recorded route | not needed | Brown full test recorded in `FJ33` | yes, \(\chi(x)=3,\chi(y)=2\) | finite-rank free, specifically \(F_2\) in `FJ33` | `FJ26` finite-rank free-by-cyclic route | formulation-safe through existing `FJ26` route, not a new `FJCw` case | already removed; novelty risk if reused | none; already routed | stop if proposed as a new residual subtraction |
| `CAND-T001-003` | \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\) | unknown in this inventory | Internally verified for the recorded family route in `FJ36` | not used | not needed for recorded route | not needed | Brown-positive finite generation in `FJ34`; Bass--Serre freeness bridge in `FJ36` | yes, \(\chi_{p,q}(x)=q,\chi_{p,q}(y)=p\) | finite-rank free, rank not computed | `FJ26` finite-rank free-by-cyclic route | formulation-safe through existing `FJ26` route, not a new `FJCw` case | already removed; novelty risk if reused | none; already routed | stop if proposed as a new residual subtraction |
| `TPL-RB003-004-008` | template placeholder only | unknown | unknown | unknown | unknown | unknown | not computed | unknown | unknown | none selected | unresolved | unrecorded | identify a real presentation or family before source work | stop unless future module supplies an actual candidate, bridge lemma, or obstruction |

## Candidate intake checklist

For every future candidate row, record:

- Candidate ID;
- presentation;
- relator status: proper power? yes / no / unknown;
- torsion-free status;
- \(\pi(w)\) status if relevant;
- hyperbolicity route: known / blocked / unknown;
- CAT(0) / special route: known / blocked / unknown;
- BNS / Brown data;
- epimorphism to \(\mathbb Z\) available?;
- kernel type: finite-rank free / countable free / hyperbolic / unknown;
- extension theorem candidate;
- `FJCw` / full-FJ formulation safety;
- prior-art risk;
- next proof obligation;
- stop condition.

## Non-use warnings

- Do not fabricate candidate families.
- Do not count `CAND-T001-001`, `CAND-T001-002`, or `CAND-T001-003` as new
  residual subtractions.
- Do not use `TPL-RB003-004-008` as a mathematical candidate; it is a
  placeholder for future module work.
- Do not open a source-summary module unless a row above changes or a new
  candidate row is justified.

## Next update

`FJ55` should test whether primitive-extension / hierarchy data can create a
candidate-level bridge, candidate row, or obstruction for the selected hybrid
packet.
