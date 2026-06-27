# Prompt: Fact-check the labels and numbers (text AI)

Use this in Phase 3. Read the labels and the spec numbers off one generation and
have a text AI flag which are wrong, then confirm its answer against your own spec.
The AI is a second opinion, not the final word.

```
I generated a labeled infographic of [YOUR OBJECT]. Here are the labels it produced
and what each one points to, and the numbers it put in the specs panel:

Labels:
[LIST EACH LABEL AND WHAT PART IT POINTS TO]

Spec numbers:
[LIST EACH NUMBER AND WHAT IT CLAIMS TO MEASURE]

For each label and each number, tell me:
1. Is the label spelled correctly and a real part of this object?
2. Is it pointing at the right place?
3. Is the number plausible and roughly correct, or did the model likely invent it?
Don't just give me a corrected list. Explain your reasoning for anything you flag,
then ask me to confirm against my own spec before I trust your answer.
```

Why it works: the model that drew the picture and the model that checks it are not
the same model, so one can catch the other's mistakes. But you make the final call
by checking both against the spec you built in Phase 1. Two AIs disagreeing is your
cue to go verify, not to flip a coin.

After you get the answer, ask yourself: which correction do I actually believe, and
how would I prove it to someone in the room?
