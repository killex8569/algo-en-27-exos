## Consignes

**Niveau** : simple
**Internet autorisé** : non
**Langage** : C

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_
## Enoncé

- initialiser une variable "age" à une valeur numérique positive (n'importe laquelle)
- initialiser une variable "majorite" à la valeur 18 (ou 21 si vous voulez)
- si la valeur de "age" est inférieure à la valeur de "majorite", afficher le message "la personne est mineure, elle a X ans" (remplacer X par la valeur de "age")
- sinon, afficher le message "la personne est majeure, elle a X ans" (remplacer X par la valeur de "age")

## Exemples de résultat

--> la personne est mineure, elle a 17 ans

OU

--> la personne est majeure, elle a 20 ans

## Documentation
| Instruction                                      | Code                     |
| ------------------------------------------------ | ------------------------ |
| initialiser un code C                            | `int main() { ... }`     |
| Initialiser une variable (pour un nombre entier) | `int x = 4;`             |
| condition if                                     | `if (x < 4) { ... }`<br> |
| afficher la valeur d'une variable                | `printf("%d", x);`       |
| Terminer un code C                               | `return 0;`              |
**Remarque** : par convention, la fonction "main" en C renvoie un integer (<u>int</u> main()) qui vaut 0 si tout c'est bien passé, 1 s'il y a une erreur (d'où le `return 0;`)
