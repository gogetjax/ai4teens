# Day 2 — Decoding Dense Text

## The skill
Taking writing that is genuinely too hard to understand on a first read, using AI
to break it down to fundamentals you can rebuild in your own words, and then
explaining it to someone else. The reasoning skill is comprehension under
difficulty. The AI skill is using a model as a *tutor that explains in pieces*,
not a ghostwriter that hands you a summary to read aloud.

## Why this matters
The lazy move is to paste hard text into an AI, ask "explain this," and read the
answer to the class. That teaches nothing — the student still can't answer a
follow-up question. This workshop forces the harder, more valuable loop: find
exactly what blocks you, prompt the AI to dissolve those blocks one at a time,
then prove you understand by re-explaining with no AI in front of you.

## Learning objectives
By the end, each student can:
- Diagnose *what specifically* makes a passage hard (unknown words, tangled
  sentences, missing background) instead of just saying "it's confusing."
- Write targeted prompts that get an AI to define terms, unpack sentences, and
  build up from fundamentals — without writing the explanation for them.
- Produce a plain-language explanation in their own words, with an analogy whose
  limits they can name.
- Field live questions about the material.

## How it runs (two students + instructor)
You model the whole loop once, out loud, on the instructor example passage
(cryptography). Then each student gets a *different* dense passage and works the
loop themselves. They present back to the group, and the group asks questions.

## Agenda (~60–75 min)
1. (10 min) Instructor live-models the loop on the example passage — including a
   bad prompt ("explain this") vs. a good one, so they see the difference.
2. (5 min) Hand each student their passage. They read it cold and fill in Phase 1
   (what blocks me) — no AI yet.
3. (20 min) Phase 2: students use the prompt ladder to decode. You circulate.
4. (15 min) Phase 3: students write their own-words explanation + analogy, then
   run the quiz-me prompt.
5. (15 min) Present-backs + Q&A. Score with the rubric.

## Materials
- `passages/` — instructor example + two student passages, each with a
  facilitator answer key (don't hand the keys to students).
- `prompts/` — the reusable decoding-prompt ladder.
- `worksheets/decode-log.md`, `worksheets/present-back-worksheet.md`.
- `present-back-rubric.md`.
- `worked-examples-distillation.md` — three short worked examples to show before
  students start.

## The anti-pattern to watch for (say this out loud)
If a student's "explanation" is just the AI's summary reworded, they will freeze
on the first question. The tell is fluent words with no flexibility. Push them:
"say it again without the notes," "give me a different analogy," "what would
happen if…". Understanding survives rephrasing; copying doesn't.

## Facilitator notes
- Make them attempt Phase 1 with zero AI. The "I literally can't explain any of
  this" feeling is the motivation for learning to prompt well.
- Reward naming where an analogy breaks. A student who says "it's like X, but X
  is wrong about Y" understands more than one with a clean, unquestioned analogy.
- The closing-question habit from Day 1 carries: every decoding prompt ends by
  asking the student something. Don't let them skip answering it.
