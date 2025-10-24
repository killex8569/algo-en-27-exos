## Consignes

**Niveau** : Complexe
**Internet autorisé** : non
**Langage** : Bash

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_
## Enoncé


- Votre script devras inclure plusieurs paramètres de la valeur de votre choix (pas de nombre de paramètres définis, 2 minimum, pas de maximum).
- Initialiser un tableau `tab` qui est vide pour le moment
- Votre script devra :
    - Créer un fichier `result.txt` si il n'existe pas déjà.
    - Le programme utilise les paramètres pour trouver le minimum, la maximum et calculer la moyenne et l'affecteras dans cet ordre au variables : `min`, `moy`, `max`.
    - Ajouter dans un tableau en Bash `tab` en premier la valeur minimum, puis la valeur moyenne et enfin la valeur max en dernière position.
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

--> Initialisation de paramètres en bash ($1 à $n)

--> Boucle for en bash

--> condition if et elif en bash

--> Peut-être réexpliquer avec du pseudo code ou expliquation comment faire pour trouver le min et le max 

--> Ajouter valeur à tableau en bash (juste en dessous, je te laisse faire le tri etc...)


### Déclaration d'un tableau vide
Tableau=()

### Ajouter des valeurs au tableau

Tableau+=("Linux")
Tableau+=("Windows")
Tableau+=("MacOS")

