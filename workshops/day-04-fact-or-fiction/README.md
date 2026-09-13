# Day 4 — AI: Fact or Fiction

## The skill
Taking a claim you cannot personally settle, getting an AI to state it and back it
with sources, and then verifying it against the real world before you believe it or
repeat it. This is the hardest version of the skill the first three days built.
Day 2, you caught the AI distorting a text by checking it against your own
understanding. Day 3, you caught it inventing parts and specs by checking against a
known spec. Day 4, you catch it inventing facts and sources by checking against
reality, where nobody hands you the answer key.

## The frame: Bot on Trial
The AI is the defendant. You are the investigator. Reality is the judge. Every
claim goes on trial, and you reach a verdict you can defend with receipts. It is a
game with a scoreboard, and the one rule that makes it a real skill instead of a
shouting match: no receipt, no points. Points are earned by verification backed by
a source, never by a hot take.

## Why this matters
An AI will hand you a fabricated citation with a real-sounding author, a real
journal, and a plausible year, and it looks exactly as trustworthy as a real one.
It will also hand you a true statistic stripped of the context that makes it
honest. Both failures look authoritative. The lazy move is to believe the confident
answer and repeat it. This workshop trains the opposite reflex: check the source
exists, check it says what the AI claimed, check the number against the base rate,
before it leaves your mouth. That reflex is the single most useful thing a teenager
can carry out of an AI literacy class.

## Learning objectives
By the end, each student can:
- Take a claim they cannot personally settle and get an AI to state it and cite
  sources for it.
- Verify a source three ways: does it exist, does it actually say what the AI
  claimed, and is it credible (lateral reading).
- Spot the common tricks a statistic uses to mislead, and ask "out of how many."
- Reach one of four verdicts and defend it with a receipt: Busted, Guilty of Spin,
  Cleared, or Mistrial.
- Notice the gap between how confident an AI sounds and how correct it turns out to
  be.

## The four verdicts
- **Busted** — the claim or its source is fabricated or false.
- **Guilty of spin** — the claim is technically true but misleading out of context.
- **Cleared** — the claim checks out and the sources are real and on point.
- **Mistrial** — it cannot be verified either way with the time and sources you
  have. (This is a real, honest verdict, not a cop-out. Saying "I can't confirm
  this" is a skill.)

## How it runs (two students + instructor)
Open with the gasp moment (below). Then each student picks a claim from the claim
bank, puts the bot on trial, investigates, and delivers a verdict to the group.
Points go up on the scoreboard as verdicts are defended. The instructor plays judge
and decides whether a receipt is good enough to score.

## The gasp moment (open with this)
Pick a claim, ask an AI to explain it and cite its sources, and read the sources
aloud so they sound impressive: a real journal, a named author, a year. Then open
them live, in front of the students. Some will not exist. That thirty seconds sells
the entire workshop better than any lecture. Have one or two claims pre-tested that
reliably make your models fabricate, so it does not fizzle if a model happens to
answer honestly on the day (see `examples/instructor-example-fabricated-source.md`).

## Tools
This is the first workshop that pairs a chatbot with the open web. Students use an
AI to generate the claim and its sources, then a search engine or browser to verify
them. The examples use two chatbots for the head-to-head, but any will do.

## Agenda (~75–90 min)
1. (15 min) The gasp moment, live, on an instructor claim. Introduce the four
   verdicts and the scoreboard. Teach the one rule: no receipt, no points.
2. (10 min) Walk `how-a-statistic-lies.md` so students have the tricks in hand
   before they hit the Scary Statistics claims.
3. (10 min) Students pick a claim (Phase 1) and predict how confident the AI will
   sound versus how right it will be.
4. (15 min) Phase 2: put the bot on trial, log every claim and every source.
5. (20 min) Phase 3: investigate and verify. Circulate and judge receipts.
6. (15 min) Phase 4: verdicts to the group, scored on the board.

## Materials
- `scoreboard.html` — the on-screen scoreboard. Open it in any browser on the
  projector. Add a team per student or pair; tap a verdict button to score.
- `how-a-statistic-lies.md` — the five-trick mini-lesson. Teach before the game.
- `examples/` — two instructor examples (a fabricated source, a true-but-misleading
  stat) and `claim-bank.md`. The claim bank has a student-facing menu and a
  facilitator answer key with the real data and sources. Do not hand the answer
  key to students working those claims.
- `prompts/` — the investigator toolkit.
- `worksheets/case-file.md` (the receipt sheet) and
  `worksheets/confidence-meter.md` (the gag).
- `verdict-rubric.md` — how points are earned.

## The anti-pattern to watch for (say this out loud)
Points for opinions. The moment a student earns a point for "I just think that's
fake," the game has taught the opposite of what you want. Every point needs a
receipt: a source that exists, that you opened, that says what you say it says.
"It feels wrong" is a reason to investigate, never a verdict.

## Facilitator notes on the sensitive claims
The Scary Statistics set touches immigration, group size, and crime. It is built so
the real data defuses a stereotype rather than putting a group on trial. Hold two
lines:
- Name the misconception as a misconception and pair it with the reality in the
  same breath. Never leave a false claim hanging in the air, because repeating a
  lie on its own makes people believe it more, even when you meant to debunk it.
- Lead the group-size item with the point that everyone does this, including about
  their own group, because it comes from how brains handle proportions, not from
  prejudice. That keeps any student in the room from feeling indicted.
If a claim turns into "do you agree with it" instead of "did you verify it," steer
back to the receipt. The question is never whether you like the answer. It is
whether the source is real and says what was claimed.
