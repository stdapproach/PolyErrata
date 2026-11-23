# PolyErrata

An open, volunteer effort to systematically check mathematics books (and books with heavy formulas, such as flight dynamics and classical mechanics) for typos and mathematical errors, and to publish verified corrections.

## Why

Mathematics textbooks contain errors that survive reprints for decades. Authors are busy, publishers rarely re-check every formula, and a reader who finds a sign error often assumes the mistake is their own. Checking is slow when one person does it alone.

PolyErrata applies the idea behind the Polymath project (Tim Gowers, 2009): many small, public contributions can check and solve things that are hard to do in isolation. Here, the work is to read carefully, verify each claim, and document the result.

Intellectual inspiration: V. I. Arnold's view that mathematics is a natural science with open problems, and his essay on polymathematics.

## Agenda

Read the math. Find the errors. Publish the fix. Credit the reader.

## Principles

1. Every erratum has a page number, the printed text, the correct version, and a reason. The reason is a derivation or a counterexample that anyone can check by hand.
2. Corrections are public and versioned in this repository.
3. Publishers and authors are informed directly before or alongside publication.
4. We do not reproduce copyrighted book text. Errata cite page, line, and formula only.
5. Be precise and respectful. The goal is a correct book, not a hostile review.

## Repository layout

- `errata/` one Markdown file per book, listing confirmed and probable errata
- `CONTRIBUTING.md` how to submit a check or an erratum
- `LICENSE` CC BY 4.0

## How to contribute

1. Pick a book and read it with a pen.
2. For each finding, record: page, what is printed, what it should be, and why.
3. Open an issue or pull request that adds your entry to the relevant file in `errata/`.
4. Reviewers confirm or reject each entry.

See `CONTRIBUTING.md` for details.

## Status

Started with a complete page-by-page check of V. I. Arnold, *Geometry of Complex Numbers, Quaternions and Spinors* (MCCME, 2002). See `errata/1_arnold-complex-numbers-quaternions-spinors-2002/1_arnold_v0.md`.

## Hashtags

#PolyErrata #MathErrata #CheckTheMath

## License

Text of errata and documentation: Creative Commons Attribution 4.0 International (CC BY 4.0). See `LICENSE`.
