# Known Classes Ledger

## Status

First-pass source-verified table started in `FJ11` and extended for
Artin-group subclasses in `FJ18`.

This ledger records known Farrell--Jones cases only after a theorem
statement has been checked. A row is usable only under its stated
hypotheses and version flags.

| Group class | K-theory? | L-theory? | Coefficients? | Reference | Source status | Notes |
|---|---|---|---|---|---|---|
| Hyperbolic groups | yes, all degrees | yes, all degrees | additive categories | Bartels--Lueck--Reich (2008); Bartels--Lueck (2012) | source-verified for FJ11; proof skeleton expanded in FJ13 | K-theory all degrees from Bartels--Lueck--Reich; L-theory with coefficients from Bartels--Lueck's class \(\mathcal B\). |
| Finite-dimensional CAT(0)-groups | yes, all degrees | yes, all degrees | additive categories | Wegner (2012); Bartels--Lueck (2012) | source-verified for FJ11; proof skeleton expanded in FJ14 | Wegner supplies full K-theory through strong transfer reducibility; Bartels--Lueck supplies L-theory for groups acting properly, cocompactly, and isometrically on finite-dimensional CAT(0)-spaces. |
| Virtually solvable groups | yes, all degrees | yes, all degrees | additive categories | Wegner (2015) | source-verified for FJ11 | Main theorem states K- and L-theoretic Farrell--Jones with coefficients in additive categories with respect to \(\mathcal{VCyc}\). |
| Artin groups of FC-type | source says Farrell--Jones with finite wreath products | source says Farrell--Jones with finite wreath products | source-level finite wreath product formulation | Huang--Osajda (2021) | source-verified for FJ18 | Huang--Osajda prove FC-type Artin groups are Helly and record Farrell--Jones with finite wreath products as a corollary. Internal Helly proof details are not reconstructed. |
| Even Artin groups of FC-type | yes, all degrees in source FJCw | yes, all degrees in source FJCw | additive categories and finite wreath products | Brueck--Kielak--Wu (2021) | source-verified for FJ18 | Corollary B follows from normally poly-free groups; also covered by the broader Huang--Osajda FC-type row with a different route. |
| Normally poly-free groups | yes, all degrees in source FJCw | yes, all degrees in source FJCw | additive categories and finite wreath products | Brueck--Kielak--Wu (2021) | source-verified for FJ18 | Method row used for Artin applications, including even FC-type Artin groups and \(A_\Gamma\rtimes_f\mathbb Z\) for finite-graph RAAGs. |
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
- one-relator group subclasses.

The global class of all Artin groups is not recorded here as a known
Farrell--Jones case. `FJ18` records only the listed subclasses and
source-specific reduction routes.
