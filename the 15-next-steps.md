# The 15 Next Steps

## Purpose

This file records fifteen self-contained prompts that can be executed without
asking the user for a missing candidate, source, bridge, computation, or
blocker.

These prompts do not bypass `C6-PAUSE-001`. They are non-numbered governance,
consistency, and handoff tasks. They must not create `FJ101`, must not claim a
new Farrell--Jones result, and must not treat a template prompt as an accepted
payload.

Each prompt is written so that a future Codex run can execute it directly from
the repository root.

## Global execution rules for all prompts

- Work inside the `KTheory_FarrelJones` repository.
- Inspect the relevant files before editing.
- Use only repository-internal information unless the prompt explicitly says
  otherwise.
- Do not browse, cite, or import an external source unless the prompt
  explicitly authorizes source work.
- Do not create a numbered module unless the prompt explicitly supplies an
  accepted payload that satisfies `ledgers/payload_intake_protocol.md`.
- Do not create `modules/cycle_006/FJ101*` from any prompt in this file.
- Do not promote any theorem claim, residual subtraction, route closure, or
  novelty claim.
- If a checked item is ambiguous, record it as unresolved instead of promoting
  it.
- Run lightweight validation after edits: `git status --short --branch`, a
  targeted `rg` check for the changed labels, and a changed-file list.
- Commit with the project commit protocol if the prompt changes files.

## Prompt 001. Cycle-006 Pause Integrity Audit

Status: Completed

Completed by:

- `ledgers/cycle_006_pause_integrity_audit.md`

```text
Run a non-numbered cycle-006 pause integrity audit.

Goal:
Verify that the repository consistently records the current state as
`C6-PAUSE-001`, with no selected `FJ101` module and no executable open prompt
in `next_prompts.md`.

Required files to inspect first:
- `README.md`
- `PROJECT_CHARTER.md`
- `OPEN_QUESTIONS.md`
- `SCOPE_LEDGER.md`
- `NOTATION_LEDGER.md`
- `AGENTS.md`
- `next_prompts.md`
- `ledgers/payload_intake_protocol.md`
- `ledgers/cycle_006_entry_gate.md`
- `ledgers/cycle_006_payload_decision.md`

Repository object changed:
- Create or update `ledgers/cycle_006_pause_integrity_audit.md`.
- Update `README.md` and `PROJECT_CHARTER.md` only if they contradict the
  current pause state.

Required audit checks:
- `C6-PAUSE-001` is recorded.
- `OBL-C6-003` is recorded as blocking `FJ101` without a concrete accepted
  payload.
- `OQ-126` is present and open unless the repository already records a later
  accepted payload.
- `next_prompts.md` has no `Status: Open` entry unless it is a concrete
  accepted payload.
- Prompt 015 and Prompt 025 onward are not treated as executable templates.
- No `modules/cycle_006/FJ101*` file exists unless a later accepted payload
  already created it.

Success criterion:
Record a short integrity audit with "consistent", "inconsistent", or
"superseded by later accepted payload" status.

Failure criterion:
The audit tries to fill a payload placeholder, starts mathematical work, or
creates a numbered module.

Stop condition:
Stop after the integrity audit and any strictly necessary consistency edits.
```

## Prompt 002. Prompt Queue Status Normalization

Status: Completed

Completed by:

- `ledgers/cycle_006_prompt_queue_audit.md`
- `next_prompts.md`

```text
Run a prompt-queue status normalization pass.

Goal:
Make `next_prompts.md` harder to misuse by ensuring that template prompts are
clearly marked as non-executable and that completed prompts have completed
metadata where the repository already supplies it.

Required files to inspect first:
- `next_prompts.md`
- `ledgers/payload_intake_protocol.md`
- `ledgers/cycle_006_payload_decision.md`
- `PROJECT_CHARTER.md`

Repository object changed:
- `next_prompts.md`
- Optional: `ledgers/cycle_006_prompt_queue_audit.md`

Required checks:
- Count `Status: Open`, `Status: Template`, and `Status: Completed`.
- Confirm the first non-completed prompt.
- Add a short warning near the top of `next_prompts.md` if absent:
  template prompts are not executable until all placeholders are concretely
  filled and accepted under the payload protocol.
- Do not convert a template into `Status: Open`.
- Do not invent a candidate, source, bridge, computation, or blocker.

Success criterion:
The queue clearly distinguishes completed prompts, templates, and executable
prompts.

Failure criterion:
The task changes mathematical status, creates `FJ101`, or silently promotes a
template.

Stop condition:
Stop after queue-label and warning normalization.
```

