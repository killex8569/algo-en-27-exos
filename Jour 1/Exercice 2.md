## Consignes

**Niveau** : moyen
**Internet autorisé** : non
**Langage** : Python

## Enoncé

- écrire la fonction calc qui a pour paramètre "val" qui :
	- demande à l'utilisateur de rentrer un nombre en input et le met dans une variable
	- si le nombre est pair, elle renvoie ce nombre multiplié par "val"
	- sinon, elle renvoie le nombre élevé au cube (puissance 3)
- appeler la fonction trois fois avec val=4, val=2 et val=-3

## Exemple de résultat

Votre nombre : 2
val = 4
8

OU

Votre nombre : 3
9

## Documentation
| Instruction                                                              | Code                                |
| ------------------------------------------------------------------------ | ----------------------------------- |
| initialiser une fonction avec pour paramètre x                           | `def func(x) :`                     |
| Initialiser une variable                                                 | `x = 4`                             |
| condition if                                                             | `if x < 4 : ... else : ...`<br>     |
| afficher la valeur d'une variable / fonction                             | `print(x)` `print(func(3))`         |
| retourner une valeur d'une fonction                                      | `return x` `return v+2`             |
| savoir si un nombre est pair                                             | `x % 2 == 0`                        |
| demander à l'utilisateur de rentrer un entier et mettre la valeur dans x | `x = int(input("entrez valeur: "))` |
| puissance                                                                | `x**2` (x "puissance" 2)            |
| appeler une fonction                                                     | `func(3)`                           |
**Remarque** : `%` permet de faire le "modulo" entre deux valeurs : récupérer le reste de la division euclidienne (ex : 10/3 -> 3x3=9 il reste 1 donc 10%3 = 1)