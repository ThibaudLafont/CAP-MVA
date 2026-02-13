Source : @MoteurM2P310


==**Fonction** : composant électromécanique qui contrôle l'ouverture et la fermeture du papillon des gaz==
- ==connecté à l'ECU qui commande le déplacement du papillon *via* l'actionneur==
- ==contrôler avec précisition l'ouverture du papillon==
- ==grâce à un moteur électrique ou pas à pas== 
- ==depuis la ralenti jusqu'à la plein charge==

==[[00_ASSETS/IMAGES/ZOTERO/20260122_172338/MoteurM2P310-undefined-x34-y40.png|Actionneur de papillon]], **composition**==
1. ==**Moteur électrique ou moteur pas à pas** : règle l'ouverture du papillon par rotation==
2. ==**Réducteur** : système d'engrenages qui réduit la vitesse du moteur et augmente son coupe==
3. ==**Ressort de rappel** : ramène le papillon en position initiale lorsque l'actionneur n'est plus alimenté==
4. ==**Butée de fin de course** : bloque la rotation au delà de 90°==
5. ==**Connecteurs électrique** : connexion entre== 
	1. ==ECU==
	2. ==Capteur de position papillon==
	3. ==Moteur éléctrique==
	4. ==Autres composants==
6. ==**Boîtier** : protège de la poussière, de l'humidité, vibrations==

==**facteurs pris en compte** : position de l’accélérateur, la vitesse du moteur, la température de l’air d’admission etc==

==**Voyant moteur allumé**==
1. ==Scanner codes défauts==
==**Vérifier les connexion électriques**==
2. ==serrées, propres, non oxydées==
3. ==sinon nettoyer avec nettoyant pour capteurs==
==**Mesurer la résistance**==
4. ==Mesure la résistance==
5. ==comparer aux valeurs de la RTA==
==**Moteur pas à pas**==
6. ==Utiliser un *driver de moteur pas à pas* (intégré dans un circuit électronique ou un microcontrôleur, génère des signaux en fonction de séquences de commande spécifiques requise. Fait tourner le moteur dans la direction et à la vitesse désirées.)==
==**Partie mécanique**==
7. ==Vérifier les engrenages : pas défectueux, tournent correctement==
8. ==Ressort de rappel : doit faire revenir le papillon en position 0 sans blocage==
9. ==Butée : vérifier que le papillon ne peut pas dépasser 90° de course==

