# Module FJ03. Classifying spaces for families

## Status

Completed, first pass

## Module type

Definition / Example / Literature verification

## Problem

Develop a reusable first-pass account of classifying spaces for
families of subgroups, especially the space
\(E_{\mathcal{VCyc}}G\) which appears in the simplified
Farrell--Jones assembly map from `FJ01`.

This module stays at the level of \(G\)-CW complexes and families of
subgroups. It does not introduce additive \(G\)-categories; those
belong to `FJ02`.

## Input

- Module `FJ01`, especially the first-pass definitions of
  \(\mathcal{VCyc}(G)\), \(E_{\mathcal F}G\), and the assembly map.
- The standing project convention that \(G\) is a discrete group.
- The standing project convention that a family of subgroups is closed
  under conjugation and passage to subgroups.
- Lueck, *Survey on Classifying Spaces for Families of Subgroups*,
  Definition 1.8 and Theorem 1.9, checked from the arXiv source for
  the terminal-object definition and the homotopy characterization.

## Output target

- Define family of subgroups.
- Define \(E_{\mathcal F}G\).
- Record the source-verified existence and uniqueness statement with
  exact hypotheses at the level needed here.
- Give introductory examples for \(\mathcal{All}\),
  \(\mathcal{Triv}\), \(\mathcal{Fin}\), and
  \(\mathcal{VCyc}\).
- Explain the canonical \(G\)-map \(E_{\mathcal F}G\to\mathrm{pt}\),
  especially for \(\mathcal F=\mathcal{VCyc}(G)\).
- Connect this map back to the assembly map from `FJ01`.

## Definitions

### Definition: Family of subgroups

Let \(G\) be a discrete group.

A **family of subgroups** \(\mathcal F\) of \(G\) is a collection of
subgroups of \(G\) such that:

1. if \(H\in\mathcal F\) and \(g\in G\), then
   \(gHg^{-1}\in\mathcal F\);
2. if \(H\in\mathcal F\) and \(K\leq H\), then
   \(K\in\mathcal F\).

This is the project convention already used in `FJ01`. Lueck's survey
uses a topological-group convention involving closed subgroups and
closure under finite intersections. For this project's discrete groups,
all subgroups are closed, and closure under passage to subgroups implies
closure under finite intersections.

### Definition: Fixed points and isotropy

Let \(X\) be a \(G\)-space and let \(H\leq G\). The **\(H\)-fixed point
space** is

\[
X^H=\{x\in X: hx=x\text{ for every }h\in H\}.
\]

For \(x\in X\), the **isotropy subgroup** or **stabilizer** of \(x\) is

\[
G_x=\{g\in G: gx=x\}.
\]

### Definition: Classifying space for a family

Let \(\mathcal F\) be a family of subgroups of \(G\).

A \(G\)-CW complex \(X\) is a **model for**
\(E_{\mathcal F}G\) if, for every subgroup \(H\leq G\),

\[
X^H\text{ is }
\begin{cases}
\text{contractible}, & H\in\mathcal F,\\
\varnothing, & H\notin\mathcal F.
\end{cases}
\]

Equivalently, in the common fixed-point formulation, the subgroups in
\(\mathcal F\) see contractible fixed-point spaces, and subgroups not
in \(\mathcal F\) see no fixed points.

### Warning

The source-verified theorem below is slightly more flexible: Lueck's
Theorem 1.9 uses weakly contractible fixed-point sets for
\(H\in\mathcal F\), together with the condition that all isotropy
groups lie in \(\mathcal F\). The project's first-pass formulation uses
contractible fixed-point spaces because that is the most readable
version for the present module.

## Main work

The point of \(E_{\mathcal F}G\) is that it is the universal
\(G\)-space, up to \(G\)-homotopy, whose isotropy groups lie in
\(\mathcal F\). Thus the family \(\mathcal F\) determines which
subgroups of \(G\) are allowed to appear as stabilizers.

When \(\mathcal F_0\subseteq\mathcal F_1\), the terminal property gives
a \(G\)-map

