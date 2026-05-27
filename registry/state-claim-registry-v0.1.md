# State Claim Registry v0.1

**Schema:** SCR-v0.1
**Date:** 2026-05-26
**Companion paper:** *Who Holds the State? A Framework for Testing Claims After Support Ends*, v1.0
**Status:** Launch registry

**Cite as:** *State Claim Registry*, v0.1, schema SCR-v0.1, 2026-05-26.

Rows are citable as: SCR-v0.1-001 through SCR-v0.1-012.

---

## Cold-start legend

This registry applies the custody framework to state claims across domains. A state claim is any claim that some condition has been achieved, transferred, retained, secured, made durable, made independent, or made capable. Each row asks: what support relation produced the visible state, what happens when that support is withdrawn at the claim's implied horizon, who or what holds continuity afterward, and whether that custody matches the original claim. For the full framework, see *Who Holds the State?*

## Registry status

```text
Schema:        SCR-v0.1
Launch scope:  12 rows
Purpose:       prove the record works across distant claims, not exhaust the corpus
Row status:    DRAFT / ACTIVE / CHALLENGED / REVISED / RETIRED
Evidence:      INFERRED / DOCUMENTED / PROBED / REPLICATED
Citation:      SCR-v0.1-[row number]
```

## Row format

| Field                 | Meaning                                             |
| --------------------- | --------------------------------------------------- |
| `Row ID`              | Stable row identifier.                              |
| `Status`              | DRAFT, ACTIVE, CHALLENGED, REVISED, or RETIRED.     |
| `Q`                   | Exact state claim.                                  |
| `κ`                   | Claim class.                                        |
| `Σ → Wt/t`            | Support relation and withdrawal horizon.            |
| `H / S / E`           | Holder, state-path, evidence standing.              |
| `Verdict`             | MATCH, MISMATCH, OPAQUE, UNPROBED, or INAPPLICABLE. |
| `Π`                   | Remedy or repricing consequence.                    |
| `Challenge condition` | Evidence that would revise the row.                 |

---

# Registry v0.1 Rows

## SCR-v0.1-001 — Daily Medication as Maintenance

**Status:** ACTIVE
**Q:** "This medication controls symptom X while taken daily."
**κ:** Maintenance.
**Σ → Wt/t:** Daily dosing → dose cessation over clinically relevant post-cessation window.
**H / S / E:** `CADENCE / SCHEDULE`; `DECAY`; `PROBED` if cessation and follow-up are observed.
**Verdict:** `MATCH`.
**Π:** None, or ordinary disclosure.
**Challenge condition:** This row's `MATCH` classification should be revised if the seller's actual claim or pricing implies terminal cure, durable correction, or independence from dosing rather than maintenance.

## SCR-v0.1-002 — Daily Medication as Cure

**Status:** ACTIVE
**Q:** "This medication cures symptom X."
**κ:** Terminal.
**Σ → Wt/t:** Daily dosing → dose cessation over cure-implied horizon.
**H / S / E:** `CADENCE / SCHEDULE`; `DECAY`; `PROBED` if cessation and follow-up are observed.
**Verdict:** `MISMATCH`.
**Π:** Relabel, term-limit, discount, or terminal-cure evidence.
**Challenge condition:** This row's `MISMATCH` classification should be revised if evidence shows symptom reduction remains above the promised threshold after dosing stops for the cure-implied horizon, without substitute treatment carrying the state.

## SCR-v0.1-003 — AI Compute Commitments

**Status:** ACTIVE
**Q:** "This compute commitment represents committed demand."
**κ:** Firm, independent.
**Σ → Wt/t:** Buyer demand, seller financing, equity support, credit support, cloud credits, related-party circularity, capacity prepayments → withdrawal of seller-linked support over the contract or financing stress window.
**H / S / E:** `SELF / BUYER` or `COMPLEMENT / OUTSIDE CAPITAL` for independent fraction; `PATRON / VENDOR` or `COMPLEMENT / SELLER-SUPPLIED CAPITAL` for seller-supported fraction; `OPAQUE` where funding path is undisclosed.
**Verdict:** `MATCH` for independent fraction; `MISMATCH` for seller-held fraction; `OPAQUE` where funding cannot be traced.
**Π:** Disclosure, discount, reserve, covenant, or exclusion from independent-demand categories.
**Challenge condition:** A `PATRON / VENDOR` or `OPAQUE` classification should be revised if evidence shows the buyer can fund and sustain the commitment above the claimed threshold after vendor financing, seller credit support, circular prepayments, and substitute seller-linked financing are withdrawn for the claim-implied stress horizon.

