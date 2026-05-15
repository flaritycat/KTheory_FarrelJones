# Module FJ07. Bass--Heller--Swan and Nil terms

## Status

Completed, first pass

## Module type

Literature verification / Theorem map / Structural warning

## Problem

Explain why the family \(\mathcal{VCyc}\) is not decorative in the
K-theoretic Farrell--Jones conjecture. The simplest test case is already
\(G=\mathbb Z\), where `FJ06` identified the target as

\[
K_n(R[t,t^{-1}]).
\]

The Bass--Heller--Swan fundamental theorem decomposes this target into
ordinary \(K\)-groups of \(R\) together with Nil-terms. Those Nil-terms
are the first visible reason that finite or trivial families do not
suffice for arbitrary coefficient rings.

## Input

- `FJ01`, for the simplified group-ring assembly map.
- `FJ03`, for terminal maps \(E_{\mathcal F}G\to\mathrm{pt}\).
- `FJ04`, for virtually cyclic subgroups.
- `FJ06`, for \(R[\mathbb Z]\cong R[t,t^{-1}]\) after choosing a
  generator.
- Weibel's K-book, Chapter V, Section 8, for the fundamental theorem and
  the relation between Nil and \(NK\) groups (Weibel, 2013).
- Lueck--Reich's survey, especially Remark 1.15 and Subsections 2.2.4
  and 2.2.5, for the Farrell--Jones interpretation of Nil-terms and the
  role of virtually cyclic subgroups (Lueck & Reich, 2004).

## Output target

A source-verified first-pass module that records:

- the definition of \(NK_n(R)\);
- the Bass--Heller--Swan split exact sequence;
- the resulting decomposition of \(K_n(R[t,t^{-1}])\);
- the reason Nil-terms force the project to keep
  \(\mathcal{VCyc}\), rather than replacing it by the finite or trivial
  family for arbitrary rings;
- exact source status and APA-style bibliography entries.

## Definitions

### Definition: \(NK_n(R)\)

Let \(R\) be an associative unital ring. Let

\[
i\colon R\longrightarrow R[t]
\]

be the inclusion as constant polynomials. Define

\[
NK_n(R)=\operatorname{coker}\bigl(K_n(R)\xrightarrow{i_*}K_n(R[t])\bigr).
\]

The evaluation map \(R[t]\to R\), \(t\mapsto 0\), splits \(i\). Thus
\(K_n(R[t])\) splits as the \(K_n(R)\)-part plus the \(NK_n(R)\)-part.

The same construction applies to \(R[t^{-1}]\). In the Bass--Heller--Swan
decomposition the two Nil summands are often displayed as two copies of
\(NK_n(R)\), one from the \(t\)-direction and one from the \(t^{-1}\)
direction.

### Definition: Nil category, first-pass version

Let \(\mathrm{Nil}(R)\) denote the category whose objects are pairs
\((P,\nu)\), where \(P\) is a finitely generated projective \(R\)-module
and \(\nu\colon P\to P\) is a nilpotent endomorphism.

This module uses the Nil category only to explain terminology. Weibel
records the relationship

\[
\mathrm{Nil}_n(R)\cong NK_{n+1}(R)
\]

in the conventions of Chapter V, Theorem 8.1 (Weibel, 2013). Lueck and
Reich similarly describe \(NK_n(R)\) as a cokernel identified with a
Nil-group shifted by one degree (Lueck & Reich, 2004, Remark 1.15).

## Main work

The module `FJ06` proves internally that for \(G=\mathbb Z\), the
simplified assembly target is

\[
K_n(R[\mathbb Z])\cong K_n(R[t,t^{-1}]).
\]

The Bass--Heller--Swan fundamental theorem then explains what extra
information is hidden in that Laurent polynomial \(K\)-group.

### Source-verified theorem: Bass--Heller--Swan split exact sequence

Let \(R\) be an associative unital ring. For every \(n\) in Weibel's
\(K\)-theory conventions, there is a canonically split exact sequence

\[
0\to K_n(R)
\xrightarrow{\Delta}
K_n(R[t])\oplus K_n(R[t^{-1}])
\xrightarrow{\pm}
K_n(R[t,t^{-1}])
\xrightarrow{\partial}
K_{n-1}(R)
\to 0.
\]

The splitting of \(\partial\) is given by multiplication by the class of
\(t\in K_1(\mathbb Z[t,t^{-1}])\) (Weibel, 2013, Chapter V, Theorem
8.2).

Using the split descriptions

\[
K_n(R[t])\cong K_n(R)\oplus NK_n(R)
\]

and

\[
K_n(R[t^{-1}])\cong K_n(R)\oplus NK_n(R),
\]

this gives the familiar Bass--Heller--Swan form

\[
K_n(R[t,t^{-1}])
\cong
K_n(R)\oplus K_{n-1}(R)\oplus NK_n(R)\oplus NK_n(R).
\]

This is recorded here as a source-verified theorem, not as a proof
inside the repository.

### Structural warning: why \(\mathcal{VCyc}\) is present

For the infinite cyclic group, the family
\(\mathcal{VCyc}(\mathbb Z)\) is the family of all subgroups, so the
Farrell--Jones assembly map from \(E_{\mathcal{VCyc}}\mathbb Z\) to
\(\mathrm{pt}\) is already an isomorphism by the point-model argument in
`FJ06`.

