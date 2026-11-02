# .gitfill

This folder is where GitFill keeps what it needs to explain this repository, and what it writes back.

| Folder | Who writes it | What it is for |
|---|---|---|
| `assets/` | You | Screenshots, the logo, demo GIFs, `brand.json` (colours, fonts, tagline) and product notes in Markdown. GitFill uses them when it writes the README, docs, decks and videos. Images are linked from the README, so keep them here. |
| `docs/` | GitFill | Engineering and architecture docs written from the code, each with the commit it was written from. `index.md` lists them. |
| `brainstorm/` | GitFill | Ideas worked out in GitFill's chat, written as specs for a coding agent: goal, decisions, the code involved, tasks and acceptance criteria. |

GitFill never treats `docs/` or `brainstorm/` as evidence about the code: it always re-reads the code itself.

**For coding agents:** a file in `brainstorm/` with `status: "ready"` is a task you can implement. Read the whole spec first, follow its tasks in order and check the acceptance criteria before you finish.
