# Module FJ17. Transfers primer

## Status

Completed

## Module type

Technique / Literature verification / Theorem map

## Problem

Understand what transfer methods do in the proof architecture for the
K-theoretic Farrell--Jones conjecture.

The earlier proof-technology modules reached the following boundary:

- `FJ15` explained obstruction categories and why control matters.
- `FJ16` explained flow spaces and long covers.
- `FJ17` explains the transfer mechanism connecting these pieces.

## Input

This module uses:

- `FJ13`, for the hyperbolic-groups proof skeleton;
- `FJ14`, for the CAT(0)-groups proof skeleton;
- `FJ15`, for obstruction categories and controlled morphisms;
- `FJ16`, for flow spaces, long covers, and contracting language.

External sources checked for this module:

- Bartels, Lueck, and Reich (2008), especially the introduction proof
  outline and Section 6 transfer construction.
- Wegner (2012), especially the introduction, Definitions 2.1 and 3.1,
  Proposition 4.1, Sections 5--7, and the transfer equation in Section 7.
- Bartels and Lueck (2012), especially the definitions of transfer
  reducibility and contracting transfers, and the proposition connecting
  suitable flow spaces plus contracting transfers to transfer
  reducibility.

## Output target

A reusable schematic explanation of how transfer maps move a controlled
obstruction problem from the one-point control space into a larger
metric control space where covers, flow, and contraction can be used.

## Definitions

**Definition.** A transfer, in the source-level controlled-algebra
setting used here, is a functor or induced \(K\)-theory map from the
obstruction category over the one-point control space to an obstruction
category over a larger metric control space. Its purpose is to replace
`pt` by a space such as \(G\times X\) or a sequence
\((G\times X_n,d_n)_{n\in\mathbb N}\).

**Definition.** Wegner defines a strong homotopy action of a group \(G\)
on a space \(X\) as a continuous map

\[
\Psi:\coprod_{j=0}^{\infty}((G\times[0,1])^j\times G\times X)\to X
\]

satisfying coherence rules that encode an action, homotopies between
composites, and higher homotopies. This is source-level notation and is
used here only as proof technology.

**Definition.** Given a strong homotopy action \(\Psi\), a finite
symmetric subset \(S\subseteq G\), and \(k\in\mathbb N\), Wegner defines
sets \(S^n_{\Psi,S,k}(g,x)\subseteq G\times X\) and a quasi-metric
\(d_{\Psi,S,k,\Lambda}\) on \(G\times X\). These encode the amount of
movement allowed by the finite control data and the homotopies.

**Definition.** A group \(G\) is strongly transfer reducible over a
family \(\mathcal F\) if, uniformly over finite control data, one can
find:

- a compact contractible controlled \(N\)-dominated metric space \(X\);
- a strong homotopy \(G\)-action \(\Psi\) on \(X\);
- an open \(\mathcal F\)-cover \(\mathcal U\) of \(G\times X\);

such that the cover has dimension at most \(N\) and every controlled
set \(S^n_{\Psi,S,k}(g,x)\) is contained in some element of
\(\mathcal U\).

**Definition.** Bartels and Lueck say that a flow space \(FS\) admits
contracting transfers if finite group-control data can be represented
inside a compact controlled space \(X\), a homotopy \(S\)-action, and a
map

\[
\iota:G\times X\to FS
\]

so that, after flowing for a large time \(T\), related points become
\(\delta\)-close up to a uniformly bounded time shift.

## Main work

### Why transfers are needed

**Heuristic.** The obstruction category over `pt` is too small for the
geometric operations needed in the proof. It sees bounded algebraic
control, but it has no geometric room in which to contract, flow, or use
large equivariant covers.

The transfer replaces the one-point control space by a better metric
space. In hyperbolic proofs this is modeled by \(G\times\overline X\),
where \(\overline X\) is a compactified Rips complex. In CAT(0) proofs,
Wegner uses compact balls in a CAT(0)-space and strong homotopy actions
because those balls are not generally honest \(G\)-spaces.

### The schematic transfer pattern

**Literature claim.** In the controlled-algebra proof route, one studies
the obstruction group

\[
K_m(\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A)).
\]

Vanishing of these groups, in the relevant range and for all additive
\(G\)-categories \(\mathcal A\), implies the corresponding assembly
isomorphism. Wegner cites this reduction to Bartels--Lueck--Reich.

The transfer pattern is:

1. Start with a class
   \[
   \xi\in K_m(\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A)).
   \]

2. Transfer it to a larger controlled category:
   \[
   \operatorname{trans}_*(\xi)
   \in
   K_m(\mathcal O^G(E_{\mathcal F}G,(G\times X_n,d_n)_{n\in\mathbb N};\mathcal A)^{>\oplus}).
   \]

