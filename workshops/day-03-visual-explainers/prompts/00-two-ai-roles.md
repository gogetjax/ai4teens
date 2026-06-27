# The Two AI Roles

This workshop uses AI in two different ways, and keeping them separate is the
whole skill.

**1. A text AI as a checker (not an answer machine).**
Before and after you generate, a regular chatbot helps you *verify* your own
thinking. You draft the parts list; it tells you what you missed. You read the
labels off an image; it flags which ones look wrong. You never let it write the
list or judge the diagram for you. You decide; it challenges.
- `verify-my-parts.md` — check your decomposition before you generate.
- `fact-check-the-labels.md` — find wrong labels after you generate.

**2. An image AI as a renderer (that you do not trust blindly).**
The image model turns your spec into a picture. It is fast, it looks
professional, and it is often wrong. Your job is to specify tightly, generate
across more than one model, and catch the errors.
- `image-prompt-recipe.md` — build a strong, efficient image prompt.
- `refine-within-a-model.md` — fix specific errors and regenerate.

**The golden rule:** the AI makes the picture, but you make the meaning. If you
present a diagram you cannot defend part by part, you have learned the tool and
skipped the object. Every text prompt below ends by asking you something, on
purpose, to keep the thinking in your hands.

Order of use:
1. `verify-my-parts.md` (Phase 1, after you draft your spec)
2. `image-prompt-recipe.md` (Phase 2)
3. `refine-within-a-model.md` (Phase 3)
4. `fact-check-the-labels.md` (Phase 3)
