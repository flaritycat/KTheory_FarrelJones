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
| \(t\) | chosen generator of \(\mathbb Z\) in multiplicative notation | local/active | FJ06 | Used to identify \(R[\mathbb Z]\cong R[t,t^{-1}]\). Also used locally in `FJ33` as the semidirect-product generator for \(G_{2,3}\). |
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
| \(\operatorname{trans}\) | transfer functor in the controlled-algebra proof route | source-level active | FJ17 | Used for both Bartels--Lueck--Reich and Wegner transfer architectures; exact categorical model deferred to OQ-020. |
| \(\operatorname{trans}_*\) | \(K\)-theory map induced by the transfer functor | source-level active | FJ17 | In Wegner's proof, composed with projection to recover the diagonal map. |
| \(\operatorname{diag}_*\) | diagonal map on \(K\)-theory induced by the diagonal inclusion into a sequence category | source-level active | FJ17 | Appears in Wegner's transfer diagram. |
| \(\operatorname{pr}_*\) | \(K\)-theory map induced by projection from the transferred control space back to the point | source-level active | FJ17 | Wegner records \(\operatorname{pr}_*\circ\operatorname{trans}_*=\operatorname{diag}_*\). |
| \(S^n_{\Psi,S,k}(g,x)\) | controlled subset of \(G\times X\) generated by finite group data and a strong homotopy action | source-level active | FJ17 | Wegner notation used in strong transfer reducibility. |
| \(d_{\Psi,S,k,\Lambda}\) | quasi-metric on \(G\times X\) associated to a strong homotopy action and finite control data | source-level active | FJ17 | Used to encode control for transfer-reducibility maps. |
| \(\Sigma_n\) | uniformly finite-dimensional simplicial complexes with isotropy in \(\mathcal F\) in Wegner's proof outline | source-level active | FJ17 | Maps from \(G\times X_n\) to \(\Sigma_n\) carry transferred classes into cover-controlled targets. |
| \(f_n:G\times X_n\to\Sigma_n\) | transfer-reducibility maps into finite-dimensional controlled complexes | source-level active | FJ17 | Used in the source proof diagram after transferring from the point. |
| \(\Gamma\) | labelled simplicial graph defining an Artin group | source-level active | FJ18 | Context-dependent; avoid confusing with a group variable unless the module is explicitly in Artin-graph notation. |
| \(V(\Gamma)\) | vertex set of the labelled graph \(\Gamma\) | source-level active | FJ18 | Used in the Artin group definition and clique notation. |
| \(A_\Gamma\) | Artin group associated to the labelled graph \(\Gamma\) | source-level active | FJ18 | Also used for right-angled Artin groups when all edge labels are \(2\). |
| \(A_T\) | Artin subgroup generated by \(T\subseteq V(\Gamma)\) | source-level active | FJ18 | In Wu's source, \(A_T\) is the Artin group of the full subgraph spanned by \(T\). |
| \(W_T\) | Coxeter group associated to the full subgraph on \(T\) | source-level active | FJ18 | Used only in the FC-type definition. |
| \(\Gamma_T\) | full subgraph of \(\Gamma\) spanned by \(T\) | source-level active | FJ18 | Recorded for compatibility with Wu's notation. |
| FC-type | Artin-group condition: clique subgroups \(A_T\) are of spherical type | source-level active | FJ18 | Source convention from the Artin literature; exact formulation checked in Wu and used by Huang--Osajda. |
| FJCw | K- and L-theoretic Farrell--Jones conjecture with finite wreath products and coefficients in additive categories | source-level flag | FJ18 | Used by Brueck--Kielak--Wu and Wu. Internal additive-category foundations remain deferred to FJ02. |
| FICwF | Roushon's isomorphism-conjecture-with-finite-wreath-products notation | source-level flag | FJ18 | Roushon applies it to K-, L-, and A-theories with coefficients; reconcile before proof-level internal use. |
| \(\langle X\mid r\rangle\) | one-relator presentation with generators \(X\) and one defining relator \(r\) | active | FJ19 | Used for one-relator groups; finite generation requires \(X\) finite. |
| \(F(\Sigma)\) | free group on the generating set \(\Sigma\) | active | FJ21 | Used in modern one-relator hierarchy sources for presentations \(F(\Sigma)/\langle\langle w\rangle\rangle\). |
| \(\langle\langle w\rangle\rangle\) | normal closure of \(w\) in a free group | active | FJ21 | Used in the quotient notation \(F(\Sigma)/\langle\langle w\rangle\rangle\). |
| Magnus subgroup | subgroup generated by a subset of generators omitting at least one generator appearing in the cyclic reduction of the relator | source-level active | FJ21 | Source convention from Linton's one-relator hierarchy orientation; exact classical variants remain to verify before proof-sensitive use. |
| Magnus hierarchy | hierarchy of one-relator groups using HNN splittings with lower-complexity one-relator vertex group and Magnus-subgroup edge groups | source-level active | FJ21 | Bridge description checked in Linton's `Hyperbolic one-relator groups`; complex-level theorem formulation recorded in FJ22. |
| \(X=(\Gamma,\lambda)\) | one-relator complex with graph \(\Gamma\) and attaching immersion \(\lambda:S^1\to\Gamma\) | source-level active | FJ22 | Linton's complex-level hierarchy language. |
| Magnus subgraph | connected subgraph \(\Lambda\subseteq\Gamma\) satisfying Linton's source hypothesis that \(\lambda\) is not supported in \(\Lambda\) | source-level active | FJ22 | Use this complex-level term when applying Linton's hierarchy theorem; do not silently replace it with a presentation-level convention. |
| one-relator splitting | HNN splitting \(\pi_1(X_i)\cong\pi_1(X_{i+1})*_{\psi_i}\) induced by identifying Magnus subgraphs | source-level active | FJ22 | Adopted from Linton's hierarchy theorem. |
| one-relator tower | finite sequence \(X_N\to\cdots\to X_1\to X_0=X\) of one-relator-complex immersions producing one-relator splittings | source-level active | FJ22 | Linton's theorem supplies such towers for finite one-relator complexes. |
| one-relator hierarchy | one-relator tower whose terminal group splits as a free product of cyclic groups | source-level active | FJ22 | Refines the FJ21 bridge term; Linton's theorem terminates in a finite cyclic group. |
| \(A_{i+1},B_{i+1}\) | associated Magnus subgraphs in the \(i\)-th one-relator splitting | source-level active | FJ22 | Their fundamental groups are identified by \(\psi_i\). |
| \(h(X)\) | hierarchy length of a one-relator complex \(X\) | source-level active | FJ22 | Minimal length of a one-relator hierarchy for \(X\), in Linton's source convention. |
| \(s\mathbb Z(\psi)\) | Linton's \(\mathbb Z\)-stable number of an isomorphism \(\psi:A\to B\) between subgroups | source-level active | FJ22 | Project shorthand only; exact recursive collections \(\mathcal A_i^\psi\) must be rechecked before computation. |
| \(\mathbb Z\)-stable HNN extension | HNN extension with finite \(s\mathbb Z(\psi)\) in Linton's source convention | source-level active | FJ22 | First-pass definition recorded; exact recursive definition remains source-dependent. |
| \(\mathbb Z\)-stable hierarchy | one-relator hierarchy with \(s\mathbb Z(\psi_i)<\infty\) at every splitting step | source-level active | FJ22 | Important for Linton's main equivalence theorem. |
| quasi-convex one-relator hierarchy | hierarchy whose associated Magnus-subgraph groups are quasi-isometrically embedded in the preceding vertex group at every step | source-level active | FJ22 | Downstream hyperbolic-route term. |
| acylindrical hierarchy | hierarchy whose Bass--Serre tree actions are acylindrical at every step | source-level active | FJ22 | Downstream term in Linton's main equivalence theorem. |
| \(H*_\psi\) | HNN extension \(\langle H,t\mid tat^{-1}=\psi(a), a\in A\rangle\) | source-level active | FJ22 | Used for inertial one-relator extension vocabulary. |
| inertial one-relator extension | Linton source term for certain HNN extensions of one-relator groups over strongly inert Magnus-subgroup data | source-level active | FJ22 | Recorded only as downstream route vocabulary. |
| locally indicable | every nontrivial finitely generated subgroup surjects onto \(\mathbb Z\) | active term | FJ19 | Structural property of torsion-free one-relator groups by Brodskii--Howie; not itself a Farrell--Jones theorem. |
| \(H_\Phi=H\rtimes_\Phi\mathbb Z\) | mapping torus of an automorphism \(\Phi\colon H\to H\) | active | FJ19 | Used for hyperbolic-by-cyclic and free-by-cyclic routes. |
| free-by-cyclic | group of the form \(F\rtimes_\Phi\mathbb Z\), with \(F\) free | active term | FJ19 | Covered by the hyperbolic-by-cyclic route when \(F\) has finite rank; broader countable-free extension rows are survey-level unless primary-source traced. |
| hyperbolic-by-cyclic-route subtraction | project bookkeeping step removing a one-relator group from `T-001` once a source-verified bridge to \(H\rtimes_\Phi\mathbb Z\), with \(H\) virtually torsion-free hyperbolic, is recorded | active term | FJ26 | Uses the Bestvina--Fujiwara--Wigglesworth row recorded in `FJ19`; does not classify one-relator mapping tori. |
| mapping-torus bridge | source-verified statement or elementary internal proof showing that a group has the required semidirect-product form \(H\rtimes_\Phi\mathbb Z\) | active term | FJ26 | An HNN splitting or epimorphism to \(\mathbb Z\) is insufficient without kernel/base control. |
| finite-rank free-by-cyclic bridge | source-verified statement or elementary internal proof showing that a group has form \(F_n\rtimes_\Phi\mathbb Z\) with \(n<\infty\) | active term | FJ26 | Included in the hyperbolic-by-cyclic route as recorded in `FJ19`; kernel-finiteness recognition remains source-sensitive. |
| hyperbolic-route subtraction | project bookkeeping step removing a one-relator group from `T-001` once a source-verified bridge to word-hyperbolicity is recorded | active term | FJ23 | Uses `ER-009`; does not prove hyperbolicity. |
| hyperbolicity bridge | source-verified statement placing a group or subclass inside the word-hyperbolic known case | active term | FJ23 | Examples include direct hyperbolicity verification or Linton hierarchy hypotheses that imply hyperbolicity. |
| hyperbolic-route residual | part of `T-001` not yet removed by the hyperbolic known-case route | active term | FJ23 | Conservative residual: may include groups whose hyperbolicity has not yet been checked. |
| CAT(0)-route subtraction | project bookkeeping step removing a one-relator group from `T-001` once a source-verified finite-dimensional CAT(0)-group bridge is recorded | active term | FJ24 | Uses `ER-009` and `FJ14`; does not construct CAT(0) actions internally. |
| CAT(0) bridge | source-verified statement placing a group or subclass inside the finite-dimensional CAT(0)-group known case | active term | FJ24 | Includes direct proper cocompact finite-dimensional CAT(0) actions and compact special cube complex bridges. |
| compact special bridge | source-verified statement that a group is the fundamental group of a compact finite-dimensional special cube complex | active term | FJ24 | Leads to a finite-dimensional CAT(0) cube complex via the universal cover; virtual-special variants need finite-index handling. |
| virtually solvable | having a solvable subgroup of finite index | active term | FJ25 | Used as the third route subtraction for `T-001`; local indicability and nontrivial abelianization are not virtual-solvability certificates. |
| virtually solvable-route subtraction | project bookkeeping step removing a one-relator group from `T-001` once a source-verified virtual-solvability bridge is recorded | active term | FJ25 | Uses `ER-009` and `FJ11`; does not classify virtually solvable one-relator groups. |
| virtually solvable bridge | source-verified statement or elementary internal proof showing that a group has a solvable subgroup of finite index | active term | FJ25 | Examples may overlap earlier hyperbolic or CAT(0) routes; do not double-count route subtractions. |
| inheritance-route subtraction | project bookkeeping step removing a one-relator group from `T-001` once an exact source-verified inheritance bridge is recorded | active term | FJ27 | Version flags must be preserved; this is not a generic closure slogan. |
| coefficient K-theory inheritance route | inheritance route using a source statement for K-theoretic Farrell--Jones with coefficients in additive categories | active term | FJ27 | Based on FJ12 rows from Bartels--Reich and Bartels--Echterhoff--Lueck. |
| full \(\mathcal{FJ}\) inheritance route | inheritance route using Lueck's source-specific full Farrell--Jones class \(\mathcal{FJ}\) | active term | FJ27 | Recorded as source-level full \(\mathcal{FJ}\), not silently relabeled as the simplified ring-coefficient formulation. |
| `T-001` residual | project-state collection of torsion-free one-relator cases not yet removed by recorded route bridges | active term | FJ28 | Not a negative theorem and not a class of counterexamples. |
| residual bucket | bookkeeping category for `T-001` cases sharing the same missing bridge or source-recognition problem | active term | FJ28 | Used in `ledgers/t001_residual.md`. |
| attack-surface candidate | residual bucket specific enough to support a source search or reduction attempt | active term | FJ28 | `FJ29` should select one candidate. |
| selected residual attack surface | residual bucket chosen for the next bounded source-verification or reduction attempt | active term | FJ29 | Project-selection term, not a theorem label. |
| kernel-recognition attack surface | the `RB-004` problem of controlling kernels of maps to \(\mathbb Z\), especially finite-rank free kernels | active term | FJ29 | Chosen as the next `T-001` attack surface. |
| first verification source | first external source selected for exact theorem and hypothesis checking in the next module | active term | FJ29 | Brown (1987) is selected for `FJ30`, but not yet active theorem input. |
| \(S(G)\) | Brown's character sphere of nonzero homomorphisms \(G\to\mathbb R\) modulo positive scalar multiplication | active term | FJ30 | Used only for Brown/BNS kernel-recognition bookkeeping. |
| \(\chi\colon G\to\mathbb Z\) | epimorphism or character used in Brown/BNS kernel-recognition tests | active term | FJ30 | In `FJ31`, \(\chi(x)=1\) and \(\chi(y)=0\) for the commutator-presentation calibration example. |
| \([\chi]\) | positive-scalar class of a nonzero character in Brown's character sphere | active term | FJ30 | Used together with \([-\chi]\) when applying Brown's finite-generation criterion. |
| Brown-positive kernel-recognition bridge | verification that both \([\chi]\) and \([-\chi]\) pass Brown's relevant criterion for a surjection \(\chi\colon G\to\mathbb Z\) | active term | FJ30 | May feed into the finite-rank free-by-cyclic route only after the free finite-rank kernel is recorded. |
| \(s_i\) | proper initial segment \(x_1x_2\cdots x_{i-1}\) of a cyclically reduced relator \(r=x_1\cdots x_n\) | local/active | FJ31 | Used to compute the Brown initial-segment sequence \(\chi(s_i)\). |
| Brown initial-segment sequence | sequence of values \(\chi(s_i)\) used in Brown's two-generator maximum-count test | active term | FJ31 | In `FJ31`, the sequence for \(\chi\) is \(0,1,1,0\), and for \(-\chi\) is \(0,-1,-1,0\). |
| \(G_{2,3}\) | selected two-generator one-relator Brown test case \(\langle x,y\mid x^2y^{-3}\rangle\) | local/active | FJ32 | `FJ33` proves \(G_{2,3}\cong F_2\rtimes\mathbb Z\). |
| \(G_{p,q}\) | nearby Brown family \(\langle x,y\mid x^p y^{-q}\rangle\), with \(p,q\geq2\) and \(\gcd(p,q)=1\) | local/active | FJ34 | Brown-positive finite-generation family; `FJ36` records the finite-rank free-by-cyclic route bridge. |
| \(\chi_{p,q}\) | epimorphism \(G_{p,q}\to\mathbb Z\) with \(\chi_{p,q}(x)=q\), \(\chi_{p,q}(y)=p\) | local/active | FJ34 | Used in the family Brown maximum-count computation. |
| \(K_{p,q}\) | kernel \(\ker(\chi_{p,q})\) | local/source-verified active | FJ35, FJ36 | Brown gives finite generation and `FJ36` proves finite-rank freeness by the Bass--Serre free-action bridge; the rank is not computed. |
| \(T_{p,q}\) | Bass--Serre tree of \(G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle\), with \(z\mapsto x^p\) and \(z\mapsto y^q\) | local/source-verified active | FJ36 | Used to prove that \(K_{p,q}\) acts freely because it intersects all conjugates of the cyclic vertex groups trivially. |
| \(a,b\) | braid-presentation generators for \(G_{2,3}\), with \(G_{2,3}\cong\langle a,b\mid aba=bab\rangle\) | local/active | FJ33 | Defined by \(a=y^{-1}x\), \(b=x^{-1}y^2\). |
| \(p,q\) | free-kernel generators in the \(G_{2,3}\cong F(p,q)\rtimes\mathbb Z\) bridge | local/active | FJ33 | Defined by \(p=ba^{-1}\), \(q=tpt^{-1}\). |
| \(\varphi\) | automorphism of \(F(p,q)\) with \(\varphi(p)=q\), \(\varphi(q)=p^{-1}q\) | local/active | FJ33 | Gives the semidirect product \(F(p,q)\rtimes_\varphi\mathbb Z\). |
| simple vertex / special edge | Brown's convex-hull terms in the two-generator one-relator criterion | active term | FJ30 | Used for the geometric version of the Brown criterion. |
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