## SCR-v0.1-004 — Household Net Worth as Wealth

**Status:** ACTIVE
**Q:** "This household holds $X of wealth."
**κ:** Durable, independent, transferable.
**Σ → Wt/t:** Wage continuity, credit access, insurance, benefits, family support, legal title, liquidity, program rules, debt covenants → withdrawal of the load-bearing mediator at shock, opportunity, or transfer horizon.
**H / S / E:** `SELF / USER` where wealth remains controlled and transferable; `PATRON`, `MEDIATOR`, `SETTING`, or `COMPLEMENT` where wealth depends on support. State-paths include `HELD`, `DECAY`, `CLAWED`, or `HOSTAGE`. Evidence may be `DOCUMENTED` through account terms, lien records, benefit rules, debt schedules, tax records, or observed stress outcomes.
**Verdict:** `MATCH` where retained custody remains household-held; `MISMATCH` where headline wealth is treated as durable or transferable but is support-held.
**Π:** Relabel, reserve, discount, covenant, disclosure, or redesigned intervention.
**Challenge condition:** A non-`SELF` holder assignment should be revised if evidence shows the household retains control, liquidity, legal use, and transferability of the claimed wealth after the specified support relation is withdrawn for the claim-implied shock or transfer horizon, without substitute support.

## SCR-v0.1-005 — Gene Therapy Durability

**Status:** ACTIVE
**Q:** "This therapy provides durable correction."
**κ:** Durable; terminal if claim language, pricing, or governance implies cure.
**Σ → Wt/t:** Biological modification, vector or cell persistence, conditioning, monitoring, rescue therapy, payer coverage, manufacturer warranties, registry participation → treatment episode plus withdrawal of substitute support over the claimed durability horizon.
**H / S / E:** `SELF / SUBSTRATE` if correction persists biologically; `CADENCE`, `PATRON`, or `COMPLEMENT` where support bundle carries the state. Paths include `HELD`, `TUNED/TAPER`, `DECAY`, `REBOUND`, `RESIDUAL`, or `HOSTAGE`. Evidence may be `DOCUMENTED` for short horizons but `INFERRED` or `UNPROBED` for horizons not reached.
**Verdict:** `MATCH` when durability is substrate-held at the claimed horizon; `UNPROBED` for unreached horizons; `MISMATCH` when durability-priced claims exceed support.
**Π:** Escrow, holdback, term-limit, discount, relabeling, registry evidence, or outcome covenant.
**Challenge condition:** A `DECAY`, `UNPROBED`, or `MISMATCH` classification should be revised if evidence shows the claimed endpoint remains above the promised threshold after the treatment episode and withdrawal of substitute support for the claim-implied durability horizon, without rescue therapy or unrelated interventions carrying the state.

## SCR-v0.1-006 — AI Assistant Time Savings

**Status:** DRAFT
**Q:** "This AI assistant saved five hours of work."
**κ:** Transfer.
**Σ → Wt/t:** Model access, prompt context, human review, revision, integration, downstream acceptance → handback and acceptance horizon.
**H / S / E:** `MEDIATOR / VENDOR` or `CADENCE / ROUTINE` if value exists only during generation and correction; `SELF / USER` if usable work survives handback. State-path may be `HELD`, `DECAY`, or `RENTED`.
**Verdict:** `MATCH` only for retained usable work; `MISMATCH` where draft production is sold as completed saved work; `UNPROBED` if no handback or acceptance measurement exists.
**Π:** Relabel, discount, TCO reprice, or disclosure of retained-work fraction.
**Challenge condition:** A `VENDOR`, `DECAY`, or `UNPROBED` classification should be revised if evidence shows usable accepted work remains above the claimed time-saving threshold after model access, prompting support, and human correction load are accounted for at handback.

## SCR-v0.1-007 — Synthetic Voice Exclusivity

**Status:** DRAFT
**Q:** "This synthetic voice is exclusive to the buyer."
**κ:** Exclusive, independent.
**Σ → Wt/t:** Training data, model weights, recipe, platform controls, licensing terms, output filters, marketplace enforcement → withdrawal of vendor enforcement and test of reproduction window.
**H / S / E:** `SELF / USER` only if the buyer controls the reproducibility boundary; `MEDIATOR / VENDOR` or `COMPLEMENT / MODEL SUPPLY` where exclusivity depends on platform enforcement or proprietary generation pipeline. State-path may be `HELD`, `RENTED`, or `DRIFTS` if similar outputs remain reproducible elsewhere.
**Verdict:** `MATCH` where exclusivity survives reproduction attempts without vendor discretion; `MISMATCH` where exclusivity is sold but reproducibility is vendor-held or open; `OPAQUE` if the reproduction boundary is undisclosed.
**Π:** Relabel, discount, disclosure, exclusion from exclusive-asset categories, or covenant.
**Challenge condition:** A `VENDOR`, `DRIFTS`, or `OPAQUE` classification should be revised if evidence shows materially similar voice outputs cannot be reproduced after withdrawal of vendor enforcement and after access to comparable models, recipes, or data sources during the relevant reproduction window.

## SCR-v0.1-008 — Companion AI Continuity

**Status:** DRAFT
**Q:** "This companion AI relationship is yours and persists over time."
**κ:** Durable, transfer, independent.
**Σ → Wt/t:** Vendor account, model access, memory store, subscription, moderation policy, device access, export rights, continuity of persona → cancellation, platform shutdown, export, or model migration horizon.
**H / S / E:** `MEDIATOR / VENDOR` where continuity depends on platform operation; `CADENCE / ROUTINE` where attachment depends on repeated interaction; `SELF / USER` only where usable memory and continuity transfer. State-path may be `HOSTAGE`, `RENTED`, or `DECAY`.
**Verdict:** `MATCH` where functional continuity, memory, and access transfer to the user and survive cancellation, shutdown, or migration at the claim-implied horizon. `MISMATCH` if relationship continuity is sold as user-held but remains vendor-held. `OPAQUE` if memory and model-dependency boundaries are undisclosed.
**Π:** Disclosure, relabeling, exit right, export covenant, or exclusion from ownership-like claims.
**Challenge condition:** A `VENDOR`, `HOSTAGE`, or `MISMATCH` classification should be revised if evidence shows the user retains functional continuity, memory, and access after subscription cancellation, vendor shutdown, or platform migration for the claim-implied horizon, without substitute vendor support.

## SCR-v0.1-009 — Pension Funding

**Status:** DRAFT
**Q:** "This pension is 75% funded."
**κ:** Firm, durable.
**Σ → Wt/t:** Asset returns, employer contributions, state subsidy, legal priority, workforce demographics, discount-rate assumptions, benefit rules → stress window for returns, contributions, demographic contraction, or subsidy withdrawal.
**H / S / E:** `SELF / SUBSTRATE` where funding survives stress through assets and enforceable contributions; `PATRON / STATE` or `PATRON / EMPLOYER` where solvency depends on continuing subsidy or contribution tolerance; `SETTING / LEGAL PRIORITY` where legal recognition carries the state. State-path may be `HELD`, `DECAY`, or `CLAWED`.
**Verdict:** `MATCH` where funded status survives the relevant stress horizon; `MISMATCH` where headline funded status depends on assumptions or support not held by the plan.
**Π:** Reserve, covenant, disclosure, discount, or benefit-risk relabeling.
**Challenge condition:** A non-`SELF` holder assignment should be revised if evidence shows funded status remains above the claimed threshold after withdrawal or stress of the identified support relation for the relevant actuarial horizon.

## SCR-v0.1-010 — Software Capability as Owned Productivity

**Status:** DRAFT
**Q:** "This software gives the buyer durable capability."
**κ:** Transfer, durable, independent.
**Σ → Wt/t:** Vendor service, license, API, updates, training, implementation partner, data export, maintenance, user skill transfer → vendor exit, subscription cancellation, API deprecation, or support withdrawal horizon.
**H / S / E:** `SELF / USER` if capability transfers to the organization; `MEDIATOR / VENDOR` where capability remains service-held; `CADENCE / ROUTINE` where capability depends on continued use and support cycles. State-path may be `HELD`, `RENTED`, or `DECAY`.
**Verdict:** `MATCH` where capability remains usable after support withdrawal; `MISMATCH` where access or support is sold as transferred capability.
**Π:** TCO reprice, relabel, exit right, discount, or maintenance covenant.
**Challenge condition:** A `VENDOR`, `RENTED`, or `DECAY` classification should be revised if evidence shows users retain the claimed capability after vendor support, updates, API access, and implementation partner support are withdrawn for the claim-implied horizon.

## SCR-v0.1-011 — Microbiome Restoration

**Status:** DRAFT
**Q:** "This intervention restores the microbiome."
**κ:** Durable, terminal, or maintenance depending on claim language.
**Σ → Wt/t:** Dose, diet, host substrate, routine, clinical monitoring, repeat use, adjunct therapy → cessation of intervention and return to ordinary conditions over restoration-implied horizon.
**H / S / E:** `SELF / SUBSTRATE` if a stable equilibrium persists; `CADENCE / ROUTINE` if benefit depends on ongoing intake; `COMPLEMENT / DIET` where diet carries the state. State-path may be `HELD`, `DECAY`, `DRIFTS`, or `REBOUND`.
**Verdict:** `MATCH` for maintenance claims if ongoing routine is disclosed; `MISMATCH` for restoration claims if state decays or rebounds after cessation; `UNPROBED` if no post-cessation follow-up exists.
**Π:** Relabel, term-limit, discount, or post-cessation evidence requirement.
**Challenge condition:** A `SCHEDULE`, `DECAY`, or `UNPROBED` classification should be revised if evidence shows the claimed microbiome state remains stable after intervention cessation and return to ordinary conditions for the claim-implied horizon, without substitute routine carrying the state.

## SCR-v0.1-012 — Cosmetic Skin Change

**Status:** DRAFT
**Q:** "This product rebuilds or restores the skin."
**κ:** Transfer, durable.
**Σ → Wt/t:** Film, coating, active ingredient, routine, device, lighting/context, continued application → cleansing, cessation of use, or ordinary wear horizon.
**H / S / E:** `SURFACE / FILM` or `SURFACE / COATING` where visible state lives in a removable layer; `CADENCE / ROUTINE` where it depends on continued application; `SELF / SUBSTRATE` only where substrate change persists. State-path may be `RENTED`, `DECAY`, or `HELD`.
**Verdict:** `MATCH` where sold as temporary cosmetic presence; `MISMATCH` where surface-held state is sold as durable substrate restoration.
**Π:** Relabel, disclosure, discount, or exclusion from restoration claims.
**Challenge condition:** A `SURFACE`, `RENTED`, or `MISMATCH` classification should be revised if evidence shows the claimed skin state persists after removal of film/coating and cessation of use for the claim-implied horizon, without substitute cosmetic support.

---

## v0.1 row selection rationale

This launch set is intentionally small. It contains:

* one negative control and one paired mismatch control: daily medication maintenance / cure (SCR-v0.1-001, 002);
* three paper applications: DCT, HOLD BOX, gene therapy (SCR-v0.1-003, 004, 005);
* seven cross-domain extensions: AI productivity, synthetic voice, companion AI, pension funding, software capability, microbiome restoration, cosmetic skin change (SCR-v0.1-006 through 012).

The set is sufficient for v0.1 because it demonstrates that the same State Claim Record structure travels across clinical, financial, household, software, media, biological, and cosmetic claims without requiring new primitives.

Registry v0.1 should not try to exhaust the corpus. It should prove that the record works.

---

## Governance

**Revision policy.** Rows may be revised, challenged, retired, or expanded in later registry versions. A row revision must preserve the row ID, update the row version/date, and state what evidence caused the change.

**Challenge protocol.** Challenges should identify the row ID, the challenged field, the evidence offered, and the row's stated challenge condition.

**Version discipline.** Registry v0.1 exists to prove that the State Claim Record works across distant claims. It does not exhaust the corpus.

---

## License

CC-BY 4.0
