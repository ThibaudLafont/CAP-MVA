---
type: savoir
objet:
importance: haute
source: zotero
---
## Fonction
Informer de la quantité d'air (entrant dans le moteur ou passant par la vanne EGR)

*applications :* quantité d'air frais d'admission (injection gestion EGR)
## Composition
1. **Corps principal** 
2. **Capteur de débit d'air**
	- à fil chaud :  fil très fin en platine (120C°)
	- à fil froid
	- à film chaud : film fin, plus robuste, plus précis (160°C)
3. **Circuit électronique**
4. **Connecteur** **5 fils** : 
	1. 12V pour chauffer
	2. 5V d'alimentation du capteur
	3. Masse
	4. Signal débit d'air (0 à 5V)
	5. Thermistance (signal de température d'air)
5. **Sonde de température** : thermistance, capteur de température d'air intégré au débitmètre qui mesure la température de l'air entrant dans le moteur pour calculer la masse
6. *Fixation par bride*
## Principe de fonctionnement
### À élément chaud
- l'élément chauffant est chauffé
- la quantité d'air le refroidit plus ou moins
- plus le fil est refroidi, plus il demande d'énergie pour se maintenir à température
- c'est la mesure de la consommation du capteur qui permet de déterminer le débit de l'air
### À fil froid
- Le courant est envoyé au fil froid
- Le fil refroidit avec le passage de l'air
- Sa résistance varie avec sa température
- La tension est ajustée en conséquence
- L'ECU utilise l'information pour calculer la quantité de carburant nécessaire à l'obtention d'un rapport air-carburant optimal
## Signaux typiques
- Tension variable
- Consommation
## Valeurs caractéristiques
- **Alimentation de chauffage** : 12V
- **Alimentation de capteur** : 5V
- **Tension de sortie** : 0 à 5V
## À savoir par cœur
- film chaud > fil chaud (plus robuste, plus précis)
## Risques en cas de mal-fonction
-
## Références
- @SysElecM2P306
- @SysElecM2P305
- [[30_PROCÉDURES/PROC — Électricité — Débitmètre|PROC — Électricité — Débitmètre]]