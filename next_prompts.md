# Next Prompts

## Status

Active prompt backlog for `KTheory_FarrelJones`.

This file records possible future prompts and already executed prompt anchors.
It is not itself an accepted payload ledger. A prompt becomes actionable only
when the user submits it in chat or records it under the repository's payload
protocol.

## Update Rule

When a prompt from this file is executed:

- change `Status` from `Open` to `Completed`;
- add `Completed by`;
- add `Commit`, if committed;
- if the prompt is rejected or superseded, change `Status` to `Rejected` or
  `Superseded` and record why;
- do not renumber existing prompts.

## Legend

- `Completed`: already executed in the repository.
- `Open`: can be pasted by the user as a future request.
- `Template`: not executable until a concrete object is filled in.
- `Rejected`: recorded but not accepted as payload.
- `Superseded`: replaced by a later prompt.

## Prompt 001

Status: Completed

Completed by: `FJ83`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Exit C5-PAUSE-001 by recording accepted payload PAY-T001-K0-CL-2025-001,
then instantiate FJ83 as a bounded weaker K0 / Cohen-Lyndon source-payload
verification. Check exact source statement, hypotheses, formulation level,
and ledger effects. Do not claim full T-001 or residual subtraction.
```

## Prompt 002

Status: Completed

Completed by: `FJ84`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Use FJ83's Jaikin-Zapirain--Linton--Sanchez-Peralta K0 / Cohen-Lyndon
payload to run a candidate/family-level hypothesis audit. Determine whether
any currently recorded T-001 candidate/family satisfies the FJ83 source
hypotheses, or record that no current candidate/family is eligible.
```

## Prompt 003

Status: Completed

Completed by: `FJ85`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Run the governance-only payload-authorship checkpoint after FJ84. Record that
no mathematical payload is present unless a concrete candidate, source,
bridge, computation, formulation comparison, or prior-art blocker is supplied.
```

## Prompt 004

Status: Completed

Completed by: `FJ86`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Run FJ86 as a candidate-intake audit for
G_BS23 = <a,t | t a^2 t^{-1} a^{-3}>.
Determine whether it is candidate-admissible for T-001, already routed,
blocked by missing data, or useful only as an obstruction.
```

## Prompt 005

Status: Completed

Completed by: `FJ87`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Continue with FJ87 by checking whether G_BS23 is torsion-free. Stop after the
bounded torsion-free / HNN status audit and ledger update. Do not compute
Brown/BNS data, identify a kernel type, audit prior art, or claim a
Farrell--Jones route.
```

## Prompt 006

Status: Completed

Completed by: `FJ88`

Commit: historical, see repository log before `FJ90`

Prompt:

```text
Continue with FJ88 by running a bounded known-route / prior-art blocker audit
for CAND-T001-004, G_BS23 = BS(2,3). Check whether it is already covered by
existing repository routes or a source-verified prior-art theorem. Stop after
the route/prior-art blocker audit and ledger update.
```

## Prompt 007

Status: Completed

Completed by: `FJ89`

Commit: `1b7e4e0fc7fd64e3ebef00eaa09b1f42a70c3ff1`

Prompt:

```text
Continue with FJ89 by running a bounded live-candidate audit after the FJ88
closure of CAND-T001-004. Audit the current T-001 candidate inventory and
residual ledger to determine whether any live non-routed candidate row
remains. Do not add a new candidate, use external sources, reopen G_BS23, or
create FJ90.
```

## Prompt 008

Status: Completed

Completed by: `FJ90`

Commit: `40e70db3930ecdc36e423b0f2b839246bddee429`

Prompt:

```text
Continue with FJ90 by running a bounded candidate-intake audit for
CAND-T001-005:
G = <a,b | a b a^{-1} b^2 a b^{-3}>.
Determine whether the row is candidate-admissible for T-001, already routed,
blocked by missing data, or useful only as an obstruction record. Do not
claim Farrell-Jones, FJCw, FICwF, or residual subtraction.
```

## Prompt 009

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with FJ91 by running a bounded torsion-free source-check for
CAND-T001-005.

Payload ID: PAY-T001-CAND005-TF-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
OQ-112, OBL-C5-011, and OBL-T001-018.

Candidate, source, bridge, computation, or blocker:
CAND-T001-005:
G_FJ90 = <a,b | a b a^{-1} b^2 a b^{-3}>.

Exact statement or object:
Verify whether the non-proper-power relator check recorded in FJ90 can be
combined with a source-checked one-relator torsion theorem to promote
torsion-free status for CAND-T001-005. Use exact source hypotheses and APA
citations if any external source is checked. Stop after torsion-free status
and ledger update. Do not compute Brown/BNS data, audit prior art, or claim a
Farrell-Jones route.

Repository object changed:
modules/cycle_005/FJ91_cand005_torsion_free_source_check.md;
ledgers/payload_intake_protocol.md;
ledgers/t001_candidate_inventory.md;
ledgers/t001_residual.md;
OPEN_QUESTIONS.md;
ledgers/theorem_dependencies.md;
README.md;
PROJECT_CHARTER.md;
SCOPE_LEDGER.md;
NOTATION_LEDGER.md;
BIBLIOGRAPHY.md;
ledgers/source_status.md.

Success criterion:
FJ91 records whether torsion-free status for CAND-T001-005 is source-verified,
partially verified, or still blocked.

Failure criterion:
The module cannot verify exact theorem text/hypotheses, or it becomes a broad
one-relator survey.

Stop condition:
Stop after the torsion-free source-check and ledger update. Do not create FJ92.

Accepted?
Yes, for FJ91 torsion-free source-check only.

Follow-up module if accepted:
modules/cycle_005/FJ91_cand005_torsion_free_source_check.md
```

