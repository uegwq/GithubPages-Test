TARGET DECK
Lineare Algebra I

5.6 Berechnen und Finden von Eigen-Wert-Vektor-Raum
--
## $I$. Gegeben einen Eigenvektor, wie viele Eigenwerte gehören dazu und wie findet man diese?
***
Zu einem Eigenvektor gibt es genau einen Eigenwert! Den Eigenvektor setzt du in die Abbildung ein und schaust um wie viel er gestreckt wird.
## $II$. Gegeben einen Eigenwert, wie viele Eigenvektoren gehören dazu und wie findet man diese?
***
Folgende Überlegung:
$Ax = \lambda x$
$Ax - \lambda x = 0$
$(A - \lambda)x = 0$
$x = ker(\varphi - \lambda id)$
## $III.$ Wie finde ich alle Eigenwerte ohne überhaupt was zu wissen? Wie viele Eigenwerte kann $\varphi$ haben?
***
Mit den Nullstellen des charakteristischen Polynoms. Es gilt nämlich:
$\lambda \text{ ist ein Eigenvert} \iff \exists v\not=0:\varphi(v)=\lambda v$
$\iff \exists v\not= 0: v\in ker(\lambda id_V-\varphi)$
$\iff ker(\lambda - \varphi)\not= \{0\}$
$\iff \lambda id_V-\varphi \text{ ist nicht injektiv}$
$\iff \lambda \Bbb 1_V-A \text{ ist nicht invertierbar}$
$\iff det(\lambda \Bbb 1 - A)=0$
$\iff p_A(\lambda)=0$
## $IV$. Was ist der Sinn von dem ganzen hier?
***
![[Pasted image 20240305140900.png]]
<!--ID: 1711978844712-->


## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt