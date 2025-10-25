## Consignes

**Niveau** : Complexe  
**Internet autorisé** : non  
**Langage** : Bash

## Énoncé

- Le script prend en compte deux paramètres numériques minimum : `./script nb1 nb2 nb3...`  
- Vérifier si le nombre de paramètres est inférieur à 2, renvoyer un message d'erreur si c'est le cas et quitter le script  
- Le script doit :  
    - Créer un fichier `result.txt` s'il n'existe pas déjà.  
    - À l'aide d'une boucle `for` qui parcourt la liste des paramètres, trouver le minimum, la moyenne et le maximum des paramètres du programme. Les affecter dans cet ordre aux variables : `min`, `moy`, `max`.  
    - Ajouter dans le résultat de `tab` dans le fichier `result.txt`.


## Exemple de resultat

Paramètres donner: 10, 13, 8, 3, 16 et 18

min = 3
moy = 11.3
max = 18

tab = 3, 11.3 ,18

résultat dans le : result.txt
3, 11.8, 18

## Documentation
| Instruction                                       | Code                                     |
| ------------------------------------------------- | ---------------------------------------- |
| initialiser une variable                          | `var=5`                                  |
| récupérer les paramètre d'une commande            | `$1 $2 $3...`                            |
| boucle for "pour i allant de 1 jusqu'à x"         | `for i in $(seq 1 $x); do ... done`      |
| input utilisateur dans la variable "var"          | `read -p "entrez valeur : " var`         |
| afficher une valeur                               | `echo $var` `echo "message"`             |
| vérifier si x est inférieure à y                  | `[[ $x < $y ]]`                          |
| condition if                                      | `if ... ;then ... elif ... ;then ... fi` |
| créer un fichier                                  | `touch file.txt`                         |
| récupérer le nombre de paramètres d'un script     | `$#`                                     |
| récupérer la liste des paramètres d'un script     | `$@`                                     |
| quitter le script (0 : tout va bien ; 1 : erreur) | `exit 0` `exit 1`                        |
**Remarque** :
- trouver le minimum (ou maximum) dans un tableau :
	- on initialise une variable `min` (ou `max`) à la valeur de la première valeur du tableau
	- on parcours le tableau à partir de la deuxième valeur :
		- si on trouve une valeur inférieure (ou supérieure), `min` (ou `max`) prend cette valeur
	- une fois le tableau parcouru, on est sûr d'avoir la valeur minimale (ou maximale)
- calculer une moyenne : total/nb_valeurs
