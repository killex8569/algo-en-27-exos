## Consignes

**Niveau** : Complexe
**Internet autorisé** : non
**Langage** : Bash

_Rappel : Pour l'algo glouton, n'aller pas le chercher sur internet, faite le serieusement et faite des recherches uniquement sur les points bloquant (erreurs, syntaxtes, autres...)_

## Enoncé

- Créer un mini gestionnaire de tâche pour Linux.

- Créer les trois fonction suivantes : `main`, `taches` et `test_stop`, la fonction `main` fonctionne comme un `menu principal`.
- La première fonction `main` devra fonctionner de la manière suivante : 
    - Demander à l'utilisateur de renseigner un choix, ce choix sera variable entre 1 et 3 : 
        - 1 - Pour lancer la fonction `taches`.
        - 2 - Pour lancer la fonction `test_stop`.
        - 3 - Pour sortir et terminer le programme.
    - La fonction tâches devra lancer l'utilitaire `top` et l'actualiser toute les secondes : 
        - Si l'utilisateur tape `Q` dans le shell, alors le programme `top` s'arrête et boucle sur la fonction `main`.
    - La fonction `test_stop` permet de renseigner un PID et de kill le processus liée à ce PID et renvoie sur la fonction `main`.


## Exemples de résultat

--- fonction main

Gestionnaire de tâches V1

1 - Voir les processus en cours
2 - Stopper un service via PID
3 - Quitter le programme
Votre choix : 1

--- fonction taches

<utilitaire top>

voulez vous quitter ? : Y

--- fonction main

Gestionnaire de tâches V1

1 - Voir les processus en cours
2 - Stopper un service via PID
3 - Quitter le programme
Votre choix : 2

--- fonction test_stop

<Liste des processus en fonctionnement>

Entrer le pid que vous souhaitez stopper (q pour quitter): 2025
processus 2025 arreter.

--- fonction main

Gestionnaire de tâches V1

1 - Voir les processus en cours
2 - Stopper un service via PID
3 - Quitter le programme
Votre choix :


## Documentation

--> Fonction en Bash

- Déclaration d'une fonction en Bash `function <nom_fonction>{...}`
- Pour stopper un programme en Bash, il suffit de faire Exit 0
- L'utilitaire `top` en bash --> affiche les données du système 
- Appelle d'une fonction en bash : `<nom_fonction>`
