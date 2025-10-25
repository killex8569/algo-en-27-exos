## Consignes

**Niveau** : simple
**Internet autorisé** : non
**Langage** : C

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

- on vous donne un tableau représentant 74 lancés de dé avec le numéro sur lequel on est tombé à chaque lancé :
- `{ 6, 1, 6, 2, 6, 5, 6, 6, 1, 6, 6, 4, 3, 6, 6, 6, 2, 5, 6, 6, 1, 6, 6, 6, 6, 3, 2, 6, 6, 6, 6, 6, 4, 1, 6, 5, 2, 6, 6, 3, 5, 6, 6, 6, 2, 1, 6, 5, 6, 6, 6, 4, 2, 6, 6, 6, 3, 6, 6, 5, 6, 6, 6, 2, 1, 6, 5, 4, 2, 6, 3, 2, 6, 1 }`
- Calculer les informations suivantes :
	- Le nombre fois où on a obtenu chacun des nombres (combien de fois on a obtenu 1, combien de fois on a obtenu 2...)
	- La probabilité (entre 0 et 1) que l'on tombe sur 6 s'il on choisit un des résultat du tableau au hasard
- Afficher un message si vous pensez que le dé est truqué

##  Résultat attendu

- **1** : 8 fois
- **2** : 7 fois
- **3** : 6 fois
- **4** : 4 fois
- **5** : 7 fois
- **6** : 42 fois

- Probabilité de tomber sur 6 : ~0.56

Mais bien sûr le dé n'est pas truqué...

## Documentation
| Instruction                         | Code                                    |
| ----------------------------------- | --------------------------------------- |
| Inclure une bibliothèque standard   | `#include <stdio.h>`                    |
| Définir une fonction principale     | `int main() { ... }`                    |
| Créer un tableau d'entiers          | `int tab[] = {6, 1, 6, 2, ...};`        |
| Calculer la taille d’un tableau     | `int n = sizeof(tab) / sizeof(tab[0]);` |
| Initialiser une variable            | `int count = 0;`                        |
| Boucle for                          | `for(int i = 0; i < n; i++) { ... }`    |
| Condition if                        | `if (tab[i] == 6) { ... }`              |
| Afficher un résultat                | `printf("message %d\n", valeur);`       |
| Division pour calcul de probabilité | `float p = (float)count / n;`           |
| Comparaison de valeurs              | `if (x > y) { ... } else { ... }`       |


