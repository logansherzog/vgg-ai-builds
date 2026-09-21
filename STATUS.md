# Where every build is waiting

The same inventory as [BUILDS.md](BUILDS.md), sorted by what's blocking rather than by number.
This is the view for deciding what to do next.

**Last updated:** 21 September 2026

---

## Waiting on us

The owner has done their part. The next move is the build team's. These are the most expensive
items on the board, because someone is already leaning in.

| Build | Owner | What's owed |
|---|---|---|
| B16 Oil & Gas CRM | Adeosun Ayomide | The updated build and setup steps. Three review items were raised and all three are now fixed — they need sending, not building. Phase 1 validation and the end-to-end test are queued behind it |
| B41 Legal Draft Review | Uloma Herrington | The plan, sent to her and to her colleague, plus a time. She also wants to widen scope to advisory-services automations |
| B7 Finance Exec-Pack | Festus Ilesanmi | A proposed meeting time this week |
| B1 FBI Files | Tobi Bankole | The build plan |
| B35 Meeting → Proposal | Melissa Omede | The build plan, while she's mid project-planning |
| B25 Onboarding Intake | Kate Ogbuka | The build plan |
| B48 ERP through Claude | ERP team | The build plan, plus a walkthrough — the reply said useful but not yet fully understood |
| B20 Group Sales Pipeline | Moyo Asubiojo | The plan with a cost-per-subsidiary view. The yes is conditional on it |

## Awaiting an owner's response

Plans sent, no reply yet. All that's needed is a yes or no on whether the build is still a real
pain — a no is as useful as a yes.

B9 and B18 (Partek) · B19 and B32 (BGP) · B24 and B36 (Growth) · B12 and B38 (Central Ops) ·
B15 and B47 (Executive Office) · B49 and B50 (Executive Office) · B51 (Vigipay) · B29 (People OS,
out of office)

## Blocked on a decision

Not a build problem. Someone has to choose.

| Build | The decision |
|---|---|
| B2 Fireflies Consolidation | The data-handling policy, plus access sign-off. **Nine builds sit behind this one** |
| B32 KYC/AML Intake | The compliance approver seat is unnamed |
| B17 O&G GTM Sync | Which customer profile the motion targets |
| B34 Regulated-Ops Suite | A beachhead entity and a named approver |
| ML-50, ML-51 | AI is not permitted against the database. **ML-52 answers this** — build it first |
| B10 vs B20 | Two overlapping commercial roll-ups. Merge or separate deliberately |
| Everything in Capability 4 | Which pipeline is canonical |
| B5, B24, B37, B39, B45, B47 | Unplaced in the capability architecture. Proposed homes in [CAPABILITIES.md](CAPABILITIES.md) |

## Blocked on access

| Build | What's needed |
|---|---|
| WhatsApp triage (in use) | One organisation-level tool permission. **We don't know who the Claude org Owner is** — naming them unblocks the only build in daily use |
| B6, B25, B26, B27 | HRIS access |
| B12 | Write access to the tracking system |
| LB-1, LB-2, LB-3 | A read-only Business Central service account |
| E1 EduTech support tool | Owner sign-off, a baseline export, and a hosting decision for student data |
| B45 / Q3 reply automation | **A Zoho API key from Kassim.** Flagged 28 Aug as "expected within days"; still outstanding three weeks later. This is the whole blocker |

## Sent and untested

| Build | Owner | Since |
|---|---|---|
| B46 BMC Briefing Assistant | Taiwo Oluwafemi | 8 September. Likely a setup problem rather than a disinterest problem — worth twenty minutes together on one real brief |

## Unverified — resolve before quoting

| Build | The conflict |
|---|---|
| B22 WhatsApp Prospect Capture | Recorded as "V1 exists"; there is no artifact or run evidence. A 10 Jul request asks for it to be **developed** for DealOS — which suggests it does not exist |

**B45 is resolved.** A 28 Aug action item is to obtain a Zoho API key *in order to build* the
reply automation. The owner's brief was right and "V1 exists" was wrong. B45 is now **blocked on
access**, not unverified — see below.

---

## If only three things happen this month

1. **Send Ayomide the updated Oil & Gas build.** It's finished. Someone is idle waiting for it —
   and the cost of the wait is now concrete: on 4 August the same person said he would hand-build
   an Excel CRM for a new vertical, which the finished build already does. Sending it is also the
   cleanest live test of whether the shared-capability model holds (Q2).
2. **Get Fireflies access and the data policy signed off.** Nine builds and the whole Context
   Graph sit behind it.
3. **Name the Claude org Owner and flip one permission.** The single build in daily use is
   blocked by a toggle.

**And one that costs a single message:** chase the Zoho API key for Q3/B45. It was called
"expected within days" on 28 August and nothing else is in the way.

---

## The immediate tier

Added 21 September. Sixteen small, owned, startable items mined from the last 75 days —
see [QUICK-WINS.md](QUICK-WINS.md). They carry a different risk profile to everything above:
each is a **single mention**, so some may already be done or assigned. Each needs one confirming
message to its owner before scoping, not a meeting.

Three of them (Q1–Q3) are existing builds pointed at a new target rather than new work.
