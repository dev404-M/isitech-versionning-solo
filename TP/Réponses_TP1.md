### TP 1: Introduction et Bases de Git
- **Tâche 1 :** Cloner le dépot
![Alt text](clone.png)

- **Tâche 2 :** Analyse des commits

![Alt text](screen_git_log.png)
- **Tâche 3 :** Modification du README

![Alt text](readme_edit.png)

![Alt text](commit.png)

### TP 2: Bonnes Pratiques de Codage
- **Tâche 1 :** Analyser les commits :<br>
Les commits sont clairs et présentent tous la mention d'une action (add, remove, update, fix, merge)
- **Tâche 2 :** Identifier des exemples de bonnes pratiques de codage dans le code source : <br>
?

### TP 3: Utilisation Avancée de Git
- **Tâche 1 :** Créer des branches pour des fonctionnalités hypothétiques, fusionner ces branches. <br>
J' ai créé 2 branches (header, footer) et chacune d'elle contenait un document texte.
J'ai merge header sur footer, maintenant header contient le document texte de footer en plus.

![Alt text](textfile.png)

- **Tâche 2 :** Simuler un conflit de merge et le résoudre. <br>
J'ai créé un fichier text3.txt dans les branches header et footer avec un contenu différent

![Alt text](addtextfile.png)

Lors du commit il y a une erreur dûe à un conflit

![Alt text](fixconflict.png)

Dans l'IDE, l'éditeur de conflit apparaît et invite à prendre une décision

![Alt text](conflict.png)

En choisissant l'option voulue, on confirme le merge puis on commit : le conflit est résolu.

### TP 4: Revue de Code et Collaboration
- **Tâche 1 :** Examiner les pull requests ouvertes et fermées pour comprendre comment la revue de code est gérée.
