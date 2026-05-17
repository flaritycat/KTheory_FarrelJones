# Source Bibliography Consistency Audit

## Status

Completed.

## Purpose

This audit executes Prompt 008 from `the 15-next-steps.md`. It compares
`BIBLIOGRAPHY.md`, `ledgers/source_status.md`,
`ledgers/theorem_dependencies.md`, and `README.md` for internal consistency of
already recorded sources.

No external source was consulted. No source status is upgraded by this audit.

## Method

The audit compared author-title source identifiers and module-use labels. The
comparison treated repeated topical rows in `ledgers/source_status.md` as
compatible with a single aggregate bibliography entry when the same source is
split by topic, as with Lueck--Reich.

## Findings

| Finding | Action |
|---|---|
| Every bibliography entry has a corresponding source-status row at the author-title level, allowing for topical splits in `ledgers/source_status.md`. | No new bibliography entries were added. |
| Several Artin-source bibliography notes listed only `FJ18`, while `ledgers/source_status.md` also records later reuse in `FJ69` and, for Wu, `FJ70`. | `BIBLIOGRAPHY.md` was updated with those internal cross-references. |
| The Jaikin-Zapirain--Linton--Sanchez-Peralta source-status row still pointed future use mainly to the pre-branch `OBL-T001-022` gate. | `ledgers/source_status.md` was updated to distinguish the general FJ83 reuse gate `OBL-T001-015` from the `CAND-T001-005` reopening gate `OBL-T001-023`. |
| The bibliography/source-status pair already agrees that the Farrell--Jones original paper, Davis--Lueck assembly source, Bass--Heller--Swan original paper, Mineyev, Lueck Assembly Maps, and classical one-relator monographs remain found / to verify / no-promotion sources where so labeled. | No promotion made. |

## No-Promotion Check

This audit does not promote any source from `found`, `to verify`,
`partially read`, `metadata checked`, `comparison source`, or `background
only` to theorem-use status.

In particular:

- Farrell--Jones (1993) remains `to verify`;
- Farrell--Jones (1995) remains metadata-checked / no-promotion for direct
  Lemma 2.5 use;
- Davis--Lueck (1998) remains `to verify`;
- Bass--Heller--Swan (1964) remains found / to verify for theorem use;
- Mineyev (2005) remains found / to verify for theorem use;
- Lyndon--Schupp and Magnus--Karrass--Solitar remain found / to verify for
  classical one-relator theorem use.

## Ledger Action

- `BIBLIOGRAPHY.md` now records the later FJ69/FJ70 internal uses of the
  already recorded Artin sources.
- `ledgers/source_status.md` now records the post-FJ95 gate distinction for
  future use of the FJ83 weaker \(K_0\) / Cohen--Lyndon source payload.

## Stop Condition

Stop after internal consistency fixes. Do not add new sources, consult
external sources, or upgrade any theorem status.
