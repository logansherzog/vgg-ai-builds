# The inventory

Every distinct build, its owner, and where it actually stands.

**Status vocabulary** — used strictly:

| Term | Means |
|---|---|
| **in use** | a named person ran it on live data |
| **sent, not tested** | artifact delivered, no evidence of use |
| **staged** | built or part-built, not confirmed live |
| **plan written** | a build plan exists and has gone to the owner |
| **proposed** | a one-pager in the backlog, owner named, nothing built |
| **waiting on us** | the owner has done their part; the next move is Logan's |

Where a build is waiting on someone, it says who. That's the useful part.

---

## Main backlog (B1–B51)

| ID | Build | What it does | Owner | Unit | Status | Depends on |
|---|---|---|---|---|---|---|
| B1 | FBI File Generator | Transcript → structured profile of a VGG person | Tobi Bankole | Comms / Central Intelligence | Proposed · owner said yes, plan owed | B2 |
| B2 | Fireflies Consolidation | All staff recordings into one extraction store | Kayode Muyibi | Splashers | Plan written · **the key unlock** | data-handling policy, access sign-off |
| B3 | Context Brief Engine | On-demand "what's going on with X" brief | Uche Ukonu | Chief of Staff | Proposed | B2 |
| B4 | Leaders-Series → Newsletter | Interview → profile blurb in house voice | Tobi Bankole | Comms | Proposed | B1, B2 |
| B5 | Ecosystem Capability Registry | Who inside VGG already does X, so units stop outsourcing it | Femi Shonubi | Edutech | Proposed · **unplaced** | capability placement |
| B6 | Live Org Graph | Self-maintaining organogram; flags ghost records | Uche Ukonu | Chief of Staff | Proposed | B2, HRIS access |
| B7 | Finance Exec-Pack Drafter | Assembles the run-rate/cash pack plus narrative | Festus Ilesanmi | Advancly | Plan written · owner wants a meeting · **waiting on us** | — |
| B8 | Multi-Lens Board Report | Board pack split into people / business / technology lenses | Otaren Iduoze | Advancly | Plan written | Phase IV gate |
| B9 | USD-Benchmarked Scorecard | Normalises Naira revenue at period FX so real growth shows | Michael Onuorah | Partek / PowerTech | Proposed | FX source of truth |
| B10 | Group Commercial Scorecard | Cross-entity commercial signal → weekly GCEO view | Uche Ukonu | Group | Proposed · GCEO priority | B16, unit workflow docs |
| B11 | Cross-Entity Finance Rollup | 6+ subsidiaries into one board view, anomalies flagged | Festus Ilesanmi | Advancly / Manco | Plan written | generalises B7 |
| B12 | Ops Workstream Tracker | Tracking-message firehose → maintained EOS scorecard | Chuka Monyei | Central Ops / PMO | Sent, silent | B2, tracker write access |
| B13 | Blocker / Dependency Tracker | Extracts blockers + owner + waiting-on → weekly "what's stuck" | Melissa Omede | Manco | Plan written · owner said yes | B2 |
| B14 | Contractor Accountability | Tracks execution-extension commitments into a scorecard | Banke Ajayi | Central Ops | Proposed · overlaps the VfM function | — |
| B15 | Adoption Dashboard | Who's using which shipped skill, where the loop stalls | Adeyinka Oshin | Executive Office | Sent, silent | shipped builds to measure |
| B16 | Oil & Gas CRM | AI-first CRM for the O&G commercial pipeline | Adeosun Ayomide | Vigipay / Zenvo | Staged · v3 built, **waiting on us** · Phase 1 not yet live | Attio setup + import |
| B17 | Oil & Gas GTM Sync | Prospect research + outreach for the O&G pipeline | Adeosun Ayomide | Vigipay / Zenvo | Proposed · blocked on the ICP question | B16, ICP decision |
| B18 | Partek BD / Deal CRM | Captures founder-dependent govt and disco deal flow | Michael Onuorah | Partek / PowerTech | Sent, silent | B16 template |
| B19 | BGP New-Business CRM | The consultative FMCG/fintech sales motion | Ibijoke Oyewole | BGP / Vigipay | Sent, silent | B16, workflow doc |
| B20 | Group Sales-Ops Pipeline | Aggregates leads/won/lost across subsidiaries | Moyo Asubiojo | Edutech | **Yes, gated on cost per subsidiary** | workflow doc |
| B21 | Stakeholder Keep-Warm CRM | Partner/board tracker: last touch, sentiment, next nudge | Moyo Asubiojo | Edutech | Proposed | workflow doc |
| B22 | WhatsApp Prospect Capture | Parses prospect threads → proposed CRM diffs | Adeosun Ayomide | Vigipay / Zenvo | **Unverified** — "V1 exists" is unsupported | B16 |
| B23 | Edutech GTM Rollout | Points the existing GTM skill at the Edutech ICP | Moyo Asubiojo | Edutech Global | Identified, not started | existing GTM skill |
| B24 | Market-Intelligence Base | Competitor and market research → living repository | Lukmon Sanni | Growth / Mgmt Office | Proposed · **unplaced** | — |
| B25 | Onboarding Intake Copilot | New-hire docs + checks → clean employee record | Kate Ogbuka | People OS | Plan written · owner said yes | HRIS access |
| B26 | Group People Dashboard | Headcount/attrition/onboarding across ~15 entities | Kate Ogbuka | People OS | Plan written | data remediation |
| B27 | Recognition Autopilot | Milestone events → drafted message for approval | Otaren Iduoze | Advancly P&C | Plan written | HRIS events, B28 |
| B28 | Birthday DB Fixer | Cleans the birthday database, tracks and reminds | Executive Office (EA team) | GCEO office | Proposed · **raised 3× by the GCEO** | HRIS hygiene |
| B29 | People OS Template Engine | The right HR document per entity and situation | Fiyinfoluwa Sanwo | People OS | Sent · out-of-office only | — |
| B30 | HR Initiative Scorecard | Exit notes + engagement signal → what's working | Otaren Iduoze | Advancly P&C | Plan written | — |
| B31 | Employee Sentiment Capture | Check-in notes → people-health early warning | Kate Ogbuka | People OS | Plan written | — |
| B32 | KYC/AML Intake Copilot | Pre-fills AML/KYC forms, flags gaps, routes sign-off | Ibijoke Oyewole | BGP / Compliance | Sent, silent · **compliance approver unnamed** | named compliance officer |
| B33 | Exception Surfacer | Automatic exception reports for human review | Festus Ilesanmi | Advancly Finance | Plan written | approver per exception type |
| B34 | Regulated-Ops Suite | Reconciliation, compliance checks, transaction monitoring | Banke Ajayi | Regulated entities | Proposed | beachhead entity + approver |
| B35 | Meeting → Proposal Extractor | Ambiguous conversation → proposal or plan skeleton | Melissa Omede | Manco | Plan written · yes · **biggest reuse: analyst is the largest role** | B2 |
| B36 | Concept-Note Engine | First-draft partnership proposals and stakeholder decks | Lukmon Sanni | Growth / Mgmt Office | Sent, silent | Phase IV gate, B3 |
| B37 | Living SOP System | Proposes SOP updates from how work actually runs | Melissa Omede | Manco | Plan written · **unplaced** | — |
| B38 | Newsletter Auto-Draft | Harvests wins → monthly newsletter draft in house voice | Chuka Monyei | Central Ops | Sent, silent | — |
| B39 | Distribution Reconcile | Authoritative all-staff list from HR data; delivery tracking | Chuka Monyei | Central Ops | Proposed · **unplaced** | HR roster |
| B40 | Bio / Profile Generator | Short exec bios on request, two lengths | Executive Office (EA team) | GCEO office | Proposed | **hard dependency on B1** |
| B41 | Legal Draft Review | Pre-reviews drafts against house standard, routes a diff | Uloma Herrington | Greenhouse Capital | Plan written · **yes, and wants scope widened** · waiting on us | house-standard templates |
| B42 | Deal / Legal Tracker | Record of portfolio legal status and obligations | Uloma Herrington | Greenhouse Capital | Plan written | — |
| B43 | Policy Assistant (AiDA rebuild) | Policy/HR FAQ with a maintained, cited knowledge base | Otaren Iduoze + Sunday Ocheli | Advancly P&C + Splashers | Plan written · owner sees it as useful but not a current pain point | policy corpus |
| B44 | Infra Runbook Registry | Site history and access procedures out of one head into a base | Sunday Ocheli + Kayode Muyibi | Splashers | Sent · replied, **reply unread (encrypted)** | knowledge-transfer sessions |
| B45 | Support-Triage Rollout | Expands the support-triage assistant across units | Ann Anni | EduTech Support | **Unverified** — "V1 exists" conflicts with "nothing built" · unplaced | — |
| B46 | BMC Request Intake | 10-question intake → structured brief with gaps flagged | Taiwo Oluwafemi | BMC (EduTech) | **Sent Sep 8, never tested** | — |
| B47 | EA Scheduling Assistant | Itinerary builds, cross-account conflict detection | Adeyinka Oshin | Executive Office | Sent, silent · unplaced | B49 feeds it |
| B48 | ERP through Claude | Act on the ERP without a new login; integration hub | ERP team (Splashers) | Splashers | **Yes, Sep 18** — plan owed · GCEO priority | ERP API identity |
| B49 | Priority Meeting Queue | Who the GCEO wants to meet, by priority and city; nightly open slots and chases | Adeyinka Oshin + EA team | Executive Office | Plan written, sent Sep 17 | feeds B47 |
| B50 | Convening Invite-List | Names → scored, tiered 30-name shortlist with reasons | Adeyinka Oshin + EA team | Executive Office | Plan written, sent Sep 17 | B1, B21 |
| B51 | Meeting → Money | Post-meeting card: the need, the commercial opening, next step and owner | Adeosun Ayomide | Vigipay | Plan written, sent Sep 17 | B2, B10, B36 |

---

## VGP MindLab (ML-49 … ML-55)

These came out of the MindLab sessions and were originally numbered B49–B55, which collides with
B49/B50/B51 above. **Use the ML- prefix.**

| ID | Build | What it does | Owner | Status |
|---|---|---|---|---|
| ML-49 | HR Training & Assessment | Training content → assessments → auto-graded, HR approves scores | Adedotun Adebayo | Proposed · already being staffed via n8n |
| ML-50 | Compliance Report Drafter | Fills monthly/quarterly templates, checks cross-report consistency | Ibijoke Oyewole | Proposed · **blocked: no AI on the database** |
| ML-51 | Customer Service Collapse | Maps a 15-step process, automates the lookup and copy-paste steps | Ibijoke Oyewole → CS lead | Proposed · confirm it isn't the existing n8n automation |
| ML-52 | Safe Data Handoff | Strips and tokenises sensitive fields before Claude sees them, re-hydrates locally | VGP IT + Banke Ajayi | Proposed · **unblocks ML-50, ML-51 and most VGP cases** |
| ML-53 | Connector Finder | Describe a workflow → get the connector, the custom path, or "use n8n" | MindLab members | Proposed |
| ML-54 | MindLab Session Kit | Agenda → announcement; content → quiz; transcript → recap and actions | Adedotun Adebayo | Proposed |
| ML-55 | Use-Case Intake Queue | Submit a headache → scored on hours saved and sensitivity → sponsor approves | Maggie Oduwole / Ibijoke Oyewole | Proposed · feeds B15 |

