# Module 2 – Communication IoT

## Présentation
Dans le scénario fictif, ce module représente le transfert des mesures depuis un équipement vers une application. Il est décrit à titre pédagogique ; aucune configuration réseau réelle n'est requise.

## Objectifs documentaires
- Expliquer pourquoi les données doivent être transmises.
- Présenter simplement le rôle d'un protocole de communication.
- Donner un exemple de message structuré.

## Fonctionnement théorique
Un équipement connecté pourrait envoyer une mesure à une application par Wi-Fi. MQTT est un exemple de protocole de messagerie souvent utilisé dans les systèmes IoT. Dans le cadre de ce TP, nous illustrons seulement la structure du message, sans installer de broker.

## Exemple de message simulé
```json
{
  "capteur": "MQ-2",
  "valeur": 760,
  "seuil": 700,
  "etat": "alerte"
}
```

## Entrées et sorties (scénario)
- Entrée : mesure fictive produite par le Module 1.
- Sortie : message JSON illustratif qui pourrait être transmis à une interface.

## Liens
- [Module 1 – Capteur et acquisition](Module-1-Capteur-et-acquisition.md)
- [Module 3 – Interface utilisateur](Module-3-Interface-utilisateur.md)
- [Code de simulation](../Documentation/Simulation-IoT.html)

## Responsable documentaire
Benachenhou Abdelkarim
