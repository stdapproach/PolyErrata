# V. I. Arnold, "Geometry of Complex Numbers, Quaternions and Spinors": errors and typos

This is part of an (expectedly) long journey to revisit the mathematics in scientific books with the support of AI. The results of this work are published in the open repository PolyErrata: https://github.com/stdapproach/PolyErrata

## Intro

**Book.** Vladimir Igorevich Arnold, *Geometry of Complex Numbers, Quaternions and Spinors* (Геометрия комплексных чисел, кватернионов и спинов). Moscow: Publishing House of the Moscow Center for Continuous Mathematical Education (MCCME), 2002. Booklet, 40 pages, print run 1500 copies, signed for printing on 5 March 2002. The text is a transcript of a lecture Arnold gave to schoolchildren on 17 November 2002 (per the annotation on p. 2; the annotation gives the year as 2002).

**Identifiers**
- ISBN 5-94057-025-9
- UDC 514/515, BBC 22.1, author mark А84
- Editor V. V. Trushkov; technical editor V. M. Gurovits; recording and transcription of the lecture by R. I. Bogdanov, M. R. Bogdanov

**Bibliography and references.**
- A scientific article on the history of negative and complex numbers (arXiv:2001.10400) lists the booklet in its references as: Arnold V. I., *Geometry of Complex Numbers, Quaternions and Spinors*. Moscow: MCCME, 2002. 40 pp. This is the most explicit independent bibliographic reference I was able to find.
- A Wikipedia article about the book was not found. Searches in Russian and English sources returned only catalogue entries and bibliographic references.

**Where to obtain it.**
- The book is not in the public domain: it was published in 2002, Arnold died in 2010, and copyright is in force. I do not link to free copies on third-party sites, so as not to distribute illegal files.
- Legal options: bookshops (for example, Chitai-Gorod, though the book is currently sold out), the MCCME publishing house (via its website or catalogue; address not checked), and major libraries (Russian State Library, Russian National Library, Moscow State University and MIPT libraries, which can lend or scan the edition through interlibrary loan).

**What was checked:** all 40 pages. Formulas were reviewed by hand, not symbolically.

## A. Mathematical errors (confirmed)

| Page | As printed | What it should be, and why |
|---|---|---|
| 18 | $w z^{-1} = w\bar{z} = \overline{zw}$ | A minus sign is missing: for a purely imaginary $w$, $w\bar{z} = -\overline{zw}$ holds (since $\bar{w} = -w$). Counterexample: $z = 1,\ w = i$ gives $w\bar{z} = i$, while $\overline{zw} = -i$. |
| 38 | "Its semi-axes have lengths $2A = r^2 - r^{-2}$" | The next formula, $(2A)^2 - (2B)^2 = \left[(r^2+r^{-2})^2 - (r^2-r^{-2})^2\right] = 4$, uses $2A = r^2 + r^{-2}$. It should be $2A = r^2 + r^{-2}$. |
| 9 | Caption of Fig. 7: "$z = z \cdot w = 1$ — becomes" | Should be $zw = z = a + bi$ — becomes (with $w = 1$), as in the text on p. 9. |
| 14 | "Fig. 9. The unit vector of the rotation axis and its direction cosines" | The number duplicates Fig. 9 on p. 19. It should be Fig. 8: Figs. 1–7 are already used, and p. 18 refers to Fig. 9 for the projective plane. |

## B. Probable errors (to be checked against the printed edition)

| Page | As printed | Comment |
|---|---|---|
| 13 | Vector product: $[v_1,v_2]=\begin{vmatrix}b_1&b_2\\c_1&c_2\end{vmatrix}i+\begin{vmatrix}c_1&c_2\\a_1&a_2\end{vmatrix}j+\begin{vmatrix}a_1&a_2\\b_1&b_2\end{vmatrix}k$ | The printed formula is correct for a vector with coordinates $(a,b,c)$: the same determinant expression appears in Wilson, *Vector Analysis* (1901), article 35, which is in the public domain. But Arnold defines $v = b\,i + c\,j + d\,k$, so his coordinates are $(b,c,d)$, and in his notation the formula should read $[v_1,v_2]=\begin{vmatrix}c_1&c_2\\d_1&d_2\end{vmatrix}i+\begin{vmatrix}d_1&d_2\\b_1&b_2\end{vmatrix}j+\begin{vmatrix}b_1&b_2\\c_1&c_2\end{vmatrix}k$. This is an inconsistency of notation, not an error in the identity itself. |
| 11 | "Something here was already done by Wessel, around 1820" | Wessel's work appeared in 1797–1799. This agrees with "seven years before Argand" on p. 3 (Argand, 1806). The year should probably be 1799, or 1797–1799. |
| 22 | "Funkts. Analiz i ego prilozh., vol. $85$, no. $1$ ($2001$)" | The reference on p. $34$ (vol. $6$, $1972$) puts the 2001 volume at $35$. Probably vol. $35$. |
| 33 | "In physics, the values $a_n$ are called 'levels'" | By the definition on p. 33 the index is $m = 1, \ldots, n$. Should be $a_m$. |

## C. Requires re-verification

| Page | As printed | What it should be, and why |
|---|---|---|
| 35 | "$S^3 \subset \mathbb{C}^3 \setminus 0$" for the Hopf fibration $S^3 \to S^2$ ($\mathbb{C}P^1$) | Should be $\mathbb{C}^2 \setminus 0$. The sphere $S^3$ lies in $\mathbb{C}^2$; in $\mathbb{C}^3$ the sphere would be $S^5$. |
| 21 | "Embedding $\mathbb{R}P^3$ into the complex projective plane $\mathbb{C}P^2$" | The intended object is the real projective plane $\mathbb{R}P^2$ (the tetrahedron, 4 points, see the preceding paragraph). Should be $\mathbb{R}P^2$. |

## D. Checked, no issues found

- Quaternion multiplication, $\operatorname{Re}(pq)$ and $\operatorname{Im}(pq)$, Hamilton's table (pp. 12–13).
- The identity $|zw| = |z||w|$, and the area of a parallelogram via a determinant (pp. 6–8).
- De Moivre's formula, the formulas for $\cos 2\varphi$, $\sin 3\varphi$, and the Chebyshev polynomials (p. 10).
- Trigonometric formulas for multiplying complex numbers (p. 9).
- Rational parametrization of the circle and Pythagorean triples (pp. 23, 25).
- The genus formula $g = \frac{(n-1)(n-2)}{2}$, and the genera of curves of degree 1 and 2 (p. 29).
- The numbers $|A_3| = 24$, $|B_3| = 48$, $|H_3| = 120$, the edge counts $6, 12, 30$, and the formula $(n+1)(n+2)$ (p. 21).
- The formulas $\mathbb{C}P^2/\mathrm{Conj} \approx S^4$ and $\mathbb{H}P^4/\mathrm{Aut}/\mathrm{Conj} \approx S^{13}$ (pp. 31–32).
- The Zhukovsky function and Bolin's theorem (pp. 37–38).
- The duality formula $(A+3)(B+3)=4$, and the examples $\alpha = \frac{A+3}{2}$, $\beta = \frac{1}{\alpha}$ (p. 39).
