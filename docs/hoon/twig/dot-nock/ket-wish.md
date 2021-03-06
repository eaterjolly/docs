---
navhome: /docs
sort: 5
---

# `:wish  .^  "dotket"`

`{$wish p/moss q/seed}`: load from the Arvo namespace with Nock `11`.

## Produces

The noun whose name is `q`, cast to the icon of `p`.

## Discussion

Nock has no `11` instruction, of course.  But the virtual Nock
used to run userspace code does.  Nock `11` loads from a
typed immutable namespace defined by its virtual context.

We don't remold dynamically nouns in a `:wish`, but we do check
that the type of the value nests in `p`.
