# TODO

<!-- next-id: 13 -->

Single source of truth for everything I plan to do.
Conventions and workflow: see [AGENTS.md](AGENTS.md). Completed items move to [DONE.md](DONE.md).

Format of a task line:

```
- [ ] #ID (P2) Short actionable title  started:YYYY-MM-DD  @area  #tag  due:YYYY-MM-DD
```

- `#ID` is a stable serial number, assigned once and never reused; see `next-id` above
- `(P1)` urgent / important, `(P2)` normal, `(P3)` nice to have
- `@area` = life area or project (`@work`, `@home`, `@health`, ...)
- `started:` is added when work begins and records the actual start date
- `due:` is optional; omit it rather than inventing a date

---

## Now
Actively being worked on. Keep this to 3 items or fewer.

- [ ] #8 (P2) Verify my open tasks in osTicket and close those fixed. For the open one, verify if JIRA exists and create if not.  started:2026-09-10  @work
- [ ] #9 (P2) Start backlog job in Cursor  started:2026-09-10  @work

## Next
Committed to, but not started yet.

- [ ] #2 (P1) Investigate and create JIRA for the TODO issue Glenn reported in Teams 2026-09-08 (refs: Östlund, Sara Norlund)  → [notes/todo-2.md](notes/todo-2.md)  @work
- [ ] #4 (P2) Set up remote git repo  @meta
- [ ] #7 (P2) Investigate Emils osTicket, and answer. Create JIRA if needed.  @work
- [ ] #10 (P2) Implement QUAN-2723  @work
- [ ] #11 (P2) Implement QUAN-2724 & QUAN-2725 — Ref: osTicket 466955  @work
- [ ] #12 (P2) Enskild firma  → [notes/enskild-firma.md](notes/enskild-firma.md)  @work

## Waiting
Blocked on someone or something else. Note who/what and since when.

_Nothing yet._

## Someday / Maybe
Ideas without a commitment. Safe to ignore for weeks.

_Nothing yet._

## Recurring
Things that come back on a schedule. These stay here instead of moving to `DONE.md`;
just update `last:` when done.

_Nothing yet._
