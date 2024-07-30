TARGET DECK
Lineare Algebra I

5.3 Die Determinante einer Matrix
--
## Definition
***
Die Determinante einer Matrix ist die Summe des Produktes aller Permutationen mit dem Vorzeichen als Signum der Permutation. Aufgeschrieben lautet sie dann:
$$det(A):=\sum_{\sigma\in\mathscr{S}(n)} sgn(\sigma)\cdot a_{\sigma(1),1}\dots a_{\sigma(n),n}$$
Diese Formel nennt man auch Leibnitz-Formel
## Bemerkungen zur Determinante
***
1. es gibt viele ander Definitionen um eine Determinante zu berechnen, die sind aber alle gleich zur Leibnitz Formel eigentlich lool
2. Diese Definition macht eigentlich garnicht klar warum die Determinante voll das crazy ist
3. Die Leibnitz formel ist nicht gerade toll um die Determinante sehr großer Matrizen zu berechnen weil man $n!$ viele Summanden hat ohje.
4. Die Determinante ist alterierend in den Spalten $\iff$ Zeilen!!! Wenn eine Zeile/Spalte eine Nullspalte/Zeile ist, so ist die Determinante null. Dies bedeutet, dass sie auch **multilinear** ist!!
5. Die Determinante ist multiplikativ!! Das heißt $det(AB)=det(A)det(B)$. ($\implies$, dass die Determinante ein Gruppenhomomorphismus unter der Matrixmultiplikation ist.)
## Rechenregeln
***
1. Die Determinante ändert sich nicht beim Transponieren.
   $det(A)=det(A^T)$.
2. ist eine Matrix $A$ in eine obere/untere Dreiecksmatrix oder eine Diagonalmatrix, so ist $det(A)=a_{1,1}\dots\cdot a_{n,n}$.
## Siehe auch
***
* [[Adjunkte]]
* [[Entwicklungssatz von Laplace]]
* [[Kriterium für die Invertierbarkeit]]
<!--ID: 1711978844816-->
