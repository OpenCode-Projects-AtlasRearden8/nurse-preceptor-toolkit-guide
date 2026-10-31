# Nurse Preceptor Toolkit

An education-only manual for nurses who get asked to precept a new grad — and would love to do it without losing the shift, the orientee, or themselves. Plain English, step by step, never condescending: the way a friend would explain it.

**Education only — not medical advice.** This guide teaches coaching habits, checklists, and documentation ideas. It does not teach clinical care and never overrides your facility's policies, your state practice act, your educator, or your clinical team. AI-assisted drafts described here are things you verify before you use them. When in doubt, the policy manual and your escalation chain come first.

Built by [Asdale Dynamics, LLC](https://dylanasdale.github.io) — beginner-friendly AI education, books, and practical tools, published local-first.

## What is inside

| Chapter | One-liner |
|---|---|
| 00 · Read this first | Who it's for + the disclaimers that matter |
| 01 · A new grad at ease | Day-one scripts and the first-week structure that lowers panic |
| 02 · Teaching without rescuing | The autonomy ladder: hand the job over without dropping it |
| 03 · Feedback delivered kindly | True + specific + next-attempt-shaped, with copyable scripts |
| 04 · Growing critical thinking | The question ladder and role-play drills that make thinking visible |
| 05 · AI for lesson plans | Draft unit-level lesson plans with AI — then verify every claim |
| 06 · Dry-run scenarios | Fictional, verified practice scenarios for dead time |
| 07 · Documenting precepting hours | One row per shift; the log that feeds the official forms |
| 08 · Surviving the difficult week | Five rough shapes and their first moves, for both of you |
| 09 · Handoff readiness summary | The final week, the one-page summary, the true farewell |
| 10 · Glossary | Precepting vocabulary, translated |
| Worksheets (6) | Setup sheet, weekly teaching plan, question bank, hours log, hard-week one-pager, readiness summary |

## Run it (local-first, offline)

No dependencies. Python 3.10+ standard library only.

```bash
python3 build.py            # builds the static site into site/ and validates links
python3 build.py --check-only   # validate sources without writing anything
python3 -m unittest discover -s tests -v   # run the test suite
```

Then open `site/index.html` in any browser. No server, no network, no accounts, no analytics — nothing leaves your machine. Worksheets are print-styled, so `Ctrl/Cmd+P` gives clean printable pages.

## Project layout

```
build.py        stdlib-only static site generator (markdown -> HTML) + validation
docs/           the manual, chapter by chapter (markdown)
worksheets/     printable worksheets and logs (markdown)
tests/          unittest suite for the renderer, build, and repo integrity
site/           generated output (gitignored; rebuild anytime)
```

## Related projects

This guide is the preceptor-side companion to sibling tools built in the same spirit:

- **new-nurse-first-year-guide** — the other side of this story: the first-year new nurse's own survival manual; day-one reading for your orientee.
- **sbar-report-builder-webapp** — builds SBAR handoff reports in a form; a safe early task for an orientee.
- **shift-brain-sheet-maker** — printable shift brain sheets; a ready-made week-one teaching artifact.
- **patient-teaching-with-ai-guide** — education-only AI drafting with verification, for patient handouts.

## Privacy and safety

- Local-first: the build and the site make zero network requests (enforced by a strict Content-Security-Policy in every generated page).
- No secrets, no API keys, no patient data, no trainee data — the worksheets are blank by design, and a test suite checks for accidental credentials.
- Education-only framing is asserted on every page, in every chapter, and in every worksheet; AI prompts in the guide carry the same education-only constraints and a no-patient-data rule with teeth.

## License

MIT — see [LICENSE](LICENSE). Copyright (c) 2026 Asdale Dynamics, LLC.
