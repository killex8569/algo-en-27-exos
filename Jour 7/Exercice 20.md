## Consignes

**Niveau** : Moyen
**Internet autorisé** : non
**Langage** : Bash

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Enoncé

Remake du script linux vu lors du controle : 

- Vous devez écrire un script nommé `travail_recent` qui prend en arguments et dans cet ordre :
    - Un nom de fichier
    - Un ou plusieurs noms de dossiers
- Le script devra avoir les fonctionnalités suivantes : 
    - Donner le nombre de fichiers modifiés récemment (avec l'aide de cette commande : `find /chemin/vers/dossier -type f -mtime -7`)
    - Il écrira dans un fichier nommée : `result.txt` 
    - Si le fichier de sortie existe, alors il sera rempalcer
    - Si l'un des noms / repertoire de dossier est invalide, le programme passe à la suite et affiche juste un message d'erreur.
    - Une fois que tous le processus principal est fini, le script nous dit qu'elle est le dossier qui contient le plus de fichier récents.


## Exemple de résultat

./travail_recent comptage.txt *dossier1* *dossier2* *dossierN* *dossierN+1*
cat comptage.txt

*dossier1* : 5
*dossier2* : 7
*dossierN* : X
*dossierN+1* : Y

...

## Documentation

| Instruction                                               | Code                                   |
| --------------------------------------------------------- | -------------------------------------- |
| Vérifier l’existence d’un dossier                         | `if [ -d "$rep" ]; then ... fi`        |
| Trouver les fichiers modifiés récemment (<7 jours)        | `find "$rep" -type f -mtime -7`        |
| Compter le nombre de fichiers                             | `find "$rep" -type f -mtime -7 | wc -l`|
| Rediriger la sortie dans un fichier (remplace le contenu) | `> result.txt`                         |
| Ajouter du texte à la fin d’un fichier                    | `>> result.txt`                        |
| Afficher un message d’erreur                              | `echo "Erreur : dossier invalide" >&2` |
| Comparer deux valeurs entières                            | `if [ "$a" -gt "$b" ]; then ... fi`    |
| Parcourir tous les arguments sauf le premier              | `for rep in "${@:2}"; do ... done`     |
| Rechercher du texte dans un fichier                       | `grep "mot" fichier`                   |
