# Harvesting and resuming

Keep discovery, reading, capture and interpretation distinct. A method can finish its processing while its sources remain incomplete. Say which condition holds.

## Establish the denominator

Define the issue, archive slices, dates, providers or document sets, exclusions, and intended coverage claim. Respect an explicitly supplied snapshot as the read target; obtain authority before refreshing it. Reuse existing source registers and corpus homes.

Retain four distinct layers:

| Layer | What can be established |
|---|---|
| Archive inventory | Records known to exist in a stated store or snapshot, including known missing portions. |
| Candidate discovery | Results of actual queries, structural filters, cross-links, vocabulary variants or semantic retrieval. |
| Screening | Each candidate's inclusion, exclusion with reason, deferral, or unavailability. |
| Included-span coverage | What was actually read, captured, integrated and left unresolved within the chosen reading set. |

A complete keyword result enumerates matching records, not all relevant thinking. Record query text, tool and relevant version/configuration, date, archive binding, result identities, truncation/ranking limits, and embedding coverage when applicable. Keep the discovery record compact enough to rerun or widen. Distinguish reproducible discovery evidence from historical counts copied out of an older report.

Use related vocabulary, references and source context to challenge keyword omissions. If a claim requires examining every record in a finite inventory for relevance, perform that screening or narrow the claim. Reading every discovered candidate does not establish discovery recall.

## Retain the minimum evidence

Use the corpus's existing format. A table, prose register, database or native journal can all serve; the roles below need no mandated JSONL schema.

**Discovery record:** scope, actual searches and results, screening dispositions, known inventory/discovery limits. Group each harvest's queries and result membership in one identifiable section or manifest so its coverage claim has a findable boundary.

**Unit register:** source identity and exact version; bounded span or whole-source locator; read/capture/integration state; evidence and destination references; substantive residuals or exclusions with reasons; missing branches/attachments; processing date and relevant method binding. A coherent source may be one unit. Split long or mixed conversations into spans so a destination list cannot conceal skipped sections.

**Issue evidence:** quoted or clearly paraphrased passages with speaker, commitment where consequential, source date and resolvable locator, retaining their argumentative context. Add short lineage notes for differing formulations over time. Detailed proposition records earn their place only where attribution or interpretation requires that grain.

These roles may share a document. Keep source date separate from processing date. Use message IDs or other stable anchors where available. For line/round locators, bind and retain the exact projection or version; a hash alone is not a retrievable source. If a locator changes, preserve the historical binding and add a mapping rather than silently substituting new text.

An optional compact unit entry:

> Source S17, revision v3, messages m40–m56; read full; capture complete; integrated into “Kinds,” evidence §4. Preserved the claim, supporting contrast and counterexample. Objection at m52 remains unresolved in §4. Scheduling aside excluded as out of scope. No known missing portion. Processed 20261020T140000 using the recorded extraction method.

“Complete” is earned by retained work, not by the presence of a destination link. A contribution may be a whole argument spanning many turns. Preserve its claim, reasons, examples and objections together or explicitly account for substantive residuals. Read context needed to interpret speaker interaction; a user-turn-only extraction can miss proposals, qualifications and reactions.

## Make interruption cheap

Before expensive work, establish the durable run home, exact input/method bindings, unit identities and outside-readable progress in the project's existing mechanism. Record completed, active, remaining and failed work, the last durable result and known limits. Add resource/throughput information when the run warrants it.

Default to a source or bounded span per checkpoint. A small batch is valid when its membership and maximum interruption loss are declared in the register before work starts, and that loss is cheap. Persist source bindings, evidence, destinations/residuals and progress before marking the unit complete or moving beyond the batch. A completion marker without its evidence is invalid. Use native atomic/checkpoint semantics where available; otherwise write the evidence first and commit the completion marker last so interruption leaves the unit pending.

On resumption, inspect retained evidence and bindings rather than trusting a narrative handoff. Reuse completed units with matching inputs and methods. Reconcile changed inputs explicitly and reopen only affected work; preserve earlier versions. Resume the pending span or batch without replaying admitted work. For delegated/model work, use a route that retains completed rounds and supports usable continuation; record transformations when recovery supplies retained context to a fresh session.

## Integrate and review

Compare issue formulations across time, then develop the account in its existing home. Preserve uncertainty or competing readings where sources cannot settle them. A change of audience or immediate priority does not itself retire a constituent idea.

Review source to destination for omitted substance, and destination to source for unsupported attribution, confidence or commitment. Choose review breadth from the promised claim: an exhaustive material-capture claim requires reviewing every included span; sampling supports only a sampled quality statement. Reopen any “complete” span whose missing contribution changes the argument. Check whether an omitted example constrained the claim's meaning; preserve that constraint in the prose. Keep unanswered objections open, and attribute any newly proposed answer as development rather than silently supplying it as recovered thought.

Mechanically check the concrete record where possible:

- Every cited source/span resolves to the bound version.
- Every inventory/candidate item has the disposition appropriate to the claimed census or selection.
- Every included unit is complete, partial, pending, failed or unavailable as evidenced; totals reconcile against the retained membership.
- Completed units have evidence and destinations or deliberate exclusions; deferred/unavailable portions remain visible.
- Navigation reaches current primary homes without accidental duplicate accounts.

These checks establish structure and accounting. Faithfulness, relevance and argumentative completeness still require reading and judgment; keep that proof limit explicit.

## Finish the bounded pass honestly

Process the entire included set or report the remainder. If the scope changes, retain the prior boundary and name the revised one; deferral is not completion. Saturation can inform whether to broaden exploratory discovery, but cannot justify stopping an included-set harvest early. No new topic labels does not imply no new reasons or meanings.

Give one compact coverage statement: inventory/snapshot; discovery and screening method; candidate and included counts; inventory remainder not screened for relevance; full/partial/pending units; evidence/integration destinations; unresolved substantive residuals; unavailable portions; and interpretation-review scope. Distinguish “processed all accessible units” from “all source material available” and “all relevant thought captured.” Claim only the layer supported by the record.
