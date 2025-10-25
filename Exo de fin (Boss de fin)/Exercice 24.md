## Consignes

**Niveau** : Complexe
**Internet autorisé** : Oui
**Langage** : Bash

## Enoncé

Backup incrémental en bash

- Créer un script qui analyse un dossier et vérifie si certains éléments sont absents ou non à jour.  
  Si des fichiers sont manquants ou modifiés, le script doit créer une sauvegarde de ces fichiers :  
    - Sauvegarder les fichiers dans un nouveau dossier nommé **[nom_du_dossier]-[date]-[nb_fichiers_sauvegardés]**.
    - À chaque exécution du script, le programme vérifie le nombre de sauvegardes présentes. Si plus de 10 sauvegardes sont détectées, il supprime la plus ancienne en se basant sur la date de création.

