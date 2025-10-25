## Consignes

**Niveau** : simple
**Internet autorisé** : oui
**Langage** : Bash

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_
## Enoncé

- créer un script qui prend en paramètre un fichier de sortie et un fichier d'entrée (`./script.sh sortie.txt entree.txt`)
- ce script vérifie d'abord si le fichier d'entrée est vide : s'il est on renvoie une erreur, sinon on continue l'execution
- si le fichier de sortie n'existe pas, on le crée
- on ajoute à la fin du fichier de sortie les informations suivante :
	- le nom du fichier d'entrée
	- sa taille
	- son chemin d'accès
	- le nombre de lignes qu'il contient
	- le nombre de caractères qu'il contient
- toutes ces informations doivent être sur une seule ligne du fichier de sortie (on pourra séparer les informations par un espace ou un point-virgule ';')

## Recherches sur internet

Vous devrez notamment rechercher :
- vérifier qu'un fichier est vide en Bash
- vérifier qu'un fichier existe en Bash
- comment ajouter du texte à la fin d'un fichier