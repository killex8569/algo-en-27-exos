## Consignes

**Niveau** : moyen
**Internet autorisé** : non
**Langage** : Bash

## Enoncé

- Déclarer la fonction `lire_tableau` qui à pour paramètre `tab` qui est un tableau de **nombres entiers**.
- Dans cette fonction :
    - A l'aide d'une boucle `for`, afficher chaque élément du tableau (chaque élément à l'index i, i allant de 1 jusqu'à la longueur du tableau - 1)
- Dans le programme principal, initialiser le tableau "valeurs" avec 5 valeurs (nombre entiers, n'importe lesquels).
- Appeler la fonction `lire_tableau` avec la variable "valeurs".

## Documentation
| Instruction                                                   | Code                                |
| ------------------------------------------------------------- | ----------------------------------- |
| initialiser une fonction avec pour paramètre x                | `function name_func(x) { ... }`     |
| boucle for "pour i allant de 1 jusqu'à x"                     | `for i in $(seq 1 $x); do ... done` |
| récupérer la valeur contenu dans le tableau "tab" à l'index i | `x=${tab[i]}` `tab[i]=5`            |
| afficher une valeur                                           | `echo $var` `echo "message"`        |
| récupérer le nombre d'élément de la liste "tab"               | `${#tab[@]}`                        |
| créer un tableau                                              | `tab=(1 2 3 4)`                     |
| appeler une fonction                                          | `func arg1 arg2`                    |
**Remarques** :
- la commande "seq x y" en bash renvoie une liste de nombres allant de x à y <u>inclus</u>
- comme dans un tableau, les index commencent à 0, le dernier élément d'une liste est à l'index "longueur de la liste" - 1 : \[4, 22, 13, 9] -> il y a 4 éléments, 9 est à l'index 3
- en bash, `#` renvoie le nombre d'éléments que contient une variable (string ou tableau). `tab[@]` permet de sélectionner tous les éléments du tableau `tab`.