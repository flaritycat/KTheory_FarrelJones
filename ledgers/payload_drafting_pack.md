# Payload Drafting Pack

## Status

Active drafting aid.

## Ledger type

Payload drafting forms / Intake helper / Governance guardrail

## Purpose

This drafting pack gives copy-ready forms for future human-supplied payloads.

These forms are drafts only. They are not accepted payloads, do not satisfy
`OBL-C6-003`, do not instantiate `FJ101`, and do not create a numbered
module.

## Non-acceptance warning

Bracketed placeholders are not accepted payloads.

A copied form remains a draft until every placeholder is replaced with a
concrete object and the resulting payload passes
`ledgers/payload_intake_protocol.md`.

Writing `Accepted? Yes` inside an incomplete form does not make the payload
accepted.

## Common required fields

Every future payload must supply:

- payload ID;
- date recorded;
- payload type;
- target gate;
- concrete object;
- exact statement or object;
- APA citation requirement if an external source is used;
- source-status label;
- hypotheses and formulation level;
- repository objects changed;
- success criterion;
- failure criterion;
- stop condition;
- accepted status;
- follow-up module or artifact if accepted.

## Form 1. PAY-T001-CAND

Use this form only for a concrete torsion-free one-relator candidate or
candidate family.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-T001-CAND-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-T001-CAND

Target gate:
[Name the active gate, e.g. OQ-126 / OBL-C6-003 plus any T-001 gate such as
OBL-T001-013 or OBL-T001-023.]

Concrete object:
[Give one concrete group presentation or one explicitly defined family.
Do not write a placeholder such as "give a group here".]

Exact statement or object:
[State the bounded candidate-intake audit to run: relator status,
torsion-free status, known-route overlap, prior-art risk, route-output target,
or obstruction status.]

APA citation if external source is used:
[Required for every external source. If none is used, write:
"No external source supplied; add APA citations if the audit uses sources."]

Source-status label:
[For example: no source checked yet; source located but hypotheses to verify;
or internal repository audit only.]

Hypotheses and formulation level:
[Torsion-free one-relator candidate audit only. State whether this concerns
simplified ring-coefficient FJ, coefficient FJC, full FJ, FJCw, FICwF,
weaker K0, or governance only. Do not collapse formulations.]

Repository objects changed:
[List exact files, such as ledgers/t001_candidate_inventory.md,
ledgers/t001_residual.md, OPEN_QUESTIONS.md, ledgers/theorem_dependencies.md,
README.md, PROJECT_CHARTER.md.]

Success criterion:
[Repository-visible candidate classification: candidate-admissible,
already routed, blocked, calibration-only, or obstruction record.]

Failure criterion:
[State when to stop without promotion, e.g. missing proper-power status,
missing torsion-free data, already routed without new information, or no
route-output target.]

Stop condition:
[Stop after candidate-admissibility audit and ledger update. Do not start a
broad one-relator survey.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 2. PAY-T001-BRIDGE

Use this form for an exact bridge lemma, computation, or source theorem that
would change a `T-001` candidate, residual bucket, or route-output status.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-T001-BRIDGE-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-T001-BRIDGE

Target gate:
[Name OQ-126 / OBL-C6-003 plus the exact T-001 gate affected.]

Concrete object:
[Name the bridge lemma, computation, source theorem, candidate row, residual
bucket, or route-output object.]

Exact statement or object:
[State exactly what must be checked or computed and which project status could
change.]

APA citation if external source is used:
[Required in APA style for each external source. If no source is used, write:
"No external source used."]

Source-status label:
[external source located; exact theorem and hypotheses to be checked /
source-verified claim candidate / internal computation only.]

Hypotheses and formulation level:
[State exact hypotheses and formulation boundary: simplified FJ, coefficient
FJC, full FJ, FJCw, FICwF, weaker K0, or another explicit level.]

Repository objects changed:
[List exact module, candidate ledger, residual ledger, theorem-dependency row,
source-status ledger, bibliography, README, charter, or notation ledger.]

Success criterion:
[What bridge, computation, source-hypothesis verification, or obstruction
will count as success.]

Failure criterion:
[Missing hypotheses, formulation mismatch, prior-art overlap, non-subtractive
route, or no project-object change.]

Stop condition:
[Stop after the bridge audit / computation / source-hypothesis check and
ledger update. Do not start a broad source survey.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 3. PAY-T001-BLOCKER

Use this form for a known-route, prior-art, or obstruction audit tied to a
specific `T-001` candidate or residual row.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-T001-BLOCKER-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-T001-BLOCKER

Target gate:
[Name OQ-126 / OBL-C6-003 plus the exact T-001 blocker gate affected.]

Concrete object:
[Name the candidate row, residual bucket, route, theorem, prior-art object,
or obstruction to audit.]

Exact statement or object:
[State whether the task is a known-route audit, prior-art blocker audit,
obstruction record, or no-live-candidate status check.]

APA citation if external source is used:
[Required in APA style for each external source. If no source is used, write:
"No external source used."]

Source-status label:
[external source may be located; exact theorem and hypotheses to be checked /
internal repository audit only.]

Hypotheses and formulation level:
[State the candidate or route formulation level and the non-claim boundary.
Do not claim full T-001, coefficient FJC, FJCw, FICwF, or residual
subtraction unless exact route hypotheses are checked.]

Repository objects changed:
[List exact candidate ledger, residual ledger, route ledger, open-question
ledger, theorem-dependency ledger, README, and charter entries.]

Success criterion:
[Classify the row as already routed, blocked by missing route hypotheses,
prior-art-blocked, or still live.]

Failure criterion:
[No exact candidate/theorem/blocker is named, or the task becomes a broad
survey.]

Stop condition:
[Stop after blocker audit and ledger update. Do not compute unrelated data or
create the next module.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 4. PAY-FORMULATION

Use this form for formulation-safety comparisons involving coefficient FJC,
full Farrell--Jones, `FJCw`, `FICwF`, weaker \(K_0\), finite-index passage,
or another exact formulation boundary.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-FORMULATION-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-FORMULATION

Target gate:
[Name OQ-126 / OBL-C6-003 plus the formulation-safety gate affected.]

Concrete object:
[Name the candidate route, source theorem, formulation comparison, finite
index bridge, or ledger row needing clarification.]

Exact statement or object:
[State the exact formulation comparison or safety audit to perform.]

APA citation if external source is used:
[Required in APA style for each external source. If no source is used, write:
"No external source used."]

Source-status label:
[source located / source-verified comparison candidate / internal repository
formulation audit only.]

Hypotheses and formulation level:
[State every formulation involved and the exact non-identification boundary.
For example: FJCw is not automatically coefficient FJC or full FJ.]

Repository objects changed:
[List exact notation, inheritance, theorem-dependency, candidate, residual,
source-status, README, or charter files.]

Success criterion:
[A formulation label is clarified, a route is declared formulation-safe,
formulation-irrelevant, blocked, or in need of exact source verification.]

Failure criterion:
[Comparison lacks exact hypotheses, active route object, source theorem, or
changed repository object.]

Stop condition:
[Stop after formulation audit and ledger update. Do not promote a route unless
the exact formulation bridge is checked.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 5. PAY-ARTIN

Use this form only for a named Artin graph, graph family, subclass, source
theorem, or bridge object satisfying the Artin reactivation gate.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-ARTIN-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-ARTIN

Target gate:
OBL-ARTIN-004 and [any additional affected open question or obligation].

Concrete object:
[Name a finite Artin graph, graph family, subclass, source theorem, bridge
object, or formulation comparison. "All Artin groups" alone is not enough.]

Exact statement or object:
[State the bounded Artin reactivation task: graph/subclass audit, Wu
clique-reduction test, source-hypothesis check, formulation comparison, or
obstruction record.]

APA citation if external source is used:
[Required in APA style for every external source. If no source is used, write:
"No external source used."]

Source-status label:
[external source located; exact theorem and hypotheses to be checked /
internal Artin inventory audit only.]

Hypotheses and formulation level:
[State graph labels, finiteness, FC/spherical/even/clique hypotheses, source
route, and formulation label: FJCw, FICwF, full FJ, coefficient FJC, or other.]

Repository objects changed:
[List exact Artin inventory, open group classes ledger, open questions,
source-status, bibliography, README, charter, or theorem-dependency files.]

Success criterion:
[Named Artin row becomes covered under exact hypotheses, remains blocked,
becomes a candidate row, or records an obstruction.]

Failure criterion:
[No named graph/subclass/source theorem/bridge object is supplied, or the task
becomes a broad Artin source survey.]

Stop condition:
[Stop after Artin reactivation audit, source check, bridge test, or
obstruction record. Do not claim all Artin groups.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 6. PAY-FND-SOURCE

Use this form for a foundational source payload. For protocol compatibility,
reviewers may map this drafting type to `PAY-FND` unless the accepted payload
explicitly introduces `PAY-FND-SOURCE` as a new governance spelling.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-FND-SOURCE-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-FND-SOURCE

Target gate:
FND-QUEUE-PAUSE-001 and [any affected open question or theorem-dependency
gate].

Concrete object:
[Name an exact foundational source theorem, definition, lemma, proposition,
construction, or convention.]

Exact statement or object:
[State the exact source-hypothesis or convention check and the current
proof/candidate/route/theorem-dependency need.]

APA citation if external source is used:
[Required in APA style for every external source.]

Source-status label:
[external source located; exact theorem and hypotheses to be checked /
partially read / verified / no-promotion.]

Hypotheses and formulation level:
[State the exact foundational convention or formulation level affected.
Distinguish simplified ring-coefficient FJ, coefficient FJC, full FJ, FJCw,
FICwF, weaker K0, and governance-only status as needed.]

Repository objects changed:
[List exact notation ledger, theorem-dependency ledger, source-status ledger,
bibliography, module, README, charter, or open-question entries.]

Success criterion:
[An exact source statement is verified, partially verified, no-promoted, or
recorded as blocked with a project-object effect.]

Failure criterion:
[The item is broad background, bibliography-only, or has no current
application-tethered project need.]

Stop condition:
[Stop after foundational source-hypothesis audit and ledger update. Do not
start a broad foundations survey.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; do not use a fake FJ101 path.]
```

## Form 7. PAY-GOV

Use this form for internal project-governance work only.

Bracketed placeholders are not accepted payloads.

```text
Payload ID: [PAY-GOV-...]
Date recorded: [YYYY-MM-DD]
Payload type: PAY-GOV

Target gate:
[Name the open question, proof obligation, pause marker, handoff gate, prompt
queue, or protocol object.]

Concrete object:
[Name the exact governance object: ledger audit, reflection, prompt queue,
handoff table, checklist, README/charter alignment, or status reconciliation.]

Exact statement or object:
[State the bounded governance task and what repository state it will clarify.]

APA citation if external source is used:
No external source used, unless this governance task explicitly requires a
source-status audit.

Source-status label:
internal repository audit only, unless otherwise specified.

Hypotheses and formulation level:
Governance only. This payload does not add a candidate, source theorem,
bridge, computation, route claim, proof attempt, target reactivation,
residual subtraction, or mathematical theorem claim.

Repository objects changed:
[List exact governance ledgers, prompt files, README, charter, AGENTS, open
questions, notation ledger, scope ledger, or theorem-dependency files.]

Success criterion:
[Repository-visible status, checklist, handoff, queue, or ledger alignment is
completed.]

Failure criterion:
[The task creates mathematical content, accepts a template as a payload,
creates FJ101, or changes mathematical scope.]

Stop condition:
[Stop after governance update. Do not instantiate a numbered module unless a
separate concrete accepted payload satisfies OBL-C6-003.]

Accepted status:
Draft only until reviewed under ledgers/payload_intake_protocol.md.

Follow-up module or artifact if accepted:
[Exact path or "none"; governance artifacts may be non-module ledgers.]
```

## Final pre-submission check

Before submitting any form above as a payload, answer yes to every item:

1. Every bracketed placeholder has been replaced.
2. The concrete object is a real candidate, source, bridge, computation,
   blocker, formulation comparison, or governance object.
3. The payload names a current gate.
4. The payload names exact repository objects changed.
5. The payload has success, failure, and stop conditions.
6. External sources, if used, have APA citation requirements and
   source-status labels.
7. The payload preserves formulation distinctions.
8. The payload does not create `FJ101` unless it is the concrete accepted
   payload that satisfies `OBL-C6-003`.

If any answer is no, the form remains a draft.
