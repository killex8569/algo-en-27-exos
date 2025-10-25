## Consignes

**Niveau** : complexe
**Internet autorisé** : oui
**Langage** : Bash

## Enoncé

- Écrire un script bash qui permet de copier votre dossier /home/\[nom_user] dans une archive
- Demander à l'utilisateur :
	- Le nom de l'archive
	- L'extention de l'archive (.zip ou .tar.gz, attention, ce n'est pas la même commande de compression)
- L'archive sera créée dans le dossier /backup (le créer s'il n'existe pas déjà)
- Le nom complet de l'archive sera \[nom entré par l'utilisateur]-\[date du jour]
- Afficher à la fin du programme un message comme quoi tout s'est bien passé
- S'il y a une erreur, afficher un message d'erreur et quitter le programme
- Attention : bien vérifier si une archive du même \[nom]-\[date] existe déjà !
