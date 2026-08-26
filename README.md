# atelier-ceramique

Site WordPress pour l'organisatrice d'atelier de céramique (stages, travaux, inscriptions).
Nom de domaine à définir.

## Développement local
Environnement WordPress local à mettre en place (DDEV).
Seuls le thème et les plugins custom sont versionnés ici — jamais wp-content/uploads ni la base de données.

## Déploiement
Push sur `main` → GitHub Actions rsync du thème/plugins vers le VPS OVH.
Le contenu (stages, articles, inscriptions) est géré directement via wp-admin en production.
