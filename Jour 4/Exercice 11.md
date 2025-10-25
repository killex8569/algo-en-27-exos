## Consignes

**Niveau** : Moyen
**Internet autorisé** : non
**Langage** : Bash

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_
## Enoncé

- Vous allez devoirs refaire le jeu du juste prix.
    - Créer une fonction `juste_prix`, elle devra effectuer les actions suivantes :
        - L'ordinateur choisi en nombre entre 0 et 1000 et l'initialise dans une variable.
        - On demande à l'utilisateur de renseigner un nombre.
        - Dans le cas ou ils sont égaux, le programme s'arrête et affiche le nombre.
        - Le programme indique au joueur si sont nombre est plus petit ou plus grand que le nombre de l'ordi
        - A chaque réponse donnée par l'utilisateur, un compteur initialiser à 10 se décrémente et arriver à 0, le joueur à perdu.


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

