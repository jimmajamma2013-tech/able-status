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

- 3 jobs are running (going 00:24, going 52:48, going 41:41).
- ⚠️ The written description below may be out of date — it lists 2 but 3 jobs are actually running:
  - A · BUILDER
  - A · BUILDER (fix round)

## Waiting for you

- GITHUB ACTIONS — the cause is now GitHub's own sentence
- GITHUB BRANCH PROTECTION on able-rebuild-v1
- OPENAI CREDITS
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS

## The numbers, in plain words

- **3 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **5 finished pieces** waiting to be checked and added in
- Claude account A has used **60%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 60% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-17T21:23:51.869Z · published by fable-root-a (controller · Account A root, Claude Fable 5.1, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T21:23:51.869Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **3** (pid 83757 up 00:24 · pid 85811 up 52:48 · pid 99304 up 41:41)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **60%** · B **91%** · band: 55–65% → 1 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: de0407140ca0e555eac29055798253e075bb41ae  (fresh `git ls-remote`)
- localCanonicalHead: de0407140ca0e555eac29055798253e075bb41ae  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 8f64a9d564b3b9815e6c8af0a3664af36333d297
- lastVerifiedAt: 2026-09-17T21:23:51.038Z
- subject: feat(scripts): fold-commit — a verified branch lands on canonical in one commit attempt, with the two proofs and the census computed

- publicMirrorReadable: true (unauthenticated fetch of the raw mirror, 2026-09-17T21:24:07.646Z)

## candidates ready for verdict / fold
- THE INTEGRATED FOLD ④ @ c600dfd033 (pushed) — r1's two blockers closed at 05b9287474 (B1: the lead Work draws its people through originalOf, one-served-lineage exits 0 on the served HEAD; B2: the adapter's two stand-ins deleted, 0 hits for any table or kind derivation outside the domain, 27 of 30 releases compose identically and the three that changed are declared). Named, not proven: providers/manifestationKind.ts still derives a kind outside the domain; Deezer's embed capability disagrees with the stage; Mother draws no All-credits door; lineage does not yet ride the merge step. r2 VERDICT RUNNING on A.
- fold-bc-20260916 @ 8275960165 — r3 PASS (B3 closed; nothing r2 held regressed); FOLD-ELIGIBLE for the integrated fold ④ only
- lane A provider data @ 48fe3fc28c — r3 PASS 8·7; waits in the integrated fold ④
- BANDCAMP-IDS @ 3499e78b57 (origin/worktree-agent-afa25af8ff9958d25) — r1 PASS; folds behind the consent law in ④
- cand-claim-20260917 @ 0345ac0544 — the two-defect fix is STRANDED as 25 staged files in /Users/jamescuthbert/able-work/cand-claim (its builder died with the 14:40Z window kill); needs a resume builder to commit, then ONE fresh verdict
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings); does not enter a candidate until its fixes land
- LANE MATERIALS — STRANDED again: 26 dirty files in /Users/jamescuthbert/Able/.claude/worktrees/agent-ad409ed963fb3ce99, no commit (its in-session builder died with the 14:40Z window kill); needs a resume builder

## running lanes
- A · claude-fable-5-1 · BUILDER — THE WORK OPENING RECOMPOSED WITH QUICKLAUNCH (identity → sound → one human seam → QuickLaunch with one active mark → depth through doors; 'Listen elsewhere' retired) in quicklaunch-20260917 cut from canonical 60d0fd4cd5; task contract /tmp/packet-a-quicklaunch.md; journeys J1–J5 as Playwright on a served build; five claims for a fresh verifier (pid 85811 · log /tmp/claude-a-quicklaunch.log)
- A · claude-fable-5-1 · BUILDER (fix round) — exact Back + the sounding door r1 RETURN closes (B1 the door is inert — registry vs DOM disagree; B2 the destination carries no pause; B3 a hand-typed sound sentence) in return-exact-20260917 on 234b0a7933; ≤45 min; a different fresh instance re-stamps (pid 99304 · log /tmp/claude-a-return-fix.log)
- 3 headless claude process(es) in the table at 2026-09-17T21:23:51.869Z (pid 83757 up 00:24, pid 85811 up 52:48, pid 99304 up 41:41) — 2 of them recorded as lanes above

