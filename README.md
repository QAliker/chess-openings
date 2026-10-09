# Roulette des ouvertures

Tire au sort une ouverture (Blancs) ou une défense (Noirs) aux échecs, affiche la ligne principale et te la fait rejouer coup par coup.

- **Tirer une ouverture** : une ouverture au hasard parmi 25, filtrable par couleur.
- **Lecture** : ◀ ▶ ou flèches du clavier pour parcourir la ligne.
- **S'entraîner** : l'app joue l'adversaire, tu joues tes coups ; indice après une erreur, réponse après deux.

## Lancer

Un seul fichier, pas de build : ouvre `index.html` dans un navigateur.

## GitHub Pages

Settings → Pages → Source : branche `main`, dossier `/ (root)`. L'app sera sur `https://<user>.github.io/<repo>/`.

## Ajouter une ouverture

Ajoute une entrée au tableau `OPENINGS` dans `index.html` (`side: "w"` pour une ouverture des Blancs, `"b"` pour une défense des Noirs ; ligne en notation SAN anglaise séparée par des espaces).

Dépendance : [chess.js](https://github.com/jhlywa/chess.js) 0.10.3 via cdnjs.
