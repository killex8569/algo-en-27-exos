## Consignes

**Niveau** : Complexe
**Internet autorisé** : Oui
**Langage** : Python

_Rappel : Pour l'algo glouton, n'aller pas le chercher sur internet, faite le serieusement et faite des recherches uniquement sur les points bloquant (erreurs, syntaxtes, autres...)_

## Enoncé

## Consignes

**Niveau** : Complexe  
**Internet autorisé** : Oui  
**Langage** : Python

_Rappel : Pour l'algo glouton, n'allez pas le chercher sur Internet, faites-le sérieusement et effectuez des recherches uniquement sur les points bloquants (erreurs, syntaxes, autres...)._

## Énoncé

- Créer une fonction `algo_glouton` qui prend en paramètre :  
    - Les données du problème à résoudre (par exemple une capacité maximale et une liste d'objets avec poids et valeur pour un problème de type *knapsack*).  

- La fonction devra effectuer les actions suivantes :  
    - Vérifier la validité des entrées (capacité positive, poids et valeurs non nuls).  
    - Appliquer une stratégie gloutonne pour résoudre le problème :  
        - Déterminer le critère glouton (par exemple ratio valeur/poids des pièces de monnaies).  
        - Trier les éléments selon ce critère.  
        - Parcourir les éléments triés et ajouter à la solution la quantité maximale possible sans dépasser la contrainte principale.  
    - Calculer et retourner la solution finale (par exemple valeur maximale et liste des éléments sélectionnés).
    - Gérer les cas particuliers : liste vide, capacité nulle, entrées invalides. 

