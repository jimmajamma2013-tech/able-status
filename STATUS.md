# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

4 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 6 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 6 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- 4 jobs are running (going 01:31, going 00:10, going 32:45, going 11:11).
- ⚠️ The written description below may be out of date — it lists 7 but 4 jobs are actually running:
  - A · Fable · in-session BUILDER
  - A · Fable · in-session BUILDER
  - A · Fable · VERIFIER on cand-play-20260917 @ 2223ef94fe
  - A · Fable · BUILDER on cand-claim-20260917 @ 0345ac0544
  - C · Fable · VERIFIER: Bandcamp ids r1 on 3499e78b57
  - C · Fable · BUILDER: Phase 4 points 46–49
  - C · Fable · VERIFIER: lane F r4 on 8bca66c4d0

## Waiting for you

- GPT's GitHub connector: the private repo has ONE collaborator
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## The numbers, in plain words

- **4 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **6 finished pieces** waiting to be checked and added in
- Claude account A has used **32%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 32% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
| **Claude B** | 91% of its week used | Nearly spent, and its top tier is closed until it refills Sep 22 at 10:59pm. Held for emergencies only. |
| **Claude C** | not a separate account | Signed into the same login as A, so work on it is billed to A. One subscription is unreachable until it is signed in properly. |
| **Codex / Astra** | limit reached | Nothing can be sent here until it resets. |
| **Gemini · Grok · Kimi** | no meter exists | They can still be CALLED. What cannot be done is knowing how much is left — none of them publish a usage number. So they are used for bounded second opinions, never for work the build depends on. |
| **Local models** | free, no limit | Three models on this machine. Good for mechanical work that needs no judgement; one heavy one at a time, because memory is the limit rather than money. |

⛔ **A lane with no meter is shown as "no meter", never as zero.** A broken reading and an unused
account look identical from the outside, and only one of them is safe to spend against.


---

_Everything below is the machine detail, for GPT. You do not need to read it._

# ABLE · LIVE STATUS
_2026-09-17T14:25:04.191Z · published by fold-root-20260916 (controller · Account B root, Opus 5 1M) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T14:25:04.191Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **4** (pid 7977 up 01:31 · pid 10529 up 00:10 · pid 48461 up 32:45 · pid 84769 up 11:11)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **6** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3) · night-p0-play-button-20260917 @ d94f4d4f26 (+2)
- verdictsPending: **6** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a · night-p0-play-button-20260917 @ d94f4d4f26
- meters weekly: A **32%** · B **91%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: f1af69381774c9ba20ce9b480032d1933e8edb61  (fresh `git ls-remote`)
- localCanonicalHead: f1af69381774c9ba20ce9b480032d1933e8edb61  · agrees
- candidateBranch: cand-play-20260917 · candidateHead: 2223ef94fe042720164ee364dad17efa45625d59
- lastVerifiedAt: 2026-09-17T14:25:03.302Z
- subject: feat(capacity): the reserve floors become a machine — no account is driven to zero before its reset

- publicMirrorReadable: true (unauthenticated fetch of the raw mirror, 2026-09-17T14:25:20.538Z)

## candidates ready for verdict / fold
- cand-play-20260917 @ 2223ef94fe — canonical + the play-button P0. Clean merge, 7 src files plus useFilmStart.ts and two new tests. VERDICT IN FLIGHT on A.
- cand-claim-20260917 @ 0345ac0544 — canonical + consent-P0 + three-doors-P0, both clean, three-doors test present. Its two known defects are being fixed now, then it needs ONE fresh verdict on the post-fix SHA.
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings, all survived adversarial refutation). Does not enter a candidate until its fixes land.
- BANDCAMP-IDS @ 3499e78b57 — 17/17 album refs resolved through the promotion path, both controls, ids on ProviderObjectRef; PUSHED; builder's honest residue: the Work view's eye-check is red before AND after (126→169 P0, all inside provider iframes — an instrument question), tracks proven on a fixture only, the promotion gate not widened. r1 RUNNING on C.
- lane F @ 8bca66c4d0 — r3's F22 (probe widened to 13 sizes, 0% everywhere) and F23 (record block never outranks the lead; test planted 3/4 red) closed by the builder; PUSHED; builder names a NEW first-visit overlap at 1024×768 (consent notice over the title tail) and leaves F20/F21 open; r4 RUNNING on C

## running lanes
- A · Fable · in-session BUILDER (the Account A seat's) — fold-bc r2's one blocker B3: the renderer re-sorts a band composeWork had ordered (served on mother-2020) — in /Users/jamescuthbert/able-work/fold-bc-20260916
- A · Fable · in-session BUILDER (the Account A seat's) — LANE MATERIALS resumed from 15 stranded files: eight environment modes over the derived atmosphere; Relationship/Maker/Receipt leave generic black — in agent-ad409ed963fb3ce99
- A · Fable · VERIFIER on cand-play-20260917 @ 2223ef94fe — the founder-reported play-button P0, merged onto current canonical with zero conflicts. Five claims: the defect gone measured the way it was found (both engines, tap not mouse), the working tap not broken, pause + reduced motion, the new tests actually discriminate, floor. Log /tmp/night-verify-play.log
- A · Fable · BUILDER on cand-claim-20260917 @ 0345ac0544 — closing the two defects two separate reviews found independently: the cleared domain ablemusic.co in a user-facing removal door, and the demoted phosphor green on the claim route; plus the three doors above the fold at 320 and 360. Log /tmp/night-fix-claim.log
- C · Fable · VERIFIER: Bandcamp ids r1 on 3499e78b57 (five claims incl. the promotion-gate plant and the eye-check cross-origin question) — log /tmp/claude-c-bcv.log
- C · Fable · BUILDER: Phase 4 points 46–49 — the identity-resolver census, one facade with unchanged behaviour, shadow mode + disagreement ledger over real Maribou objects (the Blackoak class) — new worktree /Users/jamescuthbert/able-work/c-identity; log /tmp/claude-c-identity.log
- C · Fable · VERIFIER: lane F r4 on 8bca66c4d0 (F22 at all 13 sizes, F23 on the S1 copy, the builder's own new 1024×768 consent-over-title regression, present-tense parity, floor) — log /tmp/claude-c-f5.log

## blockers
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure reads 4 delivered-but-unfolded product branches against a threshold of 2. It resumes when the candidates above fold.
- B is at 90% weekly with its Fable tier fully spent — reserve only, nothing dispatched there.
- OWED: one bounded independent verdict on the status bridge itself. It has failed to launch four times and is the oldest open debt on this seat.

## needs James
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- the play-button verdict lands → PASS folds it to canonical → the founder-reported P0 is live and deliveredUnfolded drops
- the claim fixes land → re-cut that candidate from the canonical of that moment → ONE fresh verdict → fold
- then backpressure clears and the 14-packet 310-point queue resumes on A

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  72%  ·  Fable  62%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 32% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
