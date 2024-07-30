TARGET DECK
Lineare Algebra I

4.5 Quotientenvektorraum
--
## Definition
***
Es sei $V$ ein $\Bbb K$-Vektorraum und $U\subseteq V$ ein Untervektorraum.
1. Die Relation $\equiv_U$ auf $V$ ist so definiert, dass zwei Elemente $v \equiv_U w \iff v-w\in U$. Dies ist eine Äquivalenzenrelation-
2. Auf der Quotientenmenge $V\setminus U := V \setminus_{\equiv_U}$ gibt es genau eine $\Bbb K$-Vektorraumstruktur, sodass die auf jeden fall heftig surjektive Quotientenabbildung$$q: V \rightarrow V\setminus U, v\mapsto[v]_U := [v]_{\equiv_U}$$
   zu einer K-Linearen Abbildung wird. Es gelten die super praktischen und coolen Rechenregeln von Restklassenkörpern auch hier :). Bei Multiplikation aber aufpassen dass es nur skalar ist!
3. Es gilt $ker(q)=U$.
## Bemerkung
***
Stell dir deinen Punkt $p$ vor. $[p]_U$ sind dann alle Vektoren $x$ die Parallel zu $U$ sind mit dem Aufpunkt $p$. Also sind in $V \setminus U$ alle Untervektorräume die Parallel zu $U$ sind.
## Siehe auch
***
* [[Quotientenvektorraum]]
* [[Satz zu Quotienten und Komplementen]]
* [[Homomorphiesatz]]
<!--ID: 1709384076020-->
