# V. I. Arnold, *Geometry of Complex Numbers, Quaternions and Spinors* (MCCME, 2002): errata

**Scope:** all 40 pages of the PDF were checked visually, because the text layer is corrupted by non-standard font encoding. Page numbers match the printed pages. Formulas were checked by hand, not symbolically.

**Status:** draft. Items in section A must be re-verified against the printed book before publication.

## A. Mathematical errors (confirmed)

| Page | Printed | Should be | Reason |
|---|---|---|---|
| 13 | Cross product formula: `[v1,v2] = \|b1 b2; c1 c2\| i + \|c1 c2; a1 a2\| j + \|a1 a2; b1 b2\| k` | `\|c1 c2; d1 d2\| i + \|d1 d2; b1 b2\| j + \|b1 b2; c1 c2\| k` | The determinants use `a1, a2` where the components `d1, d2` belong, and the coefficients of `i, j, k` are shifted. |
| 18 | `w z^{-1} = w z̄ = \overline{zw}` | `w z̄ = -\overline{zw}` | Sign missing. For purely imaginary `w` we have `w̄ = -w`. Counterexample: `z = 1`, `w = i` gives `w z̄ = i` but `\overline{zw} = -i`. |
| 21 | "Embedding `RP³` in the complex projective plane `CP²`" | `RP²` | The discussion concerns the real projective plane (tetrahedron, 4 points, see preceding paragraph). |
| 35 | "`S³ ⊂ C³ \ 0`" for the Hopf fibration `S³ → S²` | `C² \ 0` | The sphere `S³` lies in `C²`. In `C³` the sphere would be `S⁵`. |
| 38 | "Its semi-axes have lengths `2A = r² − r⁻²`" | `2A = r² + r⁻²` | The next formula, `(2A)² − (2B)² = [(r²+r⁻²)² − (r²−r⁻²)²] = 4`, uses `2A = r² + r⁻²`. |
| 12 | "For example, `ik = iij = −j`" | `ik = i(ij) = i²j = −j` | Brackets or a dot are missing. This is a notation issue rather than a mathematical error. |

## B. Probable errors (check against the printed edition)

| Page | Printed | Comment |
|---|---|---|
| 11 | "Wessel had already done something here around 1820" | Wessel's work appeared in 1797–1799. This agrees with "seven years before Argand" on page 3 (Argand, 1806). Probably 1799 or 1797–1799. |
| 22 | "Funct. Anal. Appl., vol. 85, no. 1 (2001)" | The reference on page 34 (vol. 6, 1972) gives the journal volume for 2001 as 35. Probably `vol. 35`. |
| 9 | Caption of Fig. 7: "z = z · w = 1 — became" | Should be `zw = z = a + bi — became` (with `w = 1`), as in the text on page 9. |
| 14 | "Fig. 9. The axis of rotation and its direction cosines" | Number duplicates Fig. 9 on page 19. Should be Fig. 8: Figs. 1–7 are already used, and page 18 refers to Fig. 9 for the projective plane. |
| 33 | "In physics the values `a_n` are called 'levels'" | By the definition on page 33 the index runs over `m = 1, …, n`. Should be `a_m`. |

## C. Questionable (needs checking, not necessarily an error)

| Page | Printed | Comment |
|---|---|---|
| 39 | "Find the self-dual laws. (Newton already studied them!)" | By the formula `(A+3)(B+3)=4`, the self-dual exponents are `A = −1` and `A = −5`. Newton's law (`A = −2`) is dual to Hooke's law (`A = 1`), not to itself. This looks like a joke, but the link to Newton is unclear here. |

## D. Checked without remarks

- Quaternion multiplication, `Re(pq)` and `Im(pq)`, Hamilton's table (pp. 12–13).
- The identity `|zw| = |z||w|`, parallelogram area via determinant (pp. 6–8).
- De Moivre's formula, formulas for `cos 2φ`, `sin 3φ`, Chebyshev polynomials (p. 10).
- Trigonometric product formulas for complex numbers (p. 9).
- Rational parametrisation of the circle and Pythagorean triples (pp. 23, 25).
- Genus formula `g = (n−1)(n−2)/2`, genera of curves of degree 1 and 2 (p. 29).
- Orders `|A₃| = 24`, `|B₃| = 48`, `|H₃| = 120`, edges `6, 12, 30` and the formula `(n+1)(n+2)` (p. 21).
- `CP²/Conj ≈ S⁴`, dimension `HP⁴/Aut/Conj ≈ S¹³` (pp. 31–32).
- Joukowski function and Bolin's theorem (pp. 37–38).
- Duality formula `(A+3)(B+3)=4`, examples `α = (A+3)/2`, `β = 1/α` (p. 39).
