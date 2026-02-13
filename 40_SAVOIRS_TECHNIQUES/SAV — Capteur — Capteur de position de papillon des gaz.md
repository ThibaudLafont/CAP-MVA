---
type: savoir
objet:
importance: haute
source: zotero
---
## Fonction
Mesure l'angle d'ouverture du [[40_SAVOIRS_TECHNIQUES/SAV — Admission — Papillon des gaz|SAV — Admission — Papillon des gaz]]
## Applications
- gestion du fonctionnement moteur en informant de l'ouverture du papillon
- calcul de la quantité de carburant à injecter dans le moteur
## Composition
1. [[40_SAVOIRS_TECHNIQUES/SAV — Capteur — Potentiomètre|Potentiomètre]]
	- résistance variable
	- mesure la position angulaire du papillon
2. Levier de papillon :  bras mécanique qui se connecte au papillon des gaz et tourne avec lui
3. Circuit imprimé : traite les signaux du potentiomètre et les envoie au modulede commande moteur
4. Connecteurs : prises électriques
5. Boîtier : boitier de protection (humidité, saleté)

[[00_ASSETS/IMAGES/ZOTERO/20260122_172338/MoteurM2P309-undefined-x35-y31.png|Schéma capteur papillon]]
## Principe de fonctionnement
- le capteur mesure l'angle d'ouverture du papillon
- alimenté par le calculateur (ref 5V)
- utilisé dans la gestion du fonctionnement moteur
- souvent doublé pour plus de précision (comme pédale accélérateur)
	- piste montante
	- piste descendante
## Signaux typiques
- Tension DC de 1 à 5V
## Valeurs caractéristiques
- placé sur l'axe du volet de papillon et fixé avec des boulons et des écrous sur cet axe
## À savoir par cœur
- **Aussi appelé** : APPS, *Capteur de position de commande d'air*
## Risques en cas de mal-fonction
- à-coups accélération
- ralenti instable
- mode dégradé
- voyant moteur
## Références
- @MoteurM2P309