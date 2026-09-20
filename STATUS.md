# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

2 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 3 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 3 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- 2 jobs are running (going 01:11, going 41:32).
- ⚠️ The written description below may be out of date — it lists 0 but 2 jobs are actually running:


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

- **2 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **3 finished pieces** waiting to be checked and added in
- Claude account A has used **86%** of its week — it refills **Sep 25 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 86% of its week used | The one to spend. Routine work goes here. Refills Sep 25 at 7pm. |
| **Claude B** | 91% of its week used | Nearly spent, and its top tier is closed until it refills Sep 22 at 10:59pm. Held for emergencies only. |
| **Claude C** | not a separate account | Signed into the same login as A, so work on it is billed to A. One subscription is unreachable until it is signed in properly. |
| **Codex / Astra** | see detail below | Nothing can be sent here until it resets. |
| **Gemini · Grok · Kimi** | no meter exists | They can still be CALLED. What cannot be done is knowing how much is left — none of them publish a usage number. So they are used for bounded second opinions, never for work the build depends on. |
| **Local models** | free, no limit | Three models on this machine. Good for mechanical work that needs no judgement; one heavy one at a time, because memory is the limit rather than money. |

⛔ **A lane with no meter is shown as "no meter", never as zero.** A broken reading and an unused
account look identical from the outside, and only one of them is safe to spend against.


---

_Everything below is the machine detail, for GPT. You do not need to read it._

# ABLE · LIVE STATUS
_2026-09-20T19:04:15.596Z · published by fable-root-a (controller · Account A root, Claude Opus 5 1M, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-20T19:04:15.596Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **2** (pid 38697 up 01:11 · pid 89781 up 41:32)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3)
- verdictsPending: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587
- meters weekly: A **86%** · B **91%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: b25e8350b37085386c1a3f69ebfa9faf696c4405  (fresh `git ls-remote`)
- localCanonicalHead: b25e8350b37085386c1a3f69ebfa9faf696c4405  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 8f64a9d564b3b9815e6c8af0a3664af36333d297
- lastVerifiedAt: 2026-09-20T19:04:09.120Z
- subject: fold(phone): a credited name's default door is Able's own person page — 48a6f0cc93

- publicMirrorReadable: true (unauthenticated fetch of the raw mirror, 2026-09-20T19:04:35.194Z)

## candidates ready for verdict / fold
- none

## running lanes
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): c-person-page-r3 (BUILDER, C / Opus): answering the person-page r2 RETURN — composition, member page and the empty right column first. Log /tmp/night-c-person-page-r3.log
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): c-verify-budget (VERIFIER, C / Opus): budget-public-address @ 3ed1ec0b25. The question put to it: should canonical accept a gate that is RED on the real address? Log /tmp/night-c-verify-budget.log
- 2 headless claude process(es) in the table at 2026-09-20T19:04:15.596Z (pid 38697 up 01:11, pid 89781 up 41:32) — 0 of them recorded as lanes above

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
- TWO BUILDERS ON C, its band maximum (C reads weekly 0% — the only full lane Able owns): person-page r3 on Opus, person-door-repoint on Fable. Root integrates; root does not build.
- ON PASS, fold each, then dispatch the next funded rows on C: unity-repoint-claim-doors · soundcloud-player-comments-off · budget-measures-the-public-address (all S), then core-cultural-gate (M)
- arrival-hero-announced-first is now READY — room-chronology-wide folded, so page.tsx is free. It is the row that ends the per-push budget escape
- RECALIBRATED 2026-09-20 (founder #84/#85): docs/live/TWO-DAY-QUEUE.md RECALIBRATED block — 8 units committed, the 9th held for a double RETURN, 10 rows written OUT with their consequences named
- NOT FUNDED this window: no-template (all three rows, so dimension 5 is out entirely), work-desktop-presence, room-lower-doors-wide, room-no-photograph, physical 404, edition-fold-door, relationship-exact-back, the two fail-open instruments, the eye tab-dock clause

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly   2%  ·  Fable   1%  ·  resets Sep 26 at 11pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m (ChatGPT subscription, gpt-6-astra)  weekly  93%  ·  resets Sat, 26 Sept, 19:20  ·  admission HOLD_RESERVE
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account C at weekly 2% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