The smaller torsion-free or finite-family source sees only the classical
group-homology part. Lueck and Reich explain that, for arbitrary rings,
Nil-terms appear even for the infinite cyclic group and obstruct the
classical assembly map from being an isomorphism (Lueck & Reich, 2004,
Remark 1.15). They also describe the relative passage from finite
subgroups to virtually cyclic subgroups as the mechanism that accounts
for Nil-terms in algebraic \(K\)-theory (Lueck & Reich, 2004,
Subsection 2.2.5).

Thus the project should treat the slogan

> Virtually cyclic subgroups are where the Nil-terms live.

as a source-verified guiding warning, not as a replacement for the exact
relative assembly formalism.

### Regular-ring exception

For regular coefficient rings, Nil-terms vanish in the relevant
comparison, and Lueck--Reich record that one can reduce from
\(\mathcal{VCyc}\) to the family of finite subgroups under regularity and
invertibility hypotheses on finite subgroup orders (Lueck & Reich, 2004,
Proposition 2.14).

This does not change the project charter, because the standing coefficient
ring in the simplified formulation is an arbitrary associative unital
ring unless a module explicitly imposes stronger hypotheses.

## Proposition / Theorem / Conjecture / Example

### Source-verified theorem: Bass--Heller--Swan decomposition for \(R[\mathbb Z]\)

Let \(R\) be an associative unital ring and choose a generator \(t\) of
\(\mathbb Z\). For every \(n\) in the cited \(K\)-theory conventions,
combining the identification

\[
R[\mathbb Z]\cong R[t,t^{-1}]
\]

from `FJ06` with Weibel's fundamental theorem gives

\[
K_n(R[\mathbb Z])
\cong
K_n(R)\oplus K_{n-1}(R)\oplus NK_n(R)\oplus NK_n(R)
\]

in the \(K\)-theory conventions used in the cited source.

The two \(NK_n(R)\)-summands are the Nil-terms associated to the positive
and negative Laurent directions.

### Warning: not a vanishing theorem

This module does not prove that any particular \(NK_n(R)\) is nonzero.
It records the structural location of Nil-terms and the literature
warning that they obstruct replacing \(\mathcal{VCyc}\) by smaller
families for arbitrary coefficient rings.

## Proof or verification

The theorem statement is verified from Weibel's Chapter V, Section 8.
Theorem 8.1 identifies the Nil category contribution with \(NK\)-groups,
and Theorem 8.2 gives the split exact sequence for
\(K_n(R[t,t^{-1}])\). The direct-sum display follows by splitting
\(K_n(R[t])\) and \(K_n(R[t^{-1}])\) using evaluation at \(0\).

The Farrell--Jones interpretation is verified from Lueck--Reich. Their
Remark 1.15 explains why the infinite cyclic group already causes
Nil-term difficulties for arbitrary rings. Their Subsections 2.2.4 and
2.2.5 explain the regular-ring exception and the role of Nil-terms in the
relative passage from finite to virtually cyclic families.

No original proof of Bass--Heller--Swan is attempted here.

## References

- Lueck, W., & Reich, H. (2004). *The Baum-Connes and the Farrell-Jones
  conjectures in K- and L-theory* (arXiv:math/0402405). arXiv.
  https://arxiv.org/abs/math/0402405
- Weibel, C. A. (2013). *The K-book: An introduction to algebraic
  K-theory* (Graduate Studies in Mathematics, Vol. 145). American
  Mathematical Society. https://sites.math.rutgers.edu/~weibel/Kbook.html

The original Bass--Heller--Swan paper has been bibliographically located
but was not used as the proof source for this first-pass module.

## Dependencies

This module depends on:

- `FJ01`, for the simplified assembly map;
- `FJ03`, for terminal maps of classifying spaces for families;
- `FJ04`, for virtually cyclic subgroups;
- `FJ06`, for the infinite cyclic example and
  \(R[\mathbb Z]\cong R[t,t^{-1}]\);
- Weibel (2013), Chapter V, Section 8;
- Lueck and Reich (2004), Remark 1.15 and Subsections 2.2.4--2.2.5.

## Results produced

This module produced:

- ER-005: source-verified Bass--Heller--Swan decomposition for
  \(R[\mathbb Z]\).
- A first-pass explanation of why Nil-terms require
  \(\mathcal{VCyc}\) in the arbitrary-ring Farrell--Jones formulation.
- A source-status update selecting Weibel (2013) as the active
  first-pass source for Bass--Heller--Swan.

## Open questions generated

- Which explicit example of a ring with nonzero \(NK_n(R)\) should the
  project use if it later needs a concrete obstruction example?
- Should the original Bass--Heller--Swan paper be checked directly, or is
  Weibel's monograph sufficient for the project's first-pass theorem
  ledger?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: record completion of `FJ07` and move the next target
  to `FJ08`.
- `NOTATION_LEDGER.md`: add \(NK_n(R)\) and \(\mathrm{Nil}(R)\).
- `ESTABLISHED_RESULTS.md`: add ER-005.
- `OPEN_QUESTIONS.md`: resolve OQ-007 for first pass and add the
  follow-up source/example questions.
- `BIBLIOGRAPHY.md`: add APA-style entries for sources used in this
  module.
- `ledgers/source_status.md`: mark Weibel as active reference for
  `FJ07`, and record Lueck--Reich as active for the Nil-term/FJ-family
  interpretation.
