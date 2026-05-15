# Module FJ16. Flow spaces primer

## Status

Completed

## Module type

Technique / Literature verification / Vocabulary primer

## Problem

Understand why flow spaces enter Farrell--Jones proofs, how they help improve control, and how the hyperbolic and CAT(0) proof skeletons use related but different flow-space inputs.

## Input

- `FJ13` for the hyperbolic-groups proof skeleton.
- `FJ14` for the CAT(0)-groups proof skeleton.
- `FJ15` for control spaces, obstruction categories, and gain-control vocabulary.
- Bartels--Lueck--Reich's equivariant-cover source for hyperbolic groups.
- Bartels--Lueck's CAT(0) geodesic-flow source.

## Output target

A precise plain-language explanation of:

- what a flow space is in the sources used here;
- what "long in the flow direction" means;
- how flow-space covers produce virtually cyclic isotropy control;
- how the hyperbolic and CAT(0) flow-space inputs differ;
- what remains deferred to the transfer primer `FJ17`.

## Definitions

### Definition. Flow

A flow on a space `Z` is a continuous `\mathbb R`-action. In the equivariant setting used by the sources, a group `G` acts on `Z` and the flow is `G`-equivariant:

```text
\Phi_\tau(gz)=g\Phi_\tau(z).
```

### Definition. CAT(0) flow space `FS(X)`

For a metric space `X`, Bartels and Lueck define `FS(X)` as the set of generalized geodesics in `X`. A generalized geodesic is a continuous map `c:\mathbb R\to X` that is locally constant outside an interval and restricts to an isometry on that interval. The flow is the time-shift

```text
\Phi_\tau(c)(t)=c(t+\tau).
```

If `X` carries an isometric `G`-action, `FS(X)` inherits an isometric `G`-action commuting with the flow.

### Definition. Hyperbolic flow space

For a hyperbolic complex `X`, Bartels--Lueck--Reich use a Mineyev-style flow space `FS(X)`. It is a metric space with an isometric `G`-action and a `G`-equivariant flow. In FJ16 this construction is used only as a source-level input; the Mineyev construction is not reproduced.

### Definition. Open `\mathcal F`-cover

For a `G`-space `Z` and a collection of subgroups `\mathcal F`, Bartels--Lueck--Reich call an open cover `\mathcal U` an open `\mathcal F`-cover when translates of a cover element are equal or disjoint, the cover is `G`-invariant, and every set stabilizer belongs to `\mathcal F`.

### Definition. Long cover in the flow direction

A cover is long in the flow direction if a prescribed flow segment

```text
\Phi_{[-\alpha,\alpha]}(z)
```

lies inside one member of the cover, often with an additional small metric neighborhood. In the CAT(0) source this becomes a condition on balls around flow segments.

### Definition. `G`-period

For a flow space `FS` with `G`-action, Bartels and Lueck define the `G`-period of `z` as the infimum of positive `\tau` for which `\Phi_\tau(z)=gz` for some `g\in G`. This gives the source notation

```text
FS_{>\gamma},   FS_{\leq \gamma}.
```

These subsets separate long-period behavior from periodic flow lines that must be covered with virtually cyclic isotropy control.

### Warning. Primer boundary

FJ16 explains the vocabulary and theorem route. It does not prove the long-thin-cover theorem, Mineyev's flow-space estimates, the CAT(0) flow-space cover theorem, or transfer reducibility.

## Main work

### Why flow spaces help

Flow spaces add a time direction to the controlled-algebra problem. In `FJ15`, "gain control" meant forcing morphisms or images to stay close in chosen geometric coordinates. Flow spaces help because one can:

1. map geometric data into a space with a flow;
2. flow forward far enough to make nearby data close, up to a bounded time shift;
3. use covers that are long along flow lines and thin in the transverse directions;
4. pull those covers back to the transfer/control space.

The output is a cover whose stabilizers lie in `\mathcal{VCyc}` and whose dimension is uniformly bounded. This is the cover input needed in the controlled proof architecture.

### Hyperbolic source route

Bartels--Lueck--Reich prove an equivariant-cover theorem for word-hyperbolic groups. If `G` is word-hyperbolic and acts properly and cocompactly on a hyperbolic complex `X`, then for every `\alpha>0` there is an open `\mathcal{VCyc}`-cover of

```text
G x \overline X
```

with uniformly bounded dimension, finite quotient by `G`, and the property that each set \(g_0^\alpha\times\{c\}\) is contained in one cover element.

Their proof route uses:

- long-thin covers for spaces with equivariant flows;
- a Mineyev-style flow space `FS(X)`;
- a `G`-equivariant map `j:G x \overline X\to FS(X)`;
- a flow estimate saying that nearby group elements can be aligned after a bounded time shift and become close under the flow;
- pulling back a long-thin cover after flowing for a large time.

### CAT(0) source route

Bartels and Lueck associate to any metric space `X` the flow space `FS(X)` of generalized geodesics. For a proper finite-dimensional CAT(0)-space with a proper isometric group action, they construct covers of the CAT(0) flow space by open `\mathcal{VCyc}`-subsets.

The key CAT(0) cover theorem recorded for project use is:

