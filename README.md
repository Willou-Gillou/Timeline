# Macro Planning — Timeline

Outil de macro planning (phases, tâches, jalons, vue Gantt, export PNG), basé sur
[`willoudev/macroplanning-test`](https://github.com/willoudev/macroplanning-test) (v4.2.0).

## Développement

Aucune étape de build : `index.html` est la page complète, autonome.

```
python3 -m http.server 8000
```

## Déploiement

Déployé automatiquement sur GitHub Pages via `.github/workflows/pages.yml` à chaque push sur `main`.

Pour activer GitHub Pages (une seule fois) :
**Settings → Pages → Build and deployment → Source : GitHub Actions**
