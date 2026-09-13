# How a Statistic Lies (the five-trick mini-lesson)

Teach this before the game, in about ten minutes. A statistic does not have to be
false to mislead. Most of the misleading numbers students will meet are true.
They lie by what they leave out. Here are the five tricks, each with a question
that defuses it.

## Trick 1: The missing denominator
"Ten thousand people were injured by X last year." Ten thousand out of how many?
Out of a town, that is a catastrophe. Out of a country of hundreds of millions, it
is a rounding error. A count with no denominator is a number wearing a costume.

**Ask:** Out of how many? What is the rate, not the count?

## Trick 2: The missing base rate
"Most people arrested for Y were members of group Z." Sounds damning until you
learn that group Z is most of the population, or most of the people in the place
where arrests happen. The comparison that matters is the rate for group Z versus
the rate for everyone else, not the raw share.

**Ask:** Compared to what? What is the rate for the rest of the population?

## Trick 3: Relative versus absolute
"Doing X doubles your risk of Y." Doubles it from what? From one in a million to
two in a million is a doubling. So is from twenty percent to forty percent. The
first is nothing, the second is enormous, and the headline reads the same.

**Ask:** What is the actual risk before and after, in plain numbers?

## Trick 4: The cherry-picked window
"Crime is up thirty percent." Since when? A number that starts in an unusually
low year, or stops right before a drop, can be perfectly accurate and completely
misleading. The trend over ten or twenty years often tells the opposite story from
the trend over two.

**Ask:** Over what period? What does the longer trend look like?

## Trick 5: The shifting definition
"Teens spend nine hours a day on screens." What counts as screen time? Music
playing in the background? Homework on a laptop? Two apps open at once counted
twice? The number can be honest under one definition and absurd under another,
and the headline never tells you which was used.

**Ask:** What exactly was counted, and who decided?

## The reflex to build
When a number lands, before you react to it, ask one of the five questions. Out
of how many. Compared to what. Before and after. Over what period. What was
counted. A student who asks any one of those out loud has already beaten most
adults.

## Where the AI fits
An AI will hand you a number in the same confident tone whether it is complete,
stripped of context, or invented outright. It will also, if you ask, often supply
the missing denominator or base rate. The prompt in `prompts/out-of-how-many.md`
makes it do that. But the AI's answer to the follow-up question is itself a claim.
Verify it the same way.
