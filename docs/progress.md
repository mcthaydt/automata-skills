# Bringing automata-skills up to date: progress

The Owner, 2026-11-07: "Have we been updating automata-skills, I know we worked on automata-plus", then "Oh, let's
handle that". Each stage runs in its own thread and hands off through the documents listed here.

**Progress: 1 of 6 stages done (17%).**

| Stage | Status | Document | Pull request |
|---|---|---|---|
| 1. Audit | Done, 2026-11-07 | [2026-11-07-skills-audit.md](2026-11-07-skills-audit.md) | this branch, `claude/project-thread-l4q4y1` |
| 2. Plan and spec | Not started | | |
| 3. Plan audit | Not started | | |
| 4. Build | Not started | | |
| 5. Build audit | Not started | | |
| 6. Fixes | Not started | | |

## Where stage 2 starts

- Read the audit's short version, then sections 6 and 7. Most fixes belong in `mcthaydt/automata-framework` (the
  agent package's source, the release job, the API index and the 3D plan), not here.
- Decision D1 A (the recommended default) moves this pipeline's documents to the framework's `docs/refactor/` from
  stage 2 on, so this repository stays output only. The first mirror push deletes everything here but `.git` (audit M2).
- The audit was made against the framework's stack head `ac899051` (#443). Recheck the stack before planning: #440
  carried commits (the 0.1.0 changeset) that #441 to #443 did not have yet.
