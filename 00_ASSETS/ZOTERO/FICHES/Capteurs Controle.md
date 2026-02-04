Source : @SysElecM2P306

**fonctionnement général** : envoient des informations au calculateur

### Capteur de vitesse de rotation inductif
*role* : donner l'information de vitesse d'un élément soumis à un mouvement de rotation

*applications* : déjà renseigné

*stylé à savoir* : apparu avec les premiers allumages électroniques

==*Composition*==
- ==un aimant== 
- ==entouré d'un bobinage en cuivre== 
- ==un noyau en fer doux==
==[[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-undefined-x54-y99.png|Capteur inductif]]==

==*fonctionnement*==
==L'aimant génère un champ magnétique, déformé par le passage des dents du volant moteur (ou de la roue phonique)==
==La déformation est due à la variation de l'**entrefer** (la distance entre l'extrémité du capteur et les dents du volant moteur), du fait de la présence ou de l'absence de dent devant le capteur==

==*valeurs*==
==**entrefer volant moteur** 1 à 10mm==
==**résistance bobine** : 300 à 900 ohm==

#### ==Contrôle==
==**A. Contrôle visuel** : détérioration, encrassement, connectique==
==**B. Entrefer** : vérifier qu'il est de 1mm (non réglable)==
==**C. Résistance de la bobine** : débrancher le capteur et vérifier sa résistance, sa valeur est à comparer avec les données constructeur (300 à 900 ohm)==
==**D. Vérification du signal** : si la résistance est correcte==
1. ==Connecter un oscilloscope==
2. ==Démarrer le véhicule==
3. ==Le signal doit être [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-2-x85-y548.png|alternatif et sinusoïdal]]== 
==**E. Contrôle à la valise de diagnostic** : possible de lire la vitesse de rotation donnée par le capteur==


### Capteur de vitesse de rotation à effet Hall
==*role* : donner l'information de vitesse d'un élément soumis à un mouvement de rotation==

==*applications* : a progressivement remplacé les capteurs inductifs, ABS, capteur AAC, capteur de vitesse==

==*composition*==
- ==plaquette semi conductrice==
- ==aimant permanent==
- ==cible, une pièce métallique (roue percée, volant moteur)==

==*fonctionnement*==
==basé sur l'effet Hall :== 
- ==l'aimant engendre un champ magnétique dans lequel baigne le capteur==
- ==un courant électrique est fourni par le calculateur==
- ==il traverse la plaquette semi-conductrice==
- ==le signal varie lorsque la cible est face au capteur==

==Le signal est amplifié et numérique, c'est un signal carré dont la fréquence est proportionnelle à la fréquence de détection de la cible==
1. ==**Cible face au capteur** : *état bas*, 0V==
2. ==**Cible pas face au capteur** : *état haut*, 5V==

==*valeurs*==
==**alimentation** : 5V==
==**sortie** : 0V, la cible est face au capteur ; 5V, la cible n'est pas face au capteur==

==*à savoir par coeur*==
==**besoin d'une alimentation pour fonctionner**==
==**3 fils** : alimentation, masse, signal== 

#### ==Contrôle==
==le contrôle du signal au multimètre n'est pas possible (*étage électronique d'amplification du signal*)==

==**A. Contrôle de l'alimentation** :== 
- ==Voltmètre : alimentation et masse==
- ==Mettre le contact==
- ==Valeur attendue : 5V==
==**B. Contrôle du signal**==
- ==Oscilloscope : sortie du capteur==
- ==Démarrer le moteur==
- ==Valeur attendue : [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-3-x54-y149.png|signal carré]]==
==**C. Constrôle à la valise** : possible de lire la vitesse de rotation donnée par le capteur==

### Capteur de pression piézorésistif
==*rôle* : donner l'information de pression d'un fluide==

==*applications* : collecteur d'admission, pression de suralimentation, pression rampe commune, pression d'huile, pression fluide réfrigérant clim==

==*composition*==
- ==membrane de type piézoresistif==

==*fonctionnement*== 
- ==une tension alimente le capteur==
- ==la pression déforme la membrane==
- ==la déformation fait varier la résistance==
- ==la tension de sortie est modifiée (0,5 à 5V)==

==*valeurs*==
==**tension alimentation** : 5V==
==**tension de sortie** : 0,5 à 5V==
==**trois fils** : alimentation, masse, signal== 

#### ==Contrôle==
==**A. Au voltmètre**==
- ==Voltmètre : sortie et masse==
- ==Faire varier la pression== 
	- ==accélérer/décélérer==  
	- ==connecter une pompe à dépression directement sur le capteur==
- ==Valeur attendue : entre 0,5 et 4,5V==
==**B. À la valise de diagnostic** : possible de lire la pression donnée par le capteur==


### Capteur de température à résistance variable
==*rôle* : informer de la température d'un fluide==

==*applications* : air d'admission, eau moteur, air habitacle==

==*composition* : thermistance de type **CTN** (Coefficient de Température Négatif), c'est à dire que plus la température augmente et plus la résistance diminue==
- ==oxydes métalliques frittés==

==*fonctionnement* : les oxydes ont la propriété de changer de résistance sous l'effet de la température ; fait varier la tension de sortie==

#### ==Contrôle==
==**A. Au ohmmètre**==
- ==Ohmmètre : bornes du capteur==
- ==Démarrer le moteur==
- ==Vérifier fréquemment==
	- ==**température de l'eau** : capteur infrarouge, au niveau de la tuyauterie d'eau qui va vers le radiateur==
	- ==**la résistance du capteur** : afin de la comparer aux données constructeur==
