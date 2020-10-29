# TP Git

Nous allons composer des équipes de 3 personnes. L'objectif est de réaliser une petite page HTML / CSS et JS.

On a 3 parties importantes sur la page :

- Header (Menu avec logo)
- Un contenu (Deux colonnes avec une image et un texte)
- Footer (Fond de couleur avec un texte copyright)

Chaque groupe aura UN SEUL dépôt Github. Deux solutions se présentent pour créer ce dépôt :

- Soit une personne prend la responsabilité de créer le dépôt sur son compte Github.
- Soit une personne fait un fork du dépôt du formateur.

Le créateur devra créer un fichier HTML avec un DOCTYPE et un body vide, un fichier CSS vide et un fichier JS liés à la page HTML.

Ensuite, les deux autres personnes vont devoir être ajoutées sur le dépôt du "créateur".

Une fois que les personnes ont accès au dépôt sur Github, elles vont devoir "cloner" le dépôt :

```
cd Code
git clone https://github.com/cda-cambrai/tp-git.git
```

A cette étape, tous les membres ont le projet en commun sur leur machine.

Chaque membre va créer sa branche (header, footer ou content) puis va la pousser sur Github.

Ensuite chacun va faire son travail, committer et push sur sa branche.

A la fin du projet, quand tout le monde a finit, chacun va créer une Pull Request avec sa branche et va la "merger" dans master.
