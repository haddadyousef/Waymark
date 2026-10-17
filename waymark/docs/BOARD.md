# Waymark board (single writer: Windows session / leader)

Last checked: Sat 2026-10-17 14:20 PT. Repo hash confirmed by Windows: none yet (nothing pushed). Mac: no status entry yet.
If this is more than an hour old, it is stale. Say "check mac" to the Windows chat.

**Phase:** prep lane. **Build lane:** HOLD until Yousef records the DubHacks rules outcome (D-04).
**Permission:** building on OpenCane confirmed by Yousef, credit not required (D-18). Repo is public (D-03).

## Tasks

| ID | Owner | Task | Status | Updated |
|---|---|---|---|---|
| W0, W1, O1 | W | Plan, seed docs, drafts | done | 14:20 |
| C0a | W | Schemas and golden fixtures | todo (prep lane) | |
| C0b | W | Belief and threshold vectors, reference Python | todo (prep lane) | |
| P0 | W | API discovery, raw samples | doing, waits on folder (H4) | |
| M0 | W or Mac | Baseline plus docs on GitHub | todo, waits on GitHub App install (H3) | |
| G0 | Mac | Fork builds, patch verified, phone run | todo | |
| M1 | Mac | Seattle simulator location, sim17 runtime | todo | |
| L1 to L3, A1 to A3, E1, E2, F1, T1 | Mac | Waymark Swift code | hold | |
| P1 to P6, V1, V2, S1, D1 | W | Pipeline, eval, server, dashboard | hold | |
| H2 | Yousef | DubHacks rules and schedule | todo | |
| H3 | Yousef | Add `azphalt`, install Claude GitHub App | doing | |
| H4 | Yousef | Windows `Waymark` folder | todo | |
| H5 | Akash | Hardware facts | todo | |
| H7 | both | Spotter and go/no-go | todo | |

## Blockers

- Push from the Windows session: Claude GitHub App not installed on the repo.
- Build lane: DubHacks rules unread.

## Next three actions

- **Windows:** C0a and C0b; push as soon as write access works; P0 once the folder is granted.
- **Mac:** ack the contracts in `STATUS_M.md`, answer the seven items in `M_NOTES.md`, run G0 batches with Akash.
- **Humans:** Yousef H2, H3, H4. Akash H5 and `brew install xcodegen`.
