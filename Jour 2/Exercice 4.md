## Consignes

**Niveau** : simple
**Internet autorisé** : non
**Langage** : C

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

- créer deux variables : var1 et var2, respectivement égales à 4 et 8
- afficher les valeurs de var1 et var2 (dans cet ordre)
- créer une variable temp qui prend la valeur de var1
- var1 prend la valeur de var2
- var2 prend la valeur de temp
- afficher les valeurs de var1 et var2 (dans cet ordre)

## Exemples de résultat

début :
- var1 = 4
- var2 = 8

fin :
- var1 = 8
- var2 = 4

## Documentation
| Instruction                                      | Code                                        |
| ------------------------------------------------ | ------------------------------------------- |
| initialiser un code C                            | `int main() { ... }`                        |
| Initialiser une variable (pour un nombre entier) | `int x = 4;` `int y = x;`                   |
| afficher la valeur d'une variable                | `printf("%d", x);` `printf("%d %d", x, y);` |
| Terminer un code C                               | `return 0;`                                 |
**Remarque** : L'utilisation d'une variable "temp" est essentielle, si on ne l'utilise pas voici ce qui se passe :
```C
int var1 = 4;
int var2 = 8;
var1 = var2; // donc var1 = 8
var2 = var1; // donc var2 = 8
// donc var1 = 8 ; var2 = 8 ce n'est pas ce qu'on voulait
```