## Prompt 010

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with FJ92 by running a bounded Brown/BNS kernel-control computation
for CAND-T001-005, but only if FJ91 has verified or explicitly bracketed
torsion-free target status.

Payload ID: PAY-T001-CAND005-BROWN-BNS-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
OQ-112 or its FJ91 successor, OBL-C5-011 or its successor, and OBL-T001-018.

Object:
CAND-T001-005:
G_FJ90 = <a,b | a b a^{-1} b^2 a b^{-3}>
with epimorphism chi(a)=0, chi(b)=1.

Exact statement or object:
Compute the bounded Brown/BNS data needed to decide whether the kernel of chi
is finitely generated or whether the row remains kernel-control blocked. Use
only the Brown/BNS framework already recorded in the repository unless a new
source is explicitly required and cited.

Success criterion:
Record whether the chi-kernel is finite-rank free, finitely generated but not
identified, blocked, or unsuitable for the FJ26 route.

Failure criterion:
The module becomes a broad Brown/BNS survey or makes a route claim without a
checked kernel theorem.

Stop condition:
Stop after the kernel-control audit and ledger update. Do not create the next
module.
```

## Prompt 011

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with the next module by running a bounded known-route / prior-art
blocker audit for CAND-T001-005.

Payload ID: PAY-T001-CAND005-ROUTE-PRIORART-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
The active post-FJ90 or post-FJ91/FJ92 gate, plus OBL-T001-018.

Object:
CAND-T001-005:
G_FJ90 = <a,b | a b a^{-1} b^2 a b^{-3}>.

Exact statement or object:
Audit whether CAND-T001-005 is already removed from the T-001 residual bucket
by an existing repository route or prior-art theorem. Check only named routes:
hyperbolic, CAT(0), virtually solvable, finite-index/FJCw, finite-rank
free-by-cyclic, hyperbolic-by-cyclic, graph-of-abelian-groups, or FJ83
weaker K0/Cohen-Lyndon if the hypotheses are actually recorded.

Success criterion:
Record whether CAND-T001-005 is already routed, prior-art blocked, still
blocked, or still live after exact hypotheses are checked.

Failure criterion:
The audit becomes a broad literature survey or fails to connect a source to a
repository route.

Stop condition:
Stop after known-route / prior-art blocker audit and ledger update.
```

## Prompt 012

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a bounded FJ83 weaker K0 / Cohen-Lyndon hypothesis audit for
CAND-T001-005.

Payload ID: PAY-T001-CAND005-K0-CL-HYP-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
The active post-FJ90 gate and OBL-T001-018.

Object:
CAND-T001-005 and the FJ83 Jaikin-Zapirain--Linton--Sanchez-Peralta
weaker K0 / Cohen-Lyndon source payload.

Exact statement or object:
Check whether CAND-T001-005 has enough recorded data to satisfy the FJ83
source-hypothesis package. Do not claim full Farrell-Jones, coefficient FJC,
FJCw, FICwF, or residual subtraction. Stop after recording eligibility,
non-eligibility, or missing data.

Success criterion:
Record whether the row is FJ83-eligible, partially eligible, or not eligible
from current repository data.

Failure criterion:
The module becomes a source summary without changing candidate status or a
proof obligation.

Stop condition:
Stop after candidate-hypothesis audit and ledger update.
```

## Prompt 013

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a branch checkpoint for CAND-T001-005 after the bounded
torsion-free, kernel-control, or prior-art audit currently active in the
repository.

Payload ID: PAY-T001-CAND005-BRANCH-2026-001
Payload type: PAY-GOV

Exact statement or object:
Determine whether CAND-T001-005 should be kept as a live proof target,
routed, demoted to blocked, converted into a calibration/prior-art example,
or closed as non-actionable. Do not add new mathematical content; use only
the ledgers produced by the preceding modules.

Success criterion:
Record a branch decision and the next gate.

Failure criterion:
The checkpoint invents a new source, theorem, computation, or candidate.

Stop condition:
Stop after branch decision and ledger update.
```

