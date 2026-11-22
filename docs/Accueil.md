# Accueil du projet

## Présentation
Le projet consiste à concevoir un système d'alerte IoT pour détecter la fumée dans une pièce et transmettre une alerte à l'utilisateur par une interface connectée.

## Objectifs
- Détecter la présence de fumée ou de gaz avec un capteur MQ-2.
- Acquérir les mesures avec un ESP32.
- Transmettre les données via Wi-Fi et MQTT.
- Afficher l'état du système dans une interface web.
- Enregistrer les événements et les résultats des tests.

## Architecture
1. Le capteur MQ-2 fournit une mesure analogique.
2. L'ESP32 lit la mesure et applique un seuil de démonstration configurable.
3. L'ESP32 se connecte au Wi-Fi et publie la mesure via MQTT.
4. Un service Node.js reçoit les messages MQTT.
5. Une interface web affiche la dernière mesure et l'état associé.

## Équipe
| Membre | Responsabilité |
|---|---|
| Belkhir Mohamed | Capteur MQ-2, acquisition ESP32 et schéma électrique |
| Benachenhou Abdelkarim | Communication Wi-Fi/MQTT et réception des données |
| Belhaoua Aissa | Interface web, tests, validation et navigation du Wiki |

## Accès rapide
- [Informations du projet](Informations-du-projet.md)
- [Sommaire](Sommaire.md)
- [Modèle de page module](Template-Module.md)
- [Modules techniques](Modules/README.md)
- [Documentation](Documentation/README.md)
- [Tests](Tests/README.md)
- [Collaboration et historique](Collaboration.md)
- [Carte de navigation](Carte-de-navigation.md)
- [Bilan](Bilan.md)
