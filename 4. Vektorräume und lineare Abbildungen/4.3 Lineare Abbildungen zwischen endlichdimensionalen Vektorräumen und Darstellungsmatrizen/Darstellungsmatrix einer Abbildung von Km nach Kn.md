TARGET DECK
Lineare Algebra I

4.3 Darstellungsmatrix einer Abbildung von $\Bbb K^n$ nach $\Bbb K^m$
--
## Satz (4.3.1)
***
Man hat gesehen, dass man eine Abbildung von $K^n$ nach $K^m$ auch als Linksmultiplikation einer Matrix darstellen kann. Es gilt aber sogar:
1. für jede Matrix $A \in \Bbb K^{m \times n}$ ist die Abbildung $$\varphi_A:\Bbb K^n \rightarrow \Bbb K^m, x \mapsto Ax$$ $\Bbb K$-linear, also $\varphi \in Hom(\Bbb K^n, \Bbb K^m)$.
>**IN DEN SPALTEN DER MATRIX A STEHEN DIE BILDER DER STANDARTBASISVEKTOREN OMG**
2. Zu jeder linearen Abbildung $\varphi:\Bbb K^n \rightarrow \Bbb K^m$ gibt es eine Matrix $A \in \Bbb K^{m \times n}$, sodass "$Ax = \varphi(x)$". Diese Matrix ist eindeutig und wird auch **Darstellungsmatrix** genannt. Man bezeichnet sie mit $M_{E,E}(\varphi)$.
3. Gegeben sind zwei Matrizen $A\in \Bbb{K}^{m\times n}$ sowie $B \in \Bbb{K}^{n\times p}$. Das verketten der linearen darstellungsabbilden Abbildungen $\varphi_A$ und $\varphi_B$ entspricht dem Multiplizieren der Matrizen und umgekehrt.
4. Die Einheitsmatrix entspricht der Identitätsabbildung
5. Es gilt, dass eine Matrix $A \in \Bbb K^{m\times n}$ ist isomorph zu ihrer lineareren Abbildung $\varphi_A$.
6. Eine lineare Abbildung $\varphi = \varphi_A: \Bbb K^n \rightarrow \Bbb K^m$ ist genau dann bijektiv (also ein VR Isomorphismus), wenn $m=n$ und wenn die Darstellungsmatrix $A=M_{E,E}(\varphi)$ multiplikativ invertierbar ist.
## Siehe auch
***
* [[Invertierbare Matrizen]]
* [[Basiswechselmatrix]]
* [[Darstellungsmatrix einer linearen Abbildung]]
<!--ID: 1709305047984-->
