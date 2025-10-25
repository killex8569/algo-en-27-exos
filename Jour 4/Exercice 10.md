## Consignes

**Niveau** : Simple
**Internet autorisé** : non
**Langage** : Python

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

- créer une fonction `pfc` qui : 
    - propose au joueur de choisir entre Pierre, feuille et Ciseau en input et l'inclure dans une variable : si l'input n'est pas égale à P, F ou C, on sort de la fonction avec un message d'erreur
    - L'ordinateur choisi aléatoirement un nombre entre 0 et 2, et prend à cet index la valeur située dans le tableau `[P, F, C]`
    - L'algo compare les deux réponses du joueurs et de l'ordi. (--> Voir règles) :
	    - si le choix de l'ordi est 'P' et celui de l'utilisateur est 'F', afficher "Joueur a gagné"
	    - si le choix de l'ordi est 'C' et celui de l'utilisateur est 'C' afficher "égalité"
	    - etc.
    - Annonce le gagnant de la manche (Joueur ou Ordi), affiche aussi le choix de l'ordi et du joueurs.

## Règles

Pierre gagne sur le Ciseau.
Ciseau gagne sur le papier.
Papier gagne sur la pierre.

## Exemples de résultat

Choix joueur : P
Choix Ordi : C

Joueur a gagné !


## Documentation
| Instruction                                    | Code                            |
| ---------------------------------------------- | ------------------------------- |
| importer un module                             | `import random`                 |
| définir une fonction                           | `def nom_fonction():`           |
| générer un entier aléatoire entre 0 et 2       | `random.randint(0, 2)`          |
| créer une liste                                | `choix = ['P', 'F', 'C']`       |
| lire une entrée utilisateur                    | `var = input("Votre choix : ")` |
| comparer deux valeurs                          | `if a == b:`                    |
| conditions multiples                           | `if ... elif ... else:`         |
| quitter une fonction                           | `return`                        |
| afficher un message                            | `print("message")`              |
| accéder à un élément de liste par index        | `choix[index]`                  |
| tester l’appartenance d’une valeur à une liste | `if var in ['P', 'F', 'C']:`    |

