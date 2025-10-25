## Consignes

**Niveau** : Complexe
**Internet autorisé** : oui
**Langage** : C

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

- Créer 2 fichiers dans votre projet C :
    - Un `algo.h` dans le dossier `include`
    - Un `algo.c` dans le dossier `src`

- Dans le fichier `algo.c`, créer une fonction `juste_prix` de type void.

- Reprendre l'énnoncer de l'exo 11 du jour 4 mais cette fois à faire en C. Vous devez inclure les modifications suivantes : 
    - Déclarer une fonction `juste_prix` dans algo.c qui prend en paramètre un entier `user_rep`.
    - Initialiser les variables `ordi_rep` et `i` qui seront égales à 0.
    - Déterminer un nombre aléatoire qui sera contenue dans la variable `ordi_rep`.
    - Le programme doit laisser le user entrer une valeur : 
        - Si cette valeur est égal à celle choisi par l'ordi, le joueur gagne
        - Si elle est inférieur, le programme indique au joueur que sa valeur est plus petite.
        - Si elle est supérieur, le programme indique au joueur que sa valeur est plus grande.
        - Si l'entrer est invalide, le joueur doit de nouveau indiquer sont choix.
    

## Structure attendu

- main.c
- algo.c
- algo.h

## Exemple de résultat

Votre nombre : 500
Le nombre mystère est plus grand.
**9 vies restantes**

Votre nombre : 968
Bien joué ! Le nombre mystère était 968.
Il vous restait 9 vies.



