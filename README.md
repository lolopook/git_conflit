### Procédure pour causer un conflit de fusion

Étapes à suivre, une par une:

- Créer un nouveau dépôt sur Github
- Cloner ce dépôt localement avec git clone
- Dans le répertoire local, créer un fichier README.md contenant les paroles d’une chanson de votre choix
- Créer un commit initial sur la banche master et l’envoyer; avec git add, git commit puis git push
- Créer une branche branche1 à partir de master, avec git checkout -b
- Dans le README.md de cette branche, modifier à votre guise la première phrase des paroles, créer un commit, puis envoyer les modifications de cette branche sur github
- Revenir à la branche master avec git checkout
- Créer une branche branche2 à partir de master (comme dans l’étape précédente)
- Dans le README.md de cette branche, modifier également la première phrase des paroles avec un texte différent de celui saisi à l’étape 6, créer un commit, puis envoyer les modifications de cette branche sur GitLab
- Revenir à la branche master
- Fusionner branche1 dans master, avec git merge
- Fusionner branche2 dans master

# c'est sympa le markdown

**il est utilisé avec discord, notion etc ...**

### trois ### c'est un titre de niveau 3 avec `###`
