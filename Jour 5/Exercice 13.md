## Consignes

**Niveau** : Simple  
**Internet autorisé** : oui  
**Langage** : Bash

_Rappel : vous pouvez regarder sur Internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Énoncé

- Créer un script qui prend en paramètre un fichier de sortie et un fichier d'entrée (`./script.sh sortie.txt entree.txt`).  
- Ce script vérifie d'abord si le fichier d'entrée est vide : s'il l'est, on renvoie une erreur, sinon on continue l'exécution.  
- Si le fichier de sortie n'existe pas, on le crée.  
- On ajoute à la fin du fichier de sortie les informations suivantes :  
	- Le nom du fichier d'entrée  
	- Sa taille  
	- Son chemin d'accès  
	- Le nombre de lignes qu'il contient  
	- Le nombre de caractères qu'il contient  
- Toutes ces informations doivent être sur une seule ligne du fichier de sortie (on pourra séparer les informations par un espace ou un point-virgule ';').


## Recherches sur internet

Vous devrez notamment rechercher :
- Vérifier qu'un fichier est vide en Bash
- Vérifier qu'un fichier existe en Bash
- Comment ajouter du texte à la fin d'un fichier