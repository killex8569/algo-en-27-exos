## Consignes

**Niveau** : Moyen
**Internet autorisé** : non
**Langage** : C 

_Rappel : vous pouvez regarder sur internet comment lancer votre programme en fonction de vos outils (Windows/Linux, VS Code...)_

## Énoncé

- L’objectif de votre programme est de **recréer le jeu du Craps**, un jeu de dés populaire dans les casinos.  
- Le jeu utilise **deux dés à six faces**.  
- Le joueur lance les dés et la somme des deux valeurs détermine la suite de la partie (--> Voir les règles).

### Règles

1. **Premier lancer (Come Out Roll)** :
   - Si la somme des dés est **7 ou 11**, le joueur **gagne** immédiatement.  
   - Si la somme est **2, 3 ou 12**, le joueur **perd** immédiatement.  
   - Sinon, la somme devient le **Point** du joueur.

2. **Phase du Point** :
   - Le joueur relance les dés jusqu’à :
     - refaire la valeur du **Point** → il **gagne**,  
     - ou faire **7** → il **perd**.

3. Le programme doit :
   - Afficher chaque lancer et sa somme.  
   - Indiquer clairement si le joueur gagne ou perd.  
   - Permettre de **relancer une partie** sans relancer le programme.  

---

### Éléments optionnels

- Ajouter un **système de mise** : le joueur parie une somme et son solde évolue selon les résultats.  
- Afficher un **historique des parties** (victoires/défaites).  
- Gérer une **interface textuelle** plus claire (séparateurs, pauses entre les tours, etc.).  
- Intégrer une **fonction de hasard** avec `rand()` et `srand(time(NULL))` pour simuler les dés.  
