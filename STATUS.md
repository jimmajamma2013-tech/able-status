# ABLE — what is happening right now

**Last updated 2 minutes ago.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

6 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 3 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 3 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.

## Being worked on right now

- 6 jobs are running (going 08:11, going 00:55, going 56:08, going 56:01, going 52:05, going 46:20).
- ⚠️ The written description below may be out of date — it lists 0 but 6 jobs are actually running:


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

- **6 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **3 finished pieces** waiting to be checked and added in
- Claude account A has used **100%** of its week — it refills **Sep 25 at 7pm**
- Claude account B has used **UNKNOWN%** of its week — it refills **UNKNOWN**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 100% of its week used | The one to spend. Routine work goes here. Refills Sep 25 at 7pm. |
| **Claude B** | UNKNOWN% of its week used | Nearly spent, and its top tier is closed until it refills UNKNOWN. Held for emergencies only. |
| **Claude C** | not a separate account | Signed into the same login as A, so work on it is billed to A. One subscription is unreachable until it is signed in properly. |
| **Codex / Astra** | limit reached | Nothing can be sent here until it resets. |
| **Gemini · Grok · Kimi** | no meter exists | They can still be CALLED. What cannot be done is knowing how much is left — none of them publish a usage number. So they are used for bounded second opinions, never for work the build depends on. |
| **Local models** | free, no limit | Three models on this machine. Good for mechanical work that needs no judgement; one heavy one at a time, because memory is the limit rather than money. |

⛔ **A lane with no meter is shown as "no meter", never as zero.** A broken reading and an unused
account look identical from the outside, and only one of them is safe to spend against.


---

_Everything below is the machine detail, for GPT. You do not need to read it._

# ABLE · LIVE STATUS
_2026-09-21T15:35:38.004Z · published by fable-root-a (controller · Account A root, Claude Opus 5 1M, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-21T15:35:38.004Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **6** (pid 38019 up 08:11 · pid 50414 up 00:55 · pid 69987 up 56:08 · pid 70243 up 56:01 · pid 72795 up 52:05 · pid 78703 up 46:20)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3)
- verdictsPending: **3** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587
- meters weekly: A **100%** · B **UNKNOWN%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: 32d33512a4024a602c4e33b2ba6165ed34043a9f  (fresh `git ls-remote`)
- localCanonicalHead: 32d33512a4024a602c4e33b2ba6165ed34043a9f  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 8f64a9d564b3b9815e6c8af0a3664af36333d297
- lastVerifiedAt: 2026-09-21T15:34:06.080Z
- subject: fold(work): the record answers the hand — fec2d58bfe

## candidates ready for verdict / fold
- none

## running lanes
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): c-person-r4 (BUILDER, C / Opus): the merged truth defect (a person page sounding another Work preview) plus the three defects r3 measured. Told NOT to chase the retired bar. Log /tmp/night-c-person-r4.log
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): c-verify-soundcloud (VERIFIER, C / Opus): soundcloud-player-comments-off @ 3d82a527ac. The claim that matters: the undocumented show_comments=false parameter actually suppresses comments, measured in a real browser. Log /tmp/night-c-verify-soundcloud.log
- 6 headless claude process(es) in the table at 2026-09-21T15:35:38.004Z (pid 38019 up 08:11, pid 50414 up 00:55, pid 69987 up 56:08, pid 70243 up 56:01, pid 72795 up 52:05, pid 78703 up 46:20) — 0 of them recorded as lanes above

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
- FOUNDER #88, TWO DECISIONS: (1) the person-page bar is REPLACED — THE PERSON PAGE BAR, seven clauses, equally excellent not equally theatrical; the old "COMPLIANT >= the Maribou front page" clause is RETIRED and must never be cited. (2) The canonical public URL NEVER changes; the engine split is an ARCHITECTURE round with built-output-only acceptance. Both in docs/decisions/2026-09-20-JAMES-THE-TWO-DECISIONS-...md
- FINISH r4 first, preserving the truth invariant — a person page must never sound another Work record. Then re-judge r3+r4 against THE PERSON PAGE BAR, not the retired one.
- CONTINUE THE SOUNDCLOUD LANE: verdict running; fold on PASS.
- THEN the architecture round for the engine separation. Acceptance is bytes of built JS/HTML per address plus the real /maribou-state Fast-4G budget. A source-level import check is NOT acceptance — it would have passed green while the bytes never moved.
- Keep every account at its band and integrate before dispatching. C carries 2, A is root and builds nothing, B is spent.

## meters
```
[33m  ⚠️ An UNKNOWN above is not a low reading. Do not route work on it,[0m
[33m     and no "spend this one" verdict is issued while a meter is unreadable.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  33%  ·  Fable  50%  ·  resets Sep 26 at 11pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account C at weekly 33% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
