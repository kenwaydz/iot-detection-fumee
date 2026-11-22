# Module 1 – Capteur et acquisition

## Présentation
Dans le scénario fictif documenté, un capteur MQ-2 représente l'élément qui détecte la présence de fumée ou de certains gaz. Cette page explique son rôle sans demander de montage réel.

## Objectifs documentaires
- Présenter le rôle du capteur.
- Expliquer le principe d'une valeur mesurée.
- Décrire comment une mesure pourrait être comparée à un seuil.

## Fonctionnement théorique
Le capteur fournit une valeur qui varie selon les conditions détectées. Un microcontrôleur pourrait lire cette valeur et la comparer à un seuil configuré. Pour le TP, ces valeurs peuvent être simulées dans un petit exemple logiciel.

## Entrées et sorties (scénario)
- Entrée : valeur fictive représentant la mesure du capteur.
- Sortie : valeur numérique et état « normal » ou « alerte ».

## Exemple de données simulées
| Mesure fictive | Seuil fictif | État affiché |
|---:|---:|---|
| 420 | 700 | Normal |
| 760 | 700 | Alerte |

Ces nombres sont uniquement des exemples pédagogiques, pas des mesures physiques ni un seuil de sécurité.

## Liens
- [Modèle de page module](../Template-Module.md)
- [Module 2 – Communication IoT](Module-2-Communication-IoT.md)
- [Simulation logicielle](../Documentation/Simulation-IoT.html)
- [Scénarios de test simulés](../Tests/Scenarios-de-test.md)

## Responsable documentaire
Belkhir Mohamed
