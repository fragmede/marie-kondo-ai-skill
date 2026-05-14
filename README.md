# marie-kondo

A Claude skill that runs an aggressive refactor pass when you ask whether the code sparks joy.

## What it does

When Claude breathlessly presents a triumphant solution, ask:

> yes, but does it spark joy?

And Claude will switch from build mode into adversarial review mode against its own prior output. It inventories every function, class, dependency, config option, and exception type it introduced, then cross-examines each one with a single question: **what breaks today if I delete this?**

Hypothetical future callers, "for extensibility" abstractions, single-use helpers, ceremonial try/except blocks, and options dicts with one key all get culled.

## Triggers

- "does it spark joy?"
- "marie kondo this"
- "kondo it"
- "thank it and let it go"
- "is all this necessary?"
- "this feels like a lot"
- "tidy this up"

## Install

Download the `SKILL.md` and install it via your Claude client's skill installation flow, or package it with the `skill-creator` tooling.

## License

MIT
