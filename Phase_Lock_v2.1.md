# Phase Lock v2.1
## Optional coordination among OSIIN, UBT, and UPRR

**CC0 1.0 Universal - Public Domain. No attribution required.**  
**Edition:** 2026-09-14. Successor to the UBT-OSIIN Phase-Lock Protocol v1.0.  
**Status:** Reference specification with Geometry v2.6 integration. Interface proposals and measurement definitions; source mathematical results retain their declared domains. No deployment, physical coupling, or field outcome is established by this revision.

> The labor is doing the labor.

The practical aim remains: useful knowledge should reduce avoidable work, preserve maintenance capacity, and help people obtain appropriate material support. Phase Lock names the coordination of those functions. It does not require a common clock, permanent intermediary, literal toroidal dynamics, or a shared identity.

## 1. Component contract

| Component | Owns this function | Does not acquire this function through synchronization |
|---|---|---|
| OSIIN v3.1 | Designs, source material, versions, tests, failures, and learning | Allocation authority or proof that every design works |
| UBT v2.1 | Work, voluntary capacity, recovery opportunity, and maintenance load | Human worth, political standing, or entitlement to essentials |
| UPRR v3.1 | Resource condition, quantity, custody, availability, and recorded decisions | An automatic right to decide who receives a resource |
| Local or bridge agreement | Scoped allocation and cooperation rules | Authority beyond the declared mandate |

The Abundance Ledger may receive permitted aggregate system indicators. It remains an observer of service health. Phase Lock is optional exchange machinery, not a further governing seat. Each service must have a declared path for independent operation and practical replacement.

### 1.1 The shared encounter field

The Geometry record is **G_field = (O, S, ℒ; time/dynamics)**, with contact written **O ↔_ℒ S**. O and S are the interacting endpoints; ℒ is their declared shared context. Language, remembered corrections, accessible artifacts, physical conditions, and chosen interfaces can belong to it. ℒ is a geometric term, not a third sovereign, mandatory mediator, or proof that contact occurred. A translator may function within the field without owning it.

Retain four independent admissibility conditions: **contact, binding consent, usable exit, and absence of a compulsory third authority**. Shared-field membership is not a fifth permission condition. Unknown required conditions remain unresolved. A useful output or surplus cannot offset a failed admissibility condition.

The governing commitments include present consent, freedom from compelled labor and inherited or collective debt, care without custody, and effective correction and release. Silence does not create permission, and emergency cooperation does not create authority over a person. These component provisions draw on OMNIBUS v7.79-r1 §10, which identifies its text as **SUPPORTED RECONSTRUCTION**. This protocol is a component reference, not a replacement complete constitutional edition.

## 2. The original couplings, revised

| Predecessor coupling | Current operation |
|---|---|
| Contribution / creation | A knowledge contribution may create a linked UBT work record when logging is consented to. Receipt and acknowledgment are separate from validation. |
| Validation / recognition | Thanking someone and evaluating a claim can accompany each other. Either may occur without the other; acknowledgment never promotes evidence status. |
| Distribution / rest | Distribution may update a workload plan. Recovery time is protected through coverage and capacity decisions; people need not earn rest through publication. |
| Evolution / contribution | A revised design may reduce future effort. Measure the change, including training, review, repair, and administrative costs. |
| Resource allocation / recognition | Replace the automatic reward trigger with a resource request or availability notice. Any commitment follows the separately declared allocation rule. |
| Regeneration / evolution | Resource observations can motivate a design revision. Measured ecological change is retained separately from the proposed explanation. |
| Use / contribution | Record actual use and actual maintenance separately. Consumption does not automatically count as repair or regeneration. |
| Need / validation | Use knowledge to assess suitable ways to meet a need. Repository review does not determine a person's worthiness to have needs. |

