# Module 1 – Capteur et acquisition

## Présentation
Ce module détecte la présence de fumée à l'aide d'un capteur MQ-2 et fournit une mesure au microcontrôleur.

## Objectifs
- Acquérir une mesure du capteur.
- Surveiller son évolution.
- Fournir la valeur au microcontrôleur pour traitement.

## Matériel
- Capteur MQ-2.
- Carte Arduino ou ESP32.
- Câbles et alimentation adaptés.

## Fonctionnement
Le capteur MQ-2 réagit à certains gaz et à la fumée. Le microcontrôleur lit sa sortie puis compare la mesure à un seuil défini lors de la calibration. Le seuil retenu devra être documenté par l'équipe.

## Entrées et sorties
- Entrée : air ambiant.
- Sortie : signal analogique et/ou numérique selon le câblage.

## Technologies
Capteur MQ-2, Arduino ou ESP32, Arduino IDE.

## Tests
Vérifier la lecture au repos, la stabilité et la réaction dans un environnement de test contrôlé. Consigner les valeurs observées dans [Résultats des tests](../Tests/Resultats-des-tests.md).

## Responsable
À compléter.
