## 3.2 Gruppe

## Definition (3.2.1)

***

Ein Monoid $(G,*)$ in dem jedes Element invertierbar ist, nennt man **Gruppe**. Das heißt, eine **Gruppe** ist ein Paar $(G,*)$ aus einer [Menge] G und einer [Abbildung] *, sodass:

* $*: G \times G \rightarrow G$

* $\forall x,y,z\in G: (x*y)*z=x*(y*z)$

* $\exists e\in G: x*e=x=e*x$

* $\forall x\in G: \exists y\in G: x*y=e=y*x$

Eine kommutative Gruppe nennt man auch eine **abelsche Gruppe**.

## Lemma Einheitengruppe (3.2.2)

***

Es sei $(S,*)$ einfach ein random Monoid. Dann ist $(S^x,*)$ die Einheitengruppe von $(S,*)$. Man nimmt halt einfach nur alle invertierbaren Elemente von dem Monoid und dann ist es schon eine Gruppe yey.

## Bemerkung

***

In einer Gruppe gilt folgende Kürzungsregel:

$$\forall x,y,a\in G: (a*x=a*y \implies x=y)$$

## Siehe auch

***

* [Untergruppe](</3. Algebraische Strukturen/3.2 Gruppen/Untergruppe.md>)

* [Gruppenhomomorphismus](</3. Algebraische Strukturen/3.2 Gruppen/Gruppenhomomorphismus.md>)

* [Ring](</3. Algebraische Strukturen/3.3 Ringe und Körper/Ring.md>)

* [Vektorraum über K](</4. Vektorräume und lineare Abbildungen/4.1 Grundlegendes zu Vektorräumen und linearen Abbildungen/Vektorraum über K.md>)

* [Die alternierende Gruppe](</5. Endomorphismen/5.1 Das Signum einer Permutation/Die alternierende Gruppe.md>)

* [Permutation und symetrische Gruppe](</5. Endomorphismen/5.1 Das Signum einer Permutation/Permutation und symetrische Gruppe.md>)

<!--ID: 1709138893486-->

