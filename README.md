# Barrage pour Instagram : site de présentation

Page statique (GitHub Pages) qui présente l'extension Firefox *Barrage pour Instagram* : fonctionnement, installation, vie privée, limites,
et téléchargement.

Ce dépôt ne contient que le site. Il ne contient **aucune liste de comptes** : l'extension est un outil neutre, chacun importe la sienne.

## Publier
1. Après chaque signature par Mozilla, copier le `.xpi` signé ici sous le nom `barrage.xpi` et mettre à jour la constante `VERSION`
   en bas de `index.html`. Tant que `barrage.xpi` est absent, le bouton de téléchargement est désactivé.
2. GitHub : *Settings → Pages → Build and deployment* : **Deploy from a branch**, branche `main`, dossier **/ (root)**.
