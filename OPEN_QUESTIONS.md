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

Open inside project.

### Context

Module `FJ03` should develop classifying spaces for families with examples before advanced machinery appears and starts wearing a lab coat.

### Relevant modules

- FJ03
- FJ04
- FJ06

### Dependencies

Definitions of families and virtually cyclic groups.

### Next action

Proceed to `FJ03`.
