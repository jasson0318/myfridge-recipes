# MyFridge Recipes (GitHub Pages export)

Static catalog generated from the MyFridge Website DB.

- Base URL: `https://jasson0318.github.io/myfridge-recipes`
- Manifest: `https://jasson0318.github.io/myfridge-recipes/recipes/index.json`
- Recipe detail: `https://jasson0318.github.io/myfridge-recipes/recipes/{recipeId}/recipe.json`
- Viewer: `https://jasson0318.github.io/myfridge-recipes/recipes/{recipeId}/`

Regenerate from the Website project:

```bash
cd website
python scripts/export_github_pages.py
```

This folder is a publishable static snapshot. It does not include
Flutter sources, Admin secrets, or the SQLite development database.
