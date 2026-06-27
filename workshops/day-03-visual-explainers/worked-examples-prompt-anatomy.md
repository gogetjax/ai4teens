# Four Worked Examples — Prompt Anatomy

Show these before students start, to model the difference between a vague prompt
and a precise one. The first three use small objects so the move is clear; the
fourth shows the full infographic format you are actually building.

## Example 1 — Name the view, not just the object
**Vague:** "A diagram of a battery."
**What you get:** Usually a photo-like picture of a battery from the outside, with
no internal parts and no useful labels.
**Precise:** "A labeled cutaway cross-section of a single AA battery, sliced open
to show the inside. Label the case, the positive terminal, the negative terminal,
and the chemical paste inside."
**Lesson:** "Diagram" is not a view. The model needs to know whether to slice it
open (cutaway) or pull it apart (exploded). Name the view and half the vagueness
disappears.

## Example 2 — List the parts you want labeled
**Vague:** "A cutaway of a flower with labels."
**What you get:** Some labels, often the wrong ones, often misspelled, sometimes
pointing at nothing.
**Precise:** "A labeled cutaway of a flower. Label exactly these parts: petal,
stamen, pistil, ovary, and stem. Put each label on a thin leader line to the
correct part."
**Lesson:** If you do not name the parts, the model picks them, and it picks badly.
The list of parts is the single most powerful line in the prompt, because every
part you name is also a part you can check afterward.

## Example 3 — Set the layout and style, then expect text errors
**Vague:** "A nice infographic of the water cycle."
**What you get:** Something busy and decorative, with arrows that may not match the
real steps and words that may be gibberish.
**Precise:** "A clean, uncluttered diagram of the water cycle showing evaporation,
condensation, and precipitation, labels on thin leader lines, balanced spacing,
flat textbook style, high contrast. Keep the steps in the correct order."
**What to still expect:** Even now, the labels may be misspelled. Image models are
weak at text.
**Lesson:** Layout and style words make a diagram presentable, but they do not fix
the model's biggest weakness, which is text.

## Example 4 — The full infographic, and the numbers trap
**Vague:** "An anatomy and how it works infographic of a bicycle."
**What you get:** A page that looks the part, with panels and a specs box, but with
invented part names, a made-up weight, and a gear count that is simply wrong.
**Precise:** "A single-page teaching infographic titled 'The Bicycle' with the
subtitle 'Anatomy and How It Works'. Centerpiece: a labeled exploded view with
callouts to frame, fork, chain, crank, and rear derailleur. A side panel 'Inside
the Bicycle' listing the components. Bottom panels: How It Works (pedaling turns
the crank, which drives the chain, which turns the rear wheel), Key Features, and
Specifications listing 'Wheel size 700c', 'Typical weight 8 to 12 kg', 'Gears 1 to
22'. Clean flat textbook style."
**What to still expect:** The specs panel may still show numbers the model invented,
even the ones you supplied. Check every figure against a real source.
**Lesson:** The fuller the infographic, the more places the model can lie, and the
specs panel is the sneakiest, because a wrong number looks exactly as official as a
right one. In this format your job is to verify the words and the numbers.
