## Consignes

**Niveau** : Moyen  
**Internet autorisé** : non  
**Langage** : Bash

_Rappel : vous pouvez regarder sur Internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Énoncé

- Vous allez devoir refaire le jeu du juste prix.  
    - Créer une fonction `juste_prix`, elle devra effectuer les actions suivantes :  
        - L'ordinateur choisit un nombre entre 0 et 1000 et l'initialise dans une variable.  
        - On demande à l'utilisateur de renseigner un nombre.  
        - Dans le cas où ils sont égaux, le programme s'arrête et affiche le nombre.  
        - Le programme indique au joueur si son nombre est plus petit ou plus grand que le nombre de l'ordi.  
        - À chaque réponse donnée par l'utilisateur, un compteur initialisé à 10 se décrémente et, arrivé à 0, le joueur a perdu.



## Exemple de résultat
Votre nombre : 500
Le nombre mystère est plus grand.
**9 vies restantes**

Votre nombre : 968
Bien joué ! Le nombre mystère était 968.
Il vous restait 9 vies.

## Documentation

| Instruction                                     | Code                                                                 |
| ----------------------------------------------- | -------------------------------------------------------------------- |
| Définir une fonction                            | `function nom_fonction() { ... }`                                    |
| Générer un nombre aléatoire entre 0 et 1000     | `nombre=$((RANDOM % 1001))`                                          |
| Lire une entrée utilisateur                     | `read -p "Votre nombre : " var`                                      |
| Comparer deux valeurs numériques                | `if [ "$x" -eq "$y" ]` `if [ "$x" -lt "$y" ]` `if [ "$x" -gt "$y" ]` |
| Décrémenter / incrémenter une variable          | `((compteur--)) / ((compteur++))`                                                     |
| Afficher une valeur ou un message               | `echo "message"`                                                     |
| Boucle while (répéter tant que condition vraie) | `while [ condition ]; do ... done`                                   |
| Quitter une fonction ou un script               | `return` ou `exit 0`                                                 |
| Initialiser une variable                        | `var=0`                                                              |
| Test logique inverse                            | `! condition`                                                        |