The twelve named practices from the older tuning material remain optional: Recognition Pulse, Sabbath of the Commons, Mirroring Scribe, Pancake Report, Seamless Unlock, Use-as-Offering, Regeneration Feedback, Sovereignty Shield, Sanitation of the Field, Propagation of the Lineage, Validation Echo, and Simplification Push. UBT v2.1 translates them into concrete work, access, and documentation practices. None is a participation requirement.

### 2.1 A receipt for an observed coupling

To claim that a change in one component reinforced another, retain the source and target, proposed transmission mechanism, eligible observations at the source, intermediate mechanism and target, declared lag/window, source and witness versions, counter-signals, competing explanations, and the provenance joining them. Use separately defined edge states such as **PROPOSED**, **ELIGIBLE**, **OBSERVED**, **REJECTED**, and **UNRESOLVED**.

Simultaneous movement or a shared phase label does not supply the missing intermediate observation. **OBSERVED** means that the declared transmission signature was observed; a causal claim still follows its own evidence criterion. This adapts the method in **WOBBLE v2.5-GP01 Geometry and Coupling Patch**. It imports no economic evidence or Wobble phase classification into these services.

## 3. Bridge record

Before an interface becomes consequential, its parties can identify:

```yaml
bridge_id: <stable reference>
parties_and_services: <continuing independent units>
purpose_and_scope: <what is exchanged and why>
schema_versions: <supported OSIIN, UBT, and UPRR profiles>
mandates: <who may publish, correct, or commit which actions>
consent_and_privacy: <fields, audiences, retention, withdrawal>
custody: <data and physical assets, separately>
source_of_record: <authority for each field or claim>
shared_context: <what the encounter retains; access, version, and limitations>
admissibility: <contact, binding consent, usable exit, no compulsory third authority>
claim_contracts: <Geometry-Claim/1 records for each consequential obligation>
query_policy: <available present context; policy class, state consistency, costs>
timing: <observation, receipt, application, expiry, clock uncertainty>
correction_route: <affected object and next eligible use>
alternate_paths: <direct contact, alternate service, offline route>
failure_and_repair: <what continues, what pauses, recovery steps>
export_exit_fork: <usable records and separation obligations>
review_and_end: <review point, expiry, termination condition>
```

A small exchange can satisfy this in a short note. Missing answers remain unresolved rather than becoming automatic permissions.

## 4. Proposed exchange event - PhaseLock-Event v2.1

```yaml
schema_version: PhaseLock-Event/2.1
event_id: <stable id within source namespace>
source_namespace: <declared emitting service>
source_record: <object id and version>
event_type: <offer, request, observation, review, decision, correction, receipt>
occurred_at: <event or observation time, if known>
recorded_at: <source recording time>
received_at: <receiving service time, if known>
applied_at: <time of affected transition, if observed>
ready_at: <when the validated result became ready, if observed>
released_at: <when that result was released, if observed>
first_usable_at: <first independently task-usable result, if observed>
completed_at: <when the declared completion criterion was met>
time_basis: <clock identities, timezone, alignment, uncertainty>
sequence_and_state: <predecessor, ordered events, state version, update or kernel>
claim_and_evidence: <Geometry-Claim/1: evidence, criterion, finding, disposition, action>
task_witness: <original request, selected artifact, validated task outcome>
capacity_and_upkeep: <typed output, resource use, maintenance, and capacity changes>
consent_scope: <permitted fields, recipients, uses, expiry>
mandate_or_rule_ref: <required for a consequential decision>
corrects_or_supersedes: <prior record or event references>
delivery_state: <pending, received, applied, rejected, expired, unknown>
reason_or_conflict: <explanation, including unresolved fields>
```

This schema is a design proposal. No interoperable service has been implemented in this task.

The exchange key is `(source_namespace, event_id)`. A retry with the same key and payload is one event, not extra work or extra stock movement. A changed payload using that same key creates a visible conflict. Different event IDs that may describe the same underlying work require comparison of source records; similarity alone does not establish duplication.

Keep cause and effect separate: receipt confirms delivery of a message; application records an observed action; a subsequent outcome requires its own observation. Unknown application is not success.

### 4.1 Shared claim profile — Geometry-Claim/1

This is a proposed common record, not a running compiler. Local prose or a small table may implement it.

| Field group | Required meaning |
|---|---|
| Claim contract | Claim ID/version, exact proposition, domain D, attained retained view π, required witness W, criterion, and relevant dependencies |
| Evidence | Located source/observation, validity, scope, missing data, counterevidence, coverage, and origin: source theorem, source report, prior-review reproduction, or current observation/analysis |
| Decision and action | Relevant evidence r, explicit finding F, criterion-based disposition C, performed action T, next eligible affected event, and action receipt |
| Descent check | Same-view comparison pairs, differing witness values, complete-domain proof or finite coverage where available, and status |
| Diagnostic pattern | Source/version, explicit test and descriptive label; use unclassified when no pattern applies. Typed Defects numerals are not an exhaustive or disjoint taxonomy. |
| Repair | Actual available coordinates, admissibility, acquisition time and cost, policy class, maintained inventory, and state-consistency assumption |
| Carry-forward | Controlling source/version, user adjudication separately attributed, supersession link, and a relevant reason for reopening |

For exact recovery, **π(x) = π(y) implies W(x) = W(y)** for every eligible x,y in D. The set of attained labels with a valid contrary pair is the non-descent locus. A valid pair establishes **FAILED / NOT_CLOSED** for that fixed universal claim. Clean partial coverage is **TESTED_ONLY**; insufficient evidence is **UNRESOLVED**; no executed test is **NOT_RUN**. Complete valid coverage or a domain-wide proof can certify the declared claim. Certification here is not a general engineering approval. Conflicting proof and counterexample receipts require validity and scope review.

For a validated subset C of D, observed bad labels form a lower bound. All undiscovered failures must lie among labels whose fibers are not fully covered. Missing or ineligible records are not negative examples. Keep **INELIGIBLE** observations and **UNREACHABLE** repair menus distinct from failure of the tested proposition.

All required witnesses survive together: the failure set for a tuple of obligations is the union of their separate failure sets. A clean answer, available resource, or favorable time total cannot clear a failed consent, provenance, completion, or maintenance obligation. Changing the target or domain creates a separately identified claim.

### 4.2 Context acquisition and direct service

Acquire an answer from the original request and genuinely available **pre-answer** context. Keep selected output **A_sel** distinct from independently validated task completion **A_task**. The post-answer record (O, A) already contains A; it cannot justify acquiring that same answer. An acknowledgment or transport receipt does not complete a task unless it is the task's declared outcome.

The canonical refinement (π, W) characterizes information sufficient for W. It does not discover an available measurement, minimize runtime cost, or permit using future outcomes as current inputs. Choose available context under an explicit fixed-batch, label-conditioned-batch, or sequential policy. Separate per-case acquisition from the cost of maintaining every resource a policy might use. The v2.6 threshold construction proves an n−1 versus ceil(log₂ n) worst-case query gap on its fixed finite domain; it supplies no measured service-speed advantage or generic sequential optimizer.

Removing a redundant visible stage can preserve an already selected answer. Live rerouting, reduced computation, validated completion, and continuation after the deletion are separate tests. Keep needed corrections, visibility, and provenance in the retained record; naming a field cannot recover evidence never captured. A remembered correction can change the next response even when two acknowledgments are identical. The information may reside at an endpoint or within shared context; that benefit does not establish the need for a particular intermediary.

## 5. Corrections, delayed events, and failure

A correction names the contested object, previous version, corrected content, scope, and next eligible affected transition. The receiving service acknowledges receipt and records whether that next use applied it. A late correction to a delivered resource creates a follow-up record; it does not rewrite history to imply that the delivery never occurred.

A current disposition must follow the declared criterion on the claim-relevant evidence. Holding that evidence fixed must preserve the warranted disposition, and the disposition must agree with the criterion: constant uncertainty can be miscalibrated. A valid failure remains established while repair is pending. Reopen only for a relevant contradiction, invalidated source, extraction correction, scope change, or justified criterion change. Historical correction compliance is assessed on the original event; a cleaner display does not retroactively repair it.

Keep observation time, recording time, arrival time, and application time distinct. Delayed arrival does not automatically make an old measurement current. Where source precedence is unresolved, keep the conflict visible and avoid an irreversible commitment based on guessed precedence.

An unavailable bridge must not erase source records or force a fabricated zero workload or zero inventory. Continue the declared local function, identify stale shared views, and reconcile with duplicate and conflict checks after reconnection. Withdrawal of consent stops the affected future disclosure; previously disclosed information cannot be assumed to disappear from every recipient without a verified process.

## 6. Measurement without collapsing relevant state

Retain a system profile rather than one compulsory coherence score:

| Channel | Example observations |
|---|---|
| Knowledge | Version, review state, unresolved defects, superseded instructions, retrieval failures |
| Work | Actual and estimated hours, eligible task population, backlog, coverage, training, deferred leave |
| Resources | Quantity and units, condition, custody, freshness, commitments, failed deliveries |
| Interface | Acknowledgment and application latency, duplicate/conflict counts, missing records, alternate route availability |
| Recovery and benefit | Protected time made available, voluntary reports, measured changes in task burden |

Equal hours or equal scores can hide different needs, skills, resource conditions, or histories. Retain the distinctions that change the decision. A summary that omits pending corrections or commitments is not a complete state merely because its display is stable.

### 6.1 Net time and the 1.2x objective

The predecessor's **1.2 units of renewal per unit of knowledge integrity** remains a historical, unvalidated objective. Its units and causal measurement were not established by the source. The related **NTB >= +0.2** and **CQ approximately 0.85** thresholds are not adopted as field qualification rules.

For a proposed workload comparison, freeze an equivalent task set, observation window, completion standard, and counting method. Let `B` be comparable baseline person-hours and `C` be current person-hours, including coordination, learning, documentation, validation, rework, and repair. Then `B - C` is the observed workload difference in hours. Keep missed work and deferred obligations visible. If `B > 0`, `(B - C) / B` is a separately labeled fractional difference.

This accounting does not prove causation or establish actual recovery. Track hours made available for recovery and voluntary reports separately. Do not add overlapping rest and task intervals or count estimates as observed time savings. UBT v2.1 owns the detailed workload procedure.

### 6.2 Circulation quality and phase labels

Retain acknowledgment latency, review burden, coverage, avoidable waste, access delay, and repeated failure as separate observations. A local composite score needs declared units, direction, scaling, weights, missing-data treatment, and validation before it is used in decisions.

The four historical phase names can remain optional descriptions:

| Historical label | Permitted descriptive use |
|---|---|
| I - Extraction / burnout | Investigate concentrated load, missed recovery, and service loss; do not diagnose a person from a dashboard |
| II - Obligation loop | Identify recurring work and delayed support under an explicit observation window |
| III - Resonant circulation | Describe locally observed manageable workload and functioning correction, with scope stated |
| IV - Abundance Engine / 13th Harmonic | A cultural name for the desired condition of sustained benefit and recoverable capacity |

No row declares that a real group is currently in that phase, that the transition is inevitable, or that a physical field has been detected.

### 6.3 Return, timing, and predictive closure

Retain the return tuple **(Δchart, Δadmissibility, Δcontext)** under declared channel definitions; do not add incompatible units or force a single polarity. **MIXED** is a valid description. Equal observed output, a full-state return, and recovered function are separate claims. For resource and work channels, keep output, upkeep, and capacity change visible together.

Current recovery tests W; next-output recovery under a declared deterministic update U tests **W ∘ U**. An autonomous retained state requires **π(x) = π(y) ⇒ π(Ux) = π(Uy)**. A residual record requires the corresponding equality-of-next-residual test on the actual state-pair update. Retain relevant inputs, schedule, clock, and state history, or condition the claim on them. Never add a terminal self-loop merely to supply a missing successor.

