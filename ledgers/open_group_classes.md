# Open Group Classes Ledger

## Status

Initial candidate list only. No class is marked open or solved without source verification, because apparently mathematics works better when assertions are not just decorative noises.

| Candidate class | Current project status | Known subclasses to check | Relevant modules | Next action |
|---|---|---|---|---|
| Artin groups | partially resolved inside project: several subclasses are source-verified, but no global all-Artin theorem is recorded; deferred by `FJ20` | subclasses still outside the FJ18 rows; possible clique-reduction targets | FJ18, FJ20+ | Return after `T-001` or after source-convention reconciliation for `FJCw`/`FICwF`. |
| Torsion-free one-relator groups | selected first serious target `T-001`; global class remains unresolved inside project; `FJ19` records Lueck's open-status warning for Full Farrell--Jones and verified conditional routes; `FJ22` records the adopted one-relator hierarchy vocabulary; `FJ23` subtracts the hyperbolic route; `FJ24` subtracts the finite-dimensional CAT(0) route and compact special bridge cases; `FJ25` subtracts the virtually solvable route only when a virtual-solvability bridge is recorded; `FJ26` subtracts the hyperbolic-by-cyclic/free-by-cyclic route only when a mapping-torus or finite-rank free-by-cyclic bridge is recorded; `FJ27` subtracts version-aware inheritance routes only when exact inheritance bridges are recorded; `FJ28` creates the conservative residual ledger in `ledgers/t001_residual.md`; `FJ29` selects `RB-004` as the next attack surface; `FJ30` verifies Brown as a limited two-generator kernel-recognition source; `FJ31` runs the first Brown calibration case | selected residual bucket: `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\); Brown/BNS criterion in `ledgers/t001_kernel_recognition.md`; first calibration example in `FJ31`; other residual buckets remain deferred in `ledgers/t001_residual.md` | FJ19, FJ20+ | Continue with `FJ32`: choose a nontrivial Brown test case or family not already removed by the virtually solvable route if possible. |
| Automatic/biautomatic groups | unresolved inside project | CAT(0)-related, mapping class-related examples | FJ20+ | Defer until known-cases ledger. |
| Thompson-type groups | unresolved inside project | F, T, V and relatives | FJ20+ | Defer until known-cases ledger. |
