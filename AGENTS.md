# AGENTS.md

Instructions for any AI agent (and for me) working in this repository.

## What this repo is

A personal, plain-text TODO system. There is no code, no build, no tests.
Never add tooling, package files, or CI here unless I explicitly ask for it.

## Files

| File | Purpose |
| --- | --- |
| `TODO.md` | The single source of truth for all open tasks. |
| `DONE.md` | Append-only archive of completed tasks, grouped by month. |
| `AGENTS.md` | This file: conventions and workflow. |
| `notes/` | Optional. One file per big project, only when a task needs more than a line. |

`TODO.md` stays one file on purpose. Do not split it into per-area files.
See "Why one file" below.

## Task format

```
- [ ] #ID (P2) Short actionable title  @area  #tag  due:YYYY-MM-DD
```

- Start the title with a verb: "Call the dentist", not "Dentist".
- One line per task. If it does not fit on one line, it is a project — give it a
  file in `notes/` and link to it: `- [ ] #ID (P2) Rebuild the deck  @home  → [notes/deck.md](notes/deck.md)`.
- `#ID` is a serial number so tasks can be referred to unambiguously (e.g. "close #7").
  It is assigned once, when the task is created, and never reused or renumbered.
  The next free ID is tracked in the `<!-- next-id: N -->` comment near the top of
  `TODO.md`; bump it by one each time a task is added.
- Priority is `(P1)`, `(P2)` or `(P3)`. Default to `(P2)`.
- `@area` is mandatory, `#tag` and `due:` are optional.
- Never invent a due date. If I did not give one, leave it out.

## Sections in `TODO.md`

`Now` → `Next` → `Waiting` → `Someday / Maybe` → `Recurring`.
Keep this order and keep the section names exactly as they are; add a task to the
section that matches its real state. `Now` holds at most three tasks — if it is full,
put the new task in `Next` and tell me instead of quietly overflowing it.

## Workflow rules for agents

1. **Adding a task**: append it to the correct section of `TODO.md`. Do not reorder or
   rewrite the tasks around it.
2. **Completing a task**: remove the line from `TODO.md` and append it to the current
   month's section in `DONE.md` as `- [x] #ID YYYY-MM-DD  <title>  @area`, keeping its
   original `#ID`. Create the month heading if it is missing. Never delete a task
   without archiving it.
3. **Recurring tasks** are not archived. Update their `last:YYYY-MM-DD` in place.
4. **Never rewrite or reflow the whole file.** Make the smallest edit that does the job;
   these files are diffed and read by a human.
5. **Do not delete anything from `DONE.md`.** It is append-only.
6. **Ask, do not guess.** If a task's area, priority or section is unclear, ask me
   rather than picking one silently.
7. Use the real current date, never a placeholder.
8. After changing any file, create a local Git commit containing the change.

## Why one file

`TODO.md` is deliberately a single file: the whole point of a personal list is that
one glance shows everything competing for my attention. Split across `work.md`,
`home.md`, `health.md`, a task hides in the file I did not open that day, and I have
to remember to check all of them.

Split only when one of these is actually true:

- a single project needs its own steps, links and context → a file in `notes/`,
  still represented by one line in `TODO.md`;
- `TODO.md` passes roughly 200 lines and scrolling starts to hurt → move the
  `Someday / Maybe` section into `SOMEDAY.md` first, since it is the part I read least.

Until then, one file.
