# Phase 3 — Evaluate, refine, and select

This is the thinking phase. You have several images from two models. Most of them
have something wrong. Your job is to find it.

## Evaluate against the truth
Put each generation next to your Phase 1 spec and check it on five things. Score
them in `worksheets/model-scorecard.md`.

1. **Accuracy of parts.** Are the parts the right parts, in the right places? Did
   the model invent a part that does not exist? Did it drop one you needed? An eye
   with the retina at the front is a confident lie.
2. **Label correctness.** Are the labels spelled right, and pointing at the right
   thing? Image models are weak at text, so expect misspellings and nonsense words.
   A leader line pointing at empty space counts against the score.
3. **Number accuracy.** This is the new one for the infographic format. The model
   filled in a specs panel. Are those numbers real, or did it make them up? Check
   each one against the specs you gathered in Phase 1. Invented numbers are the
   easiest error to miss because they look so official.
4. **Legibility.** Can you actually read the labels and the panels, or are they
   mush?
5. **Clarity and looks.** Is it clean and presentable, or cluttered and confusing?

Looks come last on purpose. A stunning infographic with two invented parts and a
fake spec is worse than a plain one that is correct.

## Fact-check the labels and numbers with AI
Use `prompts/fact-check-the-labels.md`. Paste the labels and the spec numbers a
generation produced and have a text AI flag which ones are wrong. Then verify its
answer against your own spec. The AI is a second pair of eyes, not the judge: you
confirm.

## Refine within a model
Pick your most promising image and fix its specific errors with
`prompts/refine-within-a-model.md`. Change one thing at a time: fix a label, move a
part, correct a number, simplify the layout. Regenerate. Notice that some fixes
work and some make new problems. That is normal, and worth writing down.

If the labels or numbers stay garbled no matter what, a real and honest technique
is to generate the unlabeled illustration and add clean, correct labels and a real
specs table yourself. Knowing when a model cannot do something is part of
evaluating it.

## Select and decide
Pick your final image and write down two things: which model won, and on which
criteria. They may not be the same answer for every category. Maybe Model A drew
the better structure but Model B spelled the labels, while neither got the specs
right. Say so. The point is a defended choice, not a favorite.
