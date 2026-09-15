# Kawari — site web

Landing page statique pour Kawari (HTML/CSS/JS vanilla, sans build step).

## Publication via GitHub Pages

1. Pousser ce dépôt sur GitHub.
2. Aller dans **Settings > Pages**.
3. **Source** : sélectionner la branche principale (`main`), dossier `/ (root)`.
4. **Custom domain** : renseigner `getkawari.com` (le fichier `CNAME` à la
   racine du dépôt contient déjà cette valeur).
5. Configurer les enregistrements DNS du domaine `getkawari.com` pour
   pointer vers GitHub Pages (voir la documentation GitHub pour les
   enregistrements A/ALIAS/CNAME requis), puis activer **Enforce HTTPS**
   une fois le certificat généré.

## Statut des TODO

Les deux TODO initiaux (numéro WhatsApp et URL Facebook) ont été renseignés
dans `index.html` :

- Numéro WhatsApp : `https://wa.me/237671874735`
- Page Facebook : `https://www.facebook.com/profile.php?id=61594271796182`

Les commentaires `<!-- TODO ... -->` sont conservés dans le code à titre de
repère mais n'indiquent plus une valeur manquante.
