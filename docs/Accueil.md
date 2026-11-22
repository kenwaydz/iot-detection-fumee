# Accueil du projet

## Présentation
Le projet consiste à concevoir un système d'alerte IoT pour détecter la fumée dans une pièce et transmettre une alerte à l'utilisateur par notification ou e-mail.

## Objectifs
- Détecter la présence de fumée.
- Acquérir les mesures d'un capteur.
- Transmettre les données via le réseau.
- Informer l'utilisateur si le seuil configuré est dépassé.
- Conserver l'historique des événements.

## Architecture
1. Le capteur MQ-2 mesure la présence de fumée / gaz.
2. Un Arduino ou ESP32 acquiert la mesure.
3. Une connexion Wi-Fi ou MQTT transmet les données.
4. Une interface web ou mobile présente les alertes.
5. Une base de données conserve les événements.

## Équipe
| Membre | Rôle |
|---|---|
| Belkhir Mohamed | À définir |
| Benachenhou Abdelkarim | À définir |
| Belhaoua Aissa | À définir |

## Accès rapide
- [Infobox](Informations-du-projet.md)
- [Sommaire](Sommaire.md)
- [Modules techniques](Modules/README.md)
- [Documentation](Documentation/README.md)
- [Tests](Tests/README.md)
- [Bilan](Bilan.md)
