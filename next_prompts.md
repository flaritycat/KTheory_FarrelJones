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

Status: Completed

Completed by: `FJ91`

Commit: `e888bf5` (`[module] complete FJ91 torsion-free source check`)

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

Status: Completed

Completed by: `FJ92`

Commit: `dd646b0` (`[module] complete FJ92 Brown/BNS kernel-control audit`)

Prompt:

```text
Continue with FJ92 by running a bounded Brown/BNS kernel-control computation
for CAND-T001-005. FJ91 has verified torsion-free target status at
first-pass candidate-ledger level.

Payload ID: PAY-T001-CAND005-BROWN-BNS-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
OQ-113, OBL-C5-012, and OBL-T001-019.

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

Status: Completed

Completed by: `FJ93`

Commit: `910357b` (`[module] complete FJ93 known-route audit for CAND-T001-005`)

Prompt:

```text
Continue with the next module by running a bounded known-route / prior-art
blocker audit for CAND-T001-005.

Payload ID: PAY-T001-CAND005-ROUTE-PRIORART-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
The active post-FJ92 gate, plus OBL-T001-020.

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

Status: Completed

Completed by: `FJ94`

Commit: `159ae5b` (`[module] complete FJ94 K0 Cohen-Lyndon audit for CAND-T001-005`)

Prompt:

```text
Continue with a bounded FJ83 weaker K0 / Cohen-Lyndon hypothesis audit for
CAND-T001-005.

Payload ID: PAY-T001-CAND005-K0-CL-HYP-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
The active post-FJ93 gate and OBL-T001-021.

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

Status: Completed

Completed by: `FJ95`

Commit: `5fcfa54` (`[module] complete FJ95 branch checkpoint for CAND-T001-005`)

Prompt:

```text
Continue with a branch checkpoint for CAND-T001-005 after the bounded
torsion-free, kernel-control, prior-art, and FJ83 hypothesis audits currently
recorded in the repository.

Payload ID: PAY-T001-CAND005-BRANCH-2026-001
Payload type: PAY-GOV

Target gate:
The active post-FJ94 gate, OQ-116, OBL-C5-015, and OBL-T001-022.

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

Status: Completed

Completed by: `FJ96`

Commit: `45b2d4a` (`[module] complete FJ96 live-candidate audit after CAND-T001-005 demotion`)

Prompt:

```text
Continue with a live-candidate audit after the current CAND-T001-005 branch
is closed, routed, or demoted.

Payload ID: PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001
Payload type: PAY-T001-BLOCKER

Exact statement or object:
Audit ledgers/t001_candidate_inventory.md and ledgers/t001_residual.md to
determine whether any live non-routed T-001 candidate row remains after the
latest CAND-T001-005 decision. Use the post-FJ95 gate, `OQ-117`, and
`OBL-C5-016`. Do not add a new candidate or use external sources.

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

Status: Completed

Completed by: `FJ97`

Commit: `09c2a99` (`[module] complete FJ97 formulation-safety audit after no-live-candidate state`)

Prompt:

```text
Continue with a formulation-safety audit for any active candidate row whose
route depends on FJCw, coefficient FJC, full FJ, FICwF, or weaker K0-level
statements.

Payload ID: PAY-FORMULATION-SAFETY-AUDIT-2026-001
Payload type: PAY-FORMULATION

Exact statement or object:
Check whether the active candidate route uses the correct formulation label.
Use the post-FJ96 gate, `OQ-118`, and `OBL-C5-017`. If no active candidate
route remains, record formulation-irrelevant status. Do not promote across
finite-index, coefficient, finite-wreath-product, full-FJ, FICwF, or weaker
K0 boundaries without an exact source bridge.

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

Status: Completed

Completed by: `FJ98`

Commit: `db4a5b0` (`[module] complete FJ98 target-pivot readiness checkpoint`)

Prompt:

