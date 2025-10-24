## Consignes

**Niveau** : Complexe
**Internet autorisé** : oui
**Langage** : Python

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_
## Enoncé

- créer la fonction `encrypt` qui prend en paramètre "txt_clair" qui est une chaine de caractère
- dans cette fonction :
	- créer la variable "final_msg" qui sera une chaine de caractère
	- parcourir la chaine de caractère "txt_clair" :
		- si le caractère est la lettre "a", ajouter la lettre "F" à "final_msg"
		- sinon, récupérer le code ascii du caractère, convertir ce nombre en chaine de caractère pour ensuite l'ajouter à "final_msg"
	- renvoyer "final_msg"
- afficher le résultat de la fonction `encrypt` avec "a l attaque"
## Exemple de résultat

`encrypt("a l attaque")` -> "F3210832F116116F113117101"

## Recherches sur internet

Vous devrez notamment rechercher :
- récupérer le code ascii d'un caractère en python
- convertir un nombre en chaine de caractère en python