TARGET DECK
Lineare Algebra I

3.2 Injektive Gruppenhomomorphismen
--
## Definition
***
Ein Gruppenhomomorphismus ist genau dann injektiv, wenn sein Kern nur das neutrale Element enthält.
## Beweis
***
Seien $(G,*_H)$ und $(H,*_H)$ zwei Beliebige Gruppen mit $\varphi: G \rightarrow H$ ein Gruppenhomomorphismus. 
1. Richtung: Aus injektivität folgt $ker(\varphi)= \{e_G\}$.
Da $\varphi$ ein Gruppenhomomorphismus ist gilt $\varphi(e_G)=e_H$. Wenn wir jetzt behaupten ein random $a\in G$ sei im Kern, dann müsste ja gelten $\varphi(a)=e_H=\varphi(e_G)$. Tya, da $\varphi$ aber injektiv ist, folgt daraus, dass $a=e_G$. Somit ist im Kern nur $e_G$.
2. Richtung: Aus $ker(\varphi)= \{e_G\}$ folg injektivität.
Seien $a,b \in G$ derart, dass $\varphi(a)=\varphi(b)$ gilt. Daraus muss man jetzt nur noch folgern, dass $a=b$.
Also:
$$\varphi(a*_Gb^{-1}) = \varphi(a)*_H\varphi(b^{-1})=\varphi(b)*_H\varphi(b^{-1})=\varphi(b*_Gb^{-1}) = \varphi(e_G) = e_H$$
Da der Kern nur aus $e_G$ besteht und jetzt ja auch irgendwie $a*_Gb^{-1}$ im Kern ist muss also zwingenderweise gelten, dass
$a*_Gb^{-1}=e_G$. Und da haben wirs fast, wenn wir jetzt b rechts ranmultiplizieren erhalten wir
$$a = b$$
$\square$
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt
<!--ID: 1709141180850-->
