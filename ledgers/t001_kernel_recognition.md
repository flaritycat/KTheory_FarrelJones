# T-001 Kernel-Recognition Ledger

## Status

Created in `FJ30`. First nontrivial finite-rank free-kernel bridge recorded
in `FJ33`. The \(G_{p,q}\)-family bridge was recorded in `FJ36`; `FJ37`
selected beyond-Brown source selection, `FJ38` selected the normal-subgroup
source cluster, `FJ39` verified the Karrass--Solitar finitely
presented-kernel bridge, and `FJ41` verified the original BNS Theorem B1 as a
finite-generation criterion.

## Warning

This ledger records source-verified recognition criteria for selected
`RB-004` cases. It does not claim that every torsion-free one-relator
epimorphism to \(\mathbb Z\) has finitely generated kernel.

## Brown/BNS route

| Item | Project status | Source |
|---|---|---|
| Character-sphere and HNN-valuation formulation | Brown checked at first-pass level | Brown (1987), Sections 3 and 5 |
| Kernel finite-generation criterion for a surjection \(G\to\mathbb Z\) | Brown checked at first-pass level | Brown (1987), Corollary 3.2 |
| Two-generator one-relator computable criterion | Brown checked at first-pass level | Brown (1987), Theorems 4.2--4.4 |
| Original BNS invariant paper | Theorem B1 checked in `FJ41` for normal subgroups with abelian quotient | Bieri--Neumann--Strebel (1987) |
| Higher finiteness invariant context | selected as secondary source if stronger finiteness hypotheses arise | Bieri--Renz (1988) |
| Normal-subgroup bridge in CD2/duality settings | cited through Karrass--Solitar, but not independently verified | Bieri (1976) |
| One-relator finitely presented normal-subgroup comparator | checked as a bridge theorem for finite-presentation input | Karrass--Solitar (1978) |

## Project-facing route criterion

For a torsion-free one-relator group \(G\), a map
\(\chi\colon G\to\mathbb Z\) enters the `FJ26` finite-rank free-by-cyclic
route after all of the following have been recorded:

1. a source-verified presentation compatible with Brown's criterion, currently
   best understood for two-generator one-relator presentations;
2. Brown's criterion verifies both \([\chi]\) and \([-\chi]\);
3. the project records that the resulting kernel is a finite-rank free group;
4. the exact sequence
   \[
   1\to F_n\to G\to \mathbb Z\to 1
   \]
   is written with \(n<\infty\).

## Do not use as

- a global proof for all torsion-free one-relator groups;
- a proof that every epimorphism to \(\mathbb Z\) has finitely generated
  kernel;
- a Farrell--Jones theorem;
- a replacement for the `FJ26` route.

## FJ31 calibration example

| Presentation | Character | Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) | \(\chi(x)=1,\ \chi(y)=0\) | \([\chi]\) and \([-\chi]\) pass the zero-on-one-generator maximum-count test | \(\ker(\chi)=\langle y\rangle\cong F_1\), and \(G\cong F_1\rtimes\mathbb Z\) | Calibration only; already removed by the virtually solvable route |

Use of this row is limited to workflow calibration. It verifies that the
Brown test has been translated correctly into project bookkeeping, but it
does not subtract a new residual case from `T-001`.

## FJ32 selected next test case

| Presentation | Character | Preliminary Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) | \(\chi(x)=3,\ \chi(y)=2\) | \([\chi]\) and \([-\chi]\) preliminarily pass the nonzero-on-both-generators maximum-count test | deferred at selection stage; completed in the `FJ33` row below | selected for next worked Brown test |

The `FJ32` row is a selection row, not a completed route row. The completed
route bridge is the `FJ33` row below.

## FJ33 worked route bridge

| Presentation | Character | Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) | \(\chi(x)=3,\ \chi(y)=2\) | \([\chi]\) and \([-\chi]\) pass the nonzero-on-both-generators maximum-count test | \(\ker(\chi)\cong F_2\), and \(G_{2,3}\cong F_2\rtimes_\varphi\mathbb Z\) | concrete `FJ26` finite-rank free-by-cyclic route bridge |

The semidirect bridge uses the internal presentation change recorded in
`FJ33`, with
\[
\varphi(p)=q,\qquad \varphi(q)=p^{-1}q.
\]

## FJ34 nearby family boundary

