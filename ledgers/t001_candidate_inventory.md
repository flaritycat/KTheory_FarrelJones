# T-001 Candidate Inventory

## Status

Created by `FJ54` as the candidate ledger for the `RB-003` +
`RB-004`/`RB-008` hybrid attack packet. Updated by `FJ55` with
route-output proof obligations, by `FJ56` with explicit kernel-control
audit status, and by `FJ57` with the no-candidate endpoint obstruction.

This file is not a list of new examples. It records only candidate families
already present in the repository, plus clearly marked template placeholders
for future modules.

## Active attack packet

Selected packet:

`RB-003` + `RB-004`/`RB-008` hybrid: primitive-extension / hierarchy
framework combined with explicit kernel-control testing for concrete
torsion-free one-relator candidate families.

Current status after `FJ57`: blocked at candidate production. The packet can
be reactivated only after a real candidate, concrete computation, bridge
lemma, or prior-art comparison is recorded.

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

## FJ56 kernel-control audit

| Candidate ID | Kernel-control status | Route-output status | Active for `FJ57`? | FJ56 decision |
|---|---|---|---|---|
| `CAND-T001-001` | epimorphism and finite-rank free kernel recorded in `FJ31` | `FJ26` output exists but is redundant with the virtually solvable route | no | keep as calibration only |
| `CAND-T001-002` | epimorphism, Brown-positive data, and \(\ker(\chi)\cong F_2\) recorded in `FJ33` | already removed through `FJ26` | no | keep as routed example only |
| `CAND-T001-003` | epimorphism, Brown-positive finite generation, and Bass--Serre finite-rank freeness recorded in `FJ34`/`FJ36` | already removed through `FJ26` | no | keep as routed family only |
| `TPL-RB003-004-008` | no presentation, epimorphism, BNS/Brown data, or kernel type | no route output selected | no | placeholder only; future module must supply a real candidate before proof work |

`FJ56` conclusion: the repository has no live non-routed kernel-control
candidate after auditing the existing rows. The next module must either add a
repository-supported non-routed candidate row or record the no-candidate
obstruction as the current endpoint of the hybrid packet.

## FJ57 candidate-promotion attempt

| Possible promotion source | FJ57 decision | Reason |
|---|---|---|
| `CAND-T001-001` | do not promote | calibration-only and already covered by the virtually solvable route |
| `CAND-T001-002` | do not promote | already removed through `FJ26` |
| `CAND-T001-003` | do not promote | already removed through `FJ26` |
| `TPL-RB003-004-008` | do not promote | placeholder only; no presentation, route output, kernel data, or prior-art comparison |
| Non-Brown finitely presented-kernel lane | do not promote | `FJ40` records no source-ready non-Brown example |
| Direct BNS lane | do not promote | no \(\Sigma(G)\)-membership computation for a non-routed candidate |
| Finite-index / `FJCw` lane | do not promote | no named application case after `FJ48`/`FJ50` |
| `RB-006` Louder--Wilton lane | do not promote | WIP / provisional `FJ53` records only hyperbolic overlap and no concrete word |

`FJ57` conclusion: the selected hybrid packet is blocked at candidate
production. The candidate inventory remains open for intake, but no current
row supports a new proof attempt.

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

## Proof-obligation inventory

| Obligation ID | Status | Source module | Statement | Required next action | Stop condition |
|---|---|---|---|---|---|
| `OBL-T001-001` | active obstruction | `FJ55` | No direct hierarchy-to-FJ bridge is currently recorded. Hierarchy existence, HNN structure, or primitive-extension shorthand must pass through an approved route output before any residual subtraction. | Use `FJ56` to attach explicit kernel-control data to repository-supported candidate rows. | Stop any hierarchy-only source lane unless it changes a candidate, route output, or obstruction. |
| `OBL-T001-002` | active requirement | `FJ55` | Every future `RB-003` + `RB-004`/`RB-008` hybrid candidate must state which route output it seeks: hyperbolicity, CAT(0)/special input, finite-rank free or hyperbolic kernel extension, or version-safe inheritance. | Add a route-output field note to candidate rows when they become active. | Stop if the candidate cannot name a route output or a documented obstruction. |
| `OBL-T001-003` | active obstruction | `FJ56` | No live non-routed kernel-control candidate is currently present in the candidate inventory. Existing concrete rows are calibration-only or already removed through `FJ26`; the remaining template row is not a mathematical candidate. | Use `FJ57` either to promote a repository-supported non-routed candidate or to record the no-candidate obstruction precisely. | Stop the hybrid packet if no real candidate, bridge lemma, or obstruction beyond this inventory can be recorded. |
| `OBL-T001-004` | active obstruction | `FJ57` | The selected `RB-003` + `RB-004`/`RB-008` hybrid packet is blocked at candidate production. | Use `FJ58` to decide whether another candidate-production lane can be made legitimate. | Do not reactivate the hybrid packet unless a real candidate, concrete computation, bridge lemma, or prior-art comparison is recorded. |

## Non-use warnings

- Do not fabricate candidate families.
- Do not count `CAND-T001-001`, `CAND-T001-002`, or `CAND-T001-003` as new
  residual subtractions.
- Do not use `TPL-RB003-004-008` as a mathematical candidate; it is a
  placeholder for future module work.
- Do not open a source-summary module unless a row above changes or a new
  candidate row is justified.

## Next update

`FJ58` should decide which candidate-production lane, if any, can replace the
blocked hybrid packet without reopening passive source accumulation.