3. Use maps
   \[
   f_n:G\times X_n\to\Sigma_n
   \]
   into uniformly finite-dimensional complexes whose isotropy groups
   lie in \(\mathcal F\). These maps come from the transfer-reducibility
   data.

4. Use cover and stability results to make the target category over the
   \(\Sigma_n\)'s have trivial \(K\)-theory.

5. Use the projection identity
   \[
   \operatorname{pr}_*\circ\operatorname{trans}_*
   =
   \operatorname{diag}_*
   \]
   to show that if the transferred class dies, then the original class
   dies.

This is the clean conceptual point: transfer does not by itself prove
vanishing. It moves the class to a place where the flow-space and cover
technology can act on it.

### Hyperbolic transfer route

**Source-verified claim.** Bartels--Lueck--Reich describe the hyperbolic
proof as a two-step enlargement of the metric control space. First, a
transfer replaces the basic control space by \(G\times\overline X\),
where \(\overline X\) is a compactification of a Rips complex. Second,
contracting maps associated to equivariant open covers improve the
control.

**Source-verified claim.** Their transfer theorem constructs a
\(K\)-theory map

\[
\operatorname{trans}:
K_m\mathcal O^G(E)
\to
K_m\mathcal O^G(E,(G\times\overline X,d_{C(n)})_{n\in\mathbb N})
\]

for \(m\geq 1\), which is a right inverse to the relevant projection
maps after applying \(K\)-theory. The transfer is implemented through
Waldhausen categories of homotopy finitely dominated chain complexes.

**Warning.** FJ17 does not reconstruct this Waldhausen-category proof.
It records the source-level role of the transfer theorem and the data
it supplies to the proof skeleton.

### CAT(0) transfer route

**Source-verified claim.** Wegner proves that if \(G\) is strongly
transfer reducible over a family \(\mathcal F\), then the
K-theoretic assembly map

\[
H_m^G(E_{\mathcal F}G;\mathbf K_{\mathcal A})
\to
H_m^G(\mathrm{pt};\mathbf K_{\mathcal A})
\cong
K_m(\int_G\mathcal A)
\]

is an isomorphism for all \(m\in\mathbb Z\) and every additive
\(G\)-category \(\mathcal A\).

**Source-verified claim.** Wegner proves that every CAT(0)-group is
strongly transfer reducible over \(\mathcal{VCyc}\). The proof uses
large closed CAT(0) balls as compact controlled spaces and strong
homotopy actions arising from projection along geodesics.

**Source-verified claim.** Wegner's transfer functor has the form

\[
\operatorname{trans}:
\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A)
\to
\widetilde{\operatorname{ch}}_{\mathrm{hfd}}
\mathcal O^G(E_{\mathcal F}G,(G\times X_n,d_n)_{n\in\mathbb N};\mathcal A)^{>\oplus},
\]

and its induced \(K\)-theory map satisfies

\[
\operatorname{pr}_*\circ\operatorname{trans}_*
=
\operatorname{diag}_*.
\]

This is the CAT(0) analogue of the right-inverse role played by the
hyperbolic transfer.

### Comparison table

| Feature | Hyperbolic route | CAT(0) route |
|---|---|---|
| Main transfer space | \(G\times\overline X\), with \(\overline X\) a compactified Rips complex | \(G\times X_n\), where \(X_n\) comes from compact CAT(0) balls |
| Action issue | Honest equivariant geometry is available in the compactified Rips setting | Closed CAT(0) balls are not generally \(G\)-spaces |
| Coherence device | Controlled transfer through chain complexes | Strong homotopy actions and higher homotopies |
| Cover input | Equivariant open covers and contracting maps | Flow-space covers plus contracting transfers |
| Algebraic output | Transfer map right-inverse to projections after \(K\)-theory | Transfer map with \(\operatorname{pr}_*\operatorname{trans}_*=\operatorname{diag}_*\) |
| What FJ17 records | Source-level transfer architecture | Source-level strong-transfer architecture |

## Proposition / Theorem / Conjecture / Example

### Theorem Map. Transfer reducibility route to assembly

**Source-verified claim.** Let \(G\) be strongly transfer reducible over
a family \(\mathcal F\) in Wegner's sense. Then the K-theoretic
Farrell--Jones assembly map with coefficients in additive
\(G\)-categories, relative to \(\mathcal F\), is an isomorphism in all
degrees.

**Hypotheses recorded from the source.**

- \(G\) is a group.
- \(\mathcal F\) is a family of subgroups of \(G\).
- \(G\) is strongly transfer reducible over \(\mathcal F\).
- \(\mathcal A\) is an additive category with a strict right
  \(G\)-action.

**Use in the project.** This theorem map explains why `FJ14` could
summarize Wegner's CAT(0) theorem through strong transfer reducibility.
It is proof technology, not a new internally proved theorem.

### Example. What a transfer does to a class

**Example.** Suppose a class