| Presentation | Character | Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\) | \(\chi_{p,q}(x)=q,\ \chi_{p,q}(y)=p\) | \([\chi_{p,q}]\) and \([-\chi_{p,q}]\) pass the nonzero-on-both-generators maximum-count test | Brown gives finite generation of \(\ker(\chi_{p,q})\); finite-rank freeness not yet recorded | family boundary only; no `FJ26` route bridge yet |

The family row records only the part controlled by Brown's checked theorem
and corollary. It does not use torus-knot terminology, fibered-knot
theorems, or an unsourced classification claim.

## FJ35 selected kernel-freeness bridge

| Presentation | Character | Brown result | Candidate freeness bridge | Route status |
|---|---|---|---|---|
| \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\) | \(\chi_{p,q}(x)=q,\ \chi_{p,q}(y)=p\) | \(K_{p,q}=\ker(\chi_{p,q})\) is finitely generated | Use the cyclic-amalgam shape \(\langle x\rangle *_{\langle z\rangle}\langle y\rangle\); \(K_{p,q}\) intersects conjugates of \(\langle x\rangle\) and \(\langle y\rangle\) trivially; verify Bass--Serre freeness in Serre's *Trees* | source selected; no family `FJ26` route bridge yet |

The selected bridge avoids torus-knot and fibered-knot classification claims.
It becomes a route bridge only after the Bass--Serre theorem statement is
source-verified.

## FJ36 verified Bass--Serre bridge

| Presentation | Character | Freeness bridge | Route status |
|---|---|---|---|
| \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\) | \(\chi_{p,q}(x)=q,\ \chi_{p,q}(y)=p\) | \(K_{p,q}\) acts freely on the Bass--Serre tree \(T_{p,q}\), so \(K_{p,q}\cong F_n\) for finite \(n\) by Brown finite generation plus the source-verified free-action theorem | family `FJ26` route bridge recorded; exact rank \(n\) not computed |

The `FJ36` bridge uses the cyclic-amalgam presentation and Bass--Serre
vertex stabilizers. It does not use torus-knot terminology, fibered-knot
classification, or a global theorem for all torsion-free one-relator groups.

## FJ37 post-Gpq audit

| Issue | Decision | Route impact |
|---|---|---|
| Exact rank of \(K_{p,q}\) | Deferred | finite rank already suffices for `FJ26` |
| More \(G_{p,q}\)-style examples | Deferred | `FJ36` covers the family at route level |
| Brown beyond two-generator criterion | Source cluster selected by `FJ38`; `FJ39` verifies only the Karrass--Solitar finite-presentation bridge; `FJ41` verifies direct BNS finite-generation theorem use; `FJ42` checks Bieri access and route delta | Bieri primary theorem text remains unverified; BNS still needs invariant computation before residual subtraction |

The next kernel-recognition task is not another computation inside the
\(G_{p,q}\)-family. It is source selection for cases outside Brown's checked
two-generator one-relator criterion.

## FJ38 beyond-Brown source cluster

| Source cluster item | Intended verification role | Current status |
|---|---|---|
| Bieri--Neumann--Strebel (1987) | direct BNS finite-generation criterion beyond Brown's restatement | Theorem B1 checked in `FJ41`; no invariant computation or residual subtraction |
| Bieri--Renz (1988) | higher finiteness context if the bridge needs finite presentation, \(\mathrm{FP}_2\), or stronger hypotheses | selected secondary source; theorem statement not yet checked |
| Bieri (1976) | normal subgroups in duality groups and groups of cohomological dimension \(2\) | metadata/source-access checked in `FJ42`; primary theorem text not directly verified |
| Karrass--Solitar (1978) | one-relator groups with finitely presented normal subgroup of infinite index | theorem form checked in `FJ39`; no concrete new candidate selected in `FJ40` |

`FJ38` is source selection only. It does not prove that any new kernel is
finitely generated, finitely presented, free, or finite rank. `FJ39` must
verify the exact statements before this ledger can record any new route
criterion.

## FJ39 finitely presented-kernel bridge

| Input | Source-verified output | Route status |
|---|---|---|
| One-relator \(G\) with \(1\ne H\trianglelefteq G\), \(H\) finitely presented, and \([G:H]=\infty\) | \(G\) is torsion-free, two-generator, and an infinite cyclic or infinite dihedral extension of a finitely generated free group | bridge source verified; no concrete residual subtraction yet |

This row uses Karrass--Solitar (1978). It does not apply to kernels known
only to be finitely generated. The infinite cyclic alternative is aligned with
the `FJ26` finite-rank free-by-cyclic route, but the infinite dihedral
alternative needs finite-index and version handling before route use.

