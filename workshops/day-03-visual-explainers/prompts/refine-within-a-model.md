# Prompt: Refine within a model

Use this in Phase 3 once you have a promising image with specific problems. Change
one thing at a time so you can tell what actually helped.

## How to refine
Most image models let you edit a generation by describing the change, or you can
re-run an adjusted prompt. Either way, fix one error per attempt:

```
Keep this diagram the same, but make these specific fixes:
- The label "[WRONG LABEL]" should read "[CORRECT LABEL]".
- The part [PART] is in the wrong place; it should be [CORRECT POSITION].
- Remove the part [INVENTED PART]; it does not belong in this object.
Change only these. Keep everything else as it is.
```

## The one-change rule
If you fix four things at once and the result is worse, you will not know which
change broke it. Fix one, regenerate, look. Log what happened in your generation
log. Some fixes work; some create new errors; some the model simply cannot do.
All three are useful findings.

## When to stop refining
If the same error survives three honest attempts, the model probably cannot fix it
with words. That is a real result. Switch models, or generate the clean
illustration and add the labels yourself.

Before your next attempt, ask: did my last change fix the thing I aimed at, or did
it just move the problem somewhere else?
