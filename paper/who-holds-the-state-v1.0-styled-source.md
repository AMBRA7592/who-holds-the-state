---
title: "Who Holds the State?"
subtitle: "A Framework for Testing Claims After Support Ends"
author: "Amadeus Brandes"
affiliation: "Independent Researcher, Germany"
date: "Working Paper --- May 2026"
version: "v1.0"
publicationdate: "2026-05-26"
companion: "State Claim Registry v0.1"
keywords: "custody, state claims, support relations, withdrawal horizon, holder assignment, repricing, composite-claim verification, AI compute commitments, wealth measurement, gene therapy pricing"
jelcodes: "D80 (Information, Knowledge, and Uncertainty), G14 (Information and Market Efficiency), G32 (Financial Risk and Risk Management), I11 (Analysis of Health Care Markets), D31 (Personal Income and Wealth Distribution)"
ssrnclassification: "Social Science Research Network---Financial Economics / Risk Management / Health Economics"
abstract: |
  Many institutional claims are measured while the support relation that produces them is still
  present, then priced or governed as if the state had transferred. A daily medication can be honest
  maintenance and dishonest cure on the same evidence. A compute commitment can report committed
  demand while the buyer's funding loops back to the seller. A household can hold visible net worth
  that survives only while credit, insurance, and benefits remain intact. A gene therapy can be priced
  as durable correction at horizons that have not yet been reached. In each case, the visible state
  may be real. The question is whether the visible state is the settled state. This paper introduces
  the State Claim Record—a compact instrument for testing such claims by naming the claim class,
  inventorying the support relation, specifying withdrawal at the claim's implied horizon, measuring
  what survives, assigning the holder of continuity, and comparing that holder to what the claim
  promised. A claim matches custody when the promised continuity is supported by the holder,
  state-path, and evidence standing; otherwise it is mismatched, opaque, or unprobed. The framework is
  descriptive before critical: it does not punish dependence, but it exposes dependence sold as
  transfer, durability, independence, or ownership. Three applications—AI compute commitments,
  household wealth as custody, and gene therapy durability—demonstrate the record's reach across
  capital, demography, and clinical pricing. A companion launch registry (State Claim Registry v0.1)
  applies the record across twelve cases from distant domains.
---

# The Problem: State Under Support

Many institutional claims are measured while the support that produces them is still present, then priced or governed as if the state had transferred. This places the problem near work on metric distortion, audit effects, and Goodhart variants, but the object here is not the metric alone; it is the custody of the claimed state after support ends (Goodhart 1975; Strathern 1997; Manheim and Garrabrant 2018).

An AI assistant is said to have saved five hours, but the claim is measured before handback, revision, and integration. A compute contract is reported as committed demand, but the buyer’s ability to pay may depend on the seller’s capital returning through the buyer. A household is said to hold wealth, but the balance may survive only while credit, insurance, benefits, employment, or family support remain intact.

A therapy is priced as durable correction, but the endpoint may be supported by monitoring, rescue care, payer tolerance, or a horizon that has not yet arrived. A synthetic voice is sold as exclusive, but its reproducibility may not be held by the buyer. A pension is reported as funded, but the apparent state may depend on demographic, subsidy, legal-priority, or return assumptions that have not faced the relevant stress.

In each case, the visible state may be real. The assistant may have produced useful text. The contract may have been signed. The household may have positive net worth. The therapy may have changed the endpoint. The voice may have been licensed. The pension may satisfy its reporting standard. The framework developed here does not begin by denying the visible state.

It asks whether the visible state is the settled state.

A state claim is any claim that some condition has been achieved, transferred, retained, secured, made durable, made independent, made exclusive, made firm, or made capable. State claims appear in product pages, financial statements, clinical claims, policy metrics, procurement files, household balance sheets, scientific reports, and regulatory disclosures. They are often treated as settled at the moment of measurement. The metric appears, the contract is signed, the endpoint improves, the balance is recorded, the asset is delivered, the label is granted.

But many state claims are measured under support. A dose is still being taken. A vendor is still operating. A platform is still hosting. A donor is still funding. A lender is still extending credit. A model is still available. A subsidy is still active. A care bundle is still present. At the moment of measurement, the claimed state and the support relation coincide. That coincidence can make a claim look settled even when continuity has not yet been assigned.

The central question is therefore not only whether the state appeared. It is who or what holds continuity when support ends.

**State is decided at withdrawal, not during use.**

This does not mean that temporary, mediated, supported, or dependent states are failures. A daily medication can be honest maintenance. A hosted service can be honest access. A subscription can be honest presence. A donor-backed program can be honest patronage. A vendor-operated system can be honest mediation. The failure appears when a dependent state is sold as transferred, a maintenance relation as a cure, a support relation as independence, a surface effect as substrate change, a backstopped commitment as independent demand, or an untested horizon as durability.

The distinction matters because state claims are not merely described. They are priced, financed, regulated, insured, ranked, reported, trusted, and acted on. If the wrong holder is assumed, price follows the wrong state. A buyer pays for transfer when they received access. An investor values independent demand when the demand is seller-held. A program counts wealth where the household holds only a fragile balance. A payer funds durability before durability has been reached. A regulator governs origin while the relevant issue is custody.

This paper introduces a compact instrument for testing such claims. It does not ask whether support is bad. It asks what kind of support produced the visible state, what happens when that support is withdrawn at the claim’s implied horizon, who or what holds continuity afterward, and whether that custody matches what was promised.

The output is a State Claim Record. Each record begins with the exact claim, names the claim class, inventories the support relation, specifies withdrawal and horizon, measures what survives, assigns the holder and state-path, grades the evidence standing, produces a verdict, and names the remedy or repricing consequence. The record is not a certificate. It can be produced unilaterally, contested by evidence, and adopted by institutions that choose to bind it.

