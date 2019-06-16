# Dépôt principal

Ce dépôt, écrit en *mkdocs*, est déployé à l'URL [https://gaetan-varlet.github.io/](https://gaetan-varlet.github.io/).

Il faut se placer dans le projet **gaetan-varlet.github.io** et exécuter la commande suivante :
`mkdocs gh-deploy --config-file ../sommaire/mkdocs.yml --remote-branch master`. Cela va récupérer le code source du projet *sommaire*, le builder et déposer le contenu du build dans la branche master du projet *gaetan-varlet.github.io* qui sera accessible à l'URL cité ci-dessus.