\[
E_{\mathcal F_0}G\longrightarrow E_{\mathcal F_1}G
\]

unique up to \(G\)-homotopy. In particular, since every family
\(\mathcal F\) is contained in the family of all subgroups
\(\mathcal{All}(G)\), there is a canonical map

\[
E_{\mathcal F}G\longrightarrow E_{\mathcal{All}}G.
\]

The space \(E_{\mathcal{All}}G\) is modeled by the one-point
\(G\)-space \(G/G\cong\mathrm{pt}\). Hence every family gives a
terminal \(G\)-map

\[
E_{\mathcal F}G\longrightarrow \mathrm{pt}.
\]

For \(\mathcal F=\mathcal{VCyc}(G)\), this is exactly the geometric map
underlying the simplified Farrell--Jones assembly map in `FJ01`:

\[
E_{\mathcal{VCyc}}G\longrightarrow \mathrm{pt}.
\]

Applying the black-box equivariant homology theory from `FJ01` gives

\[
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_R)
\longrightarrow
H_n^G(\mathrm{pt};\mathbf K_R)
\cong K_n(R[G]).
\]

## Proposition / Theorem / Conjecture / Example

### Source-verified claim: Existence and homotopy characterization

Let \(G\) be a discrete group and let \(\mathcal F\) be a project-style
family of subgroups of \(G\).

There exists a model for \(E_{\mathcal F}G\). Moreover,
\(E_{\mathcal F}G\) is terminal in the \(G\)-homotopy category of
\(G\)-CW complexes whose isotropy groups belong to \(\mathcal F\).
Consequently:

1. two models for \(E_{\mathcal F}G\) are \(G\)-homotopy equivalent;
2. if \(\mathcal F_0\subseteq\mathcal F_1\), then there is, up to
   \(G\)-homotopy, precisely one \(G\)-map
   \(E_{\mathcal F_0}G\to E_{\mathcal F_1}G\);
3. a \(G\)-CW complex \(X\) is a model for \(E_{\mathcal F}G\) if its
   isotropy groups lie in \(\mathcal F\) and \(X^H\) is weakly
   contractible for every \(H\in\mathcal F\).

Source: Lueck, *Survey on Classifying Spaces for Families of
Subgroups*, Definition 1.8 and Theorem 1.9.

### Example: The family \(\mathcal{All}(G)\)

Let

\[
\mathcal{All}(G)=\{H:H\leq G\}.
\]

The one-point \(G\)-space \(\mathrm{pt}\cong G/G\) is a model for
\(E_{\mathcal{All}}G\). Indeed, every subgroup fixes the point, so the
fixed-point space is contractible for every \(H\leq G\).

### Example: The family \(\mathcal{Triv}(G)\)

Let

\[
\mathcal{Triv}(G)=\{1\}.
\]

A model for \(E_{\mathcal{Triv}}G\) is the usual free contractible
\(G\)-CW complex \(EG\). Its isotropy groups are trivial, the
\(1\)-fixed point space is \(EG\) itself, and nontrivial subgroups have
empty fixed-point spaces.

### Example: The family \(\mathcal{Fin}(G)\)

Let

\[
\mathcal{Fin}(G)=\{H\leq G:H\text{ is finite}\}.
\]

The space \(E_{\mathcal{Fin}}G\) is often denoted
\(\underline EG\), the universal space for proper \(G\)-actions. This
module uses only the introductory fixed-point characterization:
finite subgroups have contractible fixed-point spaces, and infinite
subgroups have empty fixed-point spaces.

If \(G\) is torsion-free, then
\(\mathcal{Fin}(G)=\mathcal{Triv}(G)\), so
\(E_{\mathcal{Fin}}G\) and \(E_{\mathcal{Triv}}G\) agree up to
\(G\)-homotopy. If \(G\) is finite, then \(\mathrm{pt}\) is a model for
\(E_{\mathcal{Fin}}G\).

### Example: The family \(\mathcal{VCyc}(G)\)

Let

\[
\mathcal{VCyc}(G)=\{V\leq G:V\text{ is virtually cyclic}\}.
\]

Since finite groups are virtually cyclic,

\[
\mathcal{Fin}(G)\subseteq\mathcal{VCyc}(G)\subseteq\mathcal{All}(G).
\]

Therefore there are canonical \(G\)-maps, unique up to \(G\)-homotopy,

\[
E_{\mathcal{Fin}}G
\longrightarrow
E_{\mathcal{VCyc}}G
\longrightarrow
\mathrm{pt}.
\]

If \(G\) itself is virtually cyclic, then every subgroup of \(G\) is
virtually cyclic, so
\(\mathcal{VCyc}(G)=\mathcal{All}(G)\). In that case
\(\mathrm{pt}\) is a model for \(E_{\mathcal{VCyc}}G\).

### Warning

The maps above are maps of \(G\)-spaces. They are not yet statements
about \(K\)-theory. The \(K\)-theory assembly map appears only after
applying the equivariant homology theory
\(H_n^G(-;\mathbf K_R)\).

## Proof or verification

This module does not prove Lueck's theorem internally.

The literature verification performed here checked the arXiv source for
Lueck's survey:

- Definition 1.8 defines \(E_{\mathcal F}G\) as a terminal object in
  the \(G\)-homotopy category of \(G\)-CW complexes with isotropy in
  \(\mathcal F\).
- The paragraph after Definition 1.8 states uniqueness up to
  \(G\)-homotopy equivalence and the unique map
  \(E_{\mathcal F_0}G\to E_{\mathcal F_1}G\) for
  \(\mathcal F_0\subseteq\mathcal F_1\).
- Theorem 1.9 states existence and gives the fixed-point
  characterization using weakly contractible fixed-point sets for
  subgroups in the family.

For the project's discrete-group setting, the closed-subgroup condition
from the topological-group source is automatic. The project convention
that families are closed under passage to subgroups is stronger than
closure under finite intersections.

The examples above are immediate applications of the fixed-point
definition and the inclusions
\(\mathcal{Triv}(G)\subseteq\mathcal{Fin}(G)\subseteq
\mathcal{VCyc}(G)\subseteq\mathcal{All}(G)\).

## References

- Lueck, W. *Survey on Classifying Spaces for Families of Subgroups*.
  arXiv:math/0312378, version 2, 2004. Status: `active reference`;
  Definition 1.8 and Theorem 1.9 checked for this module.
- `FJ01`, for the simplified group-ring Farrell--Jones assembly map and
  the black-box equivariant homology notation.

## Dependencies

This module depends on:

- `FJ01`, for the simplified assembly-map target and notation.
- The project convention that \(G\) is discrete.
- Lueck's Definition 1.8 and Theorem 1.9 for the source-verified
  homotopy characterization.

## Results produced

This module produced:

- A reusable definition of family of subgroups.
- A reusable first-pass definition of \(E_{\mathcal F}G\).
- Introductory examples for \(\mathcal{All}\), \(\mathcal{Triv}\),
  \(\mathcal{Fin}\), and \(\mathcal{VCyc}\).
- A source-verified claim about existence, uniqueness up to
  \(G\)-homotopy, and the fixed-point characterization of
  \(E_{\mathcal F}G\).
- ER-002: source-verified existence and homotopy characterization of
  classifying spaces for families in the project setting.

## Open questions generated

- Should the project eventually distinguish systematically between
  weakly contractible and contractible fixed-point formulations?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: updated to record completion of `FJ03` and the
  next move to `FJ04`.
- `NOTATION_LEDGER.md`: updated with fixed-point, isotropy, and family
  notation introduced in this module.
- `ESTABLISHED_RESULTS.md`: updated with ER-002 as a source-verified
  theorem for project use.
- `OPEN_QUESTIONS.md`: updated with the weakly-contractible versus
  contractible convention question.
- `BIBLIOGRAPHY.md`: updated with Lueck's classifying-spaces survey.
- `ledgers/source_status.md`: updated with the verified FJ03 use of
  Lueck's Definition 1.8 and Theorem 1.9.
