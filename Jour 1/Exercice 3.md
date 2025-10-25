## Consignes

**Niveau** : complexe
**Internet autorisé** : non
**Langage** : Bash

## Enoncé

- demander à l'utilisateur de rentrer une valeur numérique et la mettre dans la variable "nb"
- tant que cette valeur n'est pas numérique, demander à l'utilisateur de rentrer une valeur
- une fois la valeur validée :
	- si elle est inférieur à 5, afficher "inférieur à 5"
	- afficher la valeur de "nb"

## Documentation
| Instruction                              | Code                             |
| ---------------------------------------- | -------------------------------- |
| initialiser une variable                 | `var=5`                          |
| condition while                          | `while ... ; do ... done`        |
| input utilisateur dans la variable "var" | `read -p "entrez valeur : " var` |
| afficher une valeur                      | `echo $var` `echo "message"`     |
| vérifier si une valeur est numérique     | `[[ $VAR =~ "^[0-9]+$" ]]`       |
| vérifier si x est inférieure à y         | `[[ $x < $y ]]`                  |
| condition if                             | `if ... ; then ... fi`           |

