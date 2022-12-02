# Tutoriel pour créer & gérer un dépôt GIT

- Créer un dépôt sur GITHub dans l'organisation ESIPE-INFO

### Pour windows
 - Vous pouvez installer GIT UI (https://git-scm.com/downloads)
 - Clique droit dans un répertoire -> "Git Bash Here"
 

##### Cloner un dépot
Pour importer un dépôt sur un votre ordinagteur en local
``` git clone git@github.com:INFO-ESIPE/tuto_creer_depot.git```
Après cette commande, le dépôt GIT est copié sur votre machine dans votre répertoire.

##### Modifier un dépot
Une fois que vos fichiers/répertoires modifiés sur votre machine, vous pouvez voir avec la commande ci-dessous quels fichiers ont été modifiés.
``` git status ```
Pour mettre à jour le dépôt GIT, il vous faut faire un PUSH.
Un PUSH est composé de commit (de modifications.
Pour ajouter ou modifier des fichiers sur un commit, utiliser la commande suivante :
```git add ./monfichier.txt```

Vous pouvez refaire un <git status> pour vérifier que le fichier a été ajouté au prochain commit.
Pour faire un commit, il faut utiliser cette commande et ajouter un commentaire avec -m.
```git commit -m "Ajout du fichier monfichier.txt```

Une fois vos commit fait, puis mettre à jour le dépôt sur github, utilisez la commande
```git push ```

