# Module 2 – Communication IoT

## Présentation
Ce module transmet les mesures du microcontrôleur vers une plateforme de surveillance.

## Objectifs
- Transmettre les mesures.
- Assurer la communication entre l'équipement et le serveur.
- Transporter les événements d'alerte.

## Matériel
- ESP32 ou Arduino avec connectivité réseau.
- Point d'accès Wi-Fi.
- Serveur ou plateforme de réception.

## Fonctionnement
Le microcontrôleur prépare les mesures puis les transmet au serveur via Wi-Fi. MQTT peut être utilisé si cette option est retenue. Le broker, les topics et le format des messages seront précisés après implémentation.

## Entrées et sorties
- Entrée : mesures et événements du capteur.
- Sortie : messages transmis à la plateforme.

## Technologies
Wi-Fi, ESP32 et éventuellement MQTT.

## Tests
Vérifier la connexion, la réception des messages, les pertes de communication et la reconnexion. Reporter les résultats dans [Résultats des tests](../Tests/Resultats-des-tests.md).

## Responsable
À compléter.