- for a proper finite-dimensional CAT(0)-space `X`, a proper isometric `G`-action, and compact `K\subseteq X`, there is a uniform dimension bound `M`;
- for every `\gamma>0`, there is a `G`-invariant collection of open `\mathcal{VCyc}`-subsets of `FS(X)`;
- the quotient of the cover by `G` is finite;
- the cover is long around flow segments `\Phi_{[-\gamma,\gamma]}(c)` for relevant `c\in FS(X)_{\leq\gamma}` meeting `G\cdot K`.

They then formulate the condition that a flow space admits long `\mathcal F`-covers at infinity and periodic flow lines. Combined with contracting transfers, this implies transfer reducibility over `\mathcal F`. For CAT(0)-groups, they verify the hypotheses for `\mathcal F=\mathcal{VCyc}`.

### Hyperbolic versus CAT(0) comparison

| Role | Hyperbolic source | CAT(0) source |
| --- | --- | --- |
| Flow space | Mineyev-style `FS(X)` for a hyperbolic complex. | `FS(X)` of generalized geodesics in a metric/CAT(0)-space. |
| Main cover target | `G x \overline X`. | The flow space `FS(X)`, then pulled into transfer constructions. |
| Cover shape | Long-thin covers plus pullback along a flow estimate. | Long covers around periodic flow lines and at infinity. |
| Isotropy family | `\mathcal{VCyc}`. | `\mathcal{VCyc}`. |
| Main source theorem | Equivariant `\mathcal{VCyc}`-covers for hyperbolic groups. | CAT(0)-groups are transfer reducible over `\mathcal{VCyc}` via the flow-space cover theorem and contracting transfers. |
| Proof dependency not internalized | Mineyev flow space and estimates. | CAT(0) flow-space cover theorem and contracting-transfer verification. |

### Connection back to FJ15

FJ15 explained why the obstruction-category proof wants better control spaces. FJ16 explains one way those control spaces are made useful: flow for a long time, use long covers in the flow direction, and pull those covers back to the algebraic-control setting.

The next module, `FJ17`, should explain transfers: the mechanism that moves the obstruction problem from the point into these larger controlled spaces.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim. Hyperbolic equivariant cover theorem

For word-hyperbolic groups acting properly and cocompactly on a hyperbolic complex, Bartels--Lueck--Reich prove the existence of bounded-dimensional, cofinite, open `\mathcal{VCyc}`-covers of `G x \overline X` that are wide in the `G`-coordinate.

### Source-verified claim. CAT(0) flow-space cover route

Bartels and Lueck construct the CAT(0) flow space `FS(X)`, prove the relevant long-cover theorem for periodic flow lines, and use this with contracting transfers to prove that CAT(0)-groups are transfer reducible over `\mathcal{VCyc}`.

### Heuristic. Flow converts coarse closeness into cover control

Flow-space arguments use time evolution to align geometric data and place it inside cover elements that are long along flow lines. This heuristic explains the proof architecture but is not a substitute for the cited cover theorems.

## Proof or verification

FJ16 checked the following source locations:

- Bartels--Lueck--Reich: the definition of open `\mathcal F`-cover, the equivariant cover theorem for word-hyperbolic groups, the long-thin-cover theorem for equivariant flows, and the introduction's explanation of pulling back covers from the flow space.
- Bartels--Lueck: the abstract and introduction, the definition of generalized geodesics and `FS(X)`, the time-shift flow, the CAT(0) periodic-flow-line cover theorem, the definition of long covers at infinity and periodic flow lines, the long-thin-cover theorem, and the proposition connecting suitable flow spaces plus contracting transfers to transfer reducibility.

**Warning.** FJ16 does not directly verify Mineyev's source or the detailed proofs of the two cover theorems. It records the theorem statements and proof architecture needed for the project charter.

## References

- Bartels, A., & Lueck, W. (2012). Geodesic flow for CAT(0)-groups. *Geometry & Topology, 16*(3), 1345--1391. https://doi.org/10.2140/gt.2012.16.1345
- Bartels, A., Lueck, W., & Reich, H. (2008). Equivariant covers for hyperbolic groups. *Geometry & Topology, 12*(3), 1799--1882. https://doi.org/10.2140/gt.2008.12.1799
- Mineyev, I. (2005). Flows and joins of metric spaces. *Geometry & Topology, 9*, 403--482. https://doi.org/10.2140/gt.2005.9.403

## Dependencies

This module depends on:

- `FJ13`: hyperbolic proof skeleton and wide-cover dependency.
- `FJ14`: CAT(0) proof skeleton and CAT(0) flow-space dependency.
- `FJ15`: controlled-algebra and gain-control vocabulary.

## Results produced

This module produced:

- A flow-space vocabulary bridge for `FJ17`.
- A source-verified theorem-route map for hyperbolic equivariant covers.
- A source-verified theorem-route map for CAT(0) flow-space covers.
- A warning that Mineyev's flow-space source remains to be checked directly.

## Open questions generated

- OQ-019. Which Mineyev flow-space results must be checked directly before the project uses hyperbolic flow estimates proof-sensitively?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` to mark FJ16 complete and set `FJ17` as next.
- `README.md` to show progress through FJ16.
- `SCOPE_LEDGER.md` to record the flow-spaces primer and next scope.
- `NOTATION_LEDGER.md` for flow-space notation and period notation.
- `OPEN_QUESTIONS.md` for OQ-019.
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for flow-space sources.
