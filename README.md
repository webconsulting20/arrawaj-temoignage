# Fondation Arrawaj — Carte interactive des témoignages

One-page autonome (HTML unique). Toutes les images (logo, photos clients, miniatures vidéo)
sont intégrées dans `index.html` — aucun fichier externe nécessaire.

## Déploiement

Site statique : héberger `index.html` à la racine suffit.

- **Vercel** : import du repo → framework preset « Other » → Deploy.
- Mise à jour : modifier `index.html`, puis `git commit` + `git push` (redéploiement automatique).

## Dépendances externes (chargées en ligne)

- Fond de carte : Leaflet + CARTO
- Polices : Google Fonts
- Lecture des vidéos : YouTube

La lecture vidéo importée par formulaire est locale à la session (démo, non persistée).
