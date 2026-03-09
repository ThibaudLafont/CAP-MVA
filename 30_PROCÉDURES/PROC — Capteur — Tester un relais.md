---

type: procedure

organe:

objectif:

source: zotero

---
## Objectif de la procédure
Vérifier le bon fonctionnement d’un relais électrique.
## Outillage nécessaire
- multimètre
- alimentation 12 V
- lampe témoin ou testeur de diode(option)
## Étapes
### 0. Rappels
Bornes : 
- **circuit de commande** : (86-85)(2-1)
- **circuit de puissance** : (30-87)
- **circuit de puissance repos (5 broches)** : (30-87a)

Schémas : [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-4-x319-y160.png|4 broches]] et [[00_ASSETS/IMAGES/ZOTERO/20260122_172339/SysElecM2P303-5-x53-y408.png|5 broches]]
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
## Valeurs attendues / Résultats
- résistance bobine : 60 à 90ohm
## Interprétation
- bobine coupée → relais HS
- résistance anormale → relais défectueux
- diode HS → relais dangereux
## Références
- @SysElecM2P303
- @SysElecM2P304