The argument is simple: state claims are measured under support, priced as transfer, settled by holder assignment, and repriced by the gap.

# The Instrument: State Claim Records

State claims are often measured while the support relation that produces them is still present, then priced or governed as if the state had transferred. The custody framework tests such claims by naming the claim class, inventorying the support relation, specifying withdrawal at the claim’s implied horizon, measuring what survives, assigning the holder of continuity, and comparing that assignment to what was promised. A claim matches custody when the promised continuity is supported by the holder, state-path, and evidence standing. Otherwise it is mismatched, opaque, or unprobed. The framework does not punish dependence; it exposes dependence sold as transfer, durability, independence, or ownership.

The framework’s unit is the **state claim**: a claim that some condition has been achieved, transferred, retained, secured, made durable, made independent, made exclusive, made firm, or made capable. The state claim, not the product, institution, sector, or domain, is what the framework tests. A single product may make several state claims. A therapy may make a maintenance claim for one endpoint and a durable claim for another. A software service may transfer data while renting capability. A financing arrangement may create committed demand in one respect and seller-supported demand in another. The framework therefore begins by forcing the claim into specific form.

The output is a **State Claim Record**. The record does not ask whether the visible state appeared. In many cases, it did. The customer looked younger under the film, the assistant produced a draft, the patient improved while dosed, the compute contract created reported backlog, the pension appeared funded under stated assumptions. The record asks a different question: what support relation produced the visible state, what happens when that relation is withdrawn at the claim’s implied horizon, and who or what holds continuity afterward?

The launch registry applying this record format appears in *State Claim Registry v0.1*.

Table: Core State Claim Record

| Field | Meaning |
|---|---|
| `Q` | Exact state claim being tested. |
| `κ` | Claim class: presence, access, maintenance, transfer, durable, terminal, exclusive, independent, or firm. |
| `Σ → Wt/t` | Support relation identified, then withdrawn under a specified scenario and claim-implied horizon. |
| `V → R(t)` | Visible state under support, then retained state after withdrawal at horizon `t`. |
| `H / S / E` | Holder of continuity, state-path under withdrawal, and evidence standing. |
| `Verdict` | `MATCH`, `MISMATCH`, `OPAQUE`, `UNPROBED`, or `INAPPLICABLE`. |
| `Π` | Remedy or repricing consequence: disclose, relabel, discount, escrow, holdback, term-limit, TCO reprice, covenant, reserve, exit right, or exclusion. |

`Q` is the exact state claim being tested. It should be stated in the language a buyer, reader, regulator, patient, investor, or counterparty would reasonably encounter. “This AI is useful” is too vague; “this AI assistant saved five hours of usable work” is specific enough to test. “This product improves health” is too vague; “this intervention produces durable correction after cessation” is specific enough to test. When claim sources conflict, the most prominent state-bearing claim controls unless a narrower limitation was equally prominent at the point of decision. Sources are read in declining priority: headline or primary sales claim, contractual promise, pricing basis, disclosure language, fine print, and post-hoc clarification.

`κ` is the claim class. It states what kind of continuity the claim promises.

- **Presence.** Promises a state during the experience or use.
- **Access.** Promises capability while the relationship remains active.
- **Maintenance.** Promises continued benefit through repeated intervention.
- **Transfer.** Promises that capability or state migrates to the buyer or substrate.
- **Durable.** Promises persistence after withdrawal for the represented horizon.
- **Terminal.** Promises that the need for the intervention ends.
- **Exclusive.** Promises that the state cannot be freely reproduced by others.
- **Independent.** Promises that the state does not depend on continuing seller, operator, donor, or platform support.
- **Firm.** Promises survival through a specified stress window.

A claim may contain more than one class. The record should name the class or classes that make the claim valuable. This is also where the framework avoids moralism: dependence is not a defect when the claim class admits dependence. A maintenance claim may depend on cadence and still match. An access claim may depend on a vendor and still match. The mismatch appears when dependence is sold as transfer, durability, independence, terminal cure, exclusivity, or firm commitment.

`Σ` is the support-relation inventory. Before a withdrawal scenario is chosen, the record identifies the relations that produce the visible state: dose, schedule, clinician, vendor, model, platform, account, memory store, financing loop, donor, subsidy, workforce, supply allocation, operating context, legal recognition, or other support. This inventory prevents cherry-picking. A seller should not be allowed to choose a harmless withdrawal scenario, and an analyst should not be allowed to choose a dramatic one without showing that the withdrawn relation was part of the support set. The relevant withdrawal is selected from `Σ` according to the continuity that `κ` implies.

`Wt/t` is the withdrawal scenario and horizon. `Wt` names what is withdrawn; `t` names the horizon at which survival is assessed.

**The horizon is not chosen by the analyst for convenience. It is implied by the claim.**

A presence claim is tested during use. An access claim is tested while the relationship remains active. A transfer claim is tested after handoff. A durable claim is tested after withdrawal for the represented durability period. A terminal claim is tested after cessation of intervention. A firm claim is tested during the relevant stress or event window. An exclusive claim is tested during the relevant reproduction window. The holder is always `H(Wt)`: holder under this withdrawal scenario and horizon, not holder in the abstract.

`V` is the visible state under support. It is the seller’s or institution’s peak claim measured while the support relation is still present. The framework usually does not need to dispute `V`. It accepts the visible peak as the denominator and asks what survives withdrawal. This is why the method can be applied without first winning an argument about whether the headline metric was sincere.

