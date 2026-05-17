# Payload Submission Checklist

## Status

Active project checklist.

## Ledger type

Payload intake helper / Governance checklist

## Purpose

This checklist is a practical companion to `ledgers/payload_intake_protocol.md`.
It does not accept any payload by itself, does not create a numbered module,
and does not change any mathematical claim.

Use it before treating a user request, prompt, or ledger entry as an accepted
payload.

## Required fields

A future payload must provide all of the following fields before it can
instantiate a numbered module or a bounded governance artifact:

| Field | Required content |
| --- | --- |
| Payload ID | Stable ID, not a bracketed placeholder. |
| Date recorded | Calendar date of intake. |
| Payload type | One of the protocol types in `ledgers/payload_intake_protocol.md`, unless a governance payload explicitly introduces a new type. |
| Target gate | Existing open question, proof obligation, pause marker, handoff gate, or named target gate. |
| Concrete object | Actual candidate, source theorem, bridge lemma, computation, blocker, formulation comparison, governance object, or repository object. |
| Exact statement or object | Bounded task statement precise enough to execute without asking for missing mathematical content. |
| APA citation if external source is used | Required for every external source; if no source is used, state "No external source used." |
| Source-status label | Required for external sources; for internal audits, record "internal repository audit only." |
| Hypotheses and formulation level | Exact formulation boundary, including whether the payload is governance-only. |
| Repository object changed | Specific file or files expected to change. |
| Success criterion | Repository-visible completion condition. |
| Failure criterion | Condition requiring no-promotion, blocker, rejection, or pause. |
| Stop condition | Explicit boundary preventing broad survey drift. |
| Accepted? | Must state accepted scope; acceptance is only valid if the required fields above are complete. |
| Follow-up module or artifact if accepted | Exact path or artifact type, or "none" for no-module governance work. |

## Acceptance decision tests

Before accepting, answer these questions:

1. Does the payload name a concrete object rather than a topic?
2. Does it identify a current repository gate it will change?
3. Does it name the repository files to update?
4. Does it state formulation level and non-claim boundaries?
5. Does it include APA citation requirements for any external source?
6. Does it have success, failure, and stop conditions?
7. Can the task be executed without asking the user for a missing candidate,
   source, bridge, computation, or blocker?
8. Does it avoid creating `FJ101` while `OBL-C6-003` is active, unless it is
   the concrete accepted payload that explicitly satisfies `OBL-C6-003`?

If any answer is "no", the request is not an accepted payload.

## Placeholder-only rejection examples

Reject or leave as draft:

- `Candidate: [give one concrete torsion-free one-relator group here]`;
- `Source: [paper to be supplied]`;
- `Continue`;
- `Continue with the next best payload`;
- `Execute payload object` when no payload object is recorded;
- `Accepted? Yes` attached to a form whose concrete object is still blank;
- a copied template prompt from `next_prompts.md` with unfilled placeholders.

## Governance-only acceptance examples

A repository-internal governance payload may be acceptable when it says:

- which existing ledger, reflection, queue, handoff, open question, or proof
  obligation it audits;
- which exact files it will update;
- that it adds no candidate, source theorem, bridge, computation, theorem
  claim, route claim, target reactivation, or residual subtraction;
- that it stops after status reconciliation or handoff clarification.

Governance-only acceptance does not authorize a mathematical numbered module
unless the payload explicitly supplies and satisfies the relevant module gate.

## Current cycle-006 warning

The project is currently in `C6-PAUSE-001`. `OBL-C6-003` blocks `FJ101` until
a concrete accepted payload is recorded. Template prompts are not accepted
payloads.

