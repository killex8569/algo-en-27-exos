## Consignes

**Niveau** : Moyen  
**Internet autorisé** : non  
**Langage** : Python

## Énoncé

- Écrire une fonction qui convertit un nombre binaire en décimal.  
- La fonction prend en paramètre une chaîne de caractères et renvoie un nombre entier.  
- En parcourant la chaîne à l'envers, si l'on tombe sur un "1", on ajoute 2 puissance l'index actuel au nombre décimal final.


## Documentation
| Instruction                                    | Code                               |
| ---------------------------------------------- | ---------------------------------- |
| initialiser une fonction avec pour paramètre x | `def func(x) :`                    |
| Initialiser une variable                       | `x = 4` `y = "coucou"`             |
| condition if                                   | `if x == 'a' :`<br>                |
| récupérer la longueur d'une chaine             | `len(ch)`                          |
| afficher la valeur d'une variable              | `print(x)`                         |
| retourner une valeur d'une fonction            | `return x` `return v+2`            |
| puissance                                      | `x**2` (x "puissance" 2)           |
| appeler une fonction                           | `func(3)`                          |
| boucle for de 10 à 0 (avec un i décroissant)   | `for i in range(10, -1, -1) : ...` |

**Remarque** : Pour parcourir une chaine de caractère à l'envers, on ne peut pas utiliser le raccourci python `for char in chaine`. On doit utiliser une boucle for classique allant de la longueur de la chaine - 1 jusqu'à 0 inclus (donc -1 exclus - en python, le deuxième nombre du range est exclus) : `for i in range(longueur-1,-1,-1)`