`R(t)` is the retained state after withdrawal at horizon `t`, expressed when possible as a fraction of `V`. Accepting `V` does not mean accepting an undefined denominator. The record must state the baseline, measurement function, unit, horizon, and direction of improvement wherever these are needed to compute retention. If an assistant is claimed to save five hours, `R(t)` concerns usable work retained at handback, not mere draft volume. If a therapy is claimed to be durable, `R(t)` concerns the endpoint at the claim-implied horizon after cessation or loss of support. If compute demand is claimed to be committed, `R(t)` concerns demand that survives withdrawal of seller support, substitute financing, or related-party reinforcement. Sometimes `R(t)` cannot be computed numerically; the record may still assign a holder and state-path if documentary or structural evidence is sufficient. When neither measurement nor inference is available, the evidence standing changes; the claim does not silently pass.

`H` is the holder of continuity under the specified withdrawal scenario. This is the record’s central output. `V` tells us what appeared under support. `R(t)` tells us what survived. `S` tells us the path the state followed. `H` tells us who or what carried continuity. The holder vocabulary is compact: **SELF** (`USER` or `SUBSTRATE`), **MEDIATOR** (`OPERATOR` or `VENDOR`), **SURFACE** (`FILM` or `COATING`), **CADENCE** (`SCHEDULE` or `ROUTINE`), **COMPLEMENT** (`BUNDLE` or `SUPPLY`), **SETTING** (`CONTEXT` or `ENVIRONMENT`), **PATRON** (`DONOR` or `THIRD-PARTY`), and **NONE**. Multiple holders may be present, but the record names the binding holder under the specified `Wt/t`: the holder whose withdrawal would change the verdict.

`S` is the state-path: what the state does under withdrawal. The core paths are **HELD/OWNED**, where the state persists after withdrawal at or near the promised level; **TUNED/TAPER**, where part of the state persists in modified form; **RENTED**, where the state ends with the relation; **DECAY**, where it fades on a measurable horizon; **DRIFTS**, where it moves toward an alternative state rather than simply vanishing; **REBOUND**, where the substrate ends worse than before; **CLAWED**, where the state is actively reversed or restitution is required; **HOSTAGE**, where the substrate cannot exit without losing the state or suffering penalty; **NULL/INERT**, where the state never existed; and **RESIDUAL**, where an altered remainder persists after the primary claimed state ends. These are paths, not moral grades.

`E` is evidence standing. It states how strongly the record supports the `H` and `S` assignment. The basic order is:

`UNPROBED < OPAQUE < INFERRED < DOCUMENTED < PROBED < REPLICATED`.

A claim is **unprobed** when no withdrawal or equivalent stress has been observed despite the claim requiring one. It is **opaque** when necessary support relations, funding sources, technical dependencies, or evidence are withheld. It is **inferred** when the assignment follows from public structure but lacks direct documentary confirmation. It is **documented** when contracts, budgets, logs, disclosures, filings, specifications, or maintenance records support the assignment. It is **probed** when withdrawal or an equivalent stress event has been observed. It is **replicated** when independent observers obtain the same assignment. Evidence standing does not describe the state. It describes the standing of the classification.

The verdict function composes these fields.

**A claim matches custody if and only if `κ` is supported by `H(Wt)`, `S`, and `E` at the claim-implied horizon.**

A claim is a **MATCH** when the promised continuity class is supported by the assigned holder, the observed or inferred state-path, and adequate evidence standing. A daily medication sold as maintenance can match even if the state decays after cessation, because the claim did not promise terminal cure.

A claim is a **MISMATCH** when the promised class exceeds the custody shown by `H(Wt)`, `S`, and `E`. A rented state sold as durable, a maintenance relation sold as terminal cure, a vendor-held capability sold as transferred capacity, a donor-supported outcome sold as self-sufficiency, or an open-reproducible asset sold as exclusive produces mismatch if the evidence standing is sufficient.

A claim is **OPAQUE** when the record cannot assign holder or state-path because necessary support relations or evidence are withheld. Opacity is not exoneration. It is an adverse evidence standing.

A claim is **UNPROBED** when the claim requires withdrawal evidence but no withdrawal, stress, handback, cessation, or equivalent event has been observed.

**UNPROBED $\neq$ PASS.**

A claim that has never faced the relevant horizon has not shown survival at that horizon.

A claim is **INAPPLICABLE** when the framework should not force a verdict. Inapplicability is a stopping rule, not a failure.

`Π` applies when the verdict is `MISMATCH` or `OPAQUE`, and may apply when `UNPROBED` requires further evidence; `INAPPLICABLE` returns no remedy. `Π` is the remedy or repricing consequence. It is not a punishment. It is the institutional consequence of the gap between promised and held state. Common remedies include **DISCLOSE**, **RELABEL**, **DISCOUNT**, **ESCROW**, **HOLD_BACK**, **TERM_LIMIT**, **TCO_REPRICE**, **COVENANT**, **RESERVE**, **EXIT_RIGHT**, and **EXCLUSION**. A durable claim with decay may require escrow, term limits, or discount. A transfer claim with a vendor holder may require relabeling, TCO repricing, or exit rights. A firm claim that fails its event window may require reserves, covenants, or discount. An opaque claim may require disclosure or exclusion from a category that implies custody.

The ceiling/floor asymmetry is simple. The claim sets the ceiling of promised continuity; observed survival sets the floor of demonstrated continuity. Evidence can confirm, downgrade, or leave a claim unprobed or opaque, but lack of evidence cannot upgrade a claim into a match. Silence is not neutral when the claim itself requires survival.

A State Claim Record can be produced unilaterally from public information. Sellers, institutions, or counterparties may contest the record, but its production does not require their cooperation. The proper form of contestation is a challenge condition: the row states what evidence would revise its holder, state-path, or verdict. This is what distinguishes the framework from a certification regime.

**It does not make the classification legally binding. It makes misclassification legible enough that institutions may choose to bind it.**

```text
Challenge condition:
This row's [H / S / Verdict] classification should be revised
if evidence shows that [R(t) or state-path] remains
[above / below threshold] after [specified support relation]
is withdrawn for [claim-implied horizon], without substitute support.
```

For example:

```text
Challenge condition:
H=VENDOR and Verdict=MISMATCH should be revised if evidence
shows that retained capability remains above the claimed threshold
after vendor access, managed support, and substitute financing
are withdrawn for the claim-implied horizon, without substitute support.
```

## Stopping rules

The framework returns `INAPPLICABLE` rather than forcing a verdict when:

- no separable state claim can be identified;
- no support relation can be specified;
- no meaningful withdrawal scenario exists;
- the state is constitutively relational and does not imply separability from the relation;
- the substrate drifts faster than the measurement window;
- evidence access is structurally unavailable;
- the claim is explicitly transient and priced as transient.

The instrument is therefore narrow by design. It does not classify everything. It classifies state claims whose promised continuity can be compared with custody after withdrawal. Its central question is not whether the visible state appeared, but whether the promised holder of continuity exists at the horizon the claim itself implies.

# Calibration Plate: Same Evidence, Different Claim

The purpose of the calibration plate is to show that the framework does not grade dependence as failure. It grades the mismatch between the claim class and the custody of the state.

Consider a daily medication that reduces a recurring symptom while taken. The evidence is simple. While the patient takes the medication each day, the symptom falls by 60 percent relative to baseline. When dosing stops, the effect fades over ten days and the symptom returns to baseline. There is no rebound beyond baseline, no permanent worsening, and no durable correction after cessation. The same evidence can produce two different verdicts depending on the claim.

## Claim A: maintenance

`Q`: “This medication controls symptom X while taken daily.”

`κ`: Maintenance.

`Σ → Wt/t`: The support relation is daily dosing. The withdrawal scenario is dose cessation. The horizon is the clinically relevant period after cessation, here ten days.

`V → R(t)`: The visible state is a 60 percent symptom reduction while dosed. After withdrawal, the retained effect decays toward zero by the tenth day.

`H / S / E`: The holder is `CADENCE / SCHEDULE`, because the state is carried by repeated dosing. The state-path is `DECAY`, because the effect fades after withdrawal rather than persisting. The evidence standing is `PROBED`, assuming cessation and follow-up were observed.

`Verdict`: `MATCH`.

`Π`: None, or ordinary disclosure. The claim promised maintenance, and the evidence shows maintenance. The state depends on schedule, but the claim class admits dependence. There is no custody mismatch.

## Claim B: terminal cure

`Q`: “This medication cures symptom X.”

`κ`: Terminal.

`Σ → Wt/t`: The support relation is still daily dosing. The withdrawal scenario is still dose cessation. The horizon is still the period after cessation implied by the cure claim.

`V → R(t)`: The visible state is unchanged: a 60 percent symptom reduction while dosed. The retained state is also unchanged: the effect decays toward zero after withdrawal.

`H / S / E`: The holder remains `CADENCE / SCHEDULE`. The state-path remains `DECAY`. The evidence standing remains `PROBED`.

`Verdict`: `MISMATCH`.

`Π`: Relabel, term-limit, discount, or terminal-cure evidence. If the product is a maintenance therapy, it should be sold as maintenance. If it is priced or governed as a cure, the claim exceeds custody. A terminal claim requires the relevant state to persist after the intervention ends. Here, the state does not transfer to the substrate; it is held by the dosing schedule.

The evidence did not change. The drug did not become better or worse. The framework’s verdict changed because the claim changed.

This is the calibration rule: **the same `H`, `S`, and `E` can produce a match or mismatch depending on `κ`.** `DECAY` is not inherently a defect. `SCHEDULE` is not inherently a defect. Dependence is not failure. Dependence sold as cure, transfer, durability, independence, or ownership is the failure the framework names.

# DCT - AI Compute Commitments

The state claim is simple: **“This AI compute capacity is committed demand.”** In public markets, procurement, and infrastructure finance, committed demand is treated as a state. It supports valuation, credit, capacity expansion, and claims about the durability of an AI-infrastructure buildout. The visible state is a booking, backlog, take-or-pay contract, capacity reservation, or long-term compute commitment. The custody question is whether that demand survives withdrawal of the seller’s own support.

`Q`: “This compute commitment represents committed demand.”

`κ`: Firm and independent. The claim is not merely that demand appears while financing support is present. It is that the commitment survives the relevant stress window and does not depend on continuing seller reinforcement.

`Σ`: The support-relation set includes the buyer’s independent budget, seller financing, equity investment, credit support, cloud credits, related-party circularity, capacity prepayments, resale dependence, and substitute capital. The important point is that reported demand can be produced by more than user need. It can be produced by the seller’s capital returning to the seller through the buyer. The problem is adjacent to asymmetric information and transaction-cost structure, but the record’s object is narrower: not whether the transaction is low quality or vertically dependent, but which fraction of demand is held independently after seller support is withdrawn (Akerlof 1970; Williamson 1975).

`Wt/t`: The withdrawal scenario removes seller-linked support: vendor financing, seller equity backstops, related-party credit, circular prepayments, and substitute financing that would not exist without the seller relationship. The horizon is the financing or contract stress window implied by the claim. For backlog and committed-capacity claims, this is not a one-day cancellation test. It is the period over which the buyer must fund the commitment without seller reinforcement.

`V`: The visible state is headline committed demand: the face value of compute bookings, backlog, capacity reservations, or contracted spend under support.

`R(t)`: The retained state is the portion of that demand that remains fundable and enforceable after seller-linked support is withdrawn.

**DCT decomposes the booking per dollar.** The framework does not label the whole commitment clean or tainted; it assigns custody to each fraction of the headline figure.

