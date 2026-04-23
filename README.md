# webpages

Pages web statiques destinées à être indexées par les moteurs de recherche.

## URL publique

Une fois GitHub Pages activé : **https://orbitaloop.github.io/webpages/**

## Structure

```
/
├── index.html          # Page d'accueil (liste les pages publiées)
├── robots.txt          # Autorise l'indexation
├── sitemap.xml         # Liste des pages pour les moteurs de recherche
├── _config.yml         # Configuration Jekyll (GitHub Pages)
└── pages/              # Tes pages individuelles
    └── exemple.html
```

## Activer GitHub Pages

1. Va dans **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : **main** / **/ (root)**
4. Sauvegarde — l'URL sera disponible en quelques minutes

## Ajouter une nouvelle page

1. Crée un fichier `.html` dans `pages/`
2. Ajoute son URL dans `sitemap.xml`
3. Commit & push — la page sera en ligne automatiquement

## Soumettre à Google

Pour accélérer l'indexation :
- [Google Search Console](https://search.google.com/search-console) → ajouter la propriété `https://orbitaloop.github.io/webpages/`
- Soumettre le sitemap : `https://orbitaloop.github.io/webpages/sitemap.xml`
