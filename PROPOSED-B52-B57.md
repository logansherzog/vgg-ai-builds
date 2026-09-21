# VGG AI Backlog — Proposed Additions (B52–B57)

> Immediate, small-scope asks from the same mining run live in [QUICK-WINS.md](QUICK-WINS.md).

**For review · Venture Garden Group · Central Operations · 20 September 2026**
Prepared by Logan Herzog · For: Uche Ukonu (Central Ops / Executive Office)

---

## What this is

A second mining pass over the GCEO meeting archive, run to find builds the first pass
missed. The first pass drew on 14 Leaders-Series interviews and the GCEO WhatsApp
channels. This pass reads the meeting record itself — **3,456 meetings, October 2020 to
September 2026** — and looks for work patterns that repeat.

Six new builds are proposed. Five existing builds get new evidence rather than a new
number. Everything is deduped against B1–B51.

> **On sourcing:** this document deliberately contains no meeting quotes, no financial
> figures, no counterparty names, and no personnel matters. The archive covers board,
> investor, legal, and personal conversations. Only the *shape of recurring work* is
> reported here. Evidence detail sits with Logan and can be walked through live.

---

## The rule used to decide what qualifies

Anything mined from an archive this deep has a recency problem: a complaint from 2023 may
already be solved. So the bar scales with staleness.

| Last raised | What it must show to qualify |
|---|---|
| Within 60 days | Recurs in 2+ separate meetings |
| 2–6 months | 3+ separate meetings |
| 6–12 months | 4+ separate meetings |
| Over a year | 6+ separate meetings, across multiple years |

**The older the signal, the more structural the problem has to be.** A pattern that shows
up in five separate calendar years is not a mood — it is how the organisation works.

Two further filters, both from the existing backlog's own rules:

- **A named human owner, or it is not a build.** This is the ADA lesson.
- **A variant of an existing build widens that build.** It does not get a new number.

---

## Proposed new builds

### B52 — Commitment Register  [M]
- **Owner:** Uche Ukonu / Chukwuka Monyei — Central Operations
- **Pattern:** A company-wide commitment call has run **100 times across four calendar
  years (May 2023 – July 2026)**. Teams state what they will deliver that week. What was
  committed is captured in meeting notes; whether it happened is not systematically
  checked against the next week's call.
- **Does:** Extracts each stated commitment with its owner and due date, then re-checks it
  at the following call and reports what closed, what slipped, and what was never
  mentioned again.
- **Pattern:** capture → AI extracts commitments → Central Ops approves the diff → OpenOps
  → weekly kept/slipped report.
- **Important:** this **extends OpenOps and B12**. It is not a parallel tracker. The
  commitment call is the highest-frequency, longest-running accountability ritual in the
  archive, which makes it the best available source of truth for execution state.
- **First milestone:** last four commitment calls back-filled into a kept/slipped view.
- **Depends on:** B2.

### B53 — Meeting Follow-Through Provisioning  [S]
- **Owner:** Adeyinka Oshin — GCEO EA office
- **Pattern:** Across **73 meetings spanning three years (Sept 2023 – Sept 2026, last
  raised 10 days ago)**, the same post-meeting chore recurs: stand up a chat group for the
  participants, add the right people, pass on contact details so the thread can continue.
  It is done by hand every time, and when it is skipped the thread goes cold.
- **Does:** After a meeting, proposes the follow-through package — who should be in the
  group, which contacts need saving, which introductions were promised — for one-click
  approval.
- **Pattern:** capture → AI drafts the provisioning package → EA approves → channel created
  + contacts written to the contact system → "promised but not created" report.
- **Feeds:** B47 (EA scheduling) and B22 (WhatsApp capture). Build it inside those, not beside them.
- **First milestone:** one week of GCEO meetings with the follow-through package drafted.

### B54 — Treasury Data Capture  [M]
- **Owner:** Melissa Omede (Manco) with Festus Ilesanmi (Finance)
- **Pattern:** Raised in **15 meetings over 423 days (May 2025 – July 2026)**: a treasury
  dashboard exists, but it has no live banking data flowing into it. The reporting layer
  was built before the capture layer.
- **Does:** Establishes the bank-data feed into treasury reporting, with reconciliation and
  provenance on every figure.
- **Why it is listed separately from B7/B11:** those are reporting builds. This is the
  capture gap underneath them, and it blocks both. Consistent with the backlog's own first
  principle — capture is the bottleneck, not the tool.
- **First milestone:** one entity's live balances feeding the dashboard with a reconciliation trail.
- **Depends on:** banking data access approval (see note on access below).

### B55 — Board & Committee Governance Operations  [M]
- **Owner:** Moyosore Asubiojo — Board Relations
- **Pattern:** **67 board and board-relations meetings across five calendar years
  (2022–2026, last held 12 days ago)**, plus **42 meetings over four years** referencing
  governance obligations — meeting cadence requirements, committee composition, member
  contribution follow-up. The administration of this sits with one person and is manual.
- **Does:** Maintains the governance calendar against required meeting cadence per entity,
  tracks committee membership and terms, and follows up on commitments board members make.
