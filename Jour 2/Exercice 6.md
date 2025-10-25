## Consignes

**Niveau** : Complexe
**Internet autorisé** : oui
**Langage** : Python

## Enoncé

- créer la fonction `encrypt` qui prend en paramètre "txt_clair" qui est une chaîne de caractère
- dans cette fonction :
	- créer la variable "final_msg" qui sera une chaîne de caractère
	- parcourir la chaîne de caractère "txt_clair" :
		- si le caractère est la lettre "a", ajouter la lettre "F" à "final_msg"
		- sinon, récupérer le code ascii du caractère, convertir ce nombre en chaîne de caractère pour ensuite l'ajouter à "final_msg"
	- renvoyer "final_msg"
- afficher le résultat de la fonction `encrypt` avec "a l attaque"

## Exemple de résultat

`encrypt("a l attaque")` -> "F3210832F116116F113117101"

## Recherches sur internet

Vous devrez notamment rechercher :
- récupérer le code ascii d'un caractère en python
- convertir un nombre en chaîne de caractère en python