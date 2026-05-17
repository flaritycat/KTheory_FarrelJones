# CAND-T001-005 Handoff

## Status

Completed handoff consolidation.

## Purpose

This file executes Prompt 007 from `the 15-next-steps.md`. It collects the
current repository status of `CAND-T001-005` in one place without changing
the row's mathematical status.

This is an internal handoff only. It records no new theorem, no new route, no
new source verification, and no residual subtraction.

## Source use

No external source was consulted for this handoff. The handoff summarizes
existing repository records from `FJ90` through `FJ96` and the candidate and
residual ledgers. No new APA citation is required.

## Candidate

Candidate ID: `CAND-T001-005`

Presentation:
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle.
\]

Associated epimorphism:
\[
\chi(a)=0,\qquad \chi(b)=1.
\]

Relevant bucket posture: possible `RB-004` / `RB-008` object only if a later
payload supplies kernel-control or inheritance-safe extension data.

## What has been checked

| Module | Checked item | Recorded outcome |
|---|---|---|
| `FJ90` | Candidate intake | Adds the row as a concrete blocked intake object; relator is first-pass checked as not a proper power; \(\chi(a)=0,\chi(b)=1\) is recorded. |
| `FJ91` | Torsion-free status | Records first-pass torsion-free status using the previously recorded non-proper-power check and the source already cited in `FJ91`. |
| `FJ92` | Brown/BNS kernel-control computation | Records Brown-positive finite generation for \(\ker(\chi)\); does not identify the kernel as finite-rank free. |
| `FJ93` | Known-route / prior-art blocker audit | Records no current repository route or prior-art blocker for the row. |
| `FJ94` | Weaker \(K_0\) / Cohen--Lyndon hypothesis audit | Records that the row is not FJ83-eligible from current repository data. |
| `FJ95` | Branch checkpoint | Demotes the row to blocked / inactive proof-target status and creates `OBL-T001-023`. |
| `FJ96` | Live-candidate audit | Records no live non-routed candidate after the `FJ95` demotion and creates `NLC-T001-002`. |

## Current status

`CAND-T001-005` is retained as a concrete torsion-free one-relator candidate
row, but it is not live for proof work.

Current classification:

- blocked / inactive proof-target row;
- no recorded Farrell--Jones route;
- no recorded weaker \(K_0\) consequence;
- no recorded prior-art closure;
- no residual-bucket subtraction;
- no active formulation-safety task, because no active route is recorded.

## Reopening requirement

Future work on `CAND-T001-005` must satisfy `OBL-T001-023`. A reopening
payload must supply at least one of the following concrete objects:

- finite-rank free-kernel identification;
- source-verified route bridge;
- new FJ83 weaker \(K_0\) hypothesis data;
- formulation comparison tied to a route;
- prior-art object;
- explicit reopening payload that changes a proof obligation.

Generic continuation, source-summary, or governance prompts do not reopen the
row.

## Stop conditions

Stop if `CAND-T001-005` is treated as:

- live without a payload satisfying `OBL-T001-023`;
- routed by Brown-positive finite generation alone;
- finite-rank free-by-cyclic without a finite-rank free-kernel bridge;
- FJ83-eligible without the missing Cohen--Lyndon / group-pair data;
- a proof of full `T-001`;
- a residual subtraction.

## Ledger action

`ledgers/t001_candidate_inventory.md` is updated to point future runs to this
handoff entry.
