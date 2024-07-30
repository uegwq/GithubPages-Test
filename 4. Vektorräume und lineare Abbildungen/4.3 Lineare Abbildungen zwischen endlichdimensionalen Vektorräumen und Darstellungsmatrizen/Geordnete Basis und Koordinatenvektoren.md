TARGET DECK
Lineare Algebra I

4.3 Geordnete Basis und Koordinatenvektoren
--
## Definition
***
Es sei $\Bbb K$ ein Körper und $V$ ein endlichdimensionaler Vektorraum über dem Körper $\Bbb K$ und $n$ eine Natürlich Zahl $\in \Bbb N_0$.
1. Eine **geordnete Basis** ist ein $n$-Tupel $B=(b_1,...,b_n)$ mit $b_i\in V$, sodass $\{b_1,...,b_n\}$ eine Basis von $V$ ist.
2. Es sei $B=(b_1,...,b_n)$ eine geordnete Basis von $V$. Dann ist die lineare Abbildung, die einem Spaltenvektor die Linearkombination mit der Basis zuordnet:
   $\Bbb K^n \rightarrow V,$
   $\begin{pmatrix} x_1 \\ \vdots \\ x_n \end{pmatrix} \mapsto \sum_{j=1}^{n} x_j b_j$
   ein Isomorphismus von Vektorräumen. Die Umkehrabbildung bezeichnen wir mit
   $(\cdot)_B:V \rightarrow \Bbb K^n,$
   $v = \sum_{j=1}^{n} x_j b_j \mapsto (v)_B=\begin{pmatrix} x_1 \\ \vdots \\ x_n \end{pmatrix}$
   Der Spaltenvektor $(v)_B\in \Bbb K^n$ heißt der **Koordinatenvektor von v** bezüglich der geordneten Basis B
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt
<!--ID: 1709305047973-->