==*Il est aussi possible de réaliser ce test dans une casserole d'eau que l'on fait chauffer*==
==**B. Voltmètre**==
- ==Voltmètre : bornes du capteur==
- ==Capteur branché==
- ==Démarrer le véhicule== 
- ==La tension doit augmenter durant le cycle de chauffe du moteur (0,5 à 4,5V)==
==**B. À la valise de diagnostic** : possible de lire la température donnée par le capteur==



### ==Potentiomètres==
==*rôle* convertir une donnée angulaire en tension==

==*applications* : position papillon des gaz, pédale d'accélérateur, niveau caisse, position vanne EGR==

==*fonctionnement* : une résistance variable== 
- ==alimenté en 5V (trois fils)==
- ==le curseur se déplace sur une piste dont la résistance augmente proportionnellement à sa valeur angulaire==
- ==la résistance, en variant, fait varier la tension de sortie (0 à 5V)==

==*valeurs*==
==tension de sortie : 0 à 5V==

==*à savoir*==
==pour des raisons de sécurité : deux potentiomètres dans les pédales d'accélération, la variation de la résistance est obtenue par un système à double piste (les [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-5-x291-y125.png|deux courbes]] de tension se croisent)== 

#### ==Contrôle==
==**A. Contrôle de l'alimentation**==
- ==Voltmètre : alimentation et masse==
- ==Mettre le contact==
- ==Valeur attendue : 5V==
==**B. Contrôle du signal**==
- ==Voltmètre : sortie et masse==
- ==Faire varier la position du curseur== 
- ==Comparer avec les données constructeur== 
==**B. À la valise de diagnostic** : possible de lire la position donnée par le capteur (souvent en %)==


### Débitmètre 
==*rôle* informer de la quantité d'air entrant dans le moteur==

==*application* quantité d'air frais d'admission (gestion EGR) ;== 

==*composition*==
- ==élément chauffant : fil ou film== 
- ==thermistance (capteur de température d'air intégré au débitmètre)==
- ==5 fils :== 
	1. ==12V pour chauffer==
	2. ==5V d'alimentation du capteur==
	3. ==Masse==
	4. ==Signal débit d'air (0 à 5V)==
	5. ==Thermistance (signal de température d'air)==

==*fonctionnement*==
- ==l'élément chauffant est chauffé==
- ==la quantité d'air le refroidit plus ou moins==
- ==plus le fil est refroidi, plus il demande d'énergie pour se maintenir à température==
- ==c'est la mesure de la consommation du capteur qui permet de déterminer le débit de l'air==

==*technologies*==
- ==à fil chaud :  fil très fin en platine (120C°)==
- ==à film chaud : film fin, plus robuste, plus précis (160°C)==

==*Valeurs*==
==alimentation de chauffage : 12V==
==alimentation de capteur : 5V==
==sortie : 0 à 5V==

#### ==Contrôle==
==**A. De l'alimentation du capteur**==
- ==Voltmètre : alimentation du capteur et masse==
- ==Mettre le contact==
- ==Valeur attendue : 5V==
==**B. De l'alimentation de l'alimentation de chauffage**==
- ==Voltmètre : alimentation de chauffage et masse==
- ==Mettre le contact==
- ==Valeur attendue : 12V==
==**C. Du signal du capteur de débit**==
- ==Voltmètre : sortie capteur débit et masse==
- ==Moteur tournant==
- ==Valeur attendue : oscillation entre 0,5 et 5V (tension variable en fonction du débit)==
==**D. Du signal du capteur de température**==
- ==Voltmètre : sortie thermistance et masse==
- ==Moteur tournant==
- ==Valeur attendue : tension variable entre 0,5 et 5V (tension variable en fonction du débit)==

### Sonde lambda
==*role* sonde à oxygène : mesure la teneur en oxygène contenue dans les gaz d'échappement pour optimiser l'injection, et contrôler l'efficacité du catalyseur (si sonde en aval)==

==*application* :== 
- ==sonde en amont du catalyseur : optimiser l'injection==
- ==sonde en aval du catalyseur : surveillance du catalyseur==

==*composition* : dite **sonde électrochimique**==
- ==corps en céramique poreuse==
- ==électrolyte solide==
- ==deux éléctrodes==
- ==4 fils :==
	- ==Deux pour le réchauffage==
	- ==Deux pour le signal de sortie==

==*fonctionnement* :== 
- ==chauffée à température de fonctionnement (300°C)==
- ==délivre une tension proportionnelle à la différence de la teneur en oxygène de l'air ambiant et des gaz d'échappement==

==*valeurs*==
==rapport stœchiométrique : 1g pour 14,7g d'air==
==température de fonctionnement : 300°C==

#### ==Contrôle==
==**A. Sonde amont, alimentation de chauffage**== 
- ==Voltmètre : bornes de chauffage==
- ==Valeur attendue : 12V==
==**B. Sonde amont, signal de sortie**==
- ==Oscilloscope : bornes de signal== 
- ==Moteur en fonctionnement==
- ==Sonde chaude==
- ==Valeur attendue : [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-7-x290-y99.png|signal sinusoïdal]] entre 0,2V (pauvre) et 0,8V (riche)==
==**C. Sonde aval, alimentation de chauffage**==
- ==Voltmètre : bornes de chauffage==
- ==Valeur attendue : 12V==
==**D. Sonde aval, signal de sortie**==
- ==Oscilloscope : bornes de signal== 
- ==Moteur en fonctionnement==
- ==Sonde chaude==
- ==Valeur attendue : [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-7-x290-y99.png|signal stable]], >0,5V==
- ==Si défaut : catalyseur HS==
## Autre
==EGR = optimiser le recyclage des gaz d'échappement, résuire les NO==
Élec : faire fiches des formules de base
==rapport stœchiométrique (1g pour 14,7g d'air)==
éléments de la soupape (tête, queue, etc)