## Consignes

**Niveau** : Complexe  
**Internet autorisé** : non  
**Langage** : Bash

## Énoncé

- Créer un mini gestionnaire de tâches pour Linux.  

- Créer les trois fonctions suivantes : `main`, `taches` et `test_stop`. La fonction `main` fonctionne comme un `menu principal`.  
- La fonction `main` devra fonctionner de la manière suivante :  
    - Demander à l'utilisateur de renseigner un choix, ce choix sera variable entre 1 et 3 :  
        - 1 - Pour lancer la fonction `taches`  
        - 2 - Pour lancer la fonction `test_stop`  
        - 3 - Pour sortir et terminer le programme  
    - La fonction `taches` devra lancer l'utilitaire `top` et l'actualiser toutes les secondes :  
        - Si l'utilisateur tape `Q` dans le shell, alors le programme `top` s'arrête et boucle sur la fonction `main`  
    - La fonction `test_stop` permet de renseigner un PID et de kill le processus lié à ce PID et renvoie sur la fonction `main`

## Exemples de résultat

--- fonction main  

Gestionnaire de tâches V1  

1 - Voir les processus en cours  
2 - Stopper un service via PID  
3 - Quitter le programme  
Votre choix : 1  

--- fonction taches  

<utilitaire top>  

Voulez-vous quitter ? : Y  

--- fonction main  

Gestionnaire de tâches V1  

1 - Voir les processus en cours  
2 - Stopper un service via PID  
3 - Quitter le programme  
Votre choix : 2  

--- fonction test_stop  

<Liste des processus en fonctionnement>  

Entrer le PID que vous souhaitez kill (q pour quitter) : 2025  
Processus `2025` terminé.  

--- fonction main  

Gestionnaire de tâches V1  

1 - Voir les processus en cours  
2 - Stopper un service via PID  
3 - Quitter le programme  
Votre choix :

## Documentation

--> Fonctions en Bash  

- Déclaration d'une fonction en Bash : `function <nom_fonction> { ... }`  
- Pour stopper un programme en Bash, il suffit de faire `exit 0`  
- L'utilitaire `top` en Bash --> affiche les données du système  
- Appel d'une fonction en Bash : `<nom_fonction>`
