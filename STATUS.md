# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

3 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 5 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 5 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- A · INTEGRATION BUILDER
- C · BUILDER
- C · VERIFIER

## Waiting for you

- GPT's GitHub connector: the private repo has ONE collaborator
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## The numbers, in plain words

- **3 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **5 finished pieces** waiting to be checked and added in
- Claude account A has used **36%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 36% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-17T15:32:03.336Z · published by fable-root-a (controller · Account A root, Claude Fable 5.1, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T15:32:03.336Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **3** (pid 70387 up 24:27 · pid 82986 up 10:05 · pid 97998 up 02:55)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **36%** · B **91%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: 56f2068638e68d05a35b2620c308ba8957f5cd38  (fresh `git ls-remote`)
- localCanonicalHead: 56f2068638e68d05a35b2620c308ba8957f5cd38  · agrees
- candidateBranch: fold-int-20260916 · candidateHead: NOT ON REMOTE
- lastVerifiedAt: 2026-09-17T15:31:15.770Z
- subject: docs(control-room): the process freeze, verbatim — the last planning document, and 00 carries the standing instruction

- publicMirrorReadable: true (unauthenticated fetch of the raw mirror, 2026-09-17T15:32:19.319Z)

## candidates ready for verdict / fold
- c-census-green-20260917 @ 99b432933a — r1 PASS (product 8 · assurance 7 · MIN 7): FOLD-ELIGIBLE for the next integrated fold; two non-blocking findings (an unrouted twin sentence in mergeForwardCacheWrite.ts:56,58; names now de-duplicated in the merged-forward log, unmentioned in the body)
- c-identity-census-20260917 @ cd7efdbd11 — pushed; r1 VERDICT RUNNING on C
- fold-bc-20260916 @ 8275960165 — r3 PASS (B3 closed; nothing r2 held regressed); FOLD-ELIGIBLE for the integrated fold ④ only
- lane A provider data @ 48fe3fc28c — r3 PASS 8·7; waits in the integrated fold ④
- BANDCAMP-IDS @ 3499e78b57 (origin/worktree-agent-afa25af8ff9958d25) — r1 PASS; folds behind the consent law in ④
- lane F @ 8bca66c4d0 — r4 RETURN (product 6 · assurance 7): F25 the cookie notice still covers the lead title at every landscape size, F24 three sizes missing from the probe; the three-item fix round r5 is RUNNING on C
- cand-claim-20260917 @ 0345ac0544 — the two-defect fix is STRANDED as 25 staged files in /Users/jamescuthbert/able-work/cand-claim (its builder died with the 14:40Z window kill); needs a resume builder to commit, then ONE fresh verdict
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings); does not enter a candidate until its fixes land
- LANE MATERIALS — STRANDED again: 26 dirty files in /Users/jamescuthbert/Able/.claude/worktrees/agent-ad409ed963fb3ce99, no commit (its in-session builder died with the 14:40Z window kill); needs a resume builder

## running lanes
- A · claude-opus-5 · INTEGRATION BUILDER — the integrated fold ④ — rebuild fold-int-20260916 from canonical d209087f8a by merge, merge lane A 48fe3fc28c + fold-bc 8275960165 + Bandcamp bff0ffcb77 (known conflicts: actSpec.ts, four eye-check receipts, SEATS.md), then the hard gate: providerOrder.ts and providerCapabilities.ts absorbed into resolveProviderHierarchy and the domain capability projection; proof floor at 390/834/1440; RECORD.md with five claims; no self-certification (pid 82986 · log /tmp/claude-a-int.log)
- C · claude-fable-5-1 · BUILDER — lane F r5 — the r4 work order: F25 the title x/y-disjoint from the consent notice by construction, F25's first-visit probe on the public route (red on the parent, green after), F24 three more sizes (pid 70387 · log /tmp/claude-c-f6.log)
- C · claude-fable-5-1 · VERIFIER — c-identity r1 on cd7efdbd11 — five claims: the census is complete (independent grep), one facade with no caller migrated and equal outputs on real Maribou objects, the shadow ledger records a planted disagreement, nothing reaches a fan page (served HTML byte-identical), floor (pid 97998 · log /tmp/claude-c-identity-v.log)
- FINISHED, UNRECORDED — pid 70388 is not in the process table and the seat has not written its outcome yet: c-census r1 on 99b432933a — five claims: the class shrinks (45→43, no baseline raised), sound strings byte-identical on the served build, counted strings never on a fan page, floor reproduced at the parent, escapes true of the diff
- 3 headless claude process(es) in the table at 2026-09-17T15:32:03.336Z (pid 70387 up 24:27, pid 82986 up 10:05, pid 97998 up 02:55) — 3 of them recorded as lanes above

## blockers
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- the integrated fold ④ lands on fold-int-20260916 → push by reference → ONE fresh adversarial verdict (Fable on A, five claims, the attached acceptances: QuickLaunch present or named for ⑥ · real proof at 390/834/1440 DUAL and WIDE · lane A's federation pieces survive · consent-zero · the play button still mounts on the first tap) → PASS folds to canonical → backpressure drops
- the c-census verdict (C) → PASS folds with or right after ④; c-identity @ cd7efdbd11 (pushed) gets its verdict on A Fable once the scorer finishes (A band: two)
- lane F r5 lands (C) → fresh verdict → joins the next fold
- resume the two stranded builders on A within its band: Materials (26 files → one commit → verdict) and the cand-claim fix (25 staged → commit → re-cut → ONE verdict → fold); at most one product branch waiting for integration from here
- backpressure clears → the 14-packet 310-point queue resumes on A; then ⑤ Materials / Bandcamp and ⑥ the reference Work — the founder's ten-step order in 00

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  78%  ·  Fable  73%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 36% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
