# Instructor Example — Planet Earth

> **Facilitator:** Use this one to model the whole loop live. Decompose Earth out
> loud, write the spec on the board, show a vague prompt vs. the precise one,
> generate in two models, then critique both and catch the errors in front of the
> students, including a made-up spec number. The spec below is your answer key.
> Don't hand it to a student who picks Earth.

## The object and the main view
Planet Earth, as a **cutaway cross-section**: a wedge sliced out so you can see the
layers from the center to the surface. This view beats a plain globe because the
whole point is what is inside.

## The parts (position, function)

| Part | Where it sits | What it does |
|------|---------------|--------------|
| Inner core | Dead center | Solid ball of iron and nickel. Stays solid despite huge heat because the pressure is so high. |
| Outer core | Around the inner core | Liquid iron and nickel. Its swirling motion generates Earth's magnetic field. |
| Mantle | The thick middle layer | Hot rock that flows very slowly over millions of years. Its slow churn drives the moving plates above it. |
| Crust | The thin outer shell | The cold, rigid rock we live on. Thin under oceans, thicker under continents. |
| Atmosphere | A thin band above the surface | The layer of gases held by gravity. Where weather happens and what we breathe. |

## The rest of the infographic
**How it works (panel text):** Earth is a set of nested layers. Heat left over from
its formation, plus heat from radioactive decay, keeps the inside hot. That heat
makes the mantle flow slowly, which moves the plates of the crust, and makes the
liquid outer core swirl, which generates the magnetic field that shields the
surface.

**Key features:** A liquid outer core that runs a planet-wide magnet. A solid inner
core kept solid by pressure, not cold. A thin crust broken into moving plates. A
thin atmosphere that holds in heat and water.

**Specifications (real numbers to give the model, and to check it against):**
- Diameter: about 12,742 km.
- Inner core radius: about 1,220 km.
- Mantle thickness: about 2,900 km.
- Surface temperature average: about 15 degrees C; inner core: roughly 5,200 degrees C.

**Did you know:** The inner core is hotter than the surface of many stars, yet it
is solid, because the pressure at Earth's center is too high for it to melt.

## A vague prompt vs. a precise one
**Vague (show this first, then show what's wrong with it):**
```
A diagram of the layers of the Earth.
```
This gives a generic, often inaccurate picture: layers in the wrong proportions
(the crust drawn far too thick), missing labels, and no real specs at all.

**Precise (build this from the spec):**
```
A single-page teaching infographic titled "Planet Earth" with the subtitle
"Anatomy and How It Works". Centerpiece: a large labeled cutaway cross-section of
Earth, a wedge removed to show the interior, with callout labels on thin leader
lines pointing to: inner core, outer core, mantle, crust, and atmosphere. A side
panel titled "Inside the Earth" shows the layers stacked and labeled. Along the
bottom, boxed panels: a "How It Works" panel about heat driving the mantle and
core; a "Key Features" panel listing the liquid outer core, the pressure-solid
inner core, and the thin moving crust; and a "Specifications" panel listing
"Diameter 12,742 km", "Inner core radius 1,220 km", "Mantle thickness 2,900 km".
Style: clean modern scientific infographic, flat, high-contrast, professional,
uncluttered. Keep layer thicknesses roughly to scale, with a thin crust and a thick
mantle.
```

## Errors to catch on purpose (the live lesson)
- **Crust drawn way too thick.** The most common mistake. The real crust is a thin
  skin; models love to make it a fat band.
- **Layers in the wrong order**, or the inner and outer core swapped.
- **Outer core labeled as solid.** It is liquid. That is the whole reason it makes
  the magnetic field.
- **Garbled or misspelled labels**, or an invented layer between two real ones.
- **A made-up spec number.** Even after you hand it real figures, the model may
  print "Diameter 8,000 km" or invent a core temperature. This is the number-
  checking lesson: point it out and check it against the spec.

## A strong present-back sounds like
"It's a cutaway so you can see inside. Solid iron inner core in the middle, then a
liquid outer core whose swirling makes our magnetic field, then the thick slow-
flowing mantle that moves the plates, then the thin crust we live on, and a band of
atmosphere. The first model drew the crust as thick as the mantle and listed the
diameter as 8,000 km, both wrong, that's how I knew not to trust it."
