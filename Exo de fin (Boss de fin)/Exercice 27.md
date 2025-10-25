## Consignes

**Niveau** : Complexe
**Internet autorisé** : Oui
**Langage** : C

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

- L'objectifs de votre script est de recréer le jeu du pendu, avec les règles suivantes :

    - Vous allez devoirs créer un tableau avec plusieurs mots (dans l'idéal plus de 10 mots), puis en séléctionner un aléatoirement
    - L'utilisateur ne peut rentrée uniquement qu'une seul lettre à chaque tentative.
    - L'utilisateur possède une barre de vie = 10.
    - Le programme devras lors du début de partie, affiche "_" du mots et un espace dans le cas d'un mot composer, les espaces sont les seuls caractères à ne pas compter dans les lettres.
    - A chaque fois que l'utilisateur renseigne une tentative, on regarde si la lettre est présente dans le mot :
        - Dans le cas ou la lettre est présente, on l'affiche (une ou plusieurs fois) et le joueur ne perd pas de vie.
        - Dans le cas ou la lettre n'est pas présente dans le mot, le joueurs perd un à sa vie
    - A la fin des 10 vies, le programme renvoie.

Éléments optionelles : 

- Pour les plus expérimenté, vous pouvez intégrer les éléments suivants :
    - A chaque fois que le joueur devine une mauvaise lettre, la lettre est ajouter dans une variable qui sera print à chaque proposition pour montrer les lettres déjà invalidées.



## Exemple de résultat

