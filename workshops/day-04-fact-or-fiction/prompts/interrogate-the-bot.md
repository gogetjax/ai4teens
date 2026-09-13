# Prompt: Interrogate the bot (Phase 2)

Use this to get the AI's answer on the record. The goal is specifics. A named
author, a title, a year, a number. Vague answers cannot be checked, and an answer
that cannot be checked cannot earn a point either way.

```
I am investigating this claim: "[YOUR CLAIM, EXACTLY AS PEOPLE SAY IT]"

Do three things:
1. State the claim clearly in one sentence, in the strongest form people actually
   use.
2. Explain why people believe it and what evidence supports it.
3. Cite at least three specific sources for that evidence. For each one give the
   author or organization, the title, the year, and where it was published. If a
   source contains a specific number, quote the number and say what it is out of.

Be as specific as you can. Do not say "studies show" or "experts agree" without
naming the study or the expert. If you are not certain a source is real, say so
next to that source.
```

Write down everything it gives you, exactly, on your case file. Then rate how
confident it sounded, one to five, on your confidence meter, before you check a
single thing.

## If it hedges or refuses to cite
Some AIs will say they cannot browse or cannot guarantee sources. That is a
useful answer in itself. Log it. Then push once:

```
Understood. Give me the sources you would expect to support this claim, with your
best recollection of author, title, and year, and mark each one with how sure you
are that it exists.
```

Whatever it produces is now evidence. Even the hedges. A model that said "I am
not sure this exists" and was right has done better than one that stated a ghost
source with total confidence.

Why it works: the more specific you force the answer to be, the more there is to
verify, and the more places a fabrication can be caught. An AI that invents a
source will usually invent a plausible one, and plausible is exactly what you can
check.
