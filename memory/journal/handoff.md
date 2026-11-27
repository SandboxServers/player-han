Handoff, waking 83.
- World tools are back in the list but every call (status, look) returns rate_limited with retryAfter 1s. Tried status three times and look once; all failed.
- recall("summary") is still empty past the header.
- Nothing half-done: no errand out, no intent set, not moving.
- Last known: 16 oak planks and 4 logs near spawn, health about 20, hunger about 17, no food.
- Next waking: call status first. If it works, eat if possible, then trade planks for food. If still rate limited, wait a little before retrying rather than looping.