\[
\xi\in K_m(\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A))
\]

is represented in the obstruction category over the point. Transfer
replaces it by a class over \((G\times X_n,d_n)_{n\in\mathbb N}\). The
new class carries additional metric coordinates. Those coordinates can
then be pushed through the maps \(f_n:G\times X_n\to\Sigma_n\), where
the \(\Sigma_n\) have isotropy in \(\mathcal F\) and uniformly bounded
dimension. The transfer identity with projection back to the point is
what lets this geometric manipulation say something about the original
class \(\xi\).

## Proof or verification

**Verification.** Wegner's introduction says the proof studies the
obstruction category, constructs a transfer map replacing the one-point
space by a carefully chosen metric space, then uses contracting maps on
metric spaces to gain control and prove obstruction-category vanishing.

**Verification.** Wegner's Definition 2.1 defines strong homotopy
actions; Definition 3.1 defines strong transfer reducibility; Theorem
1.1 proves the assembly isomorphism for strongly transfer reducible
groups; and Theorem 3.4 proves that every CAT(0)-group is strongly
transfer reducible over \(\mathcal{VCyc}\).

**Verification.** Wegner's Section 5 proof outline sets up the diagram
with \(\operatorname{diag}_*\), \(\operatorname{trans}_*\),
\(\operatorname{pr}_*\), the spaces \(G\times X_n\), and maps
\(f_n:G\times X_n\to\Sigma_n\). Wegner's Section 7 constructs the
transfer functor and records
\(\operatorname{pr}_*\circ\operatorname{trans}_*=\operatorname{diag}_*\).

**Verification.** Bartels--Lueck--Reich's proof outline describes the
hyperbolic transfer from \(G\) to \(G\times\overline X\), followed by
contracting maps associated to open covers. Their Section 6 transfer
theorem constructs the \(K\)-theory transfer and states its right-inverse
property with respect to the projection maps.

**Verification.** Bartels--Lueck's geodesic-flow paper defines transfer
reducibility and contracting transfers, and proves that suitable flow
spaces with long covers at infinity and periodic orbits plus contracting
transfers imply transfer reducibility.

## References

- Bartels, A., & Lueck, W. (2012). The Borel conjecture for hyperbolic
  and CAT(0)-groups. *Annals of Mathematics, 175*(2), 631--689.
  https://doi.org/10.4007/annals.2012.175.2.5. Status: `background for
  transfer reducibility terminology`; not the main checked source for
  FJ17.
- Bartels, A., & Lueck, W. (2012). Geodesic flow for CAT(0)-groups.
  *Geometry & Topology, 16*(3), 1345--1391.
  https://doi.org/10.2140/gt.2012.16.1345. Status: `active reference`.
- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic
  Farrell-Jones conjecture for hyperbolic groups. *Inventiones
  Mathematicae, 172*(1), 29--70.
  https://doi.org/10.1007/s00222-007-0093-7. Status: `active reference`.
- Bartels, A., & Reich, H. (2005). On the Farrell-Jones conjecture for
  higher algebraic K-theory. *Journal of the American Mathematical
  Society, 18*(3), 501--545.
  https://doi.org/10.1090/S0894-0347-05-00482-0. Status: `found; to
  verify for transfer-background use`.
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society,
  140*(3), 779--793.
  https://doi.org/10.1090/S0002-9939-2011-11150-X. Status: `active
  reference`.

## Dependencies

This module depends on:

- `FJ13`: hyperbolic proof skeleton.
- `FJ14`: CAT(0) proof skeleton.
- `FJ15`: obstruction-category and control vocabulary.
- `FJ16`: flow-space and long-cover vocabulary.
- Bartels--Lueck--Reich transfer theorem and proof outline.
- Wegner strong-transfer-reducibility theorem and transfer construction.
- Bartels--Lueck contracting-transfer framework.

## Results produced

This module produced:

- A first-pass transfer-primer artifact.
- A schematic theorem map from strong transfer reducibility to the
  assembly isomorphism.
- A hyperbolic-versus-CAT(0) comparison table for transfer technology.
- A source-status update marking the FJ17 transfer sections checked at
  first-pass level.

No new internally proved established result number is created.

## Open questions generated

- OQ-020. Which transfer-category model should become canonical before
  the project uses transfer proofs in detail?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` to mark `FJ17` completed and move the active
  target to `FJ18`;
- `README.md` to reflect progress through `FJ17`;
- `SCOPE_LEDGER.md` for the new current scope and open question;
- `NOTATION_LEDGER.md` for transfer notation;
- `OPEN_QUESTIONS.md` for OQ-020 and updated FJ17-related next actions;
- `BIBLIOGRAPHY.md` for source statuses and the Bartels--Reich transfer
  background entry;
- `ledgers/source_status.md` for source-checking details;
- `ledgers/theorem_dependencies.md` for the completed dependency row.
