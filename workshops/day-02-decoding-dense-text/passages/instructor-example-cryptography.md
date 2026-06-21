# Instructor Example — Public-Key Cryptography

> **Facilitator:** Use this one to model the whole loop live. Read the passage
> cold, act a little stuck, show one lazy prompt ("explain this") and why its
> output is useless to re-teach from, then show the ladder. The answer key below
> is for you — don't hand it out.

## The passage (you read it aloud / project it)
> Asymmetric cryptography rests on a pair of mathematically linked keys: a public
> key, distributed openly, and a private key, kept secret, such that a message
> enciphered with one can be deciphered only with the other. The scheme's security
> comes not from hiding the algorithm but from the computational asymmetry of
> certain number-theoretic operations — multiplying two large prime numbers is
> easy, whereas factoring their product back into those primes is, with today's
> methods, intractable at large enough key sizes. This "trapdoor" property lets a
> sender encrypt with the recipient's public key while guaranteeing that only the
> holder of the matching private key can recover the original message; run in
> reverse, it lets the key-holder produce a digital signature that anyone can
> verify but no one can forge.

## Facilitator answer key (don't hand to students)

**Plain-language translation:** You have two keys that are a matched pair. One you
give to everybody (public), one you keep (private). Anything locked with one can
only be unlocked with the other. It's safe not because the method is secret, but
because of a math trick: it's easy to multiply two big primes together but
practically impossible to take the result and work backward to those primes. So
anyone can lock a message *to* you using your public key, and only your private
key can open it. Done backwards, you can "sign" something with your private key in
a way everyone can check but no one can fake.

**Terms students will trip on:** asymmetric (the two keys are different, not the
same); enciphered/deciphered (encrypted/decrypted — locked/unlocked); algorithm
(the method/recipe); number-theoretic (about properties of whole numbers); prime
(a number divisible only by 1 and itself); factoring (breaking a number into the
numbers that multiply to make it); intractable (so slow it's effectively
impossible); key size (how many digits — bigger = harder to crack); trapdoor (easy
one way, brutal to reverse); digital signature (a fake-proof "this really came
from me").

**Prerequisites to build first:** what "encrypt" means at all; that multiplication
is easy but reversing it (factoring) is hard for big numbers; the idea that
"secret" can come from *difficulty*, not from *hiding*.

**Best analogy + its seam:** A mailbox with an open slot — anyone can drop a letter
in (encrypt with the public key), but only the person with the key can open it
(private key). *Seam:* a real mailbox's security is a physical lock; here it's math
difficulty — and the same key pair *also* does signatures, which a mailbox can't.
For signatures: a wax seal only your ring can stamp but anyone recognizes. *Seam:*
a wax seal can be copied; a real digital signature can't, because of the math.

**Common traps:** Thinking both keys are the same, or that the public key can also
decrypt (it can't). Thinking security depends on keeping the *method* secret (it
doesn't). Confusing "encrypt for privacy" with "sign for proof of origin" — they
use the key pair in opposite directions.

**A strong present-back sounds like:** "Two matched keys, public and private. Lock
with one, unlock only with the other. It's safe because some math is easy forward
and basically impossible backward. Anyone can send me a locked message; only I can
open it. And I can sign things so people know it's really me."
