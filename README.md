# Collectif JABS — site statique

Copie statique de https://collectif-jabs.fr, réalisée le 25 octobre 2026 à partir du site PHP/MySQL d'origine.

- 100 % HTML/CSS : aucune page PHP, aucune base de données.
- La barre de navigation est intégrée dans chaque page (plus de chargement par `fetch`).
- Le manifeste est figé : 268 signataires, liste complète dans `signataires.html`, formulaire de signature retiré.
- La liste des analyses (`articles/index.php`) est devenue `articles/index.html`.
- Les vidéos YouTube restent intégrées depuis YouTube ; les deux vidéos hébergées sur le site sont dans `videos/`.
- Tous les liens internes sont relatifs : le site fonctionne en local (double-clic sur `index.html`) comme sur GitHub Pages.

## Mise en ligne sur GitHub Pages

1. Créer un dépôt et y pousser le contenu de ce dossier.
2. Dans le dépôt : Settings > Pages > Source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Pour garder le domaine collectif-jabs.fr : renseigner le domaine dans Settings > Pages > Custom domain
   (GitHub crée le fichier `CNAME`), puis faire pointer le DNS du domaine vers GitHub Pages.
# jabs