The independent portion is the part covered by buyer capital or third-party demand that survives without seller reinforcement. The looped or backstopped portion is the part that exists only because seller capital, credit, or dependence sustains it. The key rule is not “seller capital contaminates the whole booking.” That would overstate the case. The sharper test is whether independent capital alone covers the booking. If the buyer has independent committed funding sufficient to cover the booking, seller capital may be irrelevant. This is the `ARM = min(B, I)` precedence rule: independent committed capital is credited first; only the residual gap is assigned to backstop, looped, or seller-supported custody. That rule prevents the framework from treating a passive minority stake as contamination when the buyer’s own capital is sufficient.

`H / S / E`: Where demand survives withdrawal, the holder is `SELF / BUYER` or `COMPLEMENT / OUTSIDE CAPITAL`: the commitment is held by buyer budget, genuine customer need, or independent financing. Where demand depends on vendor financing, credit support, circular prepayment, or seller-linked capital, the holder is `PATRON / VENDOR` or `COMPLEMENT / SELLER-SUPPLIED CAPITAL`. Where the surface buyer appears external but the funding re-converges on the seller one tier deeper, the state-path may be `RENTED`, if demand ends with financing; `DECAY`, if support expiry gradually lowers fundable demand; or `HOSTAGE`, if the commitment remains locked in a circular structure it cannot exit without losing the state. Where funding sources are undisclosed, evidence standing is `OPAQUE`, not presumed clean.

`Verdict`: The claim matches only for the independent demand fraction: the portion of committed demand that remains after seller support is withdrawn. It mismatches where the commitment is priced, financed, or valued as independent demand but is actually held by seller-linked capital. It is opaque where the funding path cannot be traced.

`Π`: The remedy is disclosure, discount, reserve, covenant, or exclusion from independent-demand categories. The repricing object is not the entire booking; it is the unsupported fraction. A commitment with 70 percent independent demand and 30 percent seller-supported demand should not be treated the same as either a clean third-party booking or a wholly circular transaction. DCT converts suspicion into a demand-custody spread.

`Challenge condition`: A `PATRON / VENDOR` or `OPAQUE` classification should be revised if evidence shows that the buyer can fund and sustain the commitment above the claimed threshold after vendor financing, seller credit support, circular prepayments, and substitute seller-linked financing are withdrawn for the claim-implied stress horizon.

`Prediction`: Across large AI-compute commitments, headline backlog will overstate independent demand wherever seller-linked capital is material and not separately disclosed. The measurable output is the **Independent Demand Fraction**: the share of the commitment that survives the withdrawal of seller support. As disclosure improves, commitments with lower independent demand fractions should receive lower valuation, tighter credit treatment, or covenant-heavy recognition relative to headline backlog.

The application shows why the framework is not a fraud screen. Some seller-supported demand may be real strategy, ecosystem financing, or rational capacity formation. The mismatch appears only when seller-held or looped demand is sold as independent committed demand. DCT’s contribution is to make that difference measurable per dollar.

# HOLD BOX - Wealth as Custody

The state claim is familiar: **“This household has built wealth.”** In policy, banking, philanthropy, and household finance, net worth is treated as a state. It is used to compare households, explain resilience, measure inequality, underwrite risk, and assess whether an intervention has created durable capacity. The visible state is an accounting number: assets minus liabilities. HOLD BOX asks whether that state is actually held by the household when the support relations around it are withdrawn.

`Q`: “This household holds $X of wealth.”

`κ`: Durable, independent, and transferable. A bare balance-sheet statement may only be a snapshot. But when net worth is used as evidence of resilience, opportunity, creditworthiness, or intergenerational progress, the claim is stronger: the wealth is assumed to survive stress, remain under household control, and transfer across time.

`Σ`: The support-relation set includes wage continuity, employer benefits, credit access, mortgage terms, insurance, public benefits, family support, informal care networks, legal title, liquidity, tax treatment, neighborhood asset markets, program restrictions, debt covenants, and emergency obligations. The same headline net worth can be held by different relations. A paid-off liquid asset, a subsidized account with withdrawal restrictions, home equity exposed to insurance withdrawal, and an asset offset by family emergency obligations may all appear as wealth, but they do not have the same holder.

`Wt/t`: The withdrawal scenario removes the load-bearing mediator that makes the visible net worth usable: employment shock, benefit withdrawal, credit tightening, insurance loss, subsidy expiration, family-support withdrawal, emergency expense, forced sale, inheritance event, or program exit. The horizon depends on the claim. For resilience, the horizon is the shock window. For opportunity, it is the period over which the asset can be converted into education, housing, relocation, or business formation. For intergenerational wealth, it is the transfer horizon.

`V`: The visible state is headline household net worth: assets minus liabilities under normal support conditions.

`R(t)`: The retained state is the portion of net worth that remains usable, controlled, and transferable after the relevant support relation is withdrawn. HOLD BOX does not reject headline net worth. It decomposes it. Wealth that remains liquid, legally controlled, insurable, and transferable after stress is retained. Wealth that disappears through forced sale, benefit clawback, debt acceleration, medical expense, uninsurability, legal friction, or emergency obligation has lower retained state at the relevant horizon.

`H / S / E`: Where the wealth remains under household control after withdrawal, the holder is `SELF / USER` or `SELF / SUBSTRATE`. Where the state depends on employer benefits, subsidy rules, donor support, lender tolerance, insurance access, or family backstop, the holder may be `PATRON / THIRD-PARTY`, `MEDIATOR / OPERATOR`, `COMPLEMENT / CREDIT`, or `SETTING / MARKET`. Credit functions as a complement when wealth depends on continuing access to it; if access tightens, the visible state can collapse. The state-path may be `HELD` where wealth survives, `DECAY` where assets drain under stress, `CLAWED` where program rules or debt terms reverse the gain, or `HOSTAGE` where the household cannot access the wealth without destroying the condition that made it valuable. Evidence standing may be documented through account rules, lien records, benefit terms, insurance availability, debt schedules, tax records, or observed stress outcomes.

`Verdict`: The claim matches when the wealth is actually held by the household at the claim-implied horizon. It mismatches when headline net worth is treated as durable, independent, or transferable wealth but is actually held by a mediator, patron, setting, or fragile complement.

**Two households can have equal visible net worth and unequal custody.**

One may hold wealth that survives job loss, insurance repricing, or intergenerational transfer. The other may show the same number only while credit remains open, benefits remain intact, family obligations remain quiet, or asset markets remain favorable.

`Π`: The remedy is relabeling, reserve, discount, covenant, disclosure, or redesigned intervention. A wealth-building program should not count gross account balance as durable progress if the balance is restricted, clawable, unusable under stress, or dependent on continuing subsidy. A lender or policy analyst should not treat equal net worth as equal resilience when the holders differ. HOLD BOX reprices wealth claims by retained custody, not by visible balance alone.

`Challenge condition`: A `PATRON`, `MEDIATOR`, `SETTING`, or `COMPLEMENT` holder assignment should be revised if evidence shows that the household retains control, liquidity, legal use, and transferability of the claimed wealth after the specified support relation is withdrawn for the claim-implied shock or transfer horizon, without substitute support.

`Prediction`: Measures that incorporate custody will reorder some households with the same headline net worth. Households with apparently similar balance sheets will show different retained wealth after stress, and interventions that raise visible balances without transferring custody will underperform on resilience, mobility, and intergenerational transfer. The wealth gap is therefore not only a magnitude gap. It is also a custody gap: a gap in who or what holds continuity when support ends.

This application does not deny the importance of headline net worth. It explains why the same number can mean different things. Wealth is not only how much appears in the box. It is who holds the box when the scaffolding is removed.

# Gene Therapy - Durability and Escrow

The state claim is powerful: **“This therapy provides durable correction.”** In gene therapy, durability is not a decorative word. It is often the difference between a high-cost intervention being priced as a temporary treatment, a long-acting therapy, or a one-time correction. The visible state may be an endpoint improvement, biomarker correction, reduced treatment burden, or clinical response after administration. The custody question is whether that state is held by the patient’s substrate after the treatment episode, or by continuing monitoring, rescue care, manufacturer support, payer tolerance, or an untested durability assumption.

`Q`: “This therapy provides durable correction.”

`κ`: Durable, and sometimes terminal. The durable claim promises persistence after the treatment episode for the represented horizon. A terminal claim is stronger: it implies the need for continuing intervention has ended. Not every gene therapy makes a terminal claim. The record should not upgrade “long-lasting” into “cure” unless the claim language, pricing, or governance does so.

`Σ`: The support-relation set includes the biological modification itself, vector or cell persistence, conditioning regimen, immunosuppression, patient selection, manufacturing quality, clinical monitoring, rescue therapy, adverse-event management, payer coverage, manufacturer warranties, registry participation, regulatory recognition, and repeat-dosing eligibility. Some of these are clinical supports; some are institutional supports. A therapy’s visible effect may be produced by the substrate holding the correction, or by a bundle of surrounding supports that keep the effect usable, recognized, and paid for.

`Wt/t`: The withdrawal scenario is the end of the treatment episode plus removal of ordinary supporting scaffolds that are not part of the claimed durable state: no repeat dosing unless the claim includes it, no extraordinary manufacturer rescue, no substitute therapy silently maintaining the endpoint, no payer exception preserving access beyond the represented claim. The horizon is the one implied by the durability claim. A five-year durability claim is tested over five years. A fifteen-year durability claim is tested over fifteen years. The horizon is not chosen by the analyst; the seller’s durability language and pricing choose it.

`V`: The visible state is the observed post-treatment effect under full support: endpoint improvement, biomarker correction, reduced treatment burden, or other stated clinical outcome.

`R(t)`: The retained state is the portion of that effect that remains at the claim-implied horizon after the treatment episode and ordinary support withdrawal. Retention must be measured against the endpoint actually priced or claimed. A surrogate biomarker may support an early record, but it is not automatically equivalent to durable clinical correction unless the claim makes that bridge defensible. Early follow-up can document a promising state; it cannot, by itself, prove a fifteen-year state.

`H / S / E`: If the correction persists in edited cells, durable expression, or a stable biological equilibrium, the holder is `SELF / SUBSTRATE`. If the state depends on repeated monitoring, rescue therapy, payer exception, manufacturer program, or a continuing care bundle, the holder may be `CADENCE / ROUTINE`, `PATRON / MANUFACTURER`, `PATRON / PAYER`, or `COMPLEMENT / CARE BUNDLE`. The state-path is `HELD` when the endpoint persists at the promised level, `TUNED/TAPER` when partial correction remains, `DECAY` when effect wanes, `REBOUND` when disease burden returns, `RESIDUAL` when an altered remainder persists without full claimed correction, or `HOSTAGE` where the patient cannot exit the support bundle without losing access, recognition, or rescue options. Evidence standing depends on horizon: early trials may be `DOCUMENTED` for short horizons but only `INFERRED` or `UNPROBED` for horizons not yet reached.

`Verdict`: The claim matches when the promised durability is supported by substrate-held correction at the claim-implied horizon, with adequate evidence standing. It mismatches when a therapy is priced or governed as durable correction but the state is actually held by continuing support, partial substitute care, short follow-up, or unproven extrapolation. It is unprobed when the claimed horizon has not yet arrived. It is opaque when the evidence needed to distinguish substrate-held durability from support-held response is unavailable.

