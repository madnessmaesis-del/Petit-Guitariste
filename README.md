# Petit Guitariste avec Jean-Claude

Application React/Vite statique, sans compte, sans API et sans serveur applicatif.

## Test local

```bash
npm install
npm run dev
```

## Publication GitHub Pages

1. Créer un dépôt GitHub vide.
2. Envoyer tout le contenu de ce dossier à la racine du dépôt.
3. Dans GitHub : Settings > Pages > Source > GitHub Actions.
4. Faire un push sur la branche `main`.
5. Le workflow `.github/workflows/deploy.yml` construit et publie automatiquement le site.

La configuration `base: './'` permet de publier le projet dans un dépôt GitHub Pages sans devoir modifier le nom du dépôt.
