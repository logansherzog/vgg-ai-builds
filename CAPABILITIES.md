# Nine capabilities, not sixty-eight builds

Sixty-eight builds is a list, not a plan. Most of them are the same four or five machines pointed
at different departments — a CRM for oil and gas is the same object as a CRM for power, and both
are the same object as the BGP new-business tracker.

Collapsing them into **nine shared capabilities** is what makes the work finishable. Each new
subsidiary then becomes a *configuration*, not a project.

---

## The nine

| # | Capability | Phase | Builds it absorbs |
|---|---|---|---|
| 1 | **Capture & Signal Engine** | I | B2 (the substrate) · B22 generalised into a channel adapter · the capture halves of B12, B13, B35 · **B53** · **B54** (the bank-data feed) |
| 2 | **Context Graph + Decision Ledger** | I | B1 · B3 · B6 · B44 · B40 · *(proposed)* B5 · *(proposed)* B24 · plus the Decision Ledger, which is new |
| 3 | **Execution Management** | II | B12 · B13 · B14 · B46 · the commitment-capture half of B35 · **B52** |
| 4 | **Commercial OS** | II | B16 (the template) · B17 · B18 · B19 · B20 · B21 · B23 · B10 · B42 · **B56** |
| 5 | **People OS** | III | B25 · B26 · B27 · B28 · B29 · B30 · B31 · *(proposed)* B39 |
| 6 | **Finance Intelligence** | III | B7 · B9 · B11 · B33 · B48 as the access layer · LB-1/2/3 unmapped · **B54** consumed here, captured in Capability 1 |
| 7 | **Governance & Controlled Workflow** | III | B32 · B34 · B41 · B43 · *(proposed)* B37 · **B55** |
| 8 | **Organisational Artifact Engine** | IV, gated | B4 · B8 · B36 · B38 · the narrative half of B7 · the drafting half of B35 |
| 9 | **AI Interface** | I — deliberately early | B15 · *(proposed)* B47 · *(proposed)* B45 |

**B57 does not sit inside a capability — it is how the others get instantiated.** The
spreadsheet-to-system intake is the repeatable method behind every Commercial OS and People OS
configuration. Treating it as a build in its own right is what stops each new unit being a project.

**Capability 3 is roughly 60% built already.** It extends the existing tracking systems rather
than standing up a parallel one — which is the difference between adoption and another dashboard
nobody opens.

**Capability 9 sits in Phase I on purpose.** If staff have to open nine new tools, adoption fails
no matter how good the builds are. The interface ships with the first capability, not after the
last one.

**Capability 8 is gated** behind a quality bar: ≥80% coverage, ≥90% of diffs actioned within 48
hours, <5% error rate. Generated documents that go out under someone's name have to earn it first.

---

## The Decision Ledger

The most important object here doesn't come from any build request.

Capture is raw by design — it records what was said, not what is true. Truth gets decided
downstream, by a person, and the Decision Ledger is where that decision is written down: what
was decided, by whom, on what evidence, when. It lives inside the Context Graph rather than as
a separate application.

Without it, the graph is a pile of assertions with no authority, and the first time two sources
disagree there's no way to say which one counts.

---

## Sequence and the honest timeline

| Phase | Length | What lands |
|---|---|---|
| I | 6–7 weeks | Capture, Context Graph, the interface |
| II | 8–9 weeks | Execution Management, Commercial OS |
| III | 9–11 weeks | People OS, Finance, Governance |
| IV | 3–4 weeks | Artifact Engine, behind the quality gate |

**Sequential: 26–31 weeks. Overlapping II and III: 18–22 weeks — and that requires a funded
second builder.** One of those two has to be chosen. The plan doesn't work if neither is.

### Phase I has a visibility problem

Six or seven weeks of infrastructure produces nothing anyone can see. That's how goodwill dies
mid-build.

Three **sidecars** run alongside it — none of them touch the Context Graph, together about 16
builder-days, each one visible:

- **B43** — the policy assistant, rebuilt properly this time
- **B28** — the birthday database, raised three times by the GCEO and cheap to fix
- **B38** — the newsletter draft, which doubles as the first real test of the Phase IV quality bar

---

## Open questions

These are genuinely open. They need decisions, not more analysis.

1. **The six unplaced builds.** B5, B24, B37, B39, B45, B47 are in the backlog and absent from the
   architecture. Proposed homes: B5 → Cap 2 · B24 → Cap 2 or 4 · B37 → Cap 7 · B39 → Cap 5 ·
   B45 → Cap 9 · B47 → Cap 9. **Unconfirmed.**
2. **Second builder, or a longer timeline?** See above.
3. **Which pipeline is canonical** — OpenOps `deal_pipeline` or the Attio CRM? Two systems are
   being built toward; only one can be the record.
4. **B7 before B11.** The architecture puts the cross-entity rollup first. Doing one entity's pack
   end to end first is lower-risk and proves the pattern before it's generalised. Proposed
   inversion, needs a yes.
5. **Where the Data Layer and the Context Graph meet.** Two efforts are converging on overlapping
   ground and should be reconciled deliberately rather than by collision.
6. **Access rules on the transcript store.** Meeting transcripts are more sensitive than dashboard
   data and shouldn't inherit the same broad read access. This needs a security review before
   anything sensitive lands.
7. **The data-handling policy** — what may be ingested, who can read it, retention, residency,
   staff notice. Legal is reviewing. **Nothing gets ingested before it's approved.** This gates
   Capability 1, which gates nine builds.

---

## What isn't mapped yet

The architecture covers 48 of roughly 62 builds. Outside it: B49, B50 and B51 (created after the
document), all seven MindLab builds, and the three VGN finance builds. They need homes in the
same nine capabilities — most obviously Commercial OS, Governance, and Finance.
