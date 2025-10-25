## Consignes

**Niveau** : Complexe  
**Internet autorisé** : oui  
**Langage** : C

## Énoncé

- Écrire l'algorithme suivant :  
	- La variable `code` contient le code suivant : "var x 3 ; var y 4"  
	- La variable `mem` est une chaîne de caractères permettant de stocker les variables sous le format suivant : "nom_var1 3;nom_var2 5" (bien respecter les espaces comme ici)  
	- Isoler les deux instructions de `code` (via le délimiteur ' ; ' avec un espace de chaque côté)  
	- Pour chaque instruction, séparer les mots (prendre l'espace en guise de délimiteur)  
	- Interpréter les instructions :  
		- Si le premier mot-clé est 'var', ajouter à la variable `mem` "\[nom_variable] \[valeur_variable];" respectivement à la position 1 et 2 de l'instruction


## Recherches sur internet

Vous devrez notamment rechercher :
- Comment faire un 'split' en C
- Comment concaténer deux chaines de caractères en C