## blockers
- THE ORDER FROM THE FOUNDER (2026-09-17 ~18:2x): keep moving through Maribou to 11/10, all models, no stopping, never reopening the Room plan or starting a broad audit. The chain, with ④ LANDED at e509cadc8b: c-census + c-identity merged onto canonical by root (one import hunk, one registry hunk) → one fresh verdict on the merged head → fast-forward → RETURN-EXACT + the sounding door (building on A) → its verdict → the Work opening with QuickLaunch → Materials from the real sleeve → Groove List → DUAL/WIDE → People/Relationship → Film V2. The scoreboard audit stays paused. B is under its weekly floor (9% left); C has 4% above its floor; A carries the builders and verdicts.
- ACCOUNT A IS AT ITS SESSION CEILING (77% of the five-hour window; the guard's ceiling is 78%): no new builder or in-session fan-out on A until the window rolls (~19:40 BST). The root seat's own work on A stays light (git reconciliation, packets, publishing). Account C carries the identity r3 builder and sits ~8% above its weekly floor; Account B rests.
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- GITHUB ACTIONS — the cause is now GitHub's own sentence (gh api …/check-runs/105264398173/annotations): "The job was not started because recent account payments have failed or your spending limit needs to be increased. Please check the 'Billing & plans' section in your settings." Action: github.com/settings/billing on jimmajamma2013-tech → fix the failed payment or raise the Actions spending limit → re-run one workflow on able-rebuild-v1. ~3 minutes. Until then every remote check is meaningless; the native Definition-of-Done runs locally per commit (tsc · vitest · build-check · eye-check · lineage), and the factory branch's act-based fallback (scripts/factory/ci-local.sh) is UNPROVEN until one job runs end to end.
- GITHUB BRANCH PROTECTION on able-rebuild-v1 (the factory seat's finding after four verifiers each routed around a local hook: anything that can run code can; the control that cannot be talked around is server-side): github.com/jimmajamma2013-tech/able-music/settings/branches → add a rule for able-rebuild-v1 → block force pushes and block deletions (leave required checks off until CI lives). ~2 minutes. The local guard stays as a tripwire, recorded as such, never as the boundary.
- OPENAI CREDITS (blocks the cross-family GPT attack; the key is on disk): platform.openai.com/settings/organization/billing → add credits. ~2 minutes.
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS (not before): `supabase login` in a terminal (~1 min) · `sentry-cli login` and confirm the Railway DSN (~3 min) · Replay account + MCP connection (~5 min) · Greptile dashboard: enable T-Rex for UI PRs only (~2 min) · Mobbin + Refero accounts and a full Figma seat (~10 min) · Cursor: sign in, connect GitHub, create Project ABLE (~5 min) · Conductor and Augment Intent sign-ins for the bake-off (~5 min each) · Lyssna for human taste tests, later.

## next actions (in order)
- exact Back + the sounding door: the r1 fix round (A, Fable, pid in running) closes B1–B3 → a different fresh instance re-stamps r2 on the new SHA → PASS merges it onto canonical (same base as ④ plus this fold; one merge, one floor)
- THE WORK OPENING + QUICKLAUNCH is BUILDING on A (quicklaunch-20260917 from 60d0fd4cd5) → its five claims → fresh verdict → fold behind exact Back
- Materials from the REAL sleeve (Gemini's highest lever: the field from the artwork's concrete grey and mustard) → the Groove List → DUAL at 834 and WIDE at 1440 (the dimension that caps product at 4) → People/Relationship → Film V2
- the factory branch after a verifier PASSES its exact repaired SHA (three RETURNs so far) · the two speed tests re-measured after QuickLaunch · the two-day comparison on every metric in the master record's table, 2026-09-19 ~21:00 BST
- the boot ceiling: cite `node scripts/factory/boot-budget.mjs` (factory branch) or `npm run boot-cost` (canonical, 41.1k at 27b5d6a99c), never a remembered number; the only large reduction left is CLAUDE.md, James's file

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  84%  ·  Fable  84%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 60% → [1m1 builder(s)[0m · one builder + an occasional verifier
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
