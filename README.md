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

- A · VERIFIER

## Waiting for you

- GITHUB ACTIONS — the cause is now GitHub's own sentence
- GITHUB BRANCH PROTECTION on able-rebuild-v1 needs GITHUB PRO first — measured: gh api …/branches/able-rebuild-v1/protection answers "Upgrade to GitHub Pro or make this repository public to enable this feature"
- OPENAI CREDITS
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS

## The numbers, in plain words

- **1 job** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **5 finished pieces** waiting to be checked and added in
- Claude account A has used **61%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 61% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-17T22:16:54.511Z · published by fable-root-a (controller · Account A root, Claude Opus 5 1M from 22:5x, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T22:16:54.511Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **1** (pid 95382 up 00:27)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **61%** · B **91%** · band: 55–65% → 1 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: a40c31a8354cd37835463e4f51501848ad7ca16f  (fresh `git ls-remote`)
- localCanonicalHead: a40c31a8354cd37835463e4f51501848ad7ca16f  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 8f64a9d564b3b9815e6c8af0a3664af36333d297
- lastVerifiedAt: 2026-09-17T22:16:53.624Z
- subject: feat(fold): exact Back and the sounding door land on canonical — the founder's two phone defects closed (r2 PASS 8·9)

## candidates ready for verdict / fold
- THE INTEGRATED FOLD ④ @ c600dfd033 (pushed) — r1's two blockers closed at 05b9287474 (B1: the lead Work draws its people through originalOf, one-served-lineage exits 0 on the served HEAD; B2: the adapter's two stand-ins deleted, 0 hits for any table or kind derivation outside the domain, 27 of 30 releases compose identically and the three that changed are declared). Named, not proven: providers/manifestationKind.ts still derives a kind outside the domain; Deezer's embed capability disagrees with the stage; Mother draws no All-credits door; lineage does not yet ride the merge step. r2 VERDICT RUNNING on A.
- fold-bc-20260916 @ 8275960165 — r3 PASS (B3 closed; nothing r2 held regressed); FOLD-ELIGIBLE for the integrated fold ④ only
- lane A provider data @ 48fe3fc28c — r3 PASS 8·7; waits in the integrated fold ④
- BANDCAMP-IDS @ 3499e78b57 (origin/worktree-agent-afa25af8ff9958d25) — r1 PASS; folds behind the consent law in ④
- cand-claim-20260917 @ 0345ac0544 — the two-defect fix is STRANDED as 25 staged files in /Users/jamescuthbert/able-work/cand-claim (its builder died with the 14:40Z window kill); needs a resume builder to commit, then ONE fresh verdict
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings); does not enter a candidate until its fixes land
- LANE MATERIALS — STRANDED again: 26 dirty files in /Users/jamescuthbert/Able/.claude/worktrees/agent-ad409ed963fb3ce99, no commit (its in-session builder died with the 14:40Z window kill); needs a resume builder

## running lanes
- A · claude-opus-5 · VERIFIER — THE WORK OPENING WITH QUICKLAUNCH r1 on quicklaunch-20260917 @ dd66cad4a2 — five claims on a served build: the opening order at 390 on three Works, one active provider mark with the rest quiet text and 'Listen elsewhere' absent, consent-zero on the Work, nothing verified lost, the floor; plus two weighed: one provider room instead of a tiered stack, and the wide composition it names as its own MIN (pid 95382 · log /tmp/claude-a-quicklaunch-verdict.log)
- 1 headless claude process(es) in the table at 2026-09-17T22:16:54.511Z (pid 95382 up 00:27) — 1 of them recorded as lanes above

