## 5.4 Polynomalgebra

## Definition

***

Eine $\Bbb K$-Algebra $A$ wird als Polynomalgebra mit einem Element $X\in A$ bezeichnet, wenn die Potenzen $\{X^k\vert k\in \Bbb N_0\}$ paarweise verschieden sind und eine Basis für $A$ bilden. Man bezeichnet dies auch als $A = \Bbb K[X]$.

Ein Element aus einer Polynomalgebra wird Polynom genannt. Es lässt sich also eindeutig als linearkombination von Potenzen von $X$ schreiben.

Alles hier funktioniert aber auch, wenn man $\Bbb K$ durch einen Kommutativen Ring ersetzt :)

## Grad eines Polynoms

***

Das Grad eines Polynoms $p\in \Bbb K[X]$ ist $deg(p)=max\{k\in \Bbb N_0 \vert a_k\not=0\}$. Der Grad des Nullpolynoms ist definiert als $deg(0) := -\infty$.

Für ihn gilt:

1. $deg(p+q)\le max\{deg(p),deg(q)\}$

2. Falls $p,q \not= 0$, dann gilt $deg(pq) = deg(p)+deg(q)$

## Existenz und Eindeutigkeit der Polynomalgebra

***

Wenn $\Bbb K$ ein Körper ist, so existiert eine Polynomalgebra $A=\Bbb K[X]$ mit einer Unbestimmten $X\in A$ und

Die Polynomalgebra ist eindeutig, bis auf eindeutige Isomorphismen. Das heißt wenn $A$ und $B$ beides Polynomalgebren über $\Bbb K$ sind, dann gibt es einen Isomorphismus zwischen ihnen. Also $A=\Bbb K[X], B=\Bbb K[Y]$. dann gibt es einen Isomorphismus zwischen $X$ und $Y$.

## Nullstellen von Polynomen

***

Es sei $\Bbb K$ ein Körper, $p\in \Bbb K[X]$ und $\lambda \in \Bbb K$. Dann sind äquivalent:

1. $p(\lambda)=0$

2. $\exists q\in \Bbb K[X]: p=(X-\lambda)q$.

Es gilt zudem, dass $p$ höchstens $deg(p)$ verschiedene Nullstellen hat.

## Siehe auch

***

* [Abbildungen von Polynomen](</5. Endomorphismen/5.4 Algebren und Polynome/Abbildungen von Polynomen.md>)

* [Das charakteristische Polynom einer Matrix](</5. Endomorphismen/5.6 Eigenwerte und Eigenvektoren/Das charakteristische Polynom einer Matrix.md>)

<!--ID: 1711978844758-->

