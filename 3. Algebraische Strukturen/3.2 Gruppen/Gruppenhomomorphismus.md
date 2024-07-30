TARGET DECK
Lineare Algebra I

3.2 Gruppenhomomorphismus
--
## Definition
***
Seien zwei [Gruppen] $(G,*_G)$ und $(H,*_H)$ gegeben. Eine [Abbildung]
$$\varphi : G \rightarrow H$$
Ist ein **Homomorphismus von Gruppen / Gruppenhomomorphimus**, wenn
$$\forall x,y\in G:\varphi (x*_Gy)= \varphi(x)*_H\varphi(y)$$
## Bermerkung
***
Daraus folgt dann automatisch, dass
$$\varphi(e_G)=e_H$$
sowie
$$\forall x\in G: \varphi(x^{-1})=(\varphi(x)^{-1})$$
## Iso- endo- und Automorphismis
***
Ein *Gruppenhomorphismus* ist ein **Gruppenisomorphismus**, wenn er bijektiv ist.
Ein *Gruppenhomomorphismus* ist ein **Gruppenendomorphismus**, wenn die Start- und Zielmenge identisch sind.
Ein *Gruppenhomomorphismus* ist ein **Gruppautomorphismus**, wenn er ein bijektiver *Gruppenendomorphismus* ist.
Zwei Gruppen sind isomorph, wenn es einen Isomorphismus zwischen ihnen gibt.
## Lemma bezüglich homomorphismen und Untergruppen
***
(a) siehe Bemerkung
(b) Es sei $U \subseteq G$ eine Untergruppe von $(G,*)$. Dann ist $\varphi(U)$ eine Untergruppe von H und $Bild(\varphi)=\varphi(G)$ eine Untergruppe von H.
(c) Es sei $W \subseteq H$ eine Untergruppe von $(H,*)$. Dann ist $\varphi ^{-1}(W)$ eine Untergruppe von G. Insbesondere ist der Kern $ker(\varphi) := \varphi ^{-1}({e_H})$ eine Untergruppe von G.
## Siehe auch
***
* [[Injektive Gruppenhomomorphismen]]
<!--ID: 1709139294269-->
