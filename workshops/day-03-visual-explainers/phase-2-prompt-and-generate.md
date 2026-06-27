# Phase 2 — Prompt and generate (across two models)

Now turn your spec into an image prompt and generate. Open
`prompts/image-prompt-recipe.md` and build your prompt region by region: title
band, main illustration, the exact parts to label, side panel, and the bottom info
panels (how it works, key features, specifications).

A vague prompt ("a diagram of a battery") gives you a vague, often wrong picture. A
precise prompt that names every region, lists the parts to label, and hands the
model your real spec numbers gives it far less room to invent. See
`worked-examples-prompt-anatomy.md` for vague vs. precise side by side.

The plan:
1. **Write one strong prompt** from your spec. Keep it detailed but efficient: name
   the parts you need labeled and the specs you want shown, skip the rest.
2. **Generate in Model A** (for example, ChatGPT Image 2). Generate it two or three
   times. The same prompt gives different results each run, and that is part of
   what you are evaluating.
3. **Generate the same prompt in Model B** (for example, Nano Banana 2). Same two
   or three runs.
4. **Log each generation** in `worksheets/generation-log.md`: which model, which
   attempt, and a quick first impression of what looks right and what looks off.

Do not refine yet, and do not pick a winner yet. Right now you are gathering
evidence. Resist the urge to fall in love with the prettiest one before you have
checked whether it is correct. That check is Phase 3.

Rule: keep your spec open next to the screen. For every generation, your job is to
compare the image to your spec, not to admire it.
