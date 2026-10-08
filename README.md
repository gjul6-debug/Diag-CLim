# Diag Monosplit — appli iPhone (web installable)

## Mise en ligne (GitHub Pages, gratuit)
1. Créer un dépôt GitHub, par ex. `diag-clim`.
2. Y déposer TOUT le contenu de ce dossier (index.html, manifest.webmanifest, sw.js, dossier icons).
3. Settings → Pages → Source : branche `main`, dossier `/ (root)` → Save.
4. L'adresse est du type `https://<ton-compte>.github.io/diag-clim/`.

## Installation sur iPhone
1. Ouvrir l'adresse dans **Safari**.
2. Bouton Partager → **Sur l'écran d'accueil** → Ajouter.
3. L'icône « Diag Clim » apparaît : l'appli s'ouvre en plein écran, sans barre Safari.
4. Après une première ouverture avec réseau, elle fonctionne **hors ligne**.

## Mise à jour
Remplacer `index.html` dans le dépôt et changer `VERSION` dans `sw.js` (ex. `diag-monosplit-v2`).
L'iPhone récupère la nouvelle version à l'ouverture suivante (parfois la 2e).

## À savoir
- Les données saisies restent sur le téléphone (aucun serveur, aucun compte).
- Un dépôt GitHub Pages public est visible par n'importe qui ayant l'adresse : ne pas y mettre de données client.
