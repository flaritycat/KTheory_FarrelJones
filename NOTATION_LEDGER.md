# Notation Ledger

| Notation | Meaning | Status | First used | Notes |
|---|---|---|---|---|
| \(R\) | associative unital ring | active | FJ01 | Standing assumption unless changed. |
| \(G\) | discrete group | active | FJ01 | Standing assumption unless changed. |
| \(H\leq G\) | subgroup of \(G\) | active | FJ01 | Used for fixed-point tests and orbit normalizations. |
| \(R[G]\) | group ring of \(G\) over \(R\) | active | FJ01 | Active notation. |
| \(RG\) | alternative notation for \(R[G]\) | inactive alternative | FJ01 | Do not use without recording a notation change. |
| \(K_n(R[G])\) | algebraic \(K\)-group of the group ring | active/black box | FJ01 | For all \(n\in\mathbb Z\), this requires a nonconnective model. |
| \(\mathbb Z\) | infinite cyclic group under addition | active | FJ04 | Used to define type I virtually cyclic groups. |
| \(t\) | chosen generator of \(\mathbb Z\) in multiplicative notation | local/active | FJ06 | Used to identify \(R[\mathbb Z]\cong R[t,t^{-1}]\). |
| \(R[t,t^{-1}]\) | Laurent polynomial ring over \(R\) | active | FJ06 | Identified with \(R[\mathbb Z]\) after choosing generator \(t\). |
| \(R[t^{-1}]\) | polynomial ring in the inverse variable \(t^{-1}\) | active | FJ07 | Used in the Bass--Heller--Swan split exact sequence. |
| \(NK_n(R)\) | cokernel of \(K_n(R)\to K_n(R[t])\) | active | FJ07 | Nil-term notation used in the Bass--Heller--Swan decomposition. |
| \(\mathrm{Nil}(R)\) | category of nilpotent endomorphisms of finitely generated projective \(R\)-modules | local/active | FJ07 | Used only to explain the terminology behind Nil-groups. |
| \(G_{\mathrm{ab}}\) | abelianization of \(G\) | active | FJ08 | Used in the low-dimensional map \(A_1\). |
| \(A_0\) | map \(K_0(R)\to K_0(R[G])\) induced by \(R\to R[G]\) | active | FJ08 | Source notation from Lueck--Reich. |
| \(A_1\) | map \(G_{\mathrm{ab}}\otimes_{\mathbb Z}K_0(R)\oplus K_1(R)\to K_1(R[G])\) | active | FJ08 | Source notation from Lueck--Reich. |
| \(\mathrm{Wh}_0^R(G)\) | cokernel of \(A_0\) | active | FJ08 | \(R\)-Whitehead group in Lueck--Reich's low-dimensional notation. |
| \(\mathrm{Wh}_1^R(G)\) | cokernel of \(A_1\) | active | FJ08 | Specializes to the classical Whitehead group for \(R=\mathbb Z\). |
| \(\mathrm{Wh}(G)\) | classical Whitehead group of \(G\) | active | FJ08 | Identified with \(\mathrm{Wh}_1^{\mathbb Z}(G)\) in FJ08. |
| \(\widetilde K_0(\mathbb Z[G])\) | reduced projective class group of \(\mathbb Z[G]\) | active | FJ08 | Identified with \(\mathrm{Wh}_0^{\mathbb Z}(G)\) in FJ08. |
| \(\widetilde K_n(A)\) | reduced algebraic \(K\)-group \(\operatorname{coker}(K_n(\mathbb Z)\to K_n(A))\) | active | FJ09 | Used for projective class group and finiteness obstruction statements. |
| \(o(X)\) | Wall finiteness obstruction of a finitely dominated CW complex \(X\) | active | FJ09 | Lives in \(\widetilde K_0(\mathbb Z[\pi_1(X)])\). |
| \(X\) | CW complex in finiteness-obstruction statements | local/active | FJ09 | Usually finitely dominated in FJ09. |
| \(BG\) | classifying space of \(G\) | active | FJ10 | For aspherical spaces \(X\) with \(\pi_1(X)=G\), \(X\) is a model for \(BG\). |
| \(L_n^{\langle -\infty\rangle}(\mathbb ZG)\) | quadratic algebraic \(L\)-group with \(-\infty\) decoration | application-only | FJ10 | Imported only for the Borel consequence theorem map. |
| \(\mathbf L^{\langle -\infty\rangle}(\mathbb Z)\) | \(L\)-theory spectrum used in the source assembly map | application-only | FJ10 | Not part of the active K-theory core. |
| \(S^{\mathrm{top}}(M)\) | topological structure set of \(M\) | application-only | FJ10 | Singleton condition is the surgery-theoretic form of Borel rigidity. |
| \(\mathcal A\) | additive category with a group action, as used in source formulations | source-level flag | FJ11 | Internal additive-category foundations remain deferred to FJ02. |
| \(\mathcal B\) | Bartels--Lueck source class containing hyperbolic groups and finite-dimensional CAT(0)-groups | source-specific | FJ11 | Used only to record Theorem B from Bartels--Lueck (2012). |
| \(D_\infty\) | infinite dihedral group \(\mathbb Z/2 * \mathbb Z/2\) | active | FJ04 | Used to define type II virtually cyclic groups. |
| \(\mathcal F\) | family of subgroups of \(G\) | active | FJ01 | Closed under conjugation and passage to subgroups. |
| \(\mathcal{All}(G)\) | family of all subgroups of \(G\) | active | FJ03 | \(E_{\mathcal{All}}G\) is modeled by \(\mathrm{pt}\). |
| \(\mathcal{Triv}(G)\) | family consisting only of the trivial subgroup | active | FJ03 | \(E_{\mathcal{Triv}}G\) is the usual free contractible \(G\)-CW complex \(EG\). |
| \(\mathcal{Fin}(G)\) | family of finite subgroups of \(G\) | active | FJ03 | \(E_{\mathcal{Fin}}G\) is often denoted \(\underline EG\). |
| \(\mathcal{VCyc}(G)\) | family of virtually cyclic subgroups of \(G\) | active | FJ01 | Sometimes abbreviated \(\mathcal{VCyc}\) when \(G\) is clear. |
| \(\mathcal{VCyc}_I(G)\) | finite subgroups plus infinite type I virtually cyclic subgroups of \(G\) | limited use | FJ04 | Recorded for source compatibility; the main FJ family remains \(\mathcal{VCyc}(G)\). |
| \(E_{\mathcal F}G\) | classifying \(G\)-CW complex for the family \(\mathcal F\) | active | FJ01 | Developed further in FJ03. |
| \(E_{\mathcal{All}}G\) | classifying space for the family of all subgroups | active | FJ03 | Modeled by \(\mathrm{pt}\). |
| \(E_{\mathcal{Triv}}G\) | classifying space for the trivial family | active | FJ03 | Usual notation: \(EG\). |
| \(E_{\mathcal{Fin}}G\) | classifying space for the family of finite subgroups | active | FJ03 | Often written \(\underline EG\). |
| \(\underline EG\) | common notation for \(E_{\mathcal{Fin}}G\) | active alias | FJ03 | Use only for the finite-subgroup family. |
| \(E_{\mathcal{VCyc}}G\) | classifying space for the virtually cyclic family | active | FJ01 | Source of the FJ assembly map. |
| \(X^H\) | fixed-point space of \(H\leq G\) acting on \(X\) | active | FJ03 | \(X^H=\{x\in X:hx=x\ \forall h\in H\}\). |
| \(G_x\) | isotropy subgroup/stabilizer of \(x\in X\) | active | FJ03 | \(G_x=\{g\in G:gx=x\}\). |
| \(\mathrm{pt}\) | one-point \(G\)-space | active | FJ01 | Carries the trivial point topology and the unique \(G\)-action. |
| \(\mathbf K_R\) | coefficient object/spectrum for algebraic \(K\)-theory of \(R\) | black box | FJ01 | Model not chosen yet. |
| \(H_n^G(-;\mathbf K_R)\) | equivariant homology theory associated to algebraic \(K\)-theory | black box | FJ01 | Normalized so \(H_n^G(G/H;\mathbf K_R)\cong K_n(R[H])\). |
| \(A_{G,R,n}\) | simplified assembly map in degree \(n\) | active | FJ01 | Introduced to name the map induced by \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\). |
