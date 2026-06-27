# Instructor Example — The Human Eye

> **Facilitator:** A second example, a biological system, useful for a second pass
> or for a student who wants anatomy. Anatomy is where image models hallucinate
> most confidently, so this is the best example for the catch-the-lie lesson. The
> spec below is your answer key. Don't hand it to a student who picks the eye.

## The object and the main view
The human eye, as a **labeled cutaway cross-section**: the eyeball sliced through
the middle so you can see from the front (cornea) to the back (retina and optic
nerve).

## The parts (position, function)

| Part | Where it sits | What it does |
|------|---------------|--------------|
| Cornea | Clear dome at the very front | The main lens. Bends incoming light first and does most of the focusing. |
| Iris | Colored ring behind the cornea | Opens and closes to control how much light gets in. The colored part. |
| Pupil | The hole in the middle of the iris | The opening light passes through. Looks black. |
| Lens | Just behind the pupil | Fine-tunes the focus and changes shape to focus on near or far things. |
| Vitreous | The large clear gel filling the middle | Jelly that holds the eyeball's round shape and lets light pass to the back. |
| Retina | Lines the inside of the back wall | The screen. Light-sensitive cells turn light into nerve signals. |
| Optic nerve | Exits the back of the eye | The cable that carries the signals to the brain. |
| Sclera | The tough outer white wall | The protective outer coat. The white of the eye. |

## The rest of the infographic
**How it works (panel text):** Light enters through the clear cornea, which does
most of the focusing, passes through the pupil, gets fine-focused by the lens,
crosses the gel-filled middle, and lands on the retina at the back. The retina
turns light into electrical signals, and the optic nerve carries them to the brain,
which builds the image you see.

**Key features:** Two lenses working together (cornea and lens). An adjustable
opening (the pupil) that controls light. A light-sensing screen (the retina) with
millions of cells. A built-in blind spot where the optic nerve exits.

**Specifications (real numbers to give the model, and to check it against):**
- Eyeball diameter: about 24 mm.
- Number of photoreceptor cells in the retina: roughly 120 million rods and 6
  million cones.
- Field of view (both eyes): roughly 200 degrees wide.

**Did you know:** Each eye has a blind spot where the optic nerve leaves the
retina, with no light-sensing cells at all. Your brain fills in the gap so you
never notice it.

## A vague prompt vs. a precise one
**Vague (show first, then critique):**
```
A diagram of the human eye.
```
Often returns a front-on photo of an eye with no internal parts, or a cutaway with
random, misspelled labels and parts in the wrong place, and no real specs.

**Precise (built from the spec):**
```
A single-page teaching infographic titled "The Human Eye" with the subtitle
"Anatomy and How It Works". Centerpiece: a large labeled cutaway cross-section of
the eye, sliced through the middle to show the inside from front to back, with
callout labels on thin leader lines pointing to: cornea, iris, pupil, lens,
vitreous, retina, optic nerve, and sclera. A side panel titled "Inside the Eye"
shows the parts separated and labeled. Along the bottom, boxed panels: a "How It
Works" panel about light focusing onto the retina and signals traveling to the
brain; a "Key Features" panel listing the two-lens system, the adjustable pupil,
and the light-sensing retina; and a "Specifications" panel listing "Eyeball
diameter 24 mm", "About 120 million rods", "Field of view about 200 degrees".
Style: clean modern scientific infographic, flat, high-contrast, professional,
uncluttered. Keep the parts in their correct anatomical positions.
```

## Errors to catch on purpose (the live lesson)
- **Retina drawn at the front.** It is at the back. A classic confident lie.
- **Cornea and lens swapped or merged**, or the lens labeled as the part that does
  all the focusing (the cornea actually does most of it).
- **Optic nerve coming off the front** instead of the back.
- **Invented or Latin-sounding nonsense parts** with garbled spelling.
- **A made-up spec number**, like an eyeball diameter of "5 cm" or an invented cell
  count. Check each number against the spec.

## A strong present-back sounds like
"Light comes in the front through the clear cornea, which does most of the
focusing, then through the pupil, the hole in the colored iris, then the lens fine-
tunes it, across the jelly in the middle, onto the retina at the back, which turns
light into signals the optic nerve carries to the brain. The first model put the
retina at the front and said the eye is 5 cm across, both impossible, that's how I
caught it."
