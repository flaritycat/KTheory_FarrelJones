# Known Classes Ledger

## Status

First-pass source-verified table started in `FJ11`, extended for
Artin-group subclasses in `FJ18`, one-relator-relevant routes in `FJ19`,
normalized for selected `FJ18` Artin rows in `FJ69`, and extended in `FJ88`
with the graph-of-abelian-groups route for Baumslag--Solitar candidates.

This ledger records known Farrell--Jones cases only after a theorem
statement has been checked. A row is usable only under its stated
hypotheses and version flags. After `FJ02`, coefficient K-theory rows are
interpreted through the Bartels--Reich additive-category convention; after
`FJ47`, finite-index overgroup passage is available for `FJCw` rows only.
`FJ48` records that no current `T-001`/`RB-005` finite-index cleanup case is
already recorded with `FJCw` subgroup input.
`FJCw`, `FICwF`, full \(\mathcal{FJ}\), and simplified ring-coefficient
statements remain separate source labels unless a comparison is checked.
After `FJ49`, finite extensions of finite-dimensional CAT(0)-groups are not
promoted to the CAT(0)-group row; Ruane records that direction as a question.

| Group class | K-theory? | L-theory? | Coefficients? | Reference | Source status | Notes |
|---|---|---|---|---|---|---|
| Hyperbolic groups | yes, all degrees | yes, all degrees | additive categories | Bartels--Lueck--Reich (2008); Bartels--Lueck (2012) | source-verified for FJ11; proof skeleton expanded in FJ13; used for FJ23 route subtraction | K-theory all degrees from Bartels--Lueck--Reich; L-theory with coefficients from Bartels--Lueck's class \(\mathcal B\). Used in `FJ23` to subtract torsion-free one-relator groups once a source-verified hyperbolicity bridge is available. |
| Hyperbolic-by-cyclic groups \(H\rtimes_\Phi\mathbb Z\), with \(H\) virtually torsion-free hyperbolic | yes, source formulation | yes, source formulation | additive categories | Bestvina--Fujiwara--Wigglesworth (2023) | source-verified for FJ19; used for FJ26 route subtraction | Main theorem covers mapping tori of automorphisms of virtually torsion-free hyperbolic groups. Includes finite-rank free-by-cyclic groups; relevant to one-relator groups only when the group is independently identified as such. Used in `FJ26` to subtract torsion-free one-relator groups once a source-verified mapping-torus or finite-rank free-by-cyclic bridge is available. |
| Finite-dimensional CAT(0)-groups | yes, all degrees | yes, all degrees | additive categories | Wegner (2012); Bartels--Lueck (2012) | source-verified for FJ11; proof skeleton expanded in FJ14; used for FJ24 route subtraction | Wegner supplies full K-theory through strong transfer reducibility; Bartels--Lueck supplies L-theory for groups acting properly, cocompactly, and isometrically on finite-dimensional CAT(0)-spaces. Used in `FJ24` to subtract torsion-free one-relator groups once a source-verified finite-dimensional CAT(0) bridge is available. |
| Virtually solvable groups | yes, all degrees | yes, all degrees | additive categories | Wegner (2015) | source-verified for FJ11; used for FJ25 route subtraction | Main theorem states K- and L-theoretic Farrell--Jones with coefficients in additive categories with respect to \(\mathcal{VCyc}\). Used in `FJ25` to subtract torsion-free one-relator groups once a source-verified virtual-solvability bridge is available. |
| Fundamental groups of graphs of abelian groups, including generalized Baumslag--Solitar and Baumslag--Solitar groups | yes in source `C` | yes in source `C` | additive categories and finite wreath products | Gandini--Meinert--Rueping (2015) | source-verified for FJ88 | The source defines `C` as the K- and L-theoretic Farrell--Jones conjecture with finite wreath products and coefficients in additive categories. The main theorem covers fundamental groups of graphs of abelian groups; Corollary 1.1 includes all Baumslag--Solitar groups. Used in `FJ88` to route `CAND-T001-004`, not to prove global `T-001`. |
| Artin groups of FC-type | source says Farrell--Jones with finite wreath products | source says Farrell--Jones with finite wreath products | source-level finite wreath product formulation | Huang--Osajda (2021) | source-verified for FJ18 | Huang--Osajda prove FC-type Artin groups are Helly and record Farrell--Jones with finite wreath products as a corollary. Internal Helly proof details are not reconstructed. |
| Weak Garside groups of finite type, including the spherical Artin and braid examples listed in FJ18 | source says Farrell--Jones with finite wreath products | source says Farrell--Jones with finite wreath products | source-level finite wreath product formulation | Huang--Osajda (2021) | source-verified for FJ18; ledger-normalized by FJ69 | Added to this ledger by FJ69 because it was already present in the FJ18 source-verified table. Use only under the source's weak finite-type Garside hypotheses. |
| Even Artin groups of FC-type | yes, all degrees in source FJCw | yes, all degrees in source FJCw | additive categories and finite wreath products | Brueck--Kielak--Wu (2021) | source-verified for FJ18 | Corollary B follows from normally poly-free groups; also covered by the broader Huang--Osajda FC-type row with a different route. |
| Normally poly-free groups | yes, all degrees in source FJCw | yes, all degrees in source FJCw | additive categories and finite wreath products | Brueck--Kielak--Wu (2021) | source-verified for FJ18 | Method row used for Artin applications, including even FC-type Artin groups and \(A_\Gamma\rtimes_f\mathbb Z\) for finite-graph RAAGs. |
| Right-angled Artin groups and finite-graph semidirect products \(A_\Gamma\rtimes_f\mathbb Z\) | source-level yes for the recorded routes | source-level yes for the recorded routes | RAAG route through CAT(0)/known-class rows; semidirect-product route through source-level FJCw | Brueck--Kielak--Wu (2021); CAT(0) route rows from FJ11/FJ14 | source-verified for FJ18; ledger-normalized by FJ69 | Added to this ledger by FJ69 because it was already present in the FJ18 source-verified table. The semidirect row assumes the source's finite simplicial graph and automorphism hypotheses. |
| Even Artin groups satisfying Wu's clique or join/tree criteria | yes in source FJCw | yes in source FJCw | additive categories and finite wreath products | Wu (2022) | source-verified for FJ18 | Applies only under Wu's finite graph, positive even label, clique, and join/tree hypotheses. |
| Roushon's listed finite real, complex, and affine Artin types | yes in source FICwF | yes in source FICwF | coefficients and finite wreath products; also A-theory in source | Roushon (2021, 2022, 2024) | source-verified for FJ18 with erratum/corrigendum caution | Includes types \(A_n\), \(B_n(=C_n)\), \(D_n\), \(F_4\), \(G_2\), \(I_2(p)\), \(\widetilde A_n\), \(\widetilde B_n\), \(\widetilde C_n\), and \(G(de,e,r)\); use the 2024 corrigendum for \(\widetilde B_n\). |

## Not yet verified here

The following classes are candidates for later rows, but this ledger does
not yet record them as source-verified known cases:

- 3-manifold groups;
- mapping class groups;
- lattices in Lie groups;
- S-arithmetic groups;
- relatively hyperbolic groups;
- additional one-relator group subclasses not covered by the conditional
  routes recorded in `FJ19`.

The global class of all Artin groups is not recorded here as a known
Farrell--Jones case. `FJ18` records only the listed subclasses and
source-specific reduction routes.

The global class of all torsion-free one-relator groups is not recorded
here as a known Farrell--Jones case. `FJ19` records conditional routes
through hyperbolic, finite-dimensional CAT(0), virtually solvable, and
hyperbolic-by-cyclic classes, and records Lueck's 2025 open-status warning
for the Full Farrell--Jones Conjecture.
