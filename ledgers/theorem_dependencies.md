# Theorem Dependencies Ledger

## Status

Initial ledger.

| Result or module | Depends on | Dependency status | Notes |
|---|---|---|---|
| FJ01 simplified conjecture statement | Black-box equivariant homology normalization | to verify | Needs source/model selection in FJ02 or a later foundations module. |
| ER-001 trivial group case | Definition of E_F G and black-box normalization | proved modulo black box | Internal proof in FJ01. |
| FJ03 classifying spaces | Definition of family of subgroups; Lueck Definition 1.8 and Theorem 1.9 | completed first pass | Produces ER-002; weakly-contractible versus contractible convention remains OQ-005. |
| ER-002 homotopy characterization of \(E_{\mathcal F}G\) | Lueck, *Survey on Classifying Spaces for Families of Subgroups*, Definition 1.8 and Theorem 1.9 | source-verified | Applied to discrete groups and project-style families. |
| FJ04 virtually cyclic groups | Basic group theory; Lueck--Reich virtually cyclic dichotomy; Lueck--Weiermann type I/type II usage | completed first pass | Produces ER-003; original Farrell--Jones 1995 proof source remains OQ-006. |
| ER-003 \(\mathcal{VCyc}(G)\) is a family | Subgroups of virtually cyclic groups are virtually cyclic; conjugation preserves isomorphism type | proved inside project | Infinite type I/type II structure is source-verified context rather than needed for the subgroup proof. |
| FJ05 trivial group standalone example | FJ01 ER-001; FJ03 classifying spaces; FJ04 \(\mathcal{VCyc}\) family | completed | Expanded proof artifact for ER-001; no new result number. |
| FJ06 infinite cyclic group example | FJ01 simplified assembly map; FJ03 classifying spaces; FJ04 virtually cyclic structure | completed | Produces ER-004; avoids Bass--Heller--Swan. |
| ER-004 infinite cyclic group case | \(\mathbb Z\) is virtually cyclic; \(E_{\mathcal{All}}\mathbb Z\simeq\mathrm{pt}\); chosen-generator identification \(R[\mathbb Z]\cong R[t,t^{-1}]\) | proved inside project | Depends on the black-box homology normalization from FJ01. |
| FJ07 Bass--Heller--Swan Nil terms | Weibel Chapter V, Theorems 8.1 and 8.2; Lueck--Reich Remark 1.15 and Subsections 2.2.4--2.2.5 | completed first pass | Produces ER-005; original Bass--Heller--Swan paper remains optional direct verification. |
| ER-005 Bass--Heller--Swan decomposition for \(R[\mathbb Z]\) | FJ06 identification \(R[\mathbb Z]\cong R[t,t^{-1}]\); Weibel fundamental theorem; definition of \(NK_n(R)\) | source-verified | Explains the Nil-term reason for retaining \(\mathcal{VCyc}\) over arbitrary coefficient rings. |
| FJ08 Whitehead group consequence | FJ01 simplified assembly; FJ07 Nil-term context; Lueck--Reich Section 1.1, Section 1.3, Proposition 2.10, and Corollary 2.11 | completed first pass | Produces ER-006; conditional on torsion-free, regular coefficients, and the relevant Farrell--Jones statement. |
| ER-006 conditional Whitehead-group vanishing | Lueck--Reich definitions of \(A_0\), \(A_1\), \(\mathrm{Wh}_0^R(G)\), and \(\mathrm{Wh}_1^R(G)\); Farrell--Jones low-dimensional consequence | source-verified theorem map | Does not apply to groups with torsion without additional hypotheses. |
| FJ09 projective class group consequence | FJ08 \(\mathrm{Wh}_0^R(G)\) framework; Lueck--Reich Section 1.1, Theorem 1.8, and Consequence 1.9 | completed first pass | Produces ER-007; separates \(\widetilde K_0(\mathbb Z[G])\) from \(\mathrm{Wh}(G)\). |
| ER-007 projective class group and finiteness-obstruction consequence | ER-006; Lueck--Reich definition of reduced \(K\)-groups; Wall finiteness obstruction as surveyed by Lueck--Reich | source-verified theorem map | Geometric consequence also needs \(G\) finitely presented. |
| FJ10 Borel conjecture consequence | Source for Borel conjecture; relation to Farrell--Jones, likely involving \(L\)-theory | not started | Must keep \(L\)-theory as a clearly marked source-verified future direction unless explicitly imported. |
