# Day 3 — Visual Explainers (Anatomy Infographics with AI)

## The skill
Taking something you want to understand (an object, a system, a concept), learning
it well enough to specify every part, every function, and a few real numbers, and
then using AI image models to turn that understanding into a clean, single-page
"Anatomy and How It Works" infographic you can present from. The reasoning skill is
decomposition: you cannot specify a labeled diagram of something you do not
understand. The AI skill is two-sided: writing a precise image prompt, and then
evaluating what comes back instead of trusting it.

## The format you are building
Look at the sample infographics. Each one is a single page with the same regions:
- A **title band**: the object's name and "Anatomy and How It Works."
- A **main illustration**: a large cutaway (sliced open) or exploded (parts pulled
  apart) view, with callout labels on thin leader lines, each label naming a part
  and often a short fact about it.
- A **side panel**: an exploded or "inside the X" breakout listing the components.
- A **bottom row of info panels**: How It Works, Key Features, Specifications (with
  real numbers), and sometimes Materials, Applications, or a Did You Know.

That is the target. The numbers matter: a specs panel is exactly where an image
model will invent a confident, wrong figure, so this format makes the
fact-checking real.

## Why this matters
An AI image model will happily hand you a gorgeous, confident, wrong infographic.
It will invent parts, misspell labels, point a leader line at empty space, put the
retina at the front of the eye, and fill a specs table with numbers it made up. The
lazy move is to generate a pretty page and present it. That teaches nothing, and
worse, it spreads errors with a professional-looking finish. This workshop forces
the harder loop: understand the object first, specify it (parts and numbers),
generate across more than one model, then catch the lies before you stand up to
talk. Students learn that not all AI tools are equal, and that the human is the
fact-checker, not the audience.

## Learning objectives
By the end, each student can:
- Decompose a real object into its parts, state what each does in their own words,
  and gather a few real specs, before generating anything.
- Write a detailed, efficient image prompt that specifies the infographic layout:
  title, main view, the parts to label, the side panel, and the info panels.
- Generate the same infographic in two (or more) image models and across several
  attempts in one model.
- Evaluate outputs against the truth: spot hallucinated parts, wrong labels,
  mislabeled positions, garbled text, and invented spec numbers, and score the
  models on accuracy, legibility, and clarity.
- Refine a prompt to fix specific errors, then select and defend a final image.
- Present the infographic, explain each labeled part and verify one spec number
  from understanding, and field live questions.

## How it runs (two students + instructor)
You model the whole loop once on an instructor example (Planet Earth, then the
human eye if you want a second pass). Then each student picks one object of their
own from the idea list (or their own choice) and works the loop. They present the
finished infographic and their model comparison, and the group asks questions.

## Tools
This is the first workshop that needs image generation. The examples use ChatGPT
Image 2 and Nano Banana 2, but the lesson is tool-agnostic: any two or more image
models work, and comparing them is the point. You also use a regular text chatbot
(ChatGPT, Claude, Gemini, Copilot) to check the parts list, the specs, and the
labels the image model produces.

## Agenda (~75–90 min)
1. (15 min) Instructor live-models the full loop on Planet Earth: decompose out
   loud, write the spec (parts and numbers), show a vague prompt vs. a precise one,
   generate in two models, then critique both outputs and catch the errors live,
   including a made-up spec number.
2. (10 min) Students pick one object and fill in Phase 1 (the spec), no image AI
   yet. They may use a text chatbot only to check what they already drafted.
3. (15 min) Phase 2: students write their image prompt and generate across two
   models, several attempts each. You circulate.
4. (20 min) Phase 3: students evaluate, fact-check labels and numbers, score the
   models, refine the prompt, and select a final image.
5. (20 min) Phase 4: present-backs (infographic walkthrough + model comparison) and
   Q&A. Score with the rubric.

## Materials
- `examples/` — two instructor examples (Planet Earth, human eye) with full specs
  and prompts, plus `student-object-ideas.md`. The specs double as facilitator
  answer keys: do not hand them to students working those objects.
- `prompts/` — the two AI roles and the reusable image-prompt recipe.
- `worksheets/object-spec.md`, `worksheets/generation-log.md`,
  `worksheets/model-scorecard.md`, `worksheets/present-worksheet.md`.
- `presentation-rubric.md`.
- `worked-examples-prompt-anatomy.md` — vague vs. precise prompts, and what each
  produces. Show these before students start.

## The anti-pattern to watch for (say this out loud)
A beautiful page is not a correct page. The tell is a student who can describe how
the infographic looks but freezes when you point at a label and ask "what does that
part actually do, and is that label in the right place?" or point at the specs and
ask "is that number real?" If they only learned the picture, not the object, they
will defend a hallucinated part and a fake number because both look official. Push
them: "which label or number did the model get wrong, and how do you know?"

## Facilitator notes
- Make them write the spec before they touch an image model. You cannot prompt
  parts and numbers you cannot name, and the struggle to name them is the learning.
- Reward catching errors over making pretty pictures. A plain infographic with every
  label and number verified beats a stunning one with three invented parts.
- Image models are weak at text and worse at numbers. Expect misspelled labels and
  invented specs. That is not a bug to hide; it is the model-evaluation lesson. Let
  students discover that one model spells better, or that the cleanest move is to
  generate the illustration and add correct labels and a real specs table
  themselves.
- The closing-question habit carries from Day 1 and Day 2: the text prompts here
  end by asking the student something. Do not let them skip answering.
