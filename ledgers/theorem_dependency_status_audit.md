# Theorem Dependency Status Audit

## Status

Completed.

## Purpose

This audit executes Prompt 009 from `the 15-next-steps.md`. It clarifies which
theorem dependencies are active, inactive, blocked, source-only, or
formulation-safety items after `cycle_005`, the post-100 review, and the
cycle-006 payload-gated pause.

No external source was consulted. No theorem statement is promoted by this
audit.

## Current Active Dependency

The only active project dependency after the cycle-006 pause is procedural:

| Active dependency | Status | Controls | Effect |
|---|---|---|---|
| `OQ-126` / `OBL-C6-003` / `C6-PAUSE-001` | active governance gate | whether a concrete accepted payload can instantiate the next numbered module | blocks `FJ101`, target reactivation, source work, proof attempts, and residual subtraction until a concrete accepted payload is recorded |

There is no active mathematical theorem dependency for a current proof target.

## Dependency Status Map

| Dependency cluster | Current status | Governing repository object | Use allowed now |
|---|---|---|---|
| Established internal and source-verified results `ER-001`--`ER-015` | established for their recorded hypotheses | `ESTABLISHED_RESULTS.md`; module rows in `ledgers/theorem_dependencies.md` | May be cited only with recorded hypotheses and formulation labels. |
| `T-001` global torsion-free one-relator target | unresolved but paused / payload-blocked | `OBL-T001-013`; `OQ-126`; `ledgers/t001_residual.md` | No proof-target work unless a concrete accepted `PAY-T001-*` payload satisfies the current gate. |
| `CAND-T001-005` | blocked / inactive proof-target row | `OBL-T001-023`; `ledgers/cand_t001_005_handoff.md` | No route work unless a reopening payload supplies finite-rank free-kernel data, a source-verified route bridge, new FJ83 data, formulation comparison, prior art, or an explicit reopening object. |
| FJ83 weaker \(K_0\) / Cohen--Lyndon source package | source-only for current inventory | `OBL-T001-015`; `OBL-T001-023` for `CAND-T001-005` | May guide a future hypothesis audit; not a full FJ, coefficient FJC, `FJCw`, `FICwF`, or residual-subtraction dependency. |
| `CAND-T001-004` / \(G_{BS23}\) | source-routed / prior-art-blocked | `ER-015`; `FJ88` | May be cited as routed by the graph-of-abelian-groups source; not live residual work. |
| `RB-006` / `FJ53` | WIP / provisional; demoted / provisionally non-subtractive | `FJ52`--`FJ54`; `ledgers/t001_residual.md` | No subtractive use unless a genuinely non-hyperbolic CAT(0), compact-special, or Farrell--Jones bridge is supplied. |
| Artin lane | paused | `OBL-ARTIN-004`; `ledgers/open_group_classes.md` | No Artin source/proof work without a named payload satisfying the reactivation gate. |
| Foundational source queue | paused | `FND-QUEUE-PAUSE-001`; `ledgers/open_group_classes.md` | No broad foundational source reading; use only a concrete accepted `PAY-FND` object. |
| Automatic / biautomatic and Thompson-type classes | deferred | `ledgers/open_group_classes.md`; target-pivot gates | No theorem dependency is active without a target-pivot payload with a changed project object. |
| Formulation-safety package | inactive for current inventory | `FJ02`; `FJ47`; `FJ97` | Keep labels distinct, but no active candidate route currently needs formulation promotion. |
| Missing-source-text items | blocked / no-promotion | `BIBLIOGRAPHY.md`; `ledgers/source_status.md` | Do not use for theorem claims until exact source text and hypotheses are checked. |

## Missing-Source-Text and No-Promotion Items

The following remain blocked for theorem-use promotion unless a future module
checks exact source text and hypotheses:

- Farrell--Jones (1993), original conjecture statement;
- Farrell--Jones (1995), direct Lemma 2.5 use;
- Davis--Lueck (1998), assembly-map foundations;
- Bass--Heller--Swan (1964), original theorem source;
- Mineyev (2005), hyperbolic flow-space construction;
- Bieri (1976), direct theorem-use source;
- Lueck (2018), assembly maps;
- Lyndon--Schupp and Magnus--Karrass--Solitar classical one-relator sources.

## Stop Conditions

Do not mark a dependency as established unless `ESTABLISHED_RESULTS.md` and a
module already justify it. Do not use this audit to create `FJ101`, reopen a
target, start a source survey, or promote a theorem statement.

## Ledger Action

`ledgers/theorem_dependencies.md` is updated with a compact current-use map
pointing to this audit.
