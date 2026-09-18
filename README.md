# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

10 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 3 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 3 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- 10 jobs are running (going 15:48, going 15:48, going 15:48, going 15:48, going 09:34, going 09:34, going 03:20, going 03:20, going 01:29:18, going 01:29:18).
- ⚠️ The written description below may be out of date — it lists 0 but 10 jobs are actually running:


## Waiting for you

- THREE RULINGS, one line each:
- TOOL LOGINS for the instrument matrix
- GITHUB ACTIONS — the cause is now GitHub's own sentence
- THE AUDIO WARM-UP RULING
- SUPABASE DISK IO: your message says a disk-budget risk was flagged; no seat has seen it and nothing in the repo records it. If Supabase emailed you, forward the numbers. To let a seat read it directly, run `supabase login` once in a terminal
- GITHUB BRANCH PROTECTION on able-rebuild-v1 needs GITHUB PRO first — measured: gh api …/branches/able-rebuild-v1/protection answers "Upgrade to GitHub Pro or make this repository public to enable this feature"
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS

## The numbers, in plain words

- **10 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **3 finished pieces** waiting to be checked and added in
- Claude account A has used **92%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 92% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-18T14:57:58.273Z · published by fable-root-a (controller · Account A root, Claude Opus 5 1M from 22:5x, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-18T14:57:58.273Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **10** (pid 12646 up 15:48 · pid 12648 up 15:48 · pid 12650 up 15:48 · pid 12651 up 15:48 · pid 54325 up 09:34 · pid 54327 up 09:34 · pid 69075 up 03:20 · pid 69094 up 03:20 · pid 74500 up 01:29:18 · pid 74507 up 01:29:18)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3)
- verdictsPending: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587
- meters weekly: A **92%** · B **91%** · band: 70%+ → 0 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: 30df339537cf25ab29ffd2207d342e4389eb3c8a  (fresh `git ls-remote`)
- localCanonicalHead: 30df339537cf25ab29ffd2207d342e4389eb3c8a  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 8f64a9d564b3b9815e6c8af0a3664af36333d297
- lastVerifiedAt: 2026-09-18T14:57:00.971Z
- subject: docs(canon): provider precedence follows intent — 02 §3, 03 point 101 annotated, the brief re-exported (#68)

## candidates ready for verdict / fold
- none

## running lanes
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): IMAGE BOUNDARY r3 (builder): the fix the second verifier prescribed — the Music page's data passes the one image check where it is created, so a disguised Google address can never reach the page; the backstop reads serialised strings properly
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): GATE REPAIR (the other tab): the three gates every slice fights — the screenshot gate treating a folder as a page, the quote checker's false alarms, and the escape counter at its limit
- 10 headless claude process(es) in the table at 2026-09-18T14:57:58.273Z (pid 12646 up 15:48, pid 12648 up 15:48, pid 12650 up 15:48, pid 12651 up 15:48, pid 54325 up 09:34, pid 54327 up 09:34, pid 69075 up 03:20, pid 69094 up 03:20, pid 74500 up 01:29:18, pid 74507 up 01:29:18) — 0 of them recorded as lanes above

