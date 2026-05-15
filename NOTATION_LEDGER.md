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
| \(\Phi^*\mathcal F\) | pullback family \(\{H\leq K:\Phi(H)\in\mathcal F\}\) for a homomorphism \(\Phi\colon K\to G\) | source-level active | FJ12 | Used in Bartels--Reich's coefficient inheritance theorem. |
| \(\mathcal{FJ}\) | Lueck's source-specific class of groups satisfying the Full Farrell--Jones Conjecture | source-specific | FJ12 | Includes more structure than the simplified ring-coefficient statement in FJ01. |
| \(\operatorname*{colim}_i G_i\) | colimit of a directed system of groups | active | FJ12 | Used in the directed-colimit inheritance ledger. |
| \(P_d(G)\) | Rips complex of \(G\) at scale \(d\) | source-level active | FJ13 | Used in the Bartels--Lueck--Reich hyperbolic-groups proof skeleton. |
| \(\partial X\) | Gromov boundary of the hyperbolic complex \(X\) in FJ13 source notation | source-level active | FJ13 | Appears in the compactification \(\overline X=X\cup\partial X\). |
| \(\overline X\) | compactification \(X\cup\partial X\) used in the hyperbolic proof skeleton | source-level active | FJ13 | In FJ13, \(X=P_d(G)\). |
| \(Y\) | finite-dimensional CAT(0)-space used in the CAT(0)-group proof source | source-level active | FJ14 | Wegner uses a proper cocompact isometric \(G\)-action on \(Y\). |
| \(\overline B_R(x_0)\) | closed ball of radius \(R\) around \(x_0\) in a CAT(0)-space | source-level active | FJ14 | Used as the compact transfer space in Wegner's CAT(0) proof route. |
| \(FS(Y)\) | flow space of generalized geodesics in the CAT(0)-space \(Y\) | source-level active | FJ14 | Bartels--Lueck flow-space cover technology is a deferred proof dependency. |
| \(\Psi\) | strong homotopy action | source-level active | FJ14 | Used because closed CAT(0) balls are not generally honest \(G\)-spaces. |
| \(\int_G\mathcal A\) | additive category/group-action construction appearing in Wegner's target \(K_m(\int_G\mathcal A)\) | source-level flag | FJ14 | Internal additive-category foundations remain deferred to FJ02. |
| \(\mathcal O^G(E_{\mathcal F}G,\mathrm{pt};\mathcal A)\) | obstruction category for the assembly map in the controlled proof route | source-level flag | FJ14 | Located as proof technology; not internally developed yet. |
| \(FS(X)\) | flow space associated to a metric, CAT(0), or hyperbolic space \(X\), depending on source context | source-level active | FJ16 | For CAT(0) sources, elements are generalized geodesics. For hyperbolic sources, the construction is Mineyev-style and remains source-level. |
| \(\Phi_\tau\) | time-\(\tau\) map of a flow | source-level active | FJ16 | In CAT(0) flow space, \(\Phi_\tau(c)(t)=c(t+\tau)\). |
| \(\Phi_I(z)\) | flow segment \(\{\Phi_t(z):t\in I\}\) | source-level active | FJ16 | Used in long-cover conditions. |
| \(FS^\mathbb R\) | fixed-point set of the flow | source-level active | FJ16 | In CAT(0) flow spaces, this includes constant generalized geodesics. |
| \(\operatorname{per}^G_\Phi(z)\) | \(G\)-period of a point in a flow space | source-level active | FJ16 | Infimum of positive flow times returning to the \(G\)-orbit. |
| \(FS_{\leq\gamma}\), \(FS_{>\gamma}\) | subsets of the flow space with \(G\)-period at most or greater than \(\gamma\) | source-level active | FJ16 | Used in periodic-flow-line cover statements. |
| \(j:G\times\overline X\to FS(X)\) | hyperbolic source map into a flow space | source-level flag | FJ16 | Used in Bartels--Lueck--Reich's flow estimate; construction not reproduced. |
| \((Y,d_Y)\) | metric control space with isometric \(G\)-action | source-level active | FJ15 | Used in Wegner's obstruction-category review. |
| \(G\times X\times Y\times [1,\infty)\) | index space for objects and morphisms in Wegner's obstruction category | source-level active | FJ15 | Records group, family-space, metric-control, and continuous-control directions. |
| \(\mathcal O^G(X,(Y,d_Y);\mathcal A)\) | obstruction category over a \(G\)-space \(X\) and metric control space \(Y\) | source-level active | FJ15 | General form of the obstruction-category notation used in Wegner. |
| \(\mathcal E^X_{Gcc}\) | equivariant continuous-control condition in the \(X\times[1,\infty)\) direction | source-level flag | FJ15 | Name recorded only; exact definition deferred to OQ-018. |
| \(\phi_{z,z'}\) | matrix coefficient of a morphism in an obstruction category | source-level active | FJ15 | Used to discuss controlled morphisms without developing the full category internally. |
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