## Prompt 014

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a live-candidate audit after the current CAND-T001-005 branch
is closed, routed, or demoted.

Payload ID: PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001
Payload type: PAY-T001-BLOCKER

Exact statement or object:
Audit ledgers/t001_candidate_inventory.md and ledgers/t001_residual.md to
determine whether any live non-routed T-001 candidate row remains after the
latest CAND-T001-005 decision. Do not add a new candidate or use external
sources.

Success criterion:
Record whether a live candidate remains. If none remains, record the exact
blocker and future payload requirements.

Failure criterion:
The module invents a candidate, starts a source survey, or reopens closed
rows without payload.

Stop condition:
Stop after live-candidate audit and ledger update.
```

## Prompt 015

Status: Template

Completed by:

Commit:

Prompt:

```text
Continue with a bounded candidate-intake audit for a new concrete T-001 row.

Payload ID: PAY-T001-CAND-[SHORT-ID]-2026-[NNN]
Payload type: PAY-T001-CAND

Target gate:
The active open question and proof obligation from the current repository.

Candidate, source, bridge, computation, or blocker:
[Replace this with one concrete torsion-free one-relator group or family.]

Exact statement or object:
Add/check this candidate as a possible non-routed T-001 row. Determine whether
it is candidate-admissible, already routed, blocked by missing data, or useful
only as an obstruction record.

Success criterion:
Record candidate status and next proof obligation.

Failure criterion:
The candidate is a placeholder, already routed without new information, lacks
basic target data, or becomes only a source summary.

Stop condition:
Stop after candidate-admissibility audit and ledger update.
```

## Prompt 016

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a formulation-safety audit for any active candidate row whose
route depends on FJCw, coefficient FJC, full FJ, FICwF, or weaker K0-level
statements.

Payload ID: PAY-FORMULATION-SAFETY-AUDIT-2026-001
Payload type: PAY-FORMULATION

Exact statement or object:
Check whether the active candidate route uses the correct formulation label.
Do not promote across finite-index, coefficient, finite-wreath-product,
full-FJ, FICwF, or weaker K0 boundaries without an exact source bridge.

Success criterion:
Record formulation-safe, formulation-blocked, or formulation-irrelevant
status for the active candidate.

Failure criterion:
The module collapses source formulations or becomes a general formulation
essay with no candidate effect.

Stop condition:
Stop after formulation-safety ledger update.
```

## Prompt 017

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a bounded target-pivot readiness checkpoint after the current
T-001 candidate lane is blocked, routed, or paused.

Payload ID: PAY-PIVOT-READINESS-2026-001
Payload type: PAY-GOV

Exact statement or object:
Compare whether T-001, the Artin lane, foundational source queue, or another
recorded target has a concrete next object. Do not start source work unless
one target has an accepted payload with changed repository object, success
criterion, failure criterion, and stop condition.

Success criterion:
Record whether a target remains active or all targets are paused.

Failure criterion:
The checkpoint starts a new source survey or proof attempt.

Stop condition:
Stop after target-pivot readiness update.
```

## Prompt 018

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a cycle-005 strategic checkpoint.

Payload ID: PAY-C5-STRATEGIC-CHECKPOINT-2026-001
Payload type: PAY-GOV

Exact statement or object:
Audit cycle_005 modules from FJ81 onward and record whether the project is
still making candidate-level progress or has returned to decorative
bookkeeping. Do not prove new mathematics and do not add source summaries.

Success criterion:
Record the current active gate, blocked lanes, and the exact next acceptable
payload types.

Failure criterion:
The checkpoint becomes a reflection essay with no ledger effect.

Stop condition:
Stop after strategic checkpoint and ledger update.
```

## Prompt 019

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with cycle_005 closure-readiness audit.

Payload ID: PAY-C5-CLOSURE-READINESS-2026-001
Payload type: PAY-GOV

Exact statement or object:
Determine whether cycle_005 should close, continue with a concrete active
payload, or pause. Do not create a reflection until the closure-readiness
audit records a handoff table and exact unresolved gates.

Success criterion:
Record closure-ready, continue-with-payload, or pause status.

Failure criterion:
The audit creates new mathematical claims or source summaries.

Stop condition:
Stop after closure-readiness audit and ledger update.
```

## Prompt 020

Status: Open

Completed by:

Commit:

Prompt:

```text
Continue with a prompt-backlog maintenance pass.

Payload ID: PAY-PROMPT-BACKLOG-MAINT-2026-001
Payload type: PAY-GOV

Exact statement or object:
Open next_prompts.md and update statuses for prompts that have been completed,
rejected, superseded, or made obsolete by repository state. Do not create a
new mathematical module unless a separate accepted payload is supplied.

Success criterion:
The prompt backlog matches repository state and no completed prompt remains
marked open.

Failure criterion:
The maintenance pass invents new mathematical work or changes module ledgers
without a payload.

Stop condition:
Stop after next_prompts.md update and commit.
```
