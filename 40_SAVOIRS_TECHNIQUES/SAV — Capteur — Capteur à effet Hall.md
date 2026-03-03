---
type: savoir
objet:
importance: haute
source: zotero
---
## Fonction
Indiquer la vitesse d'un élément en mouvement par la génération d'un signal électrique carré
## Composition
- plaquette semi conductrice
- aimant permanent
- cible, une pièce métallique (roue percée, volant moteur)
- transistor Darlington
## Principe de fonctionnement
basé sur l'effet Hall : 
- un courant traverse la plaquette semi-conductrice
- un champ magnétique perpendiculaire à ce courant est appliqué sur la plaquette
- le champ magnétique est modifié lorsqu'un objet magnétique se déplace à proximité
- cette perturbation magnétique entraîne une modification de tension appelée *tension de Hall* 
	- proportionnelle à l’intensité du champ magnétique et à la tension dans la plaquette
	- permet de déterminer si un objet métallique se situe à proximité
## Valeurs caractéristiques
- **3 fils** 
	1. alimentation (calculateur) ; parfois il n'y. a que deux fils car l'alimentation est fournie par le circuit dans lequel le capteur est utilisé
	2. masse
	3. signal de retour vers calculateur
- **alimentation** : en 5V, parfois 12V
- **fréquence** : renseigne de la vitesse
- **tension** : 5 ou 12 volts
	- signal carré (pas tension alternative)
	- fixe : 0V et 5V (parfois 12V si alimenté en 12V)
		- **Cible face au capteur** : *état bas*, 0V 
		- **Cible pas face au capteur** : *état haut*, 5V
	- c'est la fréquence qui renseigne de la vitesse 
## À savoir par cœur
- nécessite une alimentation (de 5 ou 12v)
- génère un signal électrique carrée
- la fréquence indique la vitesse
- a progressivement remplacé les capteurs inductifs, ABS, capteur AAC, capteur de vitesse
- **Tension de hall** : tension produite par la modification du champ magnétique
## Références
- @SysElecM2P306
- @SysElecM2P305
- [[30_PROCÉDURES/PROC — Électricité — Capteur Hall|PROC — Électricité — Capteur Hall]]
- @LiaisonAuSolM2P319
