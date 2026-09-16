# TODO

<!-- next-id: 20 -->

Single source of truth for everything I plan to do.
Conventions and workflow: see [AGENTS.md](AGENTS.md). Completed items move to [DONE.md](DONE.md).

Format of a task line:

```
- [ ] #ID (P2) Short actionable title  started:YYYY-MM-DD  @area  #tag  due:YYYY-MM-DD
```

- `#ID` is a stable serial number, assigned once and never reused; see `next-id` above
- `(P1)` urgent / important, `(P2)` normal, `(P3)` nice to have
- `@area` = project or operational area (`@work`, `@meta`, ...)
- `started:` is added when work begins and records the actual start date
- `due:` is optional; omit it rather than inventing a date

---

## Now
Actively being worked on. Keep this to 3 items or fewer.

- [ ] #8 (P2) Verify my open tasks in osTicket and close those fixed. For the open one, verify if JIRA exists and create if not.  started:2026-09-10  @work
- [ ] #18 (P1) Handle QUAN-2734 - Copy evaluation from linked company  @work

## Next
Committed to, but not started yet.

- [ ] #19 (P2) Investigate QUAN-1122  @work
- [ ] #2 (P1) Investigate and create JIRA for the TODO issue Glenn reported in Teams 2026-09-08 (refs: Östlund, Sara Norlund)  → [notes/todo-2.md](notes/todo-2.md)  @work
- [ ] #7 (P2) Investigate Emils osTicket, and answer. Create JIRA if needed.  @work
- [ ] #11 (P2) Implement QUAN-2724 & QUAN-2725 — Ref: osTicket 466955  @work
- [ ] #12 (P2) Enskild firma  → [notes/enskild-firma.md](notes/enskild-firma.md)  @work
- [ ] #13 (P1) Look at the missing upload issue Ihor reported when manually signing an agreement in CRM  @work
- [ ] #14 (P2) Add dropdown on create manual company to select company type  @work
- [ ] #17 (P2) Investigate why AWS logs doesn't work in Verify  @work

## Waiting
Blocked on someone or something else. Note who/what and since when.

- [ ] #9 (P2) Start backlog job in Cursor  started:2026-09-10  @work

## Someday / Maybe
Ideas without a commitment. Safe to ignore for weeks.

_Nothing yet._

## Recurring
Things that come back on a schedule. These stay here instead of moving to `DONE.md`;
just update `last:` when done.

_Nothing yet._
