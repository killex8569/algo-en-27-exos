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




## Documentation

--> Fonction en Bash

--> Stopper
