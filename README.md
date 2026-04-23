# webpages

Pages web statiques destinées à être indexées via GitHub Pages.

## Structure

```
.
├── index.html          # Page d'accueil (liste des pages)
├── robots.txt          # Autorise l'indexation
├── sitemap.xml         # Liste des URLs pour les moteurs de recherche
└── pages/              # Une page = un dossier avec son index.html
    └── exemple/
        └── index.html
```

## Ajouter une nouvelle page

1. Créer un dossier `pages/<slug>/`
2. Y placer un `index.html`
3. Ajouter l'URL dans `sitemap.xml`
4. (Optionnel) L'ajouter à la liste dans `index.html`

## Activer GitHub Pages

Settings → Pages → Source : `Deploy from a branch` → Branch : `main` / `/ (root)` → Save.

URL publique : https://orbitaloop.github.io/webpages/

## Indexation

- `robots.txt` autorise tous les crawlers
- `sitemap.xml` liste les URLs à indexer
- Soumettre le sitemap à [Google Search Console](https://search.google.com/search-console)