## blockers
- THE ORDER FROM THE FOUNDER (2026-09-17 ~18:2x): keep moving through Maribou to 11/10, all models, no stopping, never reopening the Room plan or starting a broad audit. The chain, with ④ LANDED at e509cadc8b: c-census + c-identity merged onto canonical by root (one import hunk, one registry hunk) → one fresh verdict on the merged head → fast-forward → RETURN-EXACT + the sounding door (building on A) → its verdict → the Work opening with QuickLaunch → Materials from the real sleeve → Groove List → DUAL/WIDE → People/Relationship → Film V2. The scoreboard audit stays paused. B is under its weekly floor (9% left); C has 4% above its floor; A carries the builders and verdicts.
- ACCOUNT A IS AT ITS SESSION CEILING (77% of the five-hour window; the guard's ceiling is 78%): no new builder or in-session fan-out on A until the window rolls (~19:40 BST). The root seat's own work on A stays light (git reconciliation, packets, publishing). Account C carries the identity r3 builder and sits ~8% above its weekly floor; Account B rests.
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- THREE RULINGS, one line each: (1) should Reduce Motion stop switching off the buzz? (2) the audio warm-up — Able serves it or it waits for the first tap? (3) may Able release the old Lane B file claims (B is your reserve and its scheduled jobs are now off)?
- TOOL LOGINS for the instrument matrix (each unlocks one row; none blocks today's build): a real Sentry project key (the Sentry code is already wired — the key in the settings is a placeholder) · a free Replay login · Greptile TREX switched on · a BrowserStack account for real-iPhone testing · Figma sign-in if we use it
- GITHUB ACTIONS — the cause is now GitHub's own sentence (gh api …/check-runs/105264398173/annotations): "The job was not started because recent account payments have failed or your spending limit needs to be increased. Please check the 'Billing & plans' section in your settings." Action: github.com/settings/billing on jimmajamma2013-tech → fix the failed payment or raise the Actions spending limit → re-run one workflow on able-rebuild-v1. ~3 minutes. Until then every remote check is meaningless; the native Definition-of-Done runs locally per commit (tsc · vitest · build-check · eye-check · lineage), and the factory branch's act-based fallback (scripts/factory/ci-local.sh) is UNPROVEN until one job runs end to end.
- THE AUDIO WARM-UP RULING (the last consent breach): arriving at the phone Room tells Apple a visitor came, because the first song is pre-fetched so the first tap is instant. Either Able serves that pre-fetch itself (privacy kept, the tap stays fast, Able pays the bytes) or the pre-fetch waits for a first gesture (privacy kept, the first tap is slower). Which?
- SUPABASE DISK IO: your message says a disk-budget risk was flagged; no seat has seen it and nothing in the repo records it. If Supabase emailed you, forward the numbers. To let a seat read it directly, run `supabase login` once in a terminal (only you can sign in)
- GITHUB BRANCH PROTECTION on able-rebuild-v1 needs GITHUB PRO first — measured: gh api …/branches/able-rebuild-v1/protection answers "Upgrade to GitHub Pro or make this repository public to enable this feature" (the repo is private on the free plan). So: on the same billing visit, upgrade the jimmajamma2013-tech account to GitHub Pro (about $4/month), then settings/branches → rule for able-rebuild-v1 → block force pushes and deletions. This is the control that cannot be talked around; four verifiers each routed around a local hook. ~4 minutes with the Actions fix.
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS (not before): `supabase login` in a terminal (~1 min) · `sentry-cli login` and confirm the Railway DSN (~3 min) · Replay account + MCP connection (~5 min) · Greptile dashboard: enable T-Rex for UI PRs only (~2 min) · Mobbin + Refero accounts and a full Figma seat (~10 min) · Cursor: sign in, connect GitHub, create Project ABLE (~5 min) · Conductor and Augment Intent sign-ins for the bake-off (~5 min each) · Lyssna for human taste tests, later.

## next actions (in order)
- VERIFIERS, one or two at a time as the five-hour window allows (it read 72% at 12:33): the backlog merge's r3 (a test fix), the second review-findings slice, Spotify packet two, the instruments (handshake gate + Capacity Room), the vitest register
- VISIBLE PHASE 12 (the founder's routing, adopted): the Groove List → the reference People and the Holly/Matt Relationships as real doors → the Room's own tablet/desktop layout → the Deluxe 2LP as a real object
- FEEL, in GPT's order: touch truth → time truth → the Room responds to sound
- THE FILM, behind Phase 12: compileFilmPlan printed as data first (GPT Step 2 and the census agree)
- THE TWO-DAY COMPARISON 2026-09-19 ~21:00 BST

## meters
```
[31m⛔ A IS AT OR PAST THE 90% RESERVE FLOOR — A stops building and orchestrates only.[0m
     [31m   An exhausted A stops BOTH lanes, and B’s meter then expires unspent.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  88%  ·  Fable  92%  ·  resets Sep 19 at 11pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account C at weekly 88% → [1m0 builder(s)[0m · preserve for blockers until Codex and the second Claude account return
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
