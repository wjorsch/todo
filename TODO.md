# TODO

<!-- next-id: 31 -->

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

- [ ] #18 (P1) Handle QUAN-2734 - Copy evaluation from linked company  @work
- [ ] #11 (P2) Implement QUAN-2724 & QUAN-2725 — Ref: osTicket 466955 — Note: QUAN-2724 Resume junie session "junie --session-id session-260916-090212-ybk2"  @work
- [ ] #30 (P1) Get property list for softbots and document it for agent-assisted rule setup  → [notes/softbots.md](notes/softbots.md)  @work

## Next
Committed to, but not started yet.

- [ ] #25 (P2) Fix QUAN-2770  @work
- [ ] #20 (P2) Implement QUAN-2628  @work
- [ ] #19 (P2) Investigate QUAN-1122  @work
- [ ] #2 (P1) Investigate and create JIRA for the TODO issue Glenn reported in Teams 2026-09-08 (refs: Östlund, Sara Norlund)  → [notes/todo-2.md](notes/todo-2.md)  @work
- [ ] #7 (P2) Investigate Emils osTicket, and answer. Create JIRA if needed.  @work
- [ ] #12 (P2) Enskild firma — Note: QUAN-2655  → [notes/enskild-firma.md](notes/enskild-firma.md)  @work
- [ ] #13 (P1) Look at the missing upload issue Ihor reported when manually signing an agreement in CRM  @work
- [ ] #14 (P2) Add dropdown on create manual company to select company type  @work
- [ ] #17 (P2) Investigate why AWS logs doesn't work in Verify  @work
- [ ] #22 (P1) Skapa JIRA för 400-fel när man kör rapport och väljer Källa / Strategisk kontakt  @work
- [ ] #23 (P2) Add logging to Senseworks-svc and investigate JSON parse errors  @work
- [ ] #28 (P2) Set up e2e project in CRM to enable fully automated tests  @work
- [ ] #29 (P1) Synka kunder från CRM till Senseworks  @work

## Waiting
Blocked on someone or something else. Note who/what and since when.

- [ ] #8 (P2) Verify my open tasks in osTicket and close those fixed. For the open one, verify if JIRA exists and create if not.  started:2026-09-10  @work
- [ ] #9 (P2) Start backlog job in Cursor  started:2026-09-10  @work

## Someday / Maybe
Ideas without a commitment. Safe to ignore for weeks.

_Nothing yet._

## Recurring
Things that come back on a schedule. These stay here instead of moving to `DONE.md`;
just update `last:` when done.

_Nothing yet._
