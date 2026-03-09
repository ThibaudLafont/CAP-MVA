---

type: procedure

organe:

objectif:

source: zotero

---
## Objectif de la procédure
Valider le fonctionnement d'un [[40_SAVOIRS_TECHNIQUES/SAV — Capteur — Débitmètre|débitmètre]]
## Outillage nécessaire
- Multimètre
## Étapes
### Vérification visuelle
Dommage, usure, connectique
### Contrôle de l'alimentation du capteur
1. Voltmètre : alimentation du capteur et masse
2. Mettre le contact
3. Valeur attendue : 5V
### Contrôle de l'alimentation de l'élément chauffant
1. Voltmètre : alimentation de chauffage et masse
2. Mettre le contact
3. Valeur attendue : 12V
### Contrôle du signal du capteur de débit
#### Voltmètre
1. Voltmètre : sortie capteur débit et masse
2. Moteur tournant
3. Valeur attendue : entre 0,5 et 5V (tension variable en fonction du débit)
##### Valise ODB
1. Moteur en marche
2. Lire les données de masse d'air
3. Comparer avec les valeurs RTA
4. Accélérer et décélérer, vérifier la variation du signal : si trop lent ou trop rapide, défaut possible de la sonde
### Contrôle de la résistance du capteur de débit
1. Ohmmètre : sortie capteur débit et masse
2. Moteur tournant
3. Valeur attendue : vérifier avec RTA
### Contrôle de l'alimentation du capteur de température
[[30_PROCÉDURES/PROC — Capteur — Capteur de température à résistance variable|PROC — Capteur — Capteur de température à résistance variable]]
## Valeurs attendues / Résultats
- **alimentation du capteur** : 5V
- **alimentation du chauffage** : 12V
- **signal électrique capteur débit** : signal variable entre 0,5 et 5 V (tension variable en fonction du débit)
- **thermistance** : tension variable entre 0,5 et 5V (tension variable en fonction du débit)
## Interprétation
- Résultat conforme : capteur OK
- Résultat non conforme : remplacer capteur
## Références
- @SysElecM2P306
- @SysElecM2P305