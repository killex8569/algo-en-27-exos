## Consignes

**Niveau** : complexe
**Internet autorisé** : oui
**Langage** : Bash
## Enoncé

- écrire un script bash qui permet de copier votre dossier /home/\[nom_user] dans une archive
- demander à l'utilisateur :
	- le nom de l'archive
	- l'extention de l'archive (.zip ou .tar.gz, attention, ce n'est pas la même commande de compression)
- l'archive sera créée dans le dossier /backup (le créer s'il n'existe pas déjà)
- le nom complet de l'archive sera \[nom entré par l'utilisateur]-\[date du jour]
- afficher à la fin du programme un message comme quoi tout s'est bien passé
- s'il y a une erreur, afficher un message d'erreur et quitter le programme
- attention : bien vérifier si une archive du même \[nom]-\[date] existe déjà !
