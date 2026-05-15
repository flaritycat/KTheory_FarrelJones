# Module FJ14. CAT(0) groups case

## Status

Completed

## Module type

Literature verification / Theorem map / Proof skeleton / Structural comparison

## Problem

Record a source-checked first-pass account of the CAT(0)-group case of the K-theoretic Farrell--Jones conjecture and compare its proof architecture with the hyperbolic-group case from FJ13.

## Input

- FJ01 for the simplified assembly-map target.
- FJ03 for classifying spaces for families.
- FJ04 for the family `\mathcal{VCyc}`.
- FJ11 for the known-classes ledger.
- FJ13 for the hyperbolic-groups comparison case.

## Output target

A reusable module artifact explaining:

- the source-verified CAT(0)-group theorem used in this project;
- the role of strong transfer reducibility and strong homotopy actions;
- the comparison between the hyperbolic and CAT(0) proof routes;
- which proof-technology details are deferred to FJ15--FJ17.

## Definitions

**Definition.** A CAT(0)-group, in the sense used by Wegner, is a group admitting a cocompact proper action by isometries on a finite-dimensional CAT(0)-space.

**Definition.** A strong homotopy action is a source-level device used in Wegner's CAT(0) proof to encode an action together with coherent higher homotopies. It is needed because the compact CAT(0) balls used in the transfer construction are not generally honest `G`-spaces.

**Definition.** A group `G` is strongly transfer reducible over a family `\mathcal F` if, uniformly over finite control data, one can find compact contractible controlled metric spaces, strong homotopy `G`-actions, and finite-dimensional `\mathcal F`-covers of `G` times those spaces that are wide enough for the relevant controlled subsets. This is recorded here only as proof technology; FJ14 does not reproduce the full technical definition.

**Definition.** For a CAT(0)-space `Y`, Wegner uses a flow space `FS(Y)` of generalized geodesics. Bartels and Lueck construct the flow-space cover used to obtain the virtually cyclic isotropy control in the CAT(0) proof.

**Warning.** This module is not a replacement for the additive-category formulation of FJ02, and it is not a full proof of Wegner's theorem. It records the theorem route and the dependencies that must be understood before this project can responsibly use the proof machinery.

## Main work

### Source-verified theorem route

**Source-verified claim.** Wegner proves the K-theoretic Farrell--Jones conjecture with coefficients for CAT(0)-groups. The source states the theorem in the additive-category formulation: for every additive category `\mathcal A` with strict right `G`-action, the assembly map

```text
H^G_m(E_{\mathcal{VCyc}}G; \mathbf K_{\mathcal A})
  -> H^G_m(\mathrm{pt}; \mathbf K_{\mathcal A})
     \cong K_m(\int_G \mathcal A)
```

is an isomorphism for all `m in \mathbb Z`, when `G` is a CAT(0)-group.

The proof route in Wegner has the following form:

1. Define strong transfer reducibility over a family `\mathcal F`.
2. Prove that strong transfer reducibility over `\mathcal F` implies the K-theoretic Farrell--Jones conjecture with coefficients relative to `\mathcal F`.
3. Prove that CAT(0)-groups are strongly transfer reducible over `\mathcal{VCyc}`.
4. Conclude the CAT(0)-group case by taking `\mathcal F = \mathcal{VCyc}`.

### Hyperbolic versus CAT(0) comparison

| Aspect | Hyperbolic groups, FJ13 | CAT(0)-groups, FJ14 |
| --- | --- | --- |
| Main K-theory source | Bartels, Lueck, and Reich prove the K-theoretic conjecture for hyperbolic groups. | Wegner proves the K-theoretic conjecture for CAT(0)-groups. |
| Group hypothesis | Finitely generated word-hyperbolic group. | Group acting properly, cocompactly, and isometrically on a finite-dimensional CAT(0)-space. |
| Large-scale input | Hyperbolic geometry and Rips complexes. | CAT(0) geometry and large closed balls in the associated CAT(0)-space. |
| Transfer space | A compactification of a Rips complex. | Large compact closed balls `\overline B_R(x_0)` in the CAT(0)-space. |
| Action issue | The Rips-complex setup supports an honest equivariant construction. | Closed CAT(0) balls are not generally `G`-spaces, so Wegner uses strong homotopy actions. |
| Cover technology | Equivariant covers associated to the hyperbolic proof architecture. | Covers of the CAT(0) flow space `FS(Y)`, pulled back to the transfer setting. |
| Isotropy control | Virtually cyclic isotropy enters through the hyperbolic cover construction. | Virtually cyclic isotropy enters through the Bartels--Lueck flow-space cover. |
| Obstruction category role | Vanishing of obstruction-category K-groups gives the assembly isomorphism. | Wegner uses the same obstruction-category strategy, with extra homotopy coherence in the transfer. |
| Main extra difficulty | Control over hyperbolic compactifications. | Lack of honest `G`-actions on compact balls; resolved by strong homotopy actions. |
| Deferred modules | FJ15--FJ17 explain controlled topology, flow spaces, and transfers. | FJ15--FJ17 should return to Wegner and Bartels--Lueck for the technical details. |

### Proof-technology boundary

FJ14 is allowed to use Wegner's theorem as a source-verified theorem, but it does not unpack the proof. The following ingredients are located but deferred:

- the obstruction category `\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A)`;
- the transfer from the point to a controlled compact metric space;
- controlled domination of CAT(0) balls;
- strong homotopy actions and their coherent higher homotopies;
- the flow space `FS(Y)` and the virtually cyclic covers used in the CAT(0) case;
- the vanishing argument for the obstruction category.

## Proposition / Theorem / Conjecture / Example

**Theorem.** Let `G` be a CAT(0)-group in the sense above. Then `G` satisfies the K-theoretic Farrell--Jones conjecture with coefficients, relative to the family `\mathcal{VCyc}`.

**Literature claim.** Wegner's proof runs through strong transfer reducibility over `\mathcal{VCyc}`. The key CAT(0)-specific geometric input is that CAT(0)-groups are strongly transfer reducible over `\mathcal{VCyc}`.

**Remark.** FJ11 also records CAT(0)-groups as part of the current known-classes ledger. FJ14 adds a proof-route map for the K-theory source rather than a new independent proof.

## Proof or verification

**Verification.** The theorem statement and proof route were checked against Wegner's introduction, main theorem, CAT(0)-group theorem, and proof outline. Wegner states the K-theoretic Farrell--Jones conjecture with coefficients for additive `G`-categories, proves a general theorem from strong transfer reducibility to the assembly isomorphism, and proves that CAT(0)-groups are strongly transfer reducible over `\mathcal{VCyc}`.

**Verification.** Wegner's introduction identifies the difference from the hyperbolic case: hyperbolic groups use compactified Rips complexes, while CAT(0)-groups use large closed balls in a CAT(0)-space. Because those balls are not generally `G`-spaces, the proof introduces strong homotopy actions.

**Verification.** Bartels and Lueck's CAT(0) geodesic-flow paper was located as the source for the flow-space cover technology used by Wegner. FJ14 has not yet independently verified the flow-space-cover proof; this is deferred to FJ16 and FJ17.

**Warning.** The theorem above is source-verified as a literature theorem. The internal proof is not established in this repository.

## References

- Bartels, A., & Lueck, W. (2012). Geodesic flow for CAT(0)-groups. *Geometry & Topology, 16*(3), 1345--1391. https://doi.org/10.2140/gt.2012.16.1345
- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic Farrell-Jones conjecture for hyperbolic groups. *Inventiones Mathematicae, 172*(1), 29--70. https://doi.org/10.1007/s00222-007-0093-7
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3), 779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

## Dependencies

This module depends on:

- FJ01 minimal assembly-map statement.
- FJ03 classifying spaces for families.
- FJ04 virtually cyclic groups.
- FJ11 known classes ledger.
- FJ13 hyperbolic groups case.

## Results produced

This module produced:

- A source-verified theorem entry for the K-theoretic CAT(0)-group case.
- A proof-route map through strong transfer reducibility over `\mathcal{VCyc}`.
- A structural comparison between the hyperbolic and CAT(0) proof architectures.
- A list of deferred proof-technology dependencies for FJ15--FJ17.

## Open questions generated

- OQ-017. Which exact Bartels--Lueck geodesic-flow cover lemmas and Wegner transfer lemmas must be verified before FJ16--FJ17 can safely summarize the CAT(0) proof machinery?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` to mark FJ14 complete and set FJ15 as the next module.
- `README.md` to show progress through FJ14.
- `SCOPE_LEDGER.md` to record the FJ14 proof skeleton and next scope.
- `NOTATION_LEDGER.md` for `Y`, `FS(Y)`, strong homotopy actions, and the obstruction category notation.
- `OPEN_QUESTIONS.md` for OQ-017.
- `ESTABLISHED_RESULTS.md` to clarify that ER-009 now has an FJ14 proof-route map for the CAT(0) row.
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for the Wegner and Bartels--Lueck CAT(0) sources.
