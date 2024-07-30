## 5.2 Linear in der j-ten Komponente, multilinear und alternierend

## Definition

***

Hier sei $V^n$ das $n$-Fache karthesische Produkt von V.

1. Eine Abbildung $\omega: V^n \rightarrow W$ heißt **linear in der j-ten komponente**, falls gilt, dass

   $\omega(v_1,\dots,v_{j-1},\mathbf{v+v'},v_{j+1},\dots,v_n) =  \omega(v_1,\dots,v_{j-1},\mathbf{v},v_{j+1},\dots,v_n) + \omega(v_1,\dots,v_{j-1},\mathbf{v'},v_{j+1},\dots,v_n)$

2. Eine Abbildung $\omega: V^n\rightarrow W$ heiße **Multilinear**, falls sie in jeder einzelnen Komponente linear ist. Für $n=2$ nennt man dies auch *bilinear*.

3. Eine Abbildung $\omega: V^n\rightarrow W$ heißt **alternierend,** falls die *multilinear* ist und jedes Tupel auf null abgebildet wird, sobald mindestens zwei der Komponenten gleich sind.

## Rechenregeln für alternierende Abbildungen

***

$W,V$ sind Vektorräume über einem Körper $\Bbb K$ und $\omega: V^n\rightarrow W$ sei eine alternierende Abbildung-

1. Wenn man das $\micro$-fache der $i$-ten Komponente auf die $j$-te komponente addiert ($i \not = j$), so ändert sich der Wert unter $\omega$ nicht. (macht sinn wenn man es ausseinanderzieht und sieht, dass die i-te kompoente dann doppelt ist)

2. Wenn man den $i$-ten und $j$-ten Eintrag vertauscht, so wird der Wert mit $(-1)$ multipliziert.

3. Es ist möglich aus jeder Komponente einen Koeffizienten $\lambda \in \Bbb K$ herauszuziehen.

## Transformationsformel für alternierende Abbildungen

***

Ja also uhm hä. Diese Formel sieht sehr unwichtig aus.

## Folgerung

***

$W,V$ sind Vektorräume über einem Körper $\Bbb K$ und $\omega: V^n\rightarrow W$ sei eine alternierende Abbildung.

Wenn $\omega(v_1,\dots,v_2) \not=0$, so sind $\{v_1,\dots,v_n\}$ paarweise verschieden und linear unabhängig.

## Siehe auch

***

* [Die alternierende Gruppe](</5. Endomorphismen/5.1 Das Signum einer Permutation/Die alternierende Gruppe.md>)

<!--ID: 1709389609386-->

