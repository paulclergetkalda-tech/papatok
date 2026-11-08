# PapaTok

Un mini TikTok d'anniversaire : une intro qui défile, une platine à vinyle, puis 20 vidéos avec une pochette et une musique par souvenir.

Site statique, aucun build. Déploiement sur Vercel : importer ce dépôt, preset « Other », laisser le dossier racine par défaut.

## Contenu

- `index.html` : toute la page (styles, scripts et textes).
- `assets/img/` : une pochette par chanson (`NN.jpg`, le numéro suit l'ordre des vidéos).
- `assets/audio/` : un morceau par vidéo (`NN-nom.mp4`, audio AAC).
- `assets/video/` : la vidéo de fin.

## Modifier les textes

Les textes, titres et le point de départ de chaque musique sont dans le bloc `<script id="state" type="application/json">` de `index.html`.
Le champ `st` est la seconde à laquelle la chanson démarre, `intro` est le texte qui défile au début.

## Attention

Le dépôt contient des morceaux de musique protégés. Garde-le **privé** et ne le partage qu'avec ta famille.
