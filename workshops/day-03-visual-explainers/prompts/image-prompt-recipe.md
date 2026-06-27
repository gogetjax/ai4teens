# The Image Prompt Recipe

You are prompting for a single-page "Anatomy and How It Works" infographic, not
just a picture. A strong prompt names every region of the page so the model has
little room to invent. Skip a region and the model fills it with a confident guess.

## The five regions to specify
1. **Title band.** "Title reading [OBJECT NAME] with the subtitle Anatomy and How
   It Works across the top."
2. **Main illustration.** The view: "a large labeled [cutaway cross-section /
   exploded-view] of [SUBJECT] as the centerpiece," with callout labels on thin
   leader lines.
3. **Parts to label.** List the exact parts you want shown and labeled, by name.
   This is the most important line. The model labels what you name and invents what
   you leave vague.
4. **Side panel.** "A side panel titled Inside the [OBJECT] showing the main
   components separated and labeled."
5. **Bottom info panels.** "A row of boxed panels along the bottom: How It Works,
   Key Features, and Specifications." Give the model the real content for these so
   it does not make them up.

## The template
```
A single-page teaching infographic titled "[OBJECT NAME]" with the subtitle
"Anatomy and How It Works". Centerpiece: a large labeled [cutaway cross-section /
exploded-view] of [SUBJECT], with callout labels on thin leader lines pointing to
each of these parts: [PART 1], [PART 2], [PART 3], [PART 4], [PART 5]. A side panel
titled "Inside the [OBJECT]" shows the components separated and labeled. Along the
bottom, a row of boxed panels: a "How It Works" panel reading "[YOUR HOW-IT-WORKS
TEXT]", a "Key Features" panel listing [FEATURE 1], [FEATURE 2], [FEATURE 3], and a
"Specifications" panel listing [SPEC 1 WITH NUMBER], [SPEC 2 WITH NUMBER], [SPEC 3
WITH NUMBER]. Style: clean modern scientific infographic, flat, high-contrast,
professional, uncluttered, readable labels. Keep proportions accurate and parts in
their correct positions.
```

## Keep it efficient
Detailed does not mean long. Name the parts and specs you actually need and drop
the rest. A prompt that names six real parts and three real numbers beats a
paragraph of mood words. Every part and number you name is one the model must get
right, which is also one you can check.

## A warning to expect
Image models are weak at text and worse at numbers. Even a perfect prompt may come
back with misspelled labels and a specs panel full of figures it invented, even
when you gave it the real ones. That is not your failure; it is the model's limit,
and noticing it is half the lesson. If the text stays garbled, generate the
illustration clean and add correct labels and a real specs table yourself.

After your first generation, ask yourself: which regions did my prompt control
well, and which did the model still get to invent? Tighten those lines next.
