# Read this before quoting a build number

Four different numbering schemes are in use across VGG documents and several of them collide.
Anyone reading two documents side by side will mis-read at least one build. This resolves them.

**Working rule: name the build, not the number.**

---

## The real collision

**B49, B50 and B51 mean two different things.**

| Number | In the main backlog | In the MindLab notes |
|---|---|---|
| B49 | Priority Meeting Queue | HR Training & Assessment |
| B50 | Convening Invite-List Builder | Compliance Report Drafter |
| B51 | Meeting → Money Follow-Through | 15-Step Customer Service Collapse |

Six builds, three numbers. **The MindLab set is renumbered ML-49 … ML-55** in
[BUILDS.md](BUILDS.md). Anything still saying B49–B55 for MindLab predates the fix.

---

## Schemes that look like the backlog but aren't

**The practice catalogue** uses A1–A3 / B1–B3 / C1–C3 for *commercial offers*, not builds:

| Catalogue ref | Actually refers to |
|---|---|
| B1 | AI-native CRM pilot → backlog **B16** |
| B2 | Post-meeting intelligence package → backlog **B1 + B3** |
| B3 | Policy & HR knowledge assistant → backlog **B43** |

**The GCEO workstation backlog** uses its own local B1–B14 for 14 unrelated tasks. Its B2 is
"meeting archive backfill," not the Fireflies Consolidation build.

---

## Aliases — same build, two names

| These are one build | Note |
|---|---|
| **B46 = E2** — BMC Request Intake / BMC Briefing Assistant | The gate-1 document still lists it as "identified." It shipped Sep 8 — that entry is stale |
| **B45 = E1** — Support-Triage Rollout / support-drafting tool | Same person, same surface. **Settled 21 Sep: nothing is built.** A 28 Aug action item is to obtain a Zoho API key *in order to build* the reply automation, which corroborates E1 and contradicts B45's "V1 exists". Quote it as: not built, blocked on the key |
| **B16 = V1** — Oil & Gas CRM | V2 and V3 are phases of B16, not separate builds |
| **B22 = V4** — WhatsApp prospect capture | Both claim a V1 exists; there's no artifact or run evidence, and a 10 Jul request asks for the tool to be *developed* for DealOS. **Still unverified, and the evidence now leans towards "not built"** |
| **B17 = V5 · B19 = V6 · B32 = V7 · B23 = E6** | Gate-1 use-case refs pointing back at backlog items. Counting both lists double-counts by 8 |
| **B43 = ADA = AiDA** | Spelled both ways across documents. One build. Listed twice in the backlog because it has two owners |
| **B44** appears twice | One build, two owners — infrastructure and hosting |

---

## Overlaps worth a decision

Not duplicates, but close enough that someone should choose deliberately.

- **B10 vs B20.** B10 is the commercial *signal* roll-up for the GCEO; B20 is sales-ops *pipeline*
  aggregation. Both aggregate subsidiary commercial data weekly. Merge candidates.
- **B7 vs LB-1.** Two month-end packs, two entities, two different ERPs. Confirm they aren't
  converging on the same build under different names.
- **B14 vs the value-for-money function.** Flagged as one of the strongest overlaps in the
  engagement — both track commitments against delivery.
- **B34 and ML-50.** Both are regulated-operations work blocked by the same data-governance
  question. ML-52 answers it for both.

---

## Counting

Different documents give different totals, all of them defensible:

- **48** — builds mined from the Leaders Series interviews, which is what the architecture covers
- **57** — B-numbers issued in the main backlog today *(was 51; B52–B57 added 21 Sep)*
- **~68** — every distinct build including MindLab, the VGN finance set, and the EduTech cases
- **16** — the immediate-tier items **Q1–Q16**, tracked separately in
  [QUICK-WINS.md](QUICK-WINS.md). **Do not add these to the build count** — three of them are
  existing builds pointed at a new target, and the rest are single-mention asks that still need
  confirming with their owner
- **27** — builds and plans sent in the second wave on 16 September, which is a delivery count,
  not a backlog count

**New prefix: Q.** Q-numbers are immediate-tier asks, not backlog builds. If one survives owner
confirmation and turns out to be structural, it gets a B-number and the Q-number is retired.

When a number needs to appear in a status report, say which of these it is.
