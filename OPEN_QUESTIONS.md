# Open Questions

## OQ-001. Which unresolved group class should become the first serious target?

### Status

Open inside project.

### Context

The project needs a concrete target after foundational modules. Candidate classes include Artin groups and torsion-free one-relator groups, but their exact known/open status must be source-verified.

### Relevant modules

- FJ11
- FJ18
- FJ19
- FJ20

### Dependencies

Known-cases ledger and inheritance-properties ledger.

### Next action

Defer until modules `FJ11`, `FJ12`, `FJ18`, and `FJ19` have produced verified tables.

## OQ-002. Which source should serve as the main reference for the modern Farrell--Jones statement?

### Status

Open inside project.

### Context

Module `FJ01` uses a simplified ring-coefficient formulation. The stronger additive-category formulation must not be improvised.

### Relevant modules

- FJ01
- FJ02

### Dependencies

A reliable source for the additive-category formulation.

### Next action

Use module `FJ02` to verify the exact modern statement and record theorem/source status.

## OQ-003. Which model of nonconnective algebraic K-theory should be used?

### Status

Open inside project.

### Context

The simplified conjecture in `FJ01` is stated for all \(n\in\mathbb Z\). This requires a nonconnective algebraic \(K\)-theory model, but `FJ01` intentionally treats \(H_n^G(-;\mathbf K_R)\) as a black box.

### Relevant modules

- FJ01
- FJ02

### Dependencies

Source verification for the chosen model of \(\mathbf K_R\).

### Next action

Resolve during `FJ02` or a later notation/source module.

## OQ-004. What is the most economical first model of \(E_{\mathcal{VCyc}}G\) beyond trivial examples?

### Status

Partially resolved for first pass.

### Context

Module `FJ03` should develop classifying spaces for families with examples before advanced machinery appears and starts wearing a lab coat.

### Relevant modules

- FJ03
- FJ04
- FJ06

### Dependencies

Definitions of families and virtually cyclic groups.

### Next action

Use `FJ04` and `FJ06` to develop virtually cyclic groups and the infinite cyclic example before choosing more complicated models.

## OQ-005. Should weakly contractible and contractible fixed-point formulations be separated?

### Status

Open inside project.

### Context

Module `FJ03` uses the readable contractible/empty fixed-point definition for \(E_{\mathcal F}G\). Lueck's Theorem 1.9 states the homotopy characterization using weakly contractible fixed-point spaces for subgroups in the family, together with the isotropy condition.

### Relevant modules

- FJ03
- FJ15
- FJ16

### Dependencies

A later foundations module should decide how much model-category or \(G\)-CW technical detail the project needs.

### Next action

Defer until the project needs a sharper technical convention.

## OQ-006. Should Farrell--Jones 1995 be directly verified for the virtually cyclic dichotomy?

### Status

Open inside project.

### Context

Module `FJ04` uses Lueck--Reich's source-verified statement that an infinite virtually cyclic group maps with finite kernel either onto \(\mathbb Z\) or onto \(D_\infty\). Lueck--Reich cite Farrell--Jones 1995, Lemma 2.5, as the proof source.

### Relevant modules

- FJ04
- FJ07
- FJ11

### Dependencies

Access to Farrell--Jones, *The lower algebraic K-theory of virtually infinite cyclic groups*, K-Theory 9 (1995), 13--30.

### Next action

Before using the dichotomy in a proof-sensitive way beyond first-pass structure, directly check the original Farrell--Jones 1995 lemma or another primary source with equivalent hypotheses.

## OQ-007. Which source should be used for Bass--Heller--Swan and Nil-terms?

### Status

Resolved for first pass; original-source verification remains optional.

### Context

Module `FJ06` identifies the target for \(G=\mathbb Z\) as \(K_n(R[t,t^{-1}])\), but deliberately does not decompose that group. Module `FJ07` introduces the Bass--Heller--Swan decomposition and Nil-terms.

### Relevant modules

- FJ06
- FJ07

### Dependencies

Weibel's K-book has been selected as the active first-pass theorem source, with Lueck--Reich used for the Farrell--Jones interpretation. The original Bass--Heller--Swan paper has been bibliographically located but not used as the theorem source.

### Next action

Use Weibel (2013) for first-pass theorem statements. Directly check Bass--Heller--Swan (1964) only if the project later needs original-source historical precision.

## OQ-008. Which explicit nonzero Nil example should the project use?

### Status

Open inside project.

### Context

Module `FJ07` records the structural role of Nil-terms, but it does not prove that any particular \(NK_n(R)\) is nonzero.

### Relevant modules

- FJ07
- FJ08
- FJ11

### Dependencies

A reliable source for explicit nonzero \(NK\)-groups over a concrete ring.

### Next action

Defer until a later module needs a concrete obstruction example rather than the structural Bass--Heller--Swan decomposition.

## OQ-009. Should the original Bass--Heller--Swan paper be checked directly?

### Status

Open, low urgency.

### Context

`FJ07` uses Weibel's monograph as the active theorem source. The original paper is historically important but was not needed for the first-pass theorem ledger.

### Relevant modules

- FJ07
- FJ11

### Dependencies

Bass, Heller, and Swan, *The Whitehead group of a polynomial extension*, Publications Mathematiques de l'IHES 22 (1964), 61--79.

### Next action

Check the original paper only if the project later needs historical attribution beyond the APA bibliography entry.

## OQ-010. Which source should be used for geometric Whitehead torsion?

### Status

Open inside project.

### Context

Module `FJ08` uses the algebraic \(K\)-theory cokernel definition of the Whitehead group and records a Farrell--Jones consequence. It does not develop Whitehead torsion, the \(s\)-cobordism theorem, or the geometric applications of \(\mathrm{Wh}(G)\).

### Relevant modules

- FJ08
- FJ10

### Dependencies

A reliable source for Whitehead torsion and the \(s\)-cobordism theorem, preferably a standard monograph or expert survey.

### Next action

Resolve only if `FJ10` or a later topology-facing module needs geometric consequences.
