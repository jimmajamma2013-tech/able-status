# ABLE · LIVE STATUS
_2026-09-17T10:07:31.552Z · published by fold-root-20260916 (Account A root, Claude Opus 5 1M) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T10:07:31.552Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **2** (pid 5576 up 00:30 · pid 9236 up 57:33)
- queueState: **PAUSED FOR INTEGRATION — 14 packet(s) held, not lost**
- queueDepth (live): product **0** · ci **0**
- queueHeld (paused, preserved): product **13** · ci **1**
- queueNext: product `UNKNOWN` · ci `UNKNOWN`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ a1181e412f (+5) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ a1181e412f · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **25%** · B **89%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: cf9c7f2efd4996d9894fe1595141d84d2f9c5c5a  (fresh `git ls-remote`)
- localCanonicalHead: cf9c7f2efd4996d9894fe1595141d84d2f9c5c5a  · agrees
- candidateBranch: cand-20260917 · candidateHead: 619a17d461f6ca728714aa8ad7839946f6e6eb3c
- lastVerifiedAt: 2026-09-17T10:07:30.156Z
- subject: docs(review): 35 findings on two branches, every one survived refutation

- publicMirrorReadable: true (unauthenticated fetch of the raw mirror, 2026-09-17T10:07:47.109Z)

## candidates ready for verdict / fold
- cand-20260917 @ 619a17d461 — THE INTEGRATION CANDIDATE, built from CURRENT canonical cf9c7f2efd + night-consent-20260916 + night-doors-20260916, both merged with ZERO conflicts. measured on the candidate itself: npx tsc --noEmit exit 0; the three P0 suites 26/26 green (threeDoors 9, consent-wrong-topic 13, consent-wire-route 4); the three-doors test file present. Verdict IN FLIGHT.
- night-claim-screen-20260917 @ fba480c587 — RETURNED by lane review (4 of 6 dimensions RETURN; 35 findings raised, 35 survived adversarial refutation). Does NOT enter a candidate until its fixes land.
- ci-p2-ci-waste-20260917 @ f4bdfae07f and ci-p2-lanes-ci-20260917 — RETURNED on coverage loss (three cron tests now pass on a commented-out line; axe-gate reachable by nothing automatic).

## running lanes
- Account A · FRESH VERIFIER on the frozen integration candidate 619a17d461 (five claims: consent enforced on the send path · three doors reachable by a finger at 320/375 · removal door reaches the real flow with its subject · nothing forbidden painted or printed · the merge itself honest) — log /tmp/cand-verify.log
- Account A · builder p0-play-button (the founder-reported P0: the film charges a second tap) — worktree /Users/jamescuthbert/able-work/night-p0-play-button

## blockers
- THE PRODUCT AND CI QUEUES ARE PAUSED BY RULE, not by failure — 14 packets held in QUEUE/tasks-paused.txt and tasks-ci-paused.txt, none lost. They resume when delivered-but-unfolded drops below 2.
- night-claim-screen and the two ci branches are RETURNED with grounded findings — full record docs/audits/cold-review/2026-09-17-lane-review-claim-screen-and-ci-waste.md
- OWED: one bounded independent verdict on scripts/publish-status.mjs — the status bridge has now taken four consecutive cold-review escapes and is the founder-facing surface least entitled to self-certify

## needs James
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- the candidate verdict lands → PASS folds cand-20260917 to canonical (doors land BEFORE claim-screen, which is what stops the three-doors P0 being erased) → deliveredUnfolded drops 5 to 3
- then the RETURNED branches get fix rounds against the findings, and re-enter as a NEW candidate from the canonical of that moment — never re-verified as stale lanes
- then the queue resumes

## meters
```
resets Sep 22 at 10:59pm   [2m11% of the week left · the labour lane — heavy work belongs here[0m
     [2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 25% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
