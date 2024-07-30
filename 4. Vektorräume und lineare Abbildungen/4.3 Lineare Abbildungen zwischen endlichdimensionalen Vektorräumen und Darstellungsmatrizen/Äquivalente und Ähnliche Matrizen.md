## 4.3 Äquivalente und Ähnliche Matrizen

## Definition

***

Zwei Matrizen $A,B\in \Bbb K^{m\times n}$ heißen **Äquivalent**, wenn es zwei Invertierbare Matrizen $S \in GL(m,\Bbb K)$ und $T\in GL(n,\Bbb K)$ gibt, sodass $SAT = B$.

Zwei Matrizen $A,B\in \Bbb K^{n\times n}$ heißen **Ähnlich**, wenn es eine Invertierbare Matrizen $S \in GL(n,\Bbb K)$ gibt, sodass $SAS^{-1} = B$.

Das bedeutet also, dass zwei Matrizen Ähnlich sind, wenn die denselben Endomorphismus nur bezüglich unterschiedlichen Basen beschreiben.

## Korollar 4.3.19

***

Zwei Martizen $A,B\in \Bbb K^{n\times n}$ sind genau dann äquivalent, wenn sie den gleichen Rang haben.

## Ähnlichkeitsinvarianten (5.5.7)

***

Es sei $\Bbb K$ ein Körper und $A,B\in\Bbb K^{n\times n}$. Wenn $A$ und $B$ ähnlich sind, so gilt

1. $rg(A)=rg(B)$

2. $det(A)=det(B)$

3. $tr(A)=tr(B)$

Dies ist aber keine Äquivalente Beziehung! Wenn die drei Eigenschaften erfüllt sind heißt dies nicht, dass zwei Matrizen Ähnlich sind!

4. Zudem haben zwei Ähnliche Matrizen dieselben Eigenwerte.

5. Zudem haben zwei Ähnliche Matrizen dasselbe charakteristische Polynom.

## Siehe auch

***

* [Spur einer Matrix](</5. Endomorphismen/5.5 Endomorphismen und Ähnlichkeit/Spur einer Matrix.md>)

<!--ID: 1709384076077-->

