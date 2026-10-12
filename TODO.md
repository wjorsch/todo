# TODO

<!-- next-id: 36 -->

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

_Nothing right now._

## Next
Committed to, but not started yet.

- [ ] #18 (P1) Handle QUAN-2734 - Copy evaluation from linked company  @work
- [ ] #35 (P1) Fix Anttis issues in CRM  @work
- [ ] #2 (P1) Investigate and create JIRA for the TODO issue Glenn reported in Teams 2026-09-08 (refs: Östlund, Sara Norlund)  → [notes/todo-2.md](notes/todo-2.md)  @work
- [ ] #13 (P1) Look at the missing upload issue Ihor reported when manually signing an agreement in CRM  @work
- [ ] #22 (P1) Skapa JIRA för 400-fel när man kör rapport och väljer Källa / Strategisk kontakt  @work
- [ ] #29 (P1) Synka kunder från CRM till Senseworks  @work
- [ ] #31 (P1) Fix QUAN-2829  @work
- [ ] #34 (P1) Verify AGENTS.md and more in all repos, so it matches ai-docs  @work
- [ ] #11 (P2) Implement QUAN-2724 & QUAN-2725 — Ref: osTicket 466955 — Note: QUAN-2724 Resume junie session "junie --session-id session-260916-090212-ybk2"  @work
- [ ] #12 (P2) Enskild firma — Note: QUAN-2655  → [notes/enskild-firma.md](notes/enskild-firma.md)  @work
- [ ] #14 (P2) Add dropdown on create manual company to select company type  @work
- [ ] #17 (P2) Investigate why AWS logs doesn't work in Verify  @work
- [ ] #19 (P2) Investigate QUAN-1122  @work
- [ ] #20 (P2) Implement QUAN-2628  @work
- [ ] #23 (P2) Add logging to Senseworks-svc and investigate JSON parse errors  @work
- [ ] #25 (P2) Fix QUAN-2770  @work
- [ ] #28 (P2) Set up e2e project in CRM to enable fully automated tests  @work
- [ ] #32 (P2) Create en epic or story och raffinera den — lösa dokumentuppladdning i tjänstemallar innan avtalsskickning  @work
- [ ] #33 (P2) Add user story for removing duplicated agreement files and attachments on project where files are added from service templates and email templates; today only agreement files and attachment files are deduped  @work

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
