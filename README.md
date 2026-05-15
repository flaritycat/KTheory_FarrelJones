# The Farrell--Jones Program in Algebraic K-Theory

This repository is an exploratory mathematical research archive focused on the **K-theoretic Farrell--Jones conjecture** for group rings.

## Central aim

Develop a modular research program around the Farrell--Jones conjecture by:

1. stating the conjecture precisely;
2. understanding assembly maps and classifying spaces for families;
3. working through basic examples;
4. cataloging known cases and inheritance principles;
5. identifying concrete unresolved or reducible subclasses of groups;
6. cutting the work into bounded modules.

## Current module cycle

- Active cycle: `cycle_001`
- First milestone: modules `FJ01`--`FJ07`.
- Completed first-pass modules: `FJ01`, `FJ03`, `FJ04`, `FJ05`, `FJ06`, `FJ07`, `FJ08`, and `FJ09`.
- Deferred first-milestone module: `FJ02`, the additive-category formulation.
- Current primary target: `FJ10`, the Borel conjecture consequence, without importing \(L\)-theory beyond clearly marked source-verified statements.

## Current established results

- `ER-001`: the trivial group case of the simplified K-theoretic assembly map.
- `ER-002`: the source-verified existence and homotopy characterization of classifying spaces for project-style families of subgroups.
- `ER-003`: \(\mathcal{VCyc}(G)\) is a family of subgroups, with the infinite virtually cyclic dichotomy recorded as source-verified.
- `ER-004`: for \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- `ER-005`: the source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\), including the two \(NK_n(R)\)-summands.
- `ER-006`: conditional Whitehead-group vanishing from Farrell--Jones for torsion-free groups with regular coefficients.
- `ER-007`: conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\), with the finiteness-obstruction interpretation for finitely presented groups.

See `ESTABLISHED_RESULTS.md` for exact statements, hypotheses, proof locations, and source status.

## Current cautions

- The repository has not proved or claimed the Farrell--Jones conjecture in full generality.
- `FJ06` identifies \(R[\mathbb Z]\cong R[t,t^{-1}]\) after choosing a generator, but deliberately does not use the Bass--Heller--Swan decomposition.
- `FJ07` imports Bass--Heller--Swan as a source-verified theorem, not as an internal proof.
- `FJ08` records a conditional Whitehead-group consequence; it does not claim \(\mathrm{Wh}(G)=0\) for groups with torsion.
- `FJ09` uses Lueck--Reich's survey for Wall finiteness obstruction; primary-source verification is deferred.
- The project has not yet chosen a concrete example of a ring with nonzero \(NK_n(R)\).
- All-degree statements continue to use the nonconnective \(K\)-theory convention introduced in `FJ01`.

## Source discipline

External mathematical sources should be cited in APA style where practical and tracked with project source-status labels such as `found`, `to verify`, `partially read`, `verified`, `active reference`, `background only`, and `do not use`.

Internal dependencies may be cited by repository path, module number, result number, or ledger entry.

## Repository map

```text
README.md                         public overview
PROJECT_CHARTER.md                stable project charter
SCOPE_LEDGER.md                   active scope ledger
NOTATION_LEDGER.md                notation ledger
BIBLIOGRAPHY.md                   structured bibliography
OPEN_QUESTIONS.md                 cumulative open questions
ESTABLISHED_RESULTS.md            results proved inside the project
modules/cycle_001/                first 20 modules
reflections/                      reflection reports after module cycles
ledgers/                          known cases, inheritance, sources, dependencies
references/                       reading lists and source notes
diagrams/                         dependency maps
drafts/                           proof attempts, conjecture variants, abandoned paths
```

## Warning

This project is exploratory. It does **not** claim to solve the Farrell--Jones conjecture. Claims are to be labeled as definitions, examples, propositions, theorems, conjectures, heuristics, warnings, open problems, failed attempts, literature claims, or source-verified claims.

## Persistence rule

The repository is the durable archive. Chat-based exploration is temporary unless converted into repository artifacts.