## blockers
- THE ORDER FROM THE FOUNDER (2026-09-17 ~18:2x): keep moving through Maribou to 11/10, all models, no stopping, never reopening the Room plan or starting a broad audit. The chain, with ④ LANDED at e509cadc8b: c-census + c-identity merged onto canonical by root (one import hunk, one registry hunk) → one fresh verdict on the merged head → fast-forward → RETURN-EXACT + the sounding door (building on A) → its verdict → the Work opening with QuickLaunch → Materials from the real sleeve → Groove List → DUAL/WIDE → People/Relationship → Film V2. The scoreboard audit stays paused. B is under its weekly floor (9% left); C has 4% above its floor; A carries the builders and verdicts.
- ACCOUNT A IS AT ITS SESSION CEILING (77% of the five-hour window; the guard's ceiling is 78%): no new builder or in-session fan-out on A until the window rolls (~19:40 BST). The root seat's own work on A stays light (git reconciliation, packets, publishing). Account C carries the identity r3 builder and sits ~8% above its weekly floor; Account B rests.
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- GITHUB ACTIONS — the cause is now GitHub's own sentence (gh api …/check-runs/105264398173/annotations): "The job was not started because recent account payments have failed or your spending limit needs to be increased. Please check the 'Billing & plans' section in your settings." Action: github.com/settings/billing on jimmajamma2013-tech → fix the failed payment or raise the Actions spending limit → re-run one workflow on able-rebuild-v1. ~3 minutes. Until then every remote check is meaningless; the native Definition-of-Done runs locally per commit (tsc · vitest · build-check · eye-check · lineage), and the factory branch's act-based fallback (scripts/factory/ci-local.sh) is UNPROVEN until one job runs end to end.
- GITHUB BRANCH PROTECTION on able-rebuild-v1 needs GITHUB PRO first — measured: gh api …/branches/able-rebuild-v1/protection answers "Upgrade to GitHub Pro or make this repository public to enable this feature" (the repo is private on the free plan). So: on the same billing visit, upgrade the jimmajamma2013-tech account to GitHub Pro (about $4/month), then settings/branches → rule for able-rebuild-v1 → block force pushes and deletions. This is the control that cannot be talked around; four verifiers each routed around a local hook. ~4 minutes with the Actions fix.
- OPENAI CREDITS (blocks the cross-family GPT attack; the key is on disk): platform.openai.com/settings/organization/billing → add credits. ~2 minutes.
- REPORTED, not asked: the repo-local git identity `t <t@t>` was removed at 20:5x; commits are authored James Cuthbert from 27b5d6a99c on. One line restores the placeholder if it was deliberate.
- WHEN THE FACTORY FOLDS (not before): `supabase login` in a terminal (~1 min) · `sentry-cli login` and confirm the Railway DSN (~3 min) · Replay account + MCP connection (~5 min) · Greptile dashboard: enable T-Rex for UI PRs only (~2 min) · Mobbin + Refero accounts and a full Figma seat (~10 min) · Cursor: sign in, connect GitHub, create Project ABLE (~5 min) · Conductor and Augment Intent sign-ins for the bake-off (~5 min each) · Lyssna for human taste tests, later.

## next actions (in order)
- the QuickLaunch verdict (A, Opus, running) decides the Work opening's fold; PASS folds it with scripts/fold-commit.mjs, RETURN gets one fix round at the Fable roll
- DUAL at 834 and WIDE at 1440 — the packet is written from the probe's measured numbers and dispatches at the Fable roll (~00:40 BST); it is the dimension that caps product at 4 and both the probe and the QuickLaunch builder named it independently
- the consent-zero fork on the Room's arrival warm-up — packet written; it measures Able's own-origin preview path and implements it only if the tap stays instant, otherwise it reports numbers for a founder ruling
- Materials from the REAL sleeve → the Groove List → People/Relationship → Film V2
- the factory branch after a PASS on its exact repaired SHA (three RETURNs so far; r5 held at the root seat's word while A carried two product seats) · the two-day comparison 2026-09-19 ~21:00 BST, re-running node scripts/room-composition-probe.mjs

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  84%  ·  Fable  84%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  devstral:24b · qwen3-coder:30b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 61% → [1m1 builder(s)[0m · one builder + an occasional verifier
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
