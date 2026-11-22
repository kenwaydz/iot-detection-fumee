# Scénarios de test simulés

Les tests ci-dessous vérifient uniquement le comportement de la petite simulation HTML. Ils ne testent aucun matériel réel.

## Test 1 – Générer une mesure
- Action : cliquer sur « Générer une mesure ».
- Attendu : une valeur numérique fictive apparaît.

## Test 2 – État normal
- Action : générer ou saisir une valeur inférieure au seuil.
- Attendu : l'interface affiche « Normal ».

## Test 3 – État d'alerte
- Action : générer ou saisir une valeur supérieure ou égale au seuil.
- Attendu : l'interface affiche « Alerte ».

## Test 4 – Modifier le seuil
- Action : changer le seuil dans le champ prévu.
- Attendu : l'état est recalculé selon le nouveau seuil.

## Test 5 – Historique
- Action : générer plusieurs mesures.
- Attendu : les mesures apparaissent dans la liste de l'historique.

## Limite
Les valeurs sont simulées dans le navigateur. Elles ne prouvent pas le fonctionnement d'un capteur MQ-2 ou d'un système IoT réel.
