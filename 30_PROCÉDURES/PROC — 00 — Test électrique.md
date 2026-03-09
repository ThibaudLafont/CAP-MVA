---

type: procedure

organe:

objectif:

source: zotero

---
## Objectif de la procédure
Valider le fonctionnement d'un capteur
## Outillage nécessaire
- Multimètre
- Oscilloscope (si capteur numérique)
- Valise de diagnostic
- Données constructeur
## Étapes
### 1. Contrôle visuel
- état du capteur
- connectique
- faisceau
### 2. Contrôle de l’alimentation
1. Voltmètre : alimentation et masse
2. Mettre le contact
3. Comparer avec la valeur constructeur
### 3. Contrôle du signal
1. Voltmètre ou oscilloscope : sortie capteur
2. Faire varier la grandeur mesurée (pression, position, température…)
3. Vérifier que le signal varie correctement
### 4. Contrôle à la valise
1. Lire la donnée capteur
2. Comparer avec les valeurs constructeur
3. Vérifier la cohérence de variation
## Valeurs attendues / Résultats
- alimentation : généralement **5 V**
- signal :
  - **analogique** : 0,5 → 4,5 V (valeur typique)
  - **numérique** : signal carré
  - **inductif** : signal [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P306-2-x85-y548.png|alternatif et sinusoïdal]]
## Interprétation
- alimentation absente → problème faisceau ou calculateur  
- signal incorrect → capteur défectueux  
- signal correct mais défaut présent → problème faisceau / calculateur
## Références
- @SysElecM2P306
- @SysElecM2P305
- @MoteurM2P313 
- @LiaisonAuSolM2P319