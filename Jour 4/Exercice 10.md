## Consignes

**Niveau** : Simple  
**Internet autorisé** : non  
**Langage** : Python

_Rappel : vous pouvez regarder sur Internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Énoncé

- Créer une fonction `pfc` qui :  
    - Propose au joueur de choisir entre Pierre, Feuille et Ciseau en input et l'inclut dans une variable : si l'input n'est pas égal à P, F ou C, on sort de la fonction avec un message d'erreur  
    - L'ordinateur choisit aléatoirement un nombre entre 0 et 2, et prend à cet index la valeur située dans le tableau `[P, F, C]`  
    - L'algo compare les deux réponses du joueur et de l'ordi (--> Voir règles) :  
	    - Si le choix de l'ordi est 'P' et celui de l'utilisateur est 'F', afficher "Joueur a gagné"  
	    - Si le choix de l'ordi est 'C' et celui de l'utilisateur est 'C', afficher "Égalité"  
	    - Etc.  
    - Annonce le gagnant de la manche (Joueur ou Ordi), affiche aussi le choix de l'ordi et du joueur.


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

