Source : @SysElecM2P303; @SysElecM2P304

==**utilisé pour** : éclairage, signalisation, refroidissement moteur (*l'ensemble des boitiers életroniques*)==

==**emplacement** : habitacle, sous le capot==

==**description** : petit boitier plastique avec 4 ou 5 fiches électriques==
1. ==circuit de commande==
2. ==circuit de puissance==

==**circuit de commande** : bobinage==
==**circuit de puissance** : palette mobile[[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-2-x84-y368.png]]==

==**rôle du relais** : les équipements électriques des voitures sont puissants, et le courant utilisé pour alimenter les organes électriques (lampe antibrouillard par exemple) génère une intensité qui détruirait le circuit de commande s'il était utilisé comme un interrupteur simple.==
1. ==réduire l'intensité qui passe dans la commande, donc pouvoir alimenter des consommateurs haute intensité avec une commande faible intensité==
2. ==réduire la section des fils du tableau de bord (coût, encombrement)==

==**fonctionnement**==
1. ==**la commande antibrouillard n'est pas actionnée** :== 
	1. ==le bobinage n'est pas alimenté (le circuit est ouvert)==
	2. ==la palette de puissance ne bouge pas==
	3. ==le circuit qui alimente les feux est ouvert==
2. ==**la commande antibrouillard est actionnée**`==
	1. ==le bobinage est alimenté (le circuit est fermé)==
	2. ==le bobinage produit un champ magnétique qui attire la palette de puissance==
	3. ==la palette de puissance ferme le circuit de puissance==
	4. ==le circuit qui alimente les feux est fermé==

**calul de l'intensité du circuit de commande**
- dépend de la résistance du bobinage du relais (==60 à 90ohm==)
- U = RI ; I=U/R ; si 60ohm I=12/60=0,2A

**intensité du circuit de puissance**
- chaque relais est prévu pour une certain intensité

==**identification d'un relais**==
==*2 types* : 4 ou 5 broches==
==*2 normes* : DIN et française==
==[[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-4-x320-y549.png|din et fr]]==

==**relais simples sans protection**==
==4 broches : simple, interrupteur on/off== 
- ==2 pour circuit de commande (86-66)==
- ==2 pour circuit de puissance (30-87)==


==**relais double dans protextion**==
==5 broches : une alimentation au repos (se coupe quand commandé), une alimentation en commande==


==**relais avec protection**==
==ajoute une diode qui protège le circuit de commande du relais==
==la diode fait absorber au bobinage la surtension aux bornes du relais pour ne pas endommager l'élément de commande (plusieurs centaines devolts, boîtier électronique)==

**contrôle du relais**
1. résistance et continuité du relais au repos 
	1. bobine : entre 60 et 90 ohmns
	2. puissance circuit fermé : <0.5ohm
	3. puissance circuit ouvert : OL
2. continuité de l'étage puissance quand le relais est alimenté
	2. puissance circuit fermé : <0.5ohm
	3. puissance circuit ouvert : OL
3. contrôle de la diode de protection
	1. avec une lampe
	2. avec un testeur de diode
[[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-7-x54-y99.png|img 1]]
[[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-7-x54-y99.png|img 2]]

**==NE GAMAIS UTILISER UN RELAIS SANS DIODE A LA PLACE DUN RELAIS AVEC DIODE==**

==**P=UI**==


---
---
type: procedure
source: zotero
---

## Objectif
Vérifier le bon fonctionnement d’un relais électrique.

## Outillage nécessaire
- multimètre
- alimentation 12 V
- lampe témoin (option)

## Étapes

### 1. Contrôle bobine (au repos)
- mesurer résistance bobine
- valeur attendue : 60 à 90 Ω

### 2. Contrôle puissance (au repos)
- circuit fermé : < 0,5 Ω
- circuit ouvert : OL

### 3. Contrôle puissance (alimenté)
- alimenter bobine en 12 V
- circuit fermé : < 0,5 Ω
- circuit ouvert : OL

### 4. Contrôle diode (si présente)
- test diode au multimètre
- ou lampe témoin

## Interprétation
- bobine coupée → relais HS
- résistance anormale → relais défectueux
- diode HS → relais dangereux

## Références
- Zotero : SysElecM2P303, SysElecM2P304
&