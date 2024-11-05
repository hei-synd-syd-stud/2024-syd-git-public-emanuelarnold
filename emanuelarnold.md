# Answers of Emanuel Arnold emanuelarnold

## Basics
### Task 1
On y retrouve le fichier .git ainsi que le contenu du répertoire que l'on a cloné. 
Le fichier .git permet de faire du versionning de ce fichier, il contient donc des informations
sur les modifications qui ont pu être effectuée auparavant.
### Task 2
Dans le git status, on a supprimé le fichier answers.md pour rajouter le fichier emanuelarnold.md ainsi que 
le fichier README.md. Ils sont notés untracked.
Dans le git -oneline on nous dit que on se trouve sur l'origine ainsi que sur le commit initial.
### Task 3
Les fichiers modifiés sont maintenant passés sur "changes to be committed". 
### Task 4
On peut voir que le fichier README.md a été modifié sous "Changes not staged for commit:" et 
qu'il est également sous "Changes to be committed:" en tant que new file.

### Task 5
La chaîne de caractère au début indique le numéro du commit Hash. C'est l'identifiant unique du commit.
Main est la branche sur laquelle on se trouve et head indique le dernier commit de la branche en cours de vérification. 
Dans notre cas, c'est le commit qui vient d'être effectué.
Après les parenthèses, on retrouve le message du commit.
### Task 6
En faisant un checkout sur le commit initial, le contenu du répertoir est revenu au contenu du début de labo où rien n'a été modifié.
Lorsque le checkout est refait sur le dernier commit, on a récupéré tous les fichiers grâce au fait que le repo git sauvegarde les modifications
et on peut donc revenir sur la version la plus récente du répertoir.
## Gitgraph

### Task 7
![Gitgraph](img/gitgraph.svg)

1: Nom de la branche sur laquelle on travaille.
2: short hash du commit.
3: Message du commit.
4: Auteur du commit.
5: Version du main V1.0.0 sur laquelle on travaille.
6: Position du commit le plus avancé de la branche.
7: Branche crée a partir du main par CodeQueenCarol pour ajouter des features. Est ensuite mergé dans la branche développement
8: Dernière version du main qui est push.
9: Branche développement parallèle au main. Les modifications importantes sont faites sur cette branche puis mergées sur le main.
10: Commit initial du main. = version 0 du projet.