**ML-52 is the one to do first.** Every other VGP build is waiting behind the same governance
objection, and this answers it rather than arguing with it.

---

## VGN Finance (Business Central)

| ID | Build | What it does | Owner | Status |
|---|---|---|---|---|
| LB-1 | Month-End Pack Drafter | Generates month-end packs from Business Central; AI writes commentary only, never the arithmetic | Lekan Bakare | Plan written Sep 17 |
| LB-2 | Ask-the-numbers | Ad-hoc finance questions over verified aggregates | Lekan Bakare | Plan written |
| LB-3 | Project Costing | Project-level costing from Business Central | Lekan Bakare | Plan written |

Adjacent to B7 (Advancly's pack) — different entity, different ERP. Worth confirming the two
aren't converging on the same thing.

---

## EduTech gate-1 use cases

| Ref | Build | Owner | Status |
|---|---|---|---|
| E1 | Customer-support drafting tool — Claude drafts replies as internal notes, one programme, four intents | Ann Anni | **Brief only, nothing built.** Waiting on sign-off, a baseline export, and a hosting/governance answer for student data |
| E2 | BMC Briefing Assistant | Taiwo Oluwafemi | Same build as B46 — shipped Sep 8, untested |
| E3 | Sales pipeline: define stages, then measure time-in-stage | Cyril Oni + Desmond Enechi | Identified · the definition work hasn't started; the pipeline is a spreadsheet |
| E4 | Proposal drafting for the university-signing cycle | Desmond Enechi | Identified only · no spec, no baseline |
| E5 | Shared read-only Zoho connector — the infrastructure under E1 and E3 | Logan builds; **post-handover owner unnamed** | Staged · read path tested against the live queue |

---

## GCEO Workstation

A separate track: the GCEO's own operating system rather than a unit build. 14 items and 3
routines — vault structure, meeting archive and sync, a daily command centre, a standard
post-meeting package, and an EA-team feedback loop.

**Status: 0 of 5 routines live, 2 in draft.** Blocked on access rather than on build time.

---

## Shipped infrastructure

**WhatsApp connector + daily triage — Adeyinka Oshin.** A hosted connector giving her own Claude
session access to her own WhatsApp, plus a triage skill over it. Phone paired Sep 16, tools
hard-scoped to her session, verified she cannot read anyone else's chats.

**Blocked on one toggle.** Every tool call returns "your organization requires approval for this
tool." It needs VGG's Claude organisation Owner to set the tool permission to always-allow.
**We don't know who that Owner is** — naming them unblocks the only build currently in daily use.