```text
Continue with a bounded target-pivot readiness checkpoint after the current
T-001 candidate lane is blocked, routed, or paused.

Payload ID: PAY-PIVOT-READINESS-2026-001
Payload type: PAY-GOV

Exact statement or object:
Compare whether T-001, the Artin lane, foundational source queue, or another
recorded target has a concrete next object. Use the post-FJ97 gate,
`OQ-119`, and `OBL-C5-018`. Do not start source work unless one target has
an accepted payload with changed repository object, success criterion,
failure criterion, and stop condition.

Success criterion:
Record whether a target remains active or all targets are paused.

Failure criterion:
The checkpoint starts a new source survey or proof attempt.

Stop condition:
Stop after target-pivot readiness update.
```

## Prompt 018

Status: Completed

Completed by: `FJ99`

Commit: `ec9a76a` (`[module] complete FJ99 cycle-005 strategic checkpoint`)

Prompt:

```text
Continue with a cycle-005 strategic checkpoint.

Payload ID: PAY-C5-STRATEGIC-CHECKPOINT-2026-001
Payload type: PAY-GOV

Exact statement or object:
Audit cycle_005 modules from FJ81 onward and record whether the project is
still making candidate-level progress or has returned to decorative
bookkeeping. Use the post-FJ98 gate, `OQ-120`, and `OBL-C5-019`. Do not
prove new mathematics and do not add source summaries.

Success criterion:
Record the current active gate, blocked lanes, and the exact next acceptable
payload types.

Failure criterion:
The checkpoint becomes a reflection essay with no ledger effect.

Stop condition:
Stop after strategic checkpoint and ledger update.
```

## Prompt 019

Status: Completed

Completed by: `FJ100`

Commit: `11d0616` (`[module] complete FJ100 cycle-005 closure-readiness audit`)

Prompt:

```text
Continue with cycle_005 closure-readiness audit.

Payload ID: PAY-C5-CLOSURE-READINESS-2026-001
Payload type: PAY-GOV

Exact statement or object:
Determine whether cycle_005 should close, continue with a concrete active
payload, or pause. Use the post-FJ99 gate, `OQ-121`, and `OBL-C5-020`. Do
not create a reflection until the closure-readiness audit records a handoff
table and exact unresolved gates.

Success criterion:
Record closure-ready, continue-with-payload, or pause status.

Failure criterion:
The audit creates new mathematical claims or source summaries.

Stop condition:
Stop after closure-readiness audit and ledger update.
```

## Prompt 020

Status: Completed

Completed by: `PAY-PROMPT-BACKLOG-MAINT-2026-001`

Commit: `2c2f40f` (`[cleanup] complete prompt backlog maintenance`)

Prompt:

```text
Continue with a prompt-backlog maintenance pass.

Payload ID: PAY-PROMPT-BACKLOG-MAINT-2026-001
Payload type: PAY-GOV

Exact statement or object:
Open next_prompts.md and update statuses for prompts that have been completed,
rejected, superseded, or made obsolete by repository state. Use the post-FJ100
gate, `OQ-122`, and `OBL-C5-021`. Do not create a new mathematical module
unless a separate accepted payload is supplied.

Success criterion:
The prompt backlog matches repository state and no completed prompt remains
marked open.

Failure criterion:
The maintenance pass invents new mathematical work or changes module ledgers
without a payload.

Stop condition:
Stop after next_prompts.md update and commit.
```

## Prompt Backlog Expansion After Prompt 020

This expansion preserves the payload discipline introduced in `FJ82` and
the closure-ready state recorded in `FJ100`.

Execution rule for future runs:

- `Completed`, `Rejected`, `Superseded`, and `Template` prompts are not executable.
- The first executable prompt is the first prompt whose status is exactly `Open`.
- Template prompts must be filled with a concrete candidate, source, bridge,
  computation, blocker, or governance object before execution.
- Do not create mathematical claims from prompt text alone.

## Prompt 021

Status: Completed

Completed by: `reflections/cycle_005_reflection.md`

Commit: this commit (`[reflection] close cycle 005`)

Prompt:

```text
Continue with the cycle_005 reflection after the FJ100 closure-ready handoff.

Payload ID: PAY-C5-REFLECTION-2026-001
Payload type: PAY-GOV

Target gate:
`FJ100`, `ledgers/cycle_005_handoff.md`, `OQ-122`, and `OBL-C5-021`.

Exact statement or object:
Create `reflections/cycle_005_reflection.md` as a bounded cycle reflection. Summarize what cycle_005 actually achieved, what remains gated, and what the next cycle should do. Do not prove new mathematics.

Success criterion:
Record a reflection-ready or next-cycle-ready state with exact gates.

Failure criterion:
The reflection invents a source theorem, candidate, route, or residual subtraction.

Stop condition:
Stop after reflection and ledger updates.

Notes:
Governance only unless the repository has already recorded the required input.
```

## Prompt 022

Status: Completed

Completed by: `reflections/post_100_module_strategic_review.md`

Commit:

Prompt:

```text
Continue with a post-100-module strategic review after cycle_005 reflection.

Payload ID: PAY-POST100-REVIEW-2026-001
Payload type: PAY-GOV

Target gate:
Requires `reflections/cycle_005_reflection.md` or an explicit skip record.

Exact statement or object:
Audit modules `FJ01` through the latest completed module and identify structural debt, live mathematical objects, and decorative-bookkeeping risk.

Success criterion:
Record a compact post-100-module review and next-cycle entry gate.

Failure criterion:
The review becomes a theorem claim or literature survey.

Stop condition:
Stop after review and ledger updates.

Notes:
Governance only unless the repository has already recorded the required input.
```

## Prompt 023

Status: Completed

Completed by: `ledgers/cycle_006_entry_gate.md`

Commit:

Prompt:

```text
Continue with a cycle_006 entry-gate audit.

Payload ID: PAY-C6-GATE-2026-001
Payload type: PAY-GOV

Target gate:
Requires cycle_005 reflection or post-100-module review.

Exact statement or object:
Check whether `T-001`, Artin groups, foundational conventions, or another recorded lane has a gate-satisfying payload for cycle_006.

Success criterion:
Record one selected gate-ready packet or a no-gate-ready state.

Failure criterion:
The audit reactivates a target without satisfying its gate.

Stop condition:
Stop after entry-gate update.

Notes:
Governance only unless the repository has already recorded the required input.
```

## Prompt 024

Status: Completed

Completed by: `ledgers/cycle_006_payload_decision.md`

Commit:

Prompt:

```text
Continue with a payload acquisition or project-pause decision for cycle_006.

Payload ID: PAY-C6-PAYLOAD-2026-001
Payload type: PAY-GOV

Target gate:
Requires a cycle_006 gate audit with no immediately selected mathematical packet.

Exact statement or object:
Apply the payload intake protocol and decide whether a concrete accepted payload exists for the next numbered module.

Success criterion:
Record accepted payload or a payload-gated pause.

Failure criterion:
The module starts mathematical work without a payload.

Stop condition:
Stop after payload decision.

Notes:
Governance only unless the repository has already recorded the required input.
```

