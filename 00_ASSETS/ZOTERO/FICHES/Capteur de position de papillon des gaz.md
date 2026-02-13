Source : @MoteurM2P309

==**papillon des gazs**==
- ==situé dans le collecteur d'admission du moteur==
- ==dispositif qui régule la quantité d'air qui entre dans le moteur, en contrôlant le régime (plus le papillon est ouvert, plus il y a d'air qui rentre, plus le moteur monte en régime)==

==**autre nom** : APPS, *Capteur de position de commande d'air*==

==**emplacement**==
- ==axe du volet de papillon==
- ==fixé avec des boulons et des écrous sur cet ace==

**généralités**
- ==souvent doublé pour plus de précision (comme pédale accélérateur)==
	- ==piste montante==
	- ==piste descendante==
- ==composant électrique==
- ==mesure l'angle d'ouverture du papillon des gazs ([[40_SAVOIRS_TECHNIQUES/SAV — Capteur — Potentiomètre|SAV — Capteur — Potentiomètre]])==

==**utilité**==
- ==permettre de calculer la quantité de carburant à injecter dans le moteur==

**fonctionnement**
- ==le capteur mesure l'angle d'ouverture du papillon==
- ==alimenté par le système de charge du moteur==
- ==utilisé dans la gestion du fonctionnement moteur==
- ==[[00_ASSETS/IMAGES/ZOTERO/20260122_172338/MoteurM2P309-undefined-x35-y31.png|Schéma capteur papillon]]==

**composition**
1. ==potentiomètre==
	- ==résistance variable==
	- ==mesure la position angulaire du papillon==
2. ==levier de papillon==
	1. ==bras mécanique==
	2. ==connecte au papillon des gaz et tourne avec lui==
3. ==circuit imprimé==
	- ==carte électronique==
	- ==traite les signaux du potentiomètre et les envoie au modulede commande moteur==
4. ==connecteurs : prises électriques==
5. ==boïtier : boitier de protection (humidité, saleté==)

**contrôle du capteur**
1. le **voyant moteur** est allumé
	1. scanner oDB
	2. erreurs (P0120, P0121, P0122, P0123 ou P2135) = problème avec le capteur de position de papillon
2. Vérifier les connexion électriques
	1. serrées, propres, non oxydées
	2. sinon nettoyer avec nettoyant pour capteurs
3. Mesurer la résistance
	1. Mesure la résistance
	2. comparer aux valeurs de la RTA
4. Tension de sortie
	1. Voltmètre, DC
	2. Moteur tiède
	3. La tension doit varier de façon régulière et constante lorsque l'on appuie sur l'accélérateur
		1. piste montante : 1 à 5v
		2. piste descendante : 5 à 1v
	4. Si instable ou variation irrégulière : problème capteur

