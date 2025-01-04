# Cockpit
* 3 entrées GPIO (boutons)
* 3 sorties GPIO (DEL d'état)

#### Boutons

I = V/R

I = 3.3 / 10 000 = 0.33 mA

Utiliser un connecteur **JST ZH** (compact, facile à manipuler)

#### Del d'états

R = V / I = 3.3 - V<sub>D</sub> / 0.01

V<sub>D</sub> : Chute de tension directe (i.e. tension minimale requise pour que le courant commence à circuler à travers un composant électronique). Pour une DEL rouge ou verte, V<sub>D</sub> = 2 V.

I = 10 mA (Assez de courant pour faire briller une DEL)

R = 3.3 - 2 / 0.01 = 130 Ω

Utiliser un connecteur **JST GH** (plus compact, mais un peu compliqué à manipuler)