## Prompt 003. Payload Protocol Usability Audit

Status: Completed

Completed by:

- `ledgers/payload_intake_protocol.md`
- `ledgers/payload_submission_checklist.md`

```text
Run a usability audit of `ledgers/payload_intake_protocol.md`.

Goal:
Clarify what a future accepted payload must contain, without supplying a new
payload and without creating a numbered module.

Required files to inspect first:
- `ledgers/payload_intake_protocol.md`
- `ledgers/cycle_006_payload_decision.md`
- `next_prompts.md`
- `AGENTS.md`

Repository object changed:
- `ledgers/payload_intake_protocol.md`
- Optional: create `ledgers/payload_submission_checklist.md`

Required work:
- Add or refine a checklist for accepted payloads:
  payload ID, payload type, target gate, concrete object, exact statement,
  formulation level, repository objects changed, success criterion, failure
  criterion, stop condition, and citation requirement if an external source is
  used.
- Add explicit rejection examples for placeholder-only submissions.
- Add explicit acceptance tests for repository-internal governance payloads.
- Preserve all historical accepted and rejected payload records.

Success criterion:
The protocol can be applied by a future run without asking the user for
missing fields.

Failure criterion:
The audit accepts a new payload, creates `FJ101`, or changes mathematical
claims.

Stop condition:
Stop after protocol/checklist clarification.
```

## Prompt 004. Open Question and Obligation Integrity Audit

Status: Completed

Completed by:

- `ledgers/open_question_obligation_integrity_audit.md`
- `OPEN_QUESTIONS.md`
- `ledgers/theorem_dependencies.md`
- `AGENTS.md`

```text
Run an internal open-question and proof-obligation integrity audit.

Goal:
Check that `OQ-126` and `OBL-C6-003` are aligned with the cycle-006 pause, and
that earlier cycle-005/cycle-006 obligations are not simultaneously open and
completed in contradictory ways.

Required files to inspect first:
- `OPEN_QUESTIONS.md`
- `ledgers/theorem_dependencies.md`
- `ledgers/cycle_005_handoff.md`
- `ledgers/cycle_006_entry_gate.md`
- `ledgers/cycle_006_payload_decision.md`
- `PROJECT_CHARTER.md`

Repository object changed:
- `OPEN_QUESTIONS.md`
- `ledgers/theorem_dependencies.md`
- Optional: create `ledgers/open_question_obligation_integrity_audit.md`

Required work:
- List the active cycle-006 open questions and proof obligations.
- Check whether each has a source file or ledger entry.
- Fix only clear status contradictions.
- If an item is unclear, add an unresolved note rather than resolving it.

Success criterion:
Active open questions and obligations have a single coherent status.

Failure criterion:
The audit resolves a mathematical question without proof/source verification
or creates a new target/module.

Stop condition:
Stop after internal status reconciliation.
```

## Prompt 005. T-001 Candidate Inventory Readiness Audit

Status: Completed

Completed by:

- `ledgers/t001_candidate_readiness_audit.md`
- `ledgers/t001_candidate_inventory.md`

```text
Run a readiness audit of the T-001 candidate inventory.

Goal:
Determine whether the current inventory has any row that can be acted on
without a new payload. Do not add a new candidate.

Required files to inspect first:
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `OPEN_QUESTIONS.md`
- `PROJECT_CHARTER.md`
- `README.md`

Repository object changed:
- `ledgers/t001_candidate_inventory.md`
- Optional: create `ledgers/t001_candidate_readiness_audit.md`

Required work:
- Classify every recorded candidate row as routed, blocked, calibration-only,
  placeholder/template, or live.
- For blocked rows, state the exact missing object needed to reopen the row.
- Preserve prior closures from `FJ88`, `FJ96`, and `FJ100`.
- Do not search for or invent a new candidate.

Success criterion:
The inventory clearly states whether any existing row is actionable without a
new payload.

Failure criterion:
The audit reopens a routed row without a recorded payload or starts a broad
one-relator survey.

Stop condition:
Stop after row classification and blocker notes.
```

## Prompt 006. T-001 Residual Bucket Consistency Audit

Status: Completed

Completed by:
- `ledgers/t001_residual_consistency_audit.md`
- `ledgers/t001_residual.md`

```text
Run a residual-bucket consistency audit for T-001.

Goal:
Check that the residual-bucket ledger agrees with the candidate inventory,
cycle-005 closure, post-100 review, and cycle-006 pause.

Required files to inspect first:
- `ledgers/t001_residual.md`
- `ledgers/t001_candidate_inventory.md`
- `reflections/post_100_module_strategic_review.md`
- `reflections/cycle_005_reflection.md`
- `ledgers/cycle_006_payload_decision.md`

Repository object changed:
- `ledgers/t001_residual.md`
- Optional: create `ledgers/t001_residual_consistency_audit.md`

Required work:
- Check RB-001 through RB-008 if present.
- Confirm that RB-006 remains demoted / provisionally non-subtractive unless a
  non-hyperbolic bridge has been recorded.
- Confirm that no bucket is marked subtractive merely because it overlaps a
  known hyperbolic, CAT(0), virtually solvable, finite-index/FJCw, or
  free-by-cyclic route.
- Do not add sources.

Success criterion:
The residual ledger states which buckets are closed, inactive, demoted,
blocked, or waiting for payload.

Failure criterion:
The audit claims T-001 is solved or records a new residual subtraction.

Stop condition:
Stop after residual-status reconciliation.
```

## Prompt 007. CAND-T001-005 Handoff Consolidation

Status: Completed

Completed by:
- `ledgers/cand_t001_005_handoff.md`
- `ledgers/t001_candidate_inventory.md`

```text
Run a handoff consolidation for CAND-T001-005.

Goal:
Collect the current repository status of `CAND-T001-005` into one internal
handoff entry without changing its mathematical status.

Required files to inspect first:
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`
- `modules/cycle_005/FJ91*`
- `modules/cycle_005/FJ92*`
- `modules/cycle_005/FJ93*`
- `modules/cycle_005/FJ94*`
- `modules/cycle_005/FJ95*`
- `modules/cycle_005/FJ96*`

Repository object changed:
- `ledgers/t001_candidate_inventory.md`
- Optional: create `ledgers/cand_t001_005_handoff.md`

Required work:
- Summarize what was checked for CAND-T001-005.
- State its current route / blocker / inactive status exactly as recorded.
- State what payload would be needed to reopen it.
- Do not claim a new theorem or route.

Success criterion:
Future runs can read one handoff entry and understand why CAND-T001-005 is
not currently a live non-routed row.

Failure criterion:
The task reopens CAND-T001-005 without a payload or repeats source summaries.

Stop condition:
Stop after handoff consolidation.
```

## Prompt 008. Source Status and Bibliography Consistency Audit

Status: Completed

Completed by:
- `ledgers/source_bibliography_consistency_audit.md`
- `BIBLIOGRAPHY.md`
- `ledgers/source_status.md`

```text
Run an internal source-status and bibliography consistency audit.

Goal:
Check whether sources already recorded in `BIBLIOGRAPHY.md` have matching
status entries in `ledgers/source_status.md`, without consulting new external
sources.

Required files to inspect first:
- `BIBLIOGRAPHY.md`
- `ledgers/source_status.md`
- `ledgers/theorem_dependencies.md`
- `README.md`

Repository object changed:
- `BIBLIOGRAPHY.md`
- `ledgers/source_status.md`
- Optional: create `ledgers/source_bibliography_consistency_audit.md`

Required work:
- Compare source identifiers, citations, and status labels.
- Add missing internal cross-references where the source is already recorded
  elsewhere in the repo.
- Do not add new bibliographic entries from memory.
- Do not promote "located" sources to "verified" without exact theorem text
  already present in the repository.

Success criterion:
Bibliography and source-status records agree on source status and project use.

Failure criterion:
The audit imports or upgrades external facts without source verification.

Stop condition:
Stop after internal consistency fixes.
```

## Prompt 009. Theorem Dependency Active/Inactive Map Audit

Status: Completed

Completed by:
- `ledgers/theorem_dependency_status_audit.md`
- `ledgers/theorem_dependencies.md`

```text
Run a theorem-dependency active/inactive map audit.