## Prompt 025

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-025-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 026

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-026-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 027

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-027-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 028

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-028-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 029

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-029-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 030

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-030-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 031

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-031-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 032

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-032-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 033

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-033-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 034

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-034-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 035

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-035-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 036

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-036-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 037

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-037-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 038

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-038-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 039

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-039-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 040

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-040-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 041

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-041-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 042

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-042-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 043

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-043-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 044

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-044-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 045

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-045-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 046

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-046-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 047

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-047-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 048

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-048-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 049

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-049-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 050

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-050-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 051

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-051-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 052

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-052-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 053

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-053-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 054

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-054-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 055

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-055-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 056

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-056-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 057

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-057-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 058

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-058-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 059

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-059-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 060

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-060-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 061

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-061-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 062

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-062-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 063

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-063-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 064

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-064-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 065

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-065-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 066

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-066-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 067

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-067-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 068

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-068-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 069

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-069-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 070

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-070-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 071

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-071-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 072

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-072-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 073

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-073-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 074

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-074-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 075

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-075-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 076

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-076-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 077

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-077-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 078

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-078-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 079

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-079-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 080

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-080-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 081

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-081-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 082

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-082-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 083

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-083-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 084

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-084-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 085

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-085-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 086

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-086-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 087

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-087-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 088

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-088-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 089

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-089-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 090

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-090-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 091

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-091-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 092

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-092-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 093

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-093-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 094

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-094-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 095

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-095-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 096

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-096-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 097

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-097-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 098

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-098-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 099

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-099-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 100

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-100-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 101

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-101-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 102

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-102-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 103

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-103-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 104

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-104-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 105

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-105-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 106

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-106-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 107

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-107-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 108

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-108-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 109

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-109-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 110

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-110-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 111

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-111-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 112

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-112-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 113

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-113-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 114

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-114-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 115

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-115-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 116

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-116-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 117

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-117-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 118

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-118-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 119

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-119-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 120

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-120-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 121

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-121-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 122

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-122-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 123

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-123-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 124

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-124-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 125

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-125-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 126

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-126-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 127

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-127-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 128

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-128-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 129

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-129-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 130

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-130-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 131

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-131-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 132

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-132-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 133

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-133-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 134

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-134-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 135

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 candidate-intake audit template.

Payload ID: PAY-BACKLOG-135-2026-001
Payload type: PAY-T001-CAND

Target gate:
`OBL-T001-013` or a later recorded T-001 candidate gate.

Exact statement or object:
Fill this prompt with one concrete torsion-free one-relator group or family before execution. The audit must check candidate-admissibility, already-routed status, missing data, and next proof obligation.

Success criterion:
A concrete row is classified as candidate-admissible, routed, blocked, or obstruction-only.

Failure criterion:
The candidate is a placeholder, already known without new information, or lacks target data.

Stop condition:
Stop after candidate-admissibility audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 136

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded T-001 kernel-control computation template.

Payload ID: PAY-BACKLOG-136-2026-001
Payload type: PAY-T001-COMPUTATION

Target gate:
A recorded candidate row with a named epimorphism to Z.

Exact statement or object:
Fill this prompt with a concrete candidate row and epimorphism to Z before execution. The computation must decide whether the relevant kernel is finite-rank free, finitely generated but unresolved, blocked, or unsuitable for an FJ route.

Success criterion:
Kernel-control status changes in the candidate inventory or residual ledger.

Failure criterion:
The computation becomes a broad Brown/BNS survey or assumes a kernel theorem.

Stop condition:
Stop after computation and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 137

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded known-route / prior-art blocker template.

Payload ID: PAY-BACKLOG-137-2026-001
Payload type: PAY-T001-BLOCKER

Target gate:
A recorded candidate row with unresolved route status.

Exact statement or object:
Fill this prompt with a concrete candidate row or family before execution. The audit must check only named repository routes and record exact formulation status.

Success criterion:
The row is routed, prior-art blocked, or remains blocked with exact missing hypotheses.

Failure criterion:
The audit becomes a broad literature survey.

Stop condition:
Stop after route/prior-art blocker update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 138

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded weaker K0 / Cohen-Lyndon hypothesis template.

Payload ID: PAY-BACKLOG-138-2026-001
Payload type: PAY-T001-BRIDGE

Target gate:
A concrete candidate/family row and a recorded weaker K0 source payload.

Exact statement or object:
Fill this prompt with a concrete candidate/family and the exact FJ83 hypothesis package before execution. Do not treat weaker K0 as full Farrell-Jones.

