# Cahier des charges

## Besoin
Concevoir un système connecté qui détecte la fumée dans une pièce et avertit l'utilisateur.

## Fonctionnalités attendues
- Acquisition des mesures d'un capteur MQ-2.
- Traitement par Arduino ou ESP32.
- Transmission par Wi-Fi ou MQTT.
- Affichage dans une interface web ou mobile.
- Enregistrement des événements dans une base de données.
- Déclenchement d'une alerte selon un seuil configuré.

## Contraintes
- Calibration et fiabilité du capteur.
- Délai de transmission des alertes.
- Disponibilité du réseau.
- Alimentation adaptée et sécurité électrique.
- Protection des données et contrôle d'accès.

## Critères de validation
- Les mesures sont acquises et consultables.
- Les messages sont reçus par la plateforme.
- Un événement de test déclenche l'alerte configurée.
- Les événements sont enregistrés et consultables.

## Limites
Un prototype pédagogique ne remplace pas un détecteur de fumée certifié ni un système de sécurité incendie homologué.
