# Using AI to Build Lesson Plans

**Education only — this guide is never medical advice.** This chapter teaches a verification workflow for using AI tools to draft *teaching materials* — lesson plans and scenarios — not clinical content, not patient instructions, and not anything that could be mistaken for care guidance. Every AI draft in this workflow is something a human preceptor verifies against facility-approved sources before use. This guide does not cover clinical care and never overrides your facility's policies, your unit educator, or your clinical team.

You are a clinician, not a curriculum designer — and the unit doesn't need one; it needs your week's priorities in a usable shape. AI is good at shape. It is unreliable at facts. That division of labor is the whole chapter.

## The four rules that make this safe

1. **No patient data, ever.** No names, initials, room numbers, dates, unique values, or "that case I had last year" stories detailed enough to identify anyone. Teach with categories and ranges, never with people. This rule outranks every other rule in this chapter.
2. **AI drafts, you author.** The output is a suggestion with unknown provenance. It becomes a lesson plan only after a human (you) checks every functional claim against facility-approved sources — policy manuals, your unit educator's materials, trusted professional references.
3. **No facility-confidential text into external tools.** Policy numbers, internal forms, screenshots of systems, credentialing documents: nothing proprietary or identifying goes into a chat box you don't control. Ask your educator what's treated as confidential; when unsure, leave it out.
4. **Your tools follow your institution's rules.** If your workplace has an approved-use policy for AI (many do, many are writing them), that policy names the tools and uses. The workflow below works with any tool; running it inside your approved set is on you, not this manual.

## The workflow, start to finish

**Step 1 — Name the outcome in your own words first.** One sentence: "By Friday, phase-two orientee can [skill/behavior] at [autonomy rung, from chapter 2]." If you can't write this line, AI can't help yet; it will happily generate confident text about nothing.

**Step 2 — Draft with a structure prompt.** Give the tool your sentence, the audience, the week's constraints, and the exact format you want. Example template (edit the bracketed parts; paste nothing real):

```
You are helping a nurse preceptor draft teaching materials for an
adult-med-surg unit. Education only; no clinical guidance.

Draft a 30-minute [week N] lesson plan for one orientee in [unit],
covering: [topic, e.g., "the first pass of shift organization"].

Format:
- One-sentence outcome statement starting "By the end, the orientee can…"
- Five teaching moments sequenced (do → check → debrief), each with
  the preceptor sentence to say and the orientee action expected
- Two role-play questions from [my question ladder]
- One 3-item verification checklist I can watch for
- One common-confusion paragraph written for a week-N orientee

Constraints: no medical facts or values — mark every factual
claim with [VERIFY] instead of stating it. Plain English.
```

The `[VERIFY]` convention is the trick that makes checking fast: the model marks its own factual claims, so your review becomes a hunt through a short list rather than a line-by-line read of the whole plan.

**Step 3 — Verify every `[VERIFY]`, every number, every procedure step.** Check each against policy, your educator's materials, or a current trusted reference. Delete anything you can't verify; replace it with your unit's own version. Time cost: ten honest minutes per lesson plan, and it is the ten minutes that makes the chapter worth using.

**Step 4 — De-AI the tone.** Chatbots write like brochures ("in today's fast-paced healthcare environment"). Delete that voice. Keep the structure, rewrite sentences the way you actually talk — your voice is the deliverable; the tool only built the scaffolding.

**Step 5 — Run the dry run.** Teach from the plan once on dead time or on paper. Anything that stalls (a moment that needs two extra minutes, a question that lands flat) gets a one-line edit. A local file naming it is enough — see the lesson-plan section of your [weekly teaching plan](../worksheets/weekly-teaching-plan.html).

**Step 6 — Log what you used.** Keep your record in the [precept hours log](../worksheets/precept-hours-log.html), and park any lesson that turned out well in a *personal* folder (not the facility's educational record) as that rarest of things: a reusable teaching asset whose provenance you verified yourself.

## What the draft is good at, and what it never is

| Where AI drafts shine | Where a human is always required |
|---|---|
| Sequencing your own priorities into a plan shape | Whether [topic X] is the right priority at all |
| Formatting tables, checklists, timings | Whether any step matches your unit's process |
| Generating question varieties off your ladder | What counts as safe practice on your unit |
| Writing first-draft confusion paragraphs | Whether the pedagogy fits the orientee in front of you |
| Rewriting your rough sentences into plan grammar | Everything clinical; everything graded; anything signed |

A good calibration: the tool is a competent, tireless, occasionally-confident sedentary colleague with zero facility experience. Use it for format and stamina; hold ownership of substance.

## The failure modes (and their early warnings)

- **Confident fabrication.** The draft invents a policy name, a normal range, a step order. Early warning: prose with no `[VERIFY]` markers. Counter: run your Step-3 pass with extra suspicion on anything that sounds memorized.
- **Scope creep into clinical advice.** A "lesson plan" quietly becomes care guidance. Early warning: sentences about patients rather than orientees. Counter: stop there, delete, re-prompt with the education-only constraint up front and let the clinical frame stay human.
- **The borrowed identity problem.** A published-sounding plan you didn't verify and can't defend. Early warning: the words "standard practice" appearing where your facility's actual practice differs. Counter: every plan ends with "checked against [your source] on [date] — [initials]."
- **Data leakage.** The rules' first rule. If a draft would embarrass anyone before any other concern: no identifying detail goes in, ever, even "just this once."

One line to remember: run the exact same checks you would run on teaching material from any respected source — the *source* is just newer and stranger.

## An honest time budget

Plan the tool so it pays rent. First lesson plan with this workflow: ~40–50 minutes (prompt, review, rewrite, dry run). Each similarly-shaped one after: 20–30. Handwritten from scratch: often the same as the first run every time. The savings are real but they come *after* verification discipline settles; skip the verification step to save the time and you've paid more than you saved.

## The one-line summary

AI is a formatting engine with a liability problem: it can turn your one sentence of priorities into a usable plan in minutes, and it's yours to verify, de-AI, and own — with the same care you'd use for any teaching material, and with zero patient data anywhere in the loop.

---

*Copyright (c) 2026 Asdale Dynamics, LLC. Licensed under the MIT License. Education only — not medical advice.*
