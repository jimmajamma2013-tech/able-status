# ABLE · LIVE STATUS
_2026-09-17T09:45:54.511Z · published by fold-root-20260916 (Account A root, Claude Opus 5 1M) · this file is a pointer, the evidence is in the repo_

## ⏱ FRESHNESS — read this first
- **publishedAt: 2026-09-17T09:45:54.511Z**
- statusAgeSeconds at publication: 0 · **recompute from publishedAt; anything over 600s while
  builders are running is STALE and this page should not be trusted as current**
- runningBuilders: **2** (pid 9236 up 35:56 · pid 74614 up 59:23)
- queueDepth: product **13** · ci **1**
- queueNext: product `p3-authority` · ci `p2-gates`
- deliveredUnfolded: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f (+3) · ci-p2-lanes-ci-20260917 @ 97111c83d1 (+2) · night-claim-screen-20260917 @ fba480c587 (+3) · night-consent-20260916 @ bbe92a379b (+2) · night-doors-20260916 @ 1d3f87f51a (+3)
- verdictsPending: **5** — ci-p2-ci-waste-20260917 @ f4bdfae07f · ci-p2-lanes-ci-20260917 @ 97111c83d1 · night-claim-screen-20260917 @ fba480c587 · night-consent-20260916 @ bbe92a379b · night-doors-20260916 @ 1d3f87f51a
- meters weekly: A **25%** · B **89%** · band: ≤55% → 2 builder(s)

⛔ **INTEGRATION BACKPRESSURE (James relaying GPT, 2026-09-17):** the product queue PAUSES at **2**
delivered-but-unfolded product branches, and pauses immediately if the next packet touches a file an
unfolded branch touches. Builders outrunning integration is how a folded P0 gets erased.

## canonical
- repository: jimmajamma2013-tech/able-music
- canonicalBranch: able-rebuild-v1
- remoteCanonicalHead: 11dc4a4bc4e7d467db139399d3b5ce32e3fe132a  (fresh `git ls-remote`)
- localCanonicalHead: 11dc4a4bc4e7d467db139399d3b5ce32e3fe132a  · agrees
- candidateBranch: none — four lane branches await verdicts; see machine.deliveredUnfolded · candidateHead: UNKNOWN
- lastVerifiedAt: 2026-09-17T09:45:53.404Z
- subject: docs(fold): four branches measured by trial merge — one collision, and its cause

## candidates ready for verdict / fold
- lane A provider data @ c5e927bac0 (+ its r3 verdict) — r3 PASS 8·7: step ① CLOSED; folds in the integrated fold ④ (hard gate there: providerOrder.ts/providerCapabilities.ts absorbed into the one resolver and the capability projection)
- fold-bc-20260916 @ 4984346294 — BOTH r1 findings closed by commits (3f354a9c74 the mechanical consent law; 4984346294 the renderer obeys composeWork: per-kind section lists differ, data-emphasis carried; builder names its own residue: the demo hero lost its Able preview, the mix hero points to artist SoundCloud while the stage holds Apple/Bandcamp, quickLaunch unrendered pending lane A's resolver, desktop still a stretched phone); PUSHED; r2 RUNNING on Account B (Opus)
- lane F Current Moment @ 36257f1b88 — r2's blockers closed by the builder (one object population + one trust rule; parity S1–S3 each planted red; the face probe 0% at 390/834/1440 and back on disk; the 834 door clear). Residue it names: the Room's receipt says film while the record block shows the 2025 album; 1440 title wraps 6px from the face box; F20/F21 open. r3 RUNNING (Account B, Opus)

## running lanes
- product queue builder · p0-play-button (founder-reported P0: the film charges a second tap) — worktree /Users/jamescuthbert/able-work/night-p0-play-button
- ci queue builder · p2-lanes-ci — worktree /Users/jamescuthbert/able-work/ci-p2-lanes-ci

## blockers
- 5 delivered-but-unfolded branches · 5 verdicts pending — integration is behind the builders, which is the exact condition GPT rule 1 pauses the queue on
- Greptile has posted nothing since 2026-09-06 (0 reviews/comments on the standing window PR #28 across ~700 canonical commits) — James: check app.greptile.com connection + credits
- 7 pre-existing red vitest census cases identical at canonical, B and C — owed to the sound-language / counted-noun lanes
- pre-push mobile-asset-budget is RED on canonical's own chunks (97918 496KB, 80042 430KB, throttled hero 4106ms>4000) — pre-existing, identical sizes on canonical and candidate builds; pushes use the documented PUSH_GUARD_SKIP=1; owner B-218; never widen the budget

## needs James
- GPT's GitHub connector: the private repo has ONE collaborator (jimmajamma2013-tech); the ChatGPT GitHub App must be installed on THAT account with able-music selected (github.com/settings/installations → ChatGPT → Configure). Until then GPT reads the PUBLIC mirror: https://raw.githubusercontent.com/jimmajamma2013-tech/able-status/main/STATUS.md
- Greptile: check app.greptile.com — nothing posted since 06 Sep
- which Claude capacity to buy · actions 949–1000

## next actions (in order)
- PAUSE the product queue: 5 delivered-but-unfolded branches against GPT rule 1 threshold of 2
- verdicts on the four lane branches, then fold in the order in docs/audits/2026-09-17-the-fold/INTEGRATION-MAP.md (doors BEFORE claim-screen, or the three-doors P0 is erased)
- the binding verdict is on the POST-RECONCILIATION integration candidate, not the lane branch (GPT rule 2)

## meters
```
resets Sep 22 at 11pm   [2m11% of the week left · the labour lane — heavy work belongs here[0m
     [2mband 70%+ → 0 builder(s): preserve for blockers until Codex and the second Claude account return[0m
     [33m⚠ B's Fable tap is exhausted — the premium tier is closed on B until that reset.[0m

[1m🌐 EVERY LANE WE OWN[0m
  [1mCodex / Astra[0m  [31mUNKNOWN — The provider reports a reached account limit[0m
  [1mGemini[0m  [33mUNKNOWN — no hand reading at .able/state/gemini-balance.json (the API exposes no balance) — UNKNOWN, never zero[0m
  [1mLocal (Ollama)[0m  qwen3-coder:30b · devstral:24b · gpt-oss:20b  ·  free (no meter) — capacity governed by RAM, one heavyweight at a time

[1m🎚 THE BAND (resource mode, 2026-09-16):[0m working account A at weekly 25% → [1m2 builder(s)[0m · two builders maximum; Opus only for genuinely hard work
   Opus decides (architecture · reconciliation · root cause · fold verdicts) · Fable executes ratified designs · scripts prove · Codex takes bulk implementation on its reset · local and Gemini only what they have earned.
```