Goal:
Clarify which theorem dependencies are active, inactive, blocked, source-only,
or formulation-safety items after cycle 005 and the cycle-006 pause.

Required files to inspect first:
- `ledgers/theorem_dependencies.md`
- `OPEN_QUESTIONS.md`
- `ledgers/t001_residual.md`
- `ledgers/open_group_classes.md`
- `PROJECT_CHARTER.md`

Repository object changed:
- `ledgers/theorem_dependencies.md`
- Optional: create `ledgers/theorem_dependency_status_audit.md`

Required work:
- Identify active dependencies tied to an open obligation.
- Identify dependencies that are recorded for background only.
- Identify dependencies blocked by missing source text, formulation mismatch,
  or no current candidate.
- Do not mark a dependency as established unless `ESTABLISHED_RESULTS.md` and
  a module already justify it.

Success criterion:
The theorem-dependency ledger has clear active/inactive/blocker labels for
current project use.

Failure criterion:
The audit promotes unverified theorem statements.

Stop condition:
Stop after dependency-status clarification.
```

## Prompt 010. README and Project Charter Current-State Alignment

Status: Completed

Completed by:
- `README.md`
- `PROJECT_CHARTER.md`

```text
Run a current-state alignment pass for `README.md` and `PROJECT_CHARTER.md`.

Goal:
Ensure the main public summary and the charter both state the same current
project position after `FJ100`, the post-100 review, and cycle-006 pause.

Required files to inspect first:
- `README.md`
- `PROJECT_CHARTER.md`
- `reflections/post_100_module_strategic_review.md`
- `ledgers/cycle_006_entry_gate.md`
- `ledgers/cycle_006_payload_decision.md`
- `next_prompts.md`

Repository object changed:
- `README.md`
- `PROJECT_CHARTER.md`

Required work:
- Confirm current cycle and target state.
- Confirm no `FJ101` is selected.
- Confirm future work requires a concrete accepted payload.
- Confirm template prompts are not executable.
- Do not summarize every historical module again unless needed to fix a
  contradiction.

Success criterion:
The README and charter have one coherent current-state handoff.

Failure criterion:
The update implies mathematical progress, theorem promotion, or a selected
new module.

Stop condition:
Stop after alignment edits.
```

## Prompt 011. AGENTS Instruction Alignment

Status: Completed

Completed by:
- `AGENTS.md`

```text
Run an AGENTS instruction alignment pass.

Goal:
Make sure `AGENTS.md` gives future Codex runs the current project rules after
the cycle-006 pause.

Required files to inspect first:
- `AGENTS.md`
- `ledgers/payload_intake_protocol.md`
- `ledgers/cycle_006_payload_decision.md`
- `PROJECT_CHARTER.md`
- `next_prompts.md`

Repository object changed:
- `AGENTS.md`

Required work:
- Confirm AGENTS says not to overclaim T-001.
- Confirm AGENTS says not to execute template prompts.
- Confirm AGENTS says not to create `FJ101` without a concrete accepted
  payload.
- Confirm AGENTS preserves formulation distinctions: full FJ, coefficient FJC,
  FJCw, FICwF, and weaker K0-level statements.
- Add missing instructions only if absent.

Success criterion:
AGENTS gives future runs enough local instructions to avoid the repeated
template-execution loop.

Failure criterion:
The edit weakens mathematical caution or bypasses payload discipline.

Stop condition:
Stop after instruction alignment.
```

## Prompt 012. Foundational Queue Pause Integrity Audit

Status: Completed

Completed by:
- `ledgers/foundational_queue_pause_audit.md`

```text
Run a foundational queue pause integrity audit.

Goal:
Check that the foundational source queue remains paused unless an exact,
application-tethered source payload is already recorded.

Required files to inspect first:
- `references/papers_to_read.md`
- `ledgers/theorem_dependencies.md`
- `ledgers/source_status.md`
- `OPEN_QUESTIONS.md`
- `PROJECT_CHARTER.md`
- `ledgers/cycle_006_payload_decision.md`

Repository object changed:
- Optional: create `ledgers/foundational_queue_pause_audit.md`
- Update existing ledgers only to fix clear contradictions.

Required work:
- Identify the latest recorded foundational queue status.
- Check whether any source item is already exact, application-tethered, and
  gate-ready.
- If none is gate-ready, record that no foundational source work should start
  without a new payload.
- Do not fetch external papers or verify theorem text.

Success criterion:
The foundational queue status is clear and does not invite passive source
  accumulation.

Failure criterion:
The audit starts a broad source survey or promotes source status.

Stop condition:
Stop after foundational queue status check.
```

## Prompt 013. Artin Lane Reactivation Requirement Audit

Status: Completed

Completed by:
- `ledgers/artin_reactivation_requirement_audit.md`

```text
Run an Artin lane reactivation requirement audit.

Goal:
Clarify what exact payload would be required to reactivate the Artin branch,
without selecting a graph, family, source theorem, or new Artin module.

Required files to inspect first:
- `ledgers/artin_subclass_gap_inventory.md`
- `ledgers/open_group_classes.md`
- `OPEN_QUESTIONS.md`
- `PROJECT_CHARTER.md`
- `ledgers/cycle_005_handoff.md`
- `ledgers/cycle_006_payload_decision.md`

Repository object changed:
- Optional: create `ledgers/artin_reactivation_requirement_audit.md`
- Update `ledgers/artin_subclass_gap_inventory.md` only for clear status
  contradictions.

Required work:
- Record current Artin status.
- List the exact fields needed for a future Artin reactivation payload.
- Confirm no active Artin lane exists without such a payload.
- Do not introduce a new Artin subgroup class from memory.

Success criterion:
Future runs know precisely why the Artin lane is paused and what would reopen
it.

Failure criterion:
The audit starts an Artin source survey or invents a subclass.

Stop condition:
Stop after Artin reactivation requirements are recorded.
```

## Prompt 014. No-New-Module Validation Audit

Status: Ready

```text
Run a no-new-module validation audit.

Goal:
Verify that the repository has not accidentally created `FJ101` or another
cycle-006 numbered module while the cycle-006 pause is active.

Required files to inspect first:
- `modules/`
- `next_prompts.md`
- `ledgers/cycle_006_payload_decision.md`
- `PROJECT_CHARTER.md`
- `README.md`

Repository object changed:
- Optional: create `ledgers/no_new_module_validation_audit.md`
- Update status files only if an accidental contradiction is found.

Required work:
- List `modules/cycle_006` if present.
- Search for `FJ101`.
- Search for claims that `FJ101` is selected or completed.
- Search for `Status: Open` in `next_prompts.md`.
- Record whether the module tree agrees with `C6-PAUSE-001`.

Success criterion:
The repository has a recorded validation result for the no-new-module state.

Failure criterion:
The audit creates a new module or changes mathematical scope.

Stop condition:
Stop after validation and any contradiction note.
```

## Prompt 015. Self-Contained Payload Drafting Pack

Status: Ready

```text
Create a self-contained payload drafting pack for future human-supplied
payloads.

Goal:
Give future users exact copy-ready forms for accepted payloads, while clearly
marking them as forms rather than accepted payloads.

Required files to inspect first:
- `ledgers/payload_intake_protocol.md`
- `next_prompts.md`
- `AGENTS.md`
- `ledgers/cycle_006_payload_decision.md`

Repository object changed:
- Create or update `ledgers/payload_drafting_pack.md`.
- Optional: add one cross-reference from `README.md` to the drafting pack.

Required work:
- Include copy-ready forms for:
  - `PAY-T001-CAND`
  - `PAY-T001-BRIDGE`
  - `PAY-T001-BLOCKER`
  - `PAY-FORMULATION`
  - `PAY-ARTIN`
  - `PAY-FND-SOURCE`
  - `PAY-GOV`
- Each form must state that bracketed placeholders are not accepted payloads.
- Each form must include required fields:
  payload ID, payload type, target gate, concrete object, exact statement,
  APA citation requirement if an external source is used, source-status label,
  formulation level, repository objects changed, success criterion, failure
  criterion, stop condition, and accepted status.
- Do not fill any form with a fake candidate or fake source.
- Do not mark any drafted form as accepted.

Success criterion:
The project has a practical drafting pack that can prevent future placeholder
submissions from entering the execution queue.

Failure criterion:
The task records a drafted form as an accepted payload or creates `FJ101`.

Stop condition:
Stop after drafting-pack creation and optional README cross-reference.
```