`Π`: The remedy is escrow, holdback, term-limit, discount, relabeling, registry evidence, or outcome covenant. Let `L` be the claimed lifetime or durability-priced value, and let `DCF` be the durability-contingent fraction of that value. Then `(1 − DCF) × L` may be paid up front for the demonstrated immediate state, while `DCF × L` is escrowed and released only as the claimed state survives agreed milestones. A five-year claim creates a five-year release schedule. A fifteen-year claim creates a fifteen-year release schedule.

**The seller can claim more durability, but the claim lengthens its own payment horizon.**

`Challenge condition`: A `DECAY`, `UNPROBED`, or `MISMATCH` classification should be revised if evidence shows that the claimed endpoint remains above the promised threshold after the treatment episode and withdrawal of substitute support for the claim-implied durability horizon, without rescue therapy or unrelated interventions carrying the state.

`Prediction`: Within the durability horizons the therapies themselves claim, substrate-held corrections will justify released escrow, while support-held or decaying states will require discount, relabeling, or milestone-based payment. The framework does not deny high prices for durable correction. It requires the price horizon to match the custody horizon.

The application shows the repricing layer directly. A durability claim is not merely a statement about hope, mechanism, or early response. It is a claim about who holds the state over time. If the patient’s substrate holds it, the claim can be priced as durable. If the claim depends on support that has not transferred, the price should remain partly contingent until the state does.

# What This Is Not

The framework is easy to misread because it crosses familiar categories without belonging to them. It is not a provenance system. Provenance asks where an object came from, who made it, or what process produced it. Custody asks a different question: who or what holds the claimed state when the support relation ends? A synthetic voice may have clear provenance and weak custody. A therapy may have clear origin and unproven durability. A compute contract may be real and signed while its demand is still seller-held. Origin does not settle continuity.

The framework is not a quality score. A product can be excellent and still make a mismatched state claim. A hosted service may be highly valuable as access. A daily medication may be highly valuable as maintenance. A donor-backed program may be valuable as patronage. The framework does not ask whether these arrangements are good. It asks whether the claim class matches the holder of continuity.

The framework recovers several older insights without reducing to any one of them. Work on Goodhart effects and audit culture shows how measurement can distort the objects it measures; this paper asks who holds the claimed state after the measuring or support relation is withdrawn (Goodhart 1975; Strathern 1997; Manheim and Garrabrant 2018). Akerlof names quality uncertainty; this paper names continuity uncertainty (Akerlof 1970). Williamson and vendor-lock-in work explain why dependence matters; this paper distinguishes honest dependence from dependence sold as transfer, durability, independence, or ownership (Williamson 1975; Opara-Martins, Sahandi, and Tian 2016). Path-dependence theory explains how prior arrangements constrain future choices; this paper asks whether the claimed state survives withdrawal of the arrangement that produced it (Arthur 1989). MacIntyre’s account of practices and traditions is relevant to institution-held states, but the record here is narrower: it tests claims by assigning custody after withdrawal (MacIntyre 1981). These are partial vocabularies for the problem. The State Claim Record is the proposed instrument.

It is not anti-subscription, anti-service, anti-maintenance, or anti-dependence. Dependence is often the product. This includes ordinary lock-in and path-dependent arrangements, which may be efficient, valuable, or unavoidable when named honestly (Arthur 1989; Opara-Martins, Sahandi, and Tian 2016). The mismatch appears only when dependence is sold as transfer, durability, independence, terminal cure, exclusivity, or firm commitment. `RENTED` is not a defect when sold as rented. `SCHEDULE` is not a defect when sold as maintenance. `VENDOR` is not a defect when sold as access.

It is not a fraud accusation. Mismatch can arise from imprecise marketing, immature evidence, pricing convention, category inertia, or ordinary optimism. Fraud requires a separate legal and evidentiary showing. A State Claim Record identifies a gap between promised continuity and assigned custody. Institutions may then decide whether the consequence is disclosure, relabeling, discount, escrow, covenant, reserve, exclusion, or legal action.

It is not a certification regime. The record can be produced without permission, and it can be contested by evidence. No central authority is required to make a custody claim legible. A buyer, journalist, analyst, regulator, insurer, court, platform, or procurer can produce a record from public information and revise it when better evidence arrives. Institutions may bind the record by policy, but the framework itself supplies classification and contestability, not legal force.

It is also not universal. The framework returns `INAPPLICABLE` when no separable state claim exists, no support relation can be specified, no meaningful withdrawal scenario can be formed, the state is constitutively relational, the substrate drifts faster than the measurement window, evidence access is structurally unavailable, or the claim is explicitly transient and priced as transient. Disciplined refusal is part of the instrument.

Table: Reduction Table

| If removed | The framework collapses into |
|---|---|
| `Q` - exact state claim | Domain commentary. The analyst discusses “AI,” “wealth,” or “therapy” rather than testing a claim. |
| `κ` - claim class | Anti-dependence moralism. Rented, mediated, or maintained states are treated as failures even when sold honestly. |
| `Σ → Wt/t` - support inventory, withdrawal, and horizon | Provenance or dependency talk. The analysis names relationships but does not test continuity after support ends. |
| `V → R(t)` - visible state and retained state | Vague skepticism or audit language. The framework loses the difference between appearance under support and survival after withdrawal. |
| `H` - holder of continuity | Ordinary metric critique. The analysis may show a number fell, but not who or what carried the state. |
| `S` - state-path | Binary pass/fail review. Decay, rebound, clawback, hostage states, and residual states collapse into generic failure. |
| `E` - evidence standing | Assertion without standing. The reader cannot distinguish probed, documented, inferred, opaque, and unprobed classifications. |
| `Verdict` | Vocabulary without settlement. The record names fields but does not decide whether the claim matches custody. |
| `Π` - remedy or repricing consequence | Disclosure ethics without institutional bite. The gap is named but not translated into price, reserve, escrow, covenant, or exclusion. |
| Challenge condition | Certification or opinion. The classification cannot be productively contested. |
| Stopping rules | Universalizing overreach. The framework is forced onto cases where it should refuse a verdict. |