## FJ40 finitely presented-kernel test selection

| Candidate | Finitely presented-kernel status | Route status | FJ40 decision |
|---|---|---|---|
| Commutator-presentation calibration from `FJ31` | kernel recorded as infinite cyclic | calibration only; already non-residual | not a non-Brown test case |
| \(G_{2,3}\) from `FJ33` | kernel recorded as \(F_2\) | already removed through `FJ26` | not a new test case |
| \(G_{p,q}\)-family from `FJ36` | kernel recorded as finite-rank free | already removed through `FJ26` | not a new test case |
| General beyond-Brown `RB-004` | no source-ready finitely presented normal kernel recorded | still active residual territory | no candidate selected |
| Karrass--Solitar infinite-dihedral alternative | no concrete example selected | needs finite-index/version handling before use | deferred |

`FJ40` records a negative selection result for the current repository state.
It is not a theorem that no such examples exist.

## FJ41 direct BNS theorem verification

| Input | Source-verified output | Route status |
|---|---|---|
| Finitely generated \(G\), normal \(N\trianglelefteq G\), and \(G/N\) abelian | \(N\) is finitely generated if and only if \(S(G,N)\subseteq\Sigma(G)\) | finite-generation theorem verified; no computation of \(\Sigma(G)\) and no residual subtraction |
| Surjection \(\chi\colon G\twoheadrightarrow\mathbb Z\) | \(\ker(\chi)\) is finitely generated if and only if \([\chi]\) and \([-\chi]\) lie in \(\Sigma(G)\) | matches the two-sided shape used in the Brown route, but does not replace Brown's computable criterion |

This row uses Bieri--Neumann--Strebel (1987), Theorem B1, checked in `FJ41`.
It upgrades direct BNS theorem use from selected source to active theorem map,
but it does not prove freeness, finite rank, or membership in the `FJ26`
finite-rank free-by-cyclic route.

## FJ42 Bieri source-access and route-delta check

| Candidate bridge | Current status | Route impact |
|---|---|---|
| Bieri (1976), CD \(\leq 2\) normal-subgroup theorem | comparison sources report a finitely presented normal-subgroup hypothesis; primary theorem text not directly checked | reinforces finite-presentation bottleneck; no route subtraction |
| Bieri (1976), duality-group theorem | comparison source reports a type-\(VFP\) normal-subgroup hypothesis; primary theorem text not directly checked | not an immediate finite-rank free-kernel bridge for `RB-004` |
| Karrass--Solitar bridge | already source-verified in `FJ39` | remains the only theorem-use normal-subgroup bridge in this cluster |
| Direct BNS theorem | source-verified in `FJ41` | still needs a \(\Sigma(G)\)-membership computation |

`FJ42` does not promote Bieri (1976) to theorem-use status. It records a
route-delta decision: the next module should decide whether this source
cluster is still producing mathematical progress, rather than automatically
adding another layer of bibliography.

## FJ43 route-delta checkpoint

| Candidate continuation | Decision | Reason |
|---|---|---|
| Further Bieri--Renz verification | pause | no concrete \(\mathrm{FP}_2\), finite-presentation, or higher-finiteness need is attached to a candidate |
| Direct BNS computation | pause | BNS theorem use is verified, but no new family with computable \(\Sigma(G)\)-membership is selected |
| Karrass--Solitar infinite-dihedral cleanup | defer | no source-ready finitely presented-kernel candidate currently needs the cleanup bridge |
| New Brown-style computation | require attack packet first | further computation should not repeat already removed calibration or \(G_{p,q}\)-family cases |
| Residual-bucket comparison | select next | the project needs an attack-packet decision before more source-only work |

`FJ43` pauses automatic `RB-004` source-cluster continuation. `RB-004` remains
an active recorded bucket, but further BNS/Bieri--Renz/Bieri work must be
attached to a concrete candidate, missing bridge, or named residual
subtraction.

## FJ44 attack-packet selection effect

`FJ44` selects `RB-005`, not another `RB-004` source module, as the next
attack packet. This leaves the kernel-recognition ledger in a paused but
available state: the Brown route, direct BNS theorem map, and Karrass--Solitar
cleanup bridge remain usable when a concrete candidate is selected.

## Next action

Keep `RB-004` paused until a candidate-ready route is identified. The active
project move is `FJ45`, finite-index formulation bridge checkpoint for
`RB-005`.
