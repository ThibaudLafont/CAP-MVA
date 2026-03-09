---

type: procedure

organe:

objectif:

source: zotero

---
## Objectif de la procédure
Valider le fonctionnement d'un [[40_SAVOIRS_TECHNIQUES/SAV — Capteur — Capteur de température à résistance variable|capteur de température à résistance variable]]

**Type de test** : électrique, thermique  
**Signal** : analogique
## Étapes
[[30_PROCÉDURES/PROC — 00 — Test électrique|PROC — 00 — Test électrique]] : signal analogique
### Récupérer les données constructeur
Trouver une correspondance entre résistance et température
### Faire varier le signal sonde en place
1. Ohmmètre : bornes du capteur
2. Démarrer le moteur
3. Vérifier fréquemment
	- **température de l'eau** : capteur infrarouge, au niveau de la tuyauterie d'eau qui va vers le radiateur
	- **la résistance du capteur** : afin de la comparer aux données constructeur
### Faire varier le signal sonde déposée
[[30_PROCÉDURES/PROC — 00 — Test thermique|PROC — 00 — Test thermique]] : valeur variable et corrélée à la température
1. la résistance s'abaisse/augmente progressivement
2. la tension s'abaisse/augmente progressivement
## Valeurs attendues / Résultats
- **tension de sortie** : évolue de 0,5V à 5V avec la montée en température (tension variable selon température, valeur typique mais dépend du montage)
- **résistance** : évolue avec la montée en température ; voir données constructeur
## Interprétation
- Résultat conforme : capteur OK
- Résultat non conforme : remplacer capteur
## Références
- @MoteurM2P313