# Statement and verification conditions

**Theorem.** `<statement>`

Reference: `<authors>`, `<title>`, `<DOI or arXiv id>`. Lemma numbers below refer to it.

## Setting

- Spaces and norms:
- Truncation parameters and constants:
- The map(s):
- Arithmetic the checker relies on (library, precision):

## Inputs (in `data/`)

- Frozen: `<file>`: `<what the numbers are, mathematically>`; byte layout `<element type, endianness, ordering; intervals as (inf, sup)>`. Hashes in `data/hashes.json`.
- Produced: `<object>`, by `<the produce command>` (or recomputed by the checker): `<what it is, and why the conditions do not depend on its exact value>`.
- Constructions the checker performs on the inputs (interpolation, etc.):

## Conditions to verify

Each is a finite computation in rigorous arithmetic on the inputs above.

0. **Input enclosures.** `<which stored intervals must enclose which stated quantities>`
1. **`<name>` (Lemma X).** `<inequality>`
2. ...

All conditions hold ⇒ Theorem.