- **Distinct from B8**, which generates the board *report*. This is the governance
  *operation* around it — scheduling obligations, composition, and follow-through.
- **First milestone:** governance calendar and compliance status for three entities.

### B56 — Tender & Bid Discovery  [M]
- **Owner:** Ifeanyi Monyei — Executive Office
- **Pattern:** The strongest unserved evergreen signal in the archive. Tender, RFP and bid
  activity appears in **188 meetings across five distinct calendar years (March 2022 –
  September 2026, last raised 9 days ago)**. Opportunity discovery is described as a daily
  manual search, and qualification lives with whoever happened to find it.
- **Does:** Monitors tender and RFP sources against a defined profile, scores each against
  capability and past wins, and routes qualified ones to a named owner with a decision log.
- **Pattern:** capture → AI qualifies → named owner approves pursue/decline → pipeline of
  record → weekly "what we found, what we passed on, and why" report.
- **The decision log matters more than the discovery.** Recording why a bid was declined is
  what stops the same opportunity being re-evaluated from scratch next quarter.
- **First milestone:** two weeks of monitored tenders, scored, with owner decisions recorded.
- **Depends on:** B5 (capability registry) for scoring against what the group can actually deliver.

### B57 — Spreadsheet-to-System Intake  [M]
- **Owner:** Central Operations (Uche Ukonu), delivered per requesting unit
- **Pattern:** The most pervasive pattern in the entire archive. Manual spreadsheet work —
  re-keying the same values across sheets, manual uploads, hand-maintained trackers —
  appears in **310 meetings across five calendar years (October 2021 – August 2026)**. It
  is not one team's problem; it is the organisation's default tool.
- **Does:** A repeatable intake that converts a hand-run spreadsheet into a governed system:
  document the sheet, identify the owner and the approval point, migrate it, retire the sheet.
- **Why this is a build and not an observation:** B16, B18, B19 and the new vertical below
  are all the same migration performed by hand, one unit at a time. Making the migration
  itself repeatable is what turns 48 tools into shared infrastructure.
- **First milestone:** two spreadsheets migrated through a documented intake, with the
  intake itself written down well enough for someone else to run it.

---

## Existing builds that gain evidence (no new number)

Per the rule that a variant widens the existing build rather than forking it:

| Existing build | What this pass adds |
|---|---|
| **B37 — Living SOP System** | **Widen to the EA function.** 85 EA check-in and planning meetings over 532 days show SOPs, meeting checklists and trackers being written by hand, per person, per vertical. Same build, second constituency. |
| **Commercial OS (B16/B18/B19/B20)** | A **new vertical stood up in the last 6 weeks** has already asked for a spreadsheet CRM to track leads, demos and pilots. It should be **configured as an instance of the Commercial OS, not built as a new CRM.** This is the clearest live test of whether the shared-capability model holds. |
| **B33 — Reconciliation / Exception Surfacer** | A fund reconciliation series shows the manual work in detail: linking statements to reconciliation sheets, categorising transactions, documenting inter-entity transfers. Strengthens the case; adds nothing new to scope. |
| **B47 — EA Scheduling Assistant** | Contact capture from meetings recurs over a three-year span. Already inside B47's stated scope — this confirms it should not be dropped from it. |
| **B5 / B24 — Capability Registry & Market Intel** | A recurring technical council needs cross-entity roadmap visibility and regular market-intelligence input. Both are existing builds; the council is the first concrete consumer for them. |

---

## One held item

A weekly operating cadence in one part of the group ran **40 times over 446 days** but has
not appeared in **118 days**. Under the staleness rule it clears the recurrence bar, but a
gap that long usually means the meeting ended or moved. **Confirm it is still running
before scoping anything.** Listed for completeness, not proposed.

---

## What would make these wrong

Stated plainly, because it is cheaper to hear now than after a build:

1. **B52 assumes the commitment call is still running.** Its last recorded instance is
   76 days old. If the ritual has been replaced, B52 should follow whatever replaced it.
2. **B54 depends on banking data access**, which is a permission and policy question before
   it is a build question — the same dependency Gap 4 raises for the capture layer.
3. **B56 needs a defined pursuit profile.** Without agreement on what the group will and
   will not bid for, the scoring is decoration.
4. **B57 is a process build, not a software build.** It only works if Central Ops owns the
   intake and units actually retire the sheet afterwards.
5. **None of these change the phasing.** They fit inside the existing capabilities —
   B52 and B53 into Execution Management, B54 into Finance Intelligence, B55 into
   Governance, B56 into the Commercial OS, B57 across all of them. No new capability is
   implied, and none of them should start before the capture and context layer exists.

---

## The ask

Run this through your own Claude and push back. Specifically:

- Which of B52–B57 are already solved by something live that I cannot see from the
  meeting record — OpenOps, ProjectTrak, or work in flight?
- Are the proposed owners the right people, and would they recognise the problem as theirs?
- Is the Commercial OS instance call correct for the new vertical, or is there a reason it
  genuinely needs its own build?
- Does B57 belong to Central Ops, or is it really a Technical Team function?

Anything that survives that gets a build plan in the same format as the existing ones.

---

*Prepared for VGG Central Operations · 20 September 2026 · Internal review draft*
