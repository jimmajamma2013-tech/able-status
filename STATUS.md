# ABLE — what is happening right now

**Last updated just now.**
_If that says more than about 10 minutes while work is running, this page has fallen behind and
should not be trusted. It is supposed to update itself._

## In one line

2 things are being built right now, and the build list is deliberately on hold with 14 jobs kept safe while finished work gets checked. 5 finished pieces of work are waiting to be checked and added in.

## Is anything wrong?

- The build list is paused **on purpose** — not because anything broke. Nothing has been lost; every job is kept and will resume.
- 5 pieces of finished work are waiting to be checked. That is why the list is paused: building faster than checking is how good work gets wiped out by accident.
- The second Claude account has used 91% of its week, so it is being kept in reserve for emergencies rather than doing routine work.

## Being worked on right now

- 2 jobs are running (going 45:01, going 13:45).
- ⚠️ The written description below may be out of date — it lists 1 but 2 jobs are actually running:
  - A · VERIFIER (factory-a's, read-only)

## Waiting for you

- CI IS DEAD on canonical
- GPT's GitHub connector: the private repo has ONE collaborator
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## The numbers, in plain words

- **2 jobs** being built right now
- **14 jobs** waiting in the list (on hold on purpose)
- **5 finished pieces** waiting to be checked and added in
- Claude account A has used **52%** of its week — it refills **Sep 18 at 7pm**
- Claude account B has used **91%** of its week — it refills **Sep 22 at 10:59pm**
- ⚠️ all three Claude accounts are separate and reachable

## Every model lane we can reach

| Lane | State | What it means |
|---|---|---|
| **Claude A** | 52% of its week used | The one to spend. Routine work goes here. Refills Sep 18 at 7pm. |
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
_2026-09-17T19:37:25.907Z · published by fable-root-a (controller · Account A root, Claude Fable 5.1, VS Code) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T19:37:25.907Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **2** (pid 60833 up 45:01 · pid 95289 up 13:45)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **52%** · B **91%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: e509cadc8b60c2e649248424c969fdb1e82ef6e3  (fresh `git ls-remote`)
- localCanonicalHead: e509cadc8b60c2e649248424c969fdb1e82ef6e3  · agrees
- candidateBranch: c-census-green-20260917 · candidateHead: 99b432933abdc11d1b9aac3ce522785695193952
- lastVerifiedAt: 2026-09-17T19:37:24.984Z
- subject: feat(fold): the integrated fold ④ lands on canonical — lane A + fold-bc + Bandcamp + lane F, one hierarchy, one sound owner (r2 PASS)

## candidates ready for verdict / fold
- c-identity-census-20260917 @ c9a1319901 — r3 PASS (product 7 · assurance 7): the Work-identity census is GENERATED by an AST sweep anyone can re-run, guarded against staleness, complete as a list within three stated limits; FOLD-ELIGIBLE for the next integrated fold. The sentence that may NOT be said: 'point 46 complete for Works' — 119 of 394 groups are ruled, the rest counted as joins and unread; the verifier's seeded sample puts real joins at 5 of 20 of the unread
- factory-20260917 @ cfaecd64bc (the peer seat factory-a, Account A) — infrastructure, not product: path-scoped rules (measured: headless sessions paid 181–184k first-turn tokens; the branch's probe 72k), nine trigger skills, the doorway from CLAUDE.md, CI-IS-DEAD.md; verdict running; FOLDS AFTER ④ by root, because it changes what every lane sees at boot
- THE INTEGRATED FOLD ④ @ c600dfd033 (pushed) — r1's two blockers closed at 05b9287474 (B1: the lead Work draws its people through originalOf, one-served-lineage exits 0 on the served HEAD; B2: the adapter's two stand-ins deleted, 0 hits for any table or kind derivation outside the domain, 27 of 30 releases compose identically and the three that changed are declared). Named, not proven: providers/manifestationKind.ts still derives a kind outside the domain; Deezer's embed capability disagrees with the stage; Mother draws no All-credits door; lineage does not yet ride the merge step. r2 VERDICT RUNNING on A.
- c-census-green-20260917 @ 99b432933a — r1 PASS (product 8 · assurance 7 · MIN 7): FOLD-ELIGIBLE for the next integrated fold; two non-blocking findings (an unrouted twin sentence in mergeForwardCacheWrite.ts:56,58; names now de-duplicated in the merged-forward log, unmentioned in the body)
- fold-bc-20260916 @ 8275960165 — r3 PASS (B3 closed; nothing r2 held regressed); FOLD-ELIGIBLE for the integrated fold ④ only
- lane A provider data @ 48fe3fc28c — r3 PASS 8·7; waits in the integrated fold ④
- BANDCAMP-IDS @ 3499e78b57 (origin/worktree-agent-afa25af8ff9958d25) — r1 PASS; folds behind the consent law in ④
- cand-claim-20260917 @ 0345ac0544 — the two-defect fix is STRANDED as 25 staged files in /Users/jamescuthbert/able-work/cand-claim (its builder died with the 14:40Z window kill); needs a resume builder to commit, then ONE fresh verdict
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (35 findings); does not enter a candidate until its fixes land
- LANE MATERIALS — STRANDED again: 26 dirty files in /Users/jamescuthbert/Able/.claude/worktrees/agent-ad409ed963fb3ce99, no commit (its in-session builder died with the 14:40Z window kill); needs a resume builder

## running lanes
- A · claude-opus-5 · VERIFIER (factory-a's, read-only) — the software-factory branch factory-20260917 @ b4dddde2f4, r2 — attacks the RETURN-CLOSURE rows, the taste ledger, the always-loaded kernel, law-visibility.mjs, the boot arithmetic; writes docs/audits/2026-09-17-software-factory/VERDICT-r2.md and does not commit; folds behind the census and identity folds (pid 95289 · log /tmp/claude-verify-factory-r2.log)
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): RETURN-EXACT + THE SOUNDING DOOR (the founder's own walk: Back landed 2,680 px down; no reachable pause) in worktree return-exact-20260917 cut from the fold's tip — exact Back within 8 px, zero black frames, a quiet door to the sounding object on every plane while sound plays (never a mini-player), planted walks at 390 and 1440
- UNVERIFIED — no pid recorded (an in-session agent or a stale entry): the factory branch factory-20260917 @ cfaecd64bc — a second Account A window (seat factory-a): path-scoped rules to cut the ~180k-token headless boot to ~72k, nine trigger skills, the Control Room doorway imported from CLAUDE.md; CI-IS-DEAD.md; verdict to land at ~/able-work/verify-factory-20260917/docs/audits/2026-09-17-software-factory/VERDICT-r1.md
- 2 headless claude process(es) in the table at 2026-09-17T19:37:25.907Z (pid 60833 up 45:01, pid 95289 up 13:45) — 1 of them recorded as lanes above

## blockers
- THE ORDER FROM THE FOUNDER (2026-09-17 ~18:2x): keep moving through Maribou to 11/10, all models, no stopping, never reopening the Room plan or starting a broad audit. The chain, with ④ LANDED at e509cadc8b: c-census + c-identity merged onto canonical by root (one import hunk, one registry hunk) → one fresh verdict on the merged head → fast-forward → RETURN-EXACT + the sounding door (building on A) → its verdict → the Work opening with QuickLaunch → Materials from the real sleeve → Groove List → DUAL/WIDE → People/Relationship → Film V2. The scoreboard audit stays paused. B is under its weekly floor (9% left); C has 4% above its floor; A carries the builders and verdicts.
- ACCOUNT A IS AT ITS SESSION CEILING (77% of the five-hour window; the guard's ceiling is 78%): no new builder or in-session fan-out on A until the window rolls (~19:40 BST). The root seat's own work on A stays light (git reconciliation, packets, publishing). Account C carries the identity r3 builder and sits ~8% above its weekly floor; Account B rests.
- THE PRODUCT QUEUE IS STILL PAUSED BY RULE — 14 packets held in QUEUE/tasks-paused.txt, none lost. Backpressure counts delivered-but-unfolded product branches (lane A · fold-bc · Bandcamp · c-census · c-identity = 5) against a threshold of 2. The integrated fold ④ is the one action that clears it.
- Account B rests at 91% weekly with Fable spent (resets Sep 22) — nothing dispatched there. Account C is at 77% weekly (23% left, floor 12%; resets Sep 19 23:00): the guard now says Opus for its next dispatches; the two Fable lanes above were the last Fable ones on C.
- Both root windows were killed at 14:40Z. The A seat resumed at ~14:45Z; the B seat has not. The stranded work is SNAPSHOTTED as refs (no gates, worktrees untouched): refs/wip/A/2026-09-17-materials = 752c850b62 (20 files) · refs/wip/A/2026-09-17-cand-claim-fix = 42a442f92f (24 files).
- OWED: one bounded independent verdict on the status bridge itself (oldest open debt on this seat). And the kernel §2 names claimSoundOwner/releaseSoundOwner in audioBus.ts which do not exist in src/ — a doc-vs-code mismatch the cand-play verifier found.

## needs James
- CI IS DEAD on canonical (measured 2026-09-17: every run of the day on able-rebuild-v1 fails 2–3 s in with an EMPTY step list on every job — Type check, Vitest, both Playwright suites, the two-tier invariant — so npm ci never ran). The likely cause is exhausted GitHub Actions minutes or a spending limit on the private repo; only the account owner can read billing: github.com/settings/billing (Actions minutes and the spending limit) on jimmajamma2013-tech. Until it is fixed every CI-only gate is decorative; the local gates and fresh verdicts are the real ones and are what ran today.
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- c-census-green-20260917 (99b432933a, r1 PASS 8·7) merged with canonical e509cadc8b in its worktree by root — the OpeningWorld.tsx import hunk kept both sides; tsc + the related vitest run there → c-identity-census-20260917 (7c97577436, r3 PASS) merged on top, the lessons.json hunk keeps both entries → push by reference → ONE fresh verdict on the merged head (A, Opus, five claims: census survives · identity survives · ④'s lineage still exits 0 · floor · three sizes) → fast-forward canonical
- RETURN-EXACT + the sounding door is BUILDING on A (pid 60833) in return-exact-20260917 from c600dfd033; when its commit lands: push by reference → merge with canonical (same base as ④, expected clean) → fresh verdict → fold
- the Work opening recomposed with QuickLaunch replacing 'Listen elsewhere' (the founder's sequence: identity → sound → one human seam → QuickLaunch → depth through doors) — Fable on A once the exact-Back builder exits (one builder per account)
- Materials from the REAL sleeve (mustard, dirty red, concrete, tobacco; the record's own lettering for the title; resume refs/wip/A/2026-09-17-materials 752c850b62) → the Groove List → DUAL at 834 and WIDE at 1440 (the dimension that caps product at 4)
- People/Relationship → Film V2 · the factory branch folds after its r2 verdict (running, pid 95289) · the two speed tests re-measured on the served Room after QuickLaunch

## meters
```
[2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mClaude C[0m  weekly  84%  ·  Fable  84%  ·  resets Sep 19 at 10:59pm  ·  [32mgenuinely separate[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  devstral:24b · qwen3-coder:30b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 52% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
