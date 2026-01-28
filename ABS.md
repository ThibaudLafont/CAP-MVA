L'ABS sert à éviter le blocage des roues en cas de freinage violent
- ==module la pression de freinage pour conserver une adhérence optimale : cycle[augmente, stabilise, diminue]==
- ==**système additionnel** = tant que les roues sont stables, il reste passif==
- détail fonctionnement en p. 9-10

Les roues qui se bloquent présentent une adhérence moindre
- augmentation de la distance de freinage
- dirigibilité compromise
- les pneus s'usent anormalement

**coefficient d'adhérence d'une roue**
- permet à l'ABS de calculer le glissement d'une roue
- calculé à partir du capteur inductif et de la roue phonique

en cas de dysfonctionnement du système
- **lampe témoin** 
- le freinage traditionnel est autorisé

**Composants**
- un capteur et une roue phonique par roue
- calculateur électronique
- groupe hydraulique
	- 4x électrovannes d'admission
	- 4x électrovannes d'échappement
- Voyant de contrôle 
- Prise diagnostic

**Roue phonique et capteur**
Un champ magnétique entoure le bobinage, il est déformée à chaque passage d'une dent de la roue phonique -> création d'un courant alternatif (tension, fréquence) qui permet au calculateur de déterminer la vitesse de rotation de la roue (tension nulle = roue bloquée)

**Bloc hydraulique
![[00_ASSETS/IMAGES/ZOTERO/20260122_172336/ConfortSecuM1P303-5-x288-y546.png|200]]**
- huit électrovannes (4x admin *(1)*, 4x échappement *(2)*)
- Deux **accumulateurs** *(3)* (un par diagonale) : ==évitent les coups de bélier, diminuent les temps de réponse==
- Deux **amortisseurs** *(4)* (un par diagonale) : ==atténuent les pulsations à la pédale==
- Une pompe de refoulement à deux circuits *(5)* entraînée par le moteur électrique *(6)*

**Électrovannes**, dites *tout ou rien*
- soit ouvertes, soit fermées
- admission 
	- Maître-Cylindre > Étrier
	- ouverte par défaut
- échappement
	- Pompe de refoulement > Étrier
	- fermée par défaut

**Calculateur**
Sur le bloc hydraulique
traite les signaux des capteurs de roue 
intervient sur les électrovannes pour contrôler la pression de freinage. 
