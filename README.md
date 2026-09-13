# AI4Teens

**An open-source curriculum that teaches teenagers to think *with* AI, not to outsource their
thinking to it.**

AI4Teens is a free, ready-to-run set of workshops for any teacher, parent, or mentor who wants to
help young people use AI responsibly and critically. Each workshop pairs a real reasoning skill
with a way of using AI that *sharpens* that skill instead of replacing it. No technical background
required. If you can open a chatbot and read a lesson plan, you can teach this.

## Who it's for
- Teachers running a class, club, or elective
- Parents and homeschoolers working with their own kids
- Mentors, librarians, and anyone guiding teens through their first serious use of AI

The materials are written for high-school-age students but adapt easily up or down a grade or two.

## The idea behind it
AI can either sharpen a young person's thinking or quietly do it for them. The difference is in
*how* it's used. Every activity here rests on one principle: students do the thinking first, then
use AI as a partner to check, challenge, and extend that thinking, never as a vending machine for
finished answers. The prompts are deliberately written to make AI show its reasoning and hand
judgment back to the student.

## What's inside
Each workshop lives in its own folder under `workshops/` and contains:
- a **facilitator guide** (`README.md`): goals, agenda, and how to run the session
- **teaching materials**: example content plus facilitator answer keys
- **`prompts/`**: copy-paste AI prompts, one concept per file
- **`worksheets/`**: printable / copyable student handouts

## Workshops
| Day | Topic | What students learn |
|-----|-------|---------------------|
| 01  | Arguments & Counterarguments | Break down someone's argument, then use AI to build and evaluate a counterargument that targets its real weaknesses |
| 02  | Decoding Dense Text | Diagnosing what makes a text hard; using AI to break it down to fundamentals and re-explain it in your own words |
| 03  | Visual Explainers (Anatomy Infographics) | Decompose an object into its parts and specs, prompt AI image models to render a labeled "Anatomy and How It Works" infographic, then evaluate and refine across models to catch wrong labels and invented numbers |
| 04  | AI: Fact or Fiction (Bot on Trial) | Put a claim and the AI's sources on trial: interrogate the bot, verify sources by lateral reading, spot how a statistic misleads, and reach a defended verdict backed by a receipt |

More workshops are in progress.

## Getting started
1. Pick a workshop folder under `workshops/` and open its `README.md`: that's the facilitator guide.
2. Skim the example material and answer key so you know where the lesson is headed.
3. Have students work through the activity by hand first, then use the prompts in `prompts/` with
   any AI chatbot.
4. Compare, discuss, revise.

## What you need
Any general-purpose AI chatbot: ChatGPT, Claude, Gemini, Copilot, or similar. The prompts are
tool-agnostic; nothing here depends on a specific product or a paid plan.

Day 03 additionally uses image-generation models. The examples use ChatGPT Image 2
and Nano Banana 2, but any two or more image models work, and comparing them is
part of the lesson.

Day 04 pairs a chatbot with the open web (a search engine or browser) so students
can verify the sources and numbers an AI produces. It also includes scoreboard.html,
a self-contained on-screen scoreboard you open in any browser on a projector.

## A note on safety
The materials are designed to be age-appropriate, and the lessons emphasize responsible, honest use
of AI. To protect student privacy, this repository contains no real student names or personal data.
Worksheets use blank fields you fill in locally.

## Contributing
This is an open project. Teachers and parents are welcome to use, adapt, translate, and remix these
materials, and to contribute new workshops or improvements. Open an issue to suggest something, or a
pull request to add it. New workshops should follow the structure described in `CLAUDE.md`.

## License
Released under the Creative Commons Attribution 4.0 International license (CC BY 4.0): free to use,
share, and adapt for any purpose, including in your classroom or home, as long as you give
attribution. See the `LICENSE` file.