Success criterion:
The row is classified as eligible, partially eligible, or not eligible from repository data.

Failure criterion:
The prompt collapses weaker K0 into full FJ or lacks a candidate object.

Stop condition:
Stop after hypothesis audit and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 139

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded Artin-lane reactivation template.

Payload ID: PAY-BACKLOG-139-2026-001
Payload type: PAY-ARTIN

Target gate:
`OBL-ARTIN-004` or a later recorded Artin reactivation gate.

Exact statement or object:
Fill this prompt with a named graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object before execution.

Success criterion:
An Artin subclass row changes status or a blocker is documented.

Failure criterion:
The prompt says only all Artin groups or names no changed object.

Stop condition:
Stop after Artin ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 140

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded foundational source-payload template.

Payload ID: PAY-BACKLOG-140-2026-001
Payload type: PAY-FND

Target gate:
`FND-QUEUE-PAUSE-001` or later source-queue gate.

Exact statement or object:
Fill this prompt with an exact foundational source theorem or convention whose use is required by a current proof, candidate, or route object.

Success criterion:
A convention, source-status row, or dependency changes.

Failure criterion:
The prompt is broad background or bibliography-only.

Stop condition:
Stop after source-status and dependency update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 141

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded formulation-comparison template.

Payload ID: PAY-BACKLOG-141-2026-001
Payload type: PAY-FORM

Target gate:
A recorded route or candidate whose formulation safety is unresolved.

Exact statement or object:
Fill this prompt with exact formulations to compare, such as coefficient K-theory FJC, full FJ, FJCw, FICwF, or finite-index inheritance.

Success criterion:
The formulation status becomes safe, blocked, or irrelevant with exact source labels preserved.

Failure criterion:
The comparison collapses formulation labels without a theorem.

Stop condition:
Stop after formulation ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 142

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded RB-006 non-hyperbolic bridge template.

Payload ID: PAY-BACKLOG-142-2026-001
Payload type: PAY-FJ53-RB006

Target gate:
The WIP / provisional `FJ53` and `RB-006` gate.

Exact statement or object:
Fill this prompt with a genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge, or another subtractive object. Hyperbolic overlap alone is not enough.

Success criterion:
`RB-006` status changes through a non-overlapping bridge or remains demoted with a documented blocker.

Failure criterion:
The prompt repeats the Louder-Wilton hyperbolic-overlap path only.

Stop condition:
Stop after RB-006 ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 143

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded target-pivot comparison template.

Payload ID: PAY-BACKLOG-143-2026-001
Payload type: PAY-GOV

Target gate:
A recorded pivot or all-targets-paused gate.

Exact statement or object:
Fill this prompt with the exact target lanes to compare and the repository objects that may change. Do not select a target without a gate-satisfying object.

Success criterion:
One target is selected with exact payload requirements, or all remain paused.

Failure criterion:
The comparison becomes motivational prose with no ledger effect.

Stop condition:
Stop after target-pivot ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```

## Prompt 144

Status: Template

Completed by:

Commit:

Prompt:

```text
Prepare a bounded reflection or handoff template.

Payload ID: PAY-BACKLOG-144-2026-001
Payload type: PAY-GOV

Target gate:
A recorded cycle-closure or reflection-ready state.

Exact statement or object:
Fill this prompt with the cycle, module span, and handoff ledgers to review. Do not add mathematics.

Success criterion:
The reflection records achieved work, unresolved gates, and the next exact move.

Failure criterion:
The reflection invents results or skips unresolved gates.

Stop condition:
Stop after reflection and ledger update.

Notes:
Template prompt generated for backlog capacity. It is not executable until all placeholders are concretely filled and the payload protocol accepts it.
```


Backlog expansion note: remaining generated templates are intentionally non-executable until concretized.

Backlog expansion note: remaining generated templates are intentionally non-executable until concretized.
Backlog expansion note: file intentionally stops at the 5000-line ceiling.
