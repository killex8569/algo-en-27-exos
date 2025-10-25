## Consignes

**Niveau** : Moyen  
**Internet autorisé** : non  
**Langage** : C

## Énoncé

- Créer une fonction `calc_moyenne` qui prend en paramètre deux tableaux d'entiers.  
    - Dans cette fonction :  
        - Lire les données des tableaux, les extraire et les additionner dans une variable `somme_total1` et `somme_total2`  
        - Calculer la moyenne des deux sommes dans une variable `moyenne_g`.  
        - Retourner la valeur de `moyenne_g`.  
- Dans le programme principal, initialiser deux tableaux `moy1` et `moy2` qui contiendront chacun 3 entiers au choix.  
- Afficher le résultat de la fonction ; s'il est supérieur ou égal à 10, afficher le message "L'élève a la moyenne"

## Exemples de résultat

moy1 = 12, 4, 18
moy2 = 6, 15, 13

moyenne_g = 11.3

L'élève à la moyenne

## Documentation
| Instruction                                        | Code                                                    |
| -------------------------------------------------- | ------------------------------------------------------- |
| initialiser un code C                              | `int main() { ... }`                                    |
| initialiser une fonction avec un tableau en entrée | `int func(int tab[]) { ... }`                           |
| Initialiser une variable (pour un nombre entier)   | `int x = 4;` `int y = x + 4;`                           |
| ajouter une valeur à une variable                  | `var += val`                                            |
| condition if                                       | `if (x < 4) { ... } else { ... }`<br>                   |
| boucle for de 1 à n exclu                          | `for(int i=0;i<n;i++) { ... }`                          |
| afficher la valeur d'une variable (nombre entier)  | `printf("valeur : %d", x);`<br>`printf("%d", func(3));` |
| Terminer un code C (dans la fonction main)         | `return 0;`                                             |
**Remaque** : calculer une moyenne : total/nb_valeurs