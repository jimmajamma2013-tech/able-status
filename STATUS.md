# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

1 thing is being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 5 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 5 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- C · BUILDER

## Waiting for you

- GPT's GitHub connector: the private repo has ONE collaborator
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## The numbers, in plain words

- **1 job** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **5 finished pieces** waiting to be checked and added in
- Claude account A has used **44%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 44% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-17T16:35:04.613Z · published by fable-root-a (controller · Account A root, Claude Fable 5.1, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T16:35:04.613Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **1** (pid 76231 up 16:14)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **44%** · B **91%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: 97657fc9b15358520af3cbd80da7c598362a2f46  (fresh `git ls-remote`)
- localCanonicalHead: 97657fc9b15358520af3cbd80da7c598362a2f46  · agrees
- candidateBranch: fold-int-20260916 · candidateHead: dcacb66993d7e93c87cdf049f333cd807ca665b7
- lastVerifiedAt: 2026-09-17T16:35:03.617Z
- subject: docs(verdicts): three Account C verdicts received — c-census PASS, c-identity RETURN on the record, lane F r5 PASS

## candidates ready for verdict / fold
- THE INTEGRATED FOLD ④ @ dcacb66993 on fold-int-20260916 (pushed by reference) — lane A + fold-bc + Bandcamp merged by an Opus reconciliation builder; the two provider tables absorbed into the one resolver and the capability projection (94 of 110 cells reconciled, domain wins on purchase, measured table wins on control); the hero points into the stage; consent per provider; the play button still mounts on the first tap (14/14); build 0, tsc 0, vitest 1180/1180, lineage 0; RECORD with five claims. NOT claimed: DUAL at 834 and WIDE at 1440 on the Work (a widened phone — named for ⑥/⑧). Lane F 318bee7a6c still to merge (three conflicts: two receipts, actSpec.ts) and F26 to close inside the fold; then ONE fresh verdict.
- lane F @ 318bee7a6c — r5 PASS (product 6 · assurance 7): F25 closed by construction, the title-size taste call ACCEPTED; FOLD-ELIGIBLE for the ONE integrated fold ④ with F26 (the landscape title breaks mid-word at widths 700–844) carried as a named gate item inside the fold; F27, the consent-band race and 844×390 carried
- c-identity-census-20260917 @ c30b9a0bb8 — r2 RETURN (product 7 · assurance 5): fourteen more single-line title joins the census missed; the code measured harmless by bytes. r3 building on C: a deterministic structural sweep generates the census, so the class cannot recur
- c-census-green-20260917 @ 99b432933a — r1 PASS (product 8 · assurance 7 · MIN 7): FOLD-ELIGIBLE for the next integrated fold; two non-blocking findings (an unrouted twin sentence in mergeForwardCacheWrite.ts:56,58; names now de-duplicated in the merged-forward log, unmentioned in the body)
- fold-bc-20260916 @ 8275960165 — r3 PASS (B3 closed; nothing r2 held regressed); FOLD-ELIGIBLE for the integrated fold ④ only
- lane A provider data @ 48fe3fc28c — r3 PASS 8·7; waits in the integrated fold ④
- BANDCAMP-IDS @ 3499e78b57 (origin/worktree-agent-afa25af8ff9958d25) — r1 PASS; folds behind the consent law in ④
- cand-claim-20260917 @ 0345ac0544 — the two-defect fix is STRANDED as 25 staged files in /Users/jamescuthbert/able-work/cand-claim (its builder died with the 14:40Z window kill); needs a resume builder to commit, then ONE fresh verdict
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings); does not enter a candidate until its fixes land
- LANE MATERIALS — STRANDED again: 26 dirty files in /Users/jamescuthbert/Able/.claude/worktrees/agent-ad409ed963fb3ce99, no commit (its in-session builder died with the 14:40Z window kill); needs a resume builder

## running lanes
- C · claude-fable-5-1 · BUILDER — identity census r3 — the census becomes a deterministic STRUCTURAL sweep (every title/name/slug-keyed map, every normalised equality, every slugify call site), generated rows, two planted controls, the LIMIT paragraph corrected, the mirror guard made real (pid 76231 · log /tmp/claude-c-identity-r3.log)
- FINISHED, UNRECORDED — pid 70388 is not in the process table and the seat has not written its outcome yet: c-census r1 on 99b432933a — five claims: the class shrinks (45→43, no baseline raised), sound strings byte-identical on the served build, counted strings never on a fan page, floor reproduced at the parent, escapes true of the diff
- FINISHED, UNRECORDED — pid 97998 is not in the process table and the seat has not written its outcome yet: c-identity r1 on cd7efdbd11 — five claims: the census is complete (independent grep), one facade with no caller migrated and equal outputs on real Maribou objects, the shadow ledger records a planted disagreement, nothing reaches a fan page (served HTML byte-identical), floor
- FINISHED, UNRECORDED — pid 54445 is not in the process table and the seat has not written its outcome yet: c-identity r2 on c30b9a0bb8 — the Work-scoped census complete by an independent sweep, the retitle honest, served bytes re-diffed after the rename, the shadow deterministic over eight rooms, floor
- 1 headless claude process(es) in the table at 2026-09-17T16:35:04.613Z (pid 76231 up 16:14) — 1 of them recorded as lanes above

## blockers
- ACCOUNT A IS AT ITS SESSION CEILING (77% of the five-hour window; the guard's ceiling is 78%): no new builder or in-session fan-out on A until the window rolls (~19:40 BST). The root seat's own work on A stays light (git reconciliation, packets, publishing). Account C carries the identity r3 builder and sits ~8% above its weekly floor; Account B rests.
- THE DIRECTIVE SCOREBOARD AUDIT IS PAUSED BY RULE at Account A session 70% (ceiling 78%): all nine surface measurements, the three material researchers and most refutations are journaled (run wf_ddf8e9b5-96c, 70 agents); the journey walk, the no-template test, the Opus synthesis and the critic resume from cache when A's five-hour window resets (~19:45 BST). The integrated fold builder on A must not be killed by a window reaching 100% — the 13:4x class.
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- 19:40 BST, when A's window rolls: (1) root merges lane F 318bee7a6c into fold-int (two receipts re-run, actSpec.ts keeps both sides as the builder did twice) → (2) ONE bounded Fable builder closes F26 inside the fold (one divisor or wrap rule + a no-broken-word assertion) → (3) ONE fresh adversarial verdict on the fold (five claims + the attached acceptances; the 203-size scan expects 0; the anti-template-but-still-Able gate) → PASS folds ④ to canonical
- then the two founder-measured packets, in order: RETURN-EXACT + ONE TRANSPORT (Back lands exactly; a persistent transport while sound plays — James: 'no way to switch off') and QUICKLAUNCH-STRIP (retire 'Listen elsewhere' on the Room; one active mark, the rest as text) — docs/audits/2026-09-17-directive-scoreboard/packets/
- resume the directive scoreboard from cache (run wf_ddf8e9b5-96c: journey, no-template, the Opus synthesis, the critic) and rank the remaining packets: Materials from the REAL sleeve (mustard, dirty red, concrete, tobacco; the record's own lettering), the Groove List, the reference Work at DUAL/WIDE, People/Relationship, Film V2
- the identity census r3 (C) → its verdict → folds with the next fold; c-census PASS folds with ④ or right after
- the fourteen paused packets resume on A once at most one product branch waits for integration

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  81%  ·  Fable  79%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 44% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
