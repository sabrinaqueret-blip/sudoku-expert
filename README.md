# Sudoku Expert

Sudoku en quatre niveaux (facile, moyen, difficile, expert), installable sur téléphone (PWA) et jouable hors ligne.

- Grilles générées à solution unique : de 40 cases données (facile) à 24-26 (expert)
- Bouton « Terminer » quand il reste 6 cases ou moins et que la fin se déduit sans aucun choix
- Indices progressifs : la zone à regarder, puis la case et la raison, puis le chiffre
- Notes au crayon, annulation, chronomètre, compteur d'erreurs
- Partie sauvegardée automatiquement dans le navigateur

## Installer sur téléphone

Ouvrir l'adresse GitHub Pages du dépôt dans le navigateur :

- **iPhone (Safari)** : Partager, puis « Sur l'écran d'accueil »
- **Android (Chrome)** : menu, puis « Installer l'application »

## Mettre en ligne (GitHub Pages)

Settings, Pages, Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
L'adresse sera `https://<pseudo>.github.io/sudoku-expert/`.

## Fichiers

- `index.html` : le jeu (HTML, CSS et JavaScript, sans dépendance)
- `manifest.webmanifest` : nom, icônes et affichage plein écran
- `sw.js` : cache pour le mode hors ligne (changer `CACHE` pour forcer une mise à jour)
- `icons/` : icônes de l'application