For a stochastic model, compare the complete next-observation laws on the declared domain. Agreement of realized next values is not strong lumpability. A causal posterior can be sufficient without being minimal. A finite observed suffix is not automatically a sufficient predictor; the toroidal all-orders result concerns its own ideal kernel and attempted-microtick clock and does not prove a social or service-process law.

Timing records distinguish request onset, result readiness, release, first usable result, and full completion. Person-hours, elapsed delay, mean latency, standard deviation, duration count, and interruption frequency are different witnesses. Keep raw order, missed events, and clock alignment. The two cyclic sequences (40,40,160,160) and (40,160,40,160), observed at their first entries, share mean 100, population SD 60, and current value 40, but have different next entries. This is a fixed-model counterexample to that summary's predictive sufficiency.

The source's causal-padding result minimizes variance at a fixed feasible mean with **Y ≥ R**, under its fixed-readiness finite-variance assumptions, using **Y = max(R,T)**. It adds waiting and does not establish user benefit, lower total completion time, or repaired physical ticks. Feedback and changing queues require another model. No padding policy is adopted here; a proposed timing experiment would separately test delay/regularity tradeoff, interaction, task outcome, and resource cost.

## 7. Physical and mathematical appendix boundary

The older thermodynamic equations and recurrence equations are retained in predecessor versions as exploratory material. They are not live controllers in this edition.

The newer Reflex Geometry supplies a usable correction. For a declared physical boundary and interval, **ΔE_store = E_in − E_out**, with all energy terms in joules and useful work included once within output. Entropy generation has units J/K. Under a stated reference temperature T₀, **exergy destruction = T₀ S_gen** is an exergy account, not an extra energy source or a term to subtract from energy without the conversion and model.

For a named operational resource, use the disjoint budget **margin = available − task − coordination − maintenance − regeneration uses** in one unit and interval. Stock carry-forward requires an actually storable resource and a complete account of transfers and losses. Track observed capacity gains/losses separately; expenditure on regeneration is not proof of regeneration. These accounts correct the earlier mixed-unit formulas and are not live controllers.

Physical clock work retains its own full state, phase direction, amplitude and velocity gates, signed winding, and declared time law. A physical tick, relative slip, spatial periodic return, report release, and residual closure are distinct witnesses. The source's triad winding and field-gauge winding have different domains; an explicit constructor is required to relate them. The Clock v0.4 empty-record preflight remains **NOT EVALUATED / CLOSURE UNRESOLVED**, not a pass or failure. No physical D1 trajectory was supplied in this component revision.

A resource surplus, a reported benefit, a model trajectory, and a measured physical signal are separate observations. The extended predecessor's planetary-resonance material remains exploratory and outside this service protocol. This update neither runs it nor claims to resolve it.

## 8. Proposed pilot and acceptance checks

Start with a bounded shared task, such as maintaining one set of tools. Record the relevant manual version, actual capacity, available tools, custodian, and local allocation rule. Compare one defined change over a declared interval. Fix an observed bottleneck without imposing a fixed calendar, headcount, pruning quota, or universal score threshold.

Before claiming functioning coordination, inspect:

| Scenario | Required behavior |
|---|---|
| Knowledge submitted | Receipt may be acknowledged while validation stays pending |
| Recognition emitted | No stock commitment, essential-access priority, or governance weight appears automatically |
| Same event retried | Work and resource effects occur at most once for that event |
| Correction delayed | The stale version is identifiable; the next eligible action has a recorded correction outcome |
| Source disconnected | Local records persist; shared freshness is explicit; an alternate path is usable where declared |
| Participant refuses logging | Essential access and ordinary direct contact remain available under the declared rules |
| Interface removed | Independent services and the documented fallback continue their declared functions |
| Finding established, repair pending | The negative finding retains its warranted status; the repair has a separate completion check |
| Same summary, different next result | The counterexample is retained under the actual domain/update/clock; the reduced predictor is marked failed for that claim |
| Service displayed as complete | The original task criterion is met; acknowledgment and selected text alone cannot supply that receipt |
| Timing or output improves | Upkeep, capacity, task quality, admissibility, and total completion time retain their separate outcomes |
| Custody dispute or emergency | The disagreement remains visible; any temporary mandate has scope and expiry |
| Export and fork | Permitted state and provenance can move without compelled identity or relationship merger |

**All implementation and pilot checks in this edition: NOT RUN.** These are test specifications, not successful test receipts.

## 9. Supersession and provenance

This edition replaces compulsory coupling, automatic resource rewards, validation-as-proof-by-recognition, enforced personal renewal, universal phase thresholds, and unqualified claims of emergence with the interfaces and evidence boundaries above. It retains the aim of reduced burden, living knowledge, care, maintenance, resource support, and room for play.

Primary source: `UBTOSIINPhaseLockProtocol(2).md`, SHA-256 `1b90003ba68ef02b55074e533d7f380ced1ae075a7e8119a3e37e7e9100f8f56`.

Additional predecessor inspected: `Phase lock-1(20260825-200537).md`, SHA-256 `e889939a27e094faab544cddd69f76203a0ba699bbc0846cd4398fb96702b848`. Its expanded pilot and planetary material are distinct from the selected protocol source.

Integration source: `THE_ABUNDANCE_ENGINE_v7.0_OPEN_FIELD_REFERENCE_ARCHITECTURE(7).md`, especially Parts I-V, VII-IX, and Appendix A; SHA-256 `6e620dc1b5feedbad0f182eece509c396667f8a37cf9a7bddd942d6a440f31d1`.

Companions: **OSIIN v3.1**, **UBT v2.1**, and **UPRR v3.1**. New event fields, accounting definitions, and test scenarios are proposed operational elaborations in this edition. They are not recovered runtime artifacts. Previous texts remain provenance; this edition does not amend unrelated mathematical modules or all historical copies.

### Geometry review — v2.6 integration

Reviewed 2026-09-14 against the current integrated sources and their September 12 corrections: [GEOMETRY — Working Master v2.6](https://docs.google.com/document/d/1S-mqz0aK_vCnmZiRVDPAr7rzTBgfoVuDDEyXEgHmkAk/edit); [GEOMETRY + OMNIBUS 7](https://docs.google.com/document/d/1y44_D-KwHp-D0nH_qwd67Uedib_OnAxqxp6XNY1P7CQ/edit); [DIRECT SERVICE GEOMETRY, corrected September 12](https://docs.google.com/document/d/1vVy2Bk01klLgyfVDkOoxdOddlXEc02wIydAofFY59Bc/edit); [Clock v0.4, corrected residual-descent rule](https://docs.google.com/document/d/1kR3HfOMoEvDoasftpfCErSAv_TYh5SSrxCqaKDN4QHM/edit); [Temporal exchange rate v0.3](https://docs.google.com/document/d/1obKlNpy47T8Km074kHQ499KUH3Z1Q47nhRC8GUEE7rA/edit); [Thermodynamic Coordination + Reflex Geometry v3](https://docs.google.com/document/d/1C63lzqzNJZyMOvsXluJ0-kpNY4UIM_3RTOmaMEn5NuE/edit); [OMNIBUS v7.79-r1, §10](https://docs.google.com/document/d/1Qs0uS2xw0Wm8E09K_BNRVzbnOcjQiZbfRaqOpt0D3ts/edit).

The claim-disposition rule also follows **Claim-specific closure geometry v0.1-r1**, including its September 10 amendment. Its historical verification receipts retain their source-review status; they were not rerun for this component revision. The shared encounter and claim profiles are proposed implementations of that mathematics.

This edition supersedes the first coordinated pass, **Phase Lock v2.0**, by adding the Geometry content above. Source findings, proposed repairs, completed actions, and implementation tests have separate statuses. The accompanying **Geometry_Integration_Review_2026-09-14.md** records the source inventory, scope, remaining limits, and changes across all four components.