The reduction table is also a use test. If a proposed simplification removes a field and the result collapses into one of these neighboring forms, the field is not decorative. It is doing structural work.

# Limits and Falsification

The framework is useful only if it can refuse cases and lose arguments. A method that classifies every claim, survives every counterexample, and treats every missing fact as confirmation is not an instrument. It is a vocabulary. The State Claim Record therefore has two kinds of limits: stopping rules, where the framework returns no substantive verdict, and falsification conditions, where the framework’s own predictions fail.

At the application level, each record is falsifiable through its challenge condition. A `VENDOR` holder can be revised if the claimed state survives withdrawal of vendor support. A `SCHEDULE` holder can be revised if the state persists after cadence ends. A `DECAY` path can be revised if the endpoint remains above the promised threshold at the claim-implied horizon. An `OPAQUE` status can be revised if the withheld support relation is disclosed. The framework does not ask readers to trust the analyst. It asks them to inspect what evidence would change the row.

At the synthesis level, the framework makes a stronger claim: many state claims across domains can be tested with the same compact record, the same small holder vocabulary, the same state-path vocabulary, and the same verdict rule. That claim can fail. It fails if new cases routinely require new holder types rather than recombinations of the existing set. It fails if independent analysts cannot reproduce holder assignments from the same public evidence. It fails if the negative controls do not hold - if honest access, maintenance, presence, or patronage claims are repeatedly misclassified as mismatches. It fails if `R(t)` cannot be defined in the cases where the framework claims it matters. It fails if remedies do not follow from custody gaps but require a separate moral or policy theory to become actionable.

The framework also fails if it cannot distinguish evidence standing from state-path. A claim that is `UNPROBED` is not the same as a claim that is `RENTED`; a claim that is `OPAQUE` is not the same as a claim that is `DECAY`; a claim that is `DOCUMENTED` is not the same as a claim that is `PROBED`. If the record collapses what happened to the state into what is known about the state, it loses the discipline that makes contestation possible.

The stopping rules are equally important. The framework should return `INAPPLICABLE` when no separable state claim can be identified, no support relation can be specified, no meaningful withdrawal scenario can be formed, the state is constitutively relational, the substrate drifts faster than the measurement window, evidence access is structurally unavailable, or the claim is explicitly transient and priced as transient. These are not embarrassing exceptions. They are the boundaries that keep the instrument sharp.

The initial registry tests the launch claim modestly. It does not prove that the vocabularies are final. It shows that the same record structure and small vocabulary can be reused across distant state claims. Later registry versions should make the harder question public: whether the vocabulary remains stable as coverage expands, or whether new domains force new primitives. If the vocabulary keeps expanding, the framework is not yet a framework. It is a growing taxonomy. This is the framework’s own Goodhart-style failure condition: the record must not become another expanding proxy language for the thing it was meant to test (Manheim and Garrabrant 2018).

The framework’s political property also has a limit. A State Claim Record can be produced unilaterally, but unilateral does not mean unanswerable. A unilateral record that lacks a challenge condition is only an opinion. A unilateral record that ignores contrary evidence is advocacy. A unilateral record that cannot name what would change its classification should not be published as a record.

The test of the paper is therefore practical. Can a competent reader take a state claim encountered that day, write a record, name the support relation, specify the withdrawal horizon, assign a holder, state evidence standing, produce a verdict, and say what would change it? If not, the instrument has failed. If yes, the framework has done what it set out to do: make visible the gap between state under support and state that is actually held.

State is decided at withdrawal, not during use. But the framework is decided by use.

## Disclosures {.unnumbered}

**Data and materials availability.** All materials are available at https://github.com/AMBRA7592/who-holds-the-state and archived at https://doi.org/10.5281/zenodo.20404429.

**Medical scope.** The gene therapy application discusses pricing and durability as a class of state claims. This paper contains no patient-level data, no clinical trial data, no treatment recommendation, and no human-subjects research.

# References {.unnumbered}

Akerlof, George A. 1970. “The Market for ‘Lemons’: Quality Uncertainty and the Market Mechanism.” *The Quarterly Journal of Economics* 84 (3): 488–500.

Arthur, W. Brian. 1989. “Competing Technologies, Increasing Returns, and Lock-In by Historical Events.” *The Economic Journal* 99 (394): 116–131. https://doi.org/10.2307/2234208

Goodhart, C. A. E. 1975. “Problems of Monetary Management: The U.K. Experience.” In *Papers in Monetary Economics, Volume I*. Sydney: Reserve Bank of Australia. Reprinted in C. A. E. Goodhart, *Monetary Theory and Practice*. London: Macmillan, 1984.

MacIntyre, Alasdair. 1981. *After Virtue: A Study in Moral Theory*. Notre Dame, IN: University of Notre Dame Press.

Manheim, David, and Scott Garrabrant. 2018. “Categorizing Variants of Goodhart’s Law.” arXiv:1803.04585.

Opara-Martins, Justice, Reza Sahandi, and Feng Tian. 2016. “Critical Analysis of Vendor Lock-In and Its Impact on Cloud Computing Migration: A Business Perspective.” *Journal of Cloud Computing: Advances, Systems and Applications* 5: Article 4. https://doi.org/10.1186/s13677-016-0054-z

Strathern, Marilyn. 1997. “‘Improving Ratings’: Audit in the British University System.” *European Review* 5 (3): 305–321. https://doi.org/10.1002/(SICI)1234-981X(199707)5:3<305::AID-EURO184>3.0.CO;2-4

Williamson, Oliver E. 1975. *Markets and Hierarchies: Analysis and Antitrust Implications*. New York: Free Press.
