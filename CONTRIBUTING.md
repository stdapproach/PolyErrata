# Contributing to PolyErrata

Thank you for checking the math. Every confirmed erratum makes a book more reliable.

## What counts as an erratum

- A mathematical error: wrong formula, sign, index, coefficient, theorem statement, or counterexample.
- A typo that changes meaning: wrong symbol, wrong set, wrong reference to a figure or equation.
- A questionable statement that needs checking. Mark it as "probable" and explain why.

Style or wording preferences are not errata.

## Entry format

Use one row per finding in the book's file under `errata/`:

| Page | Printed | Should be | Reason |
|---|---|---|---|
| 18 | `w z^{-1} = w z̄ = \overline{zw}` | `w z̄ = -\overline{zw}` for purely imaginary `w` | Counterexample: `z = 1`, `w = i` gives `i` on the left and `-i` on the right |

Rules:

1. Give the exact printed text or formula, using LaTeX or plain text.
2. Give the correction and the reason. A counterexample is the strongest form.
3. Do not paste long passages of copyrighted text. Quote only the formula or the shortest necessary fragment.
4. State the edition and the printing if known.

## Confidence levels

- **Confirmed**: verified against the printed book and a derivation or counterexample.
- **Probable**: the reasoning is convincing but the printed edition was not checked.
- **Questionable**: needs discussion.

## Process

1. Open an issue describing the book and the scope of your check, or go straight to a pull request.
2. Add or update the file in `errata/`.
3. Another contributor reviews the entry before it is marked confirmed.
4. Maintainers may ask for the printed page to be checked.

## Conduct

Be precise, be kind, and assume the author made an honest mistake. Criticism is about formulas, not people.
