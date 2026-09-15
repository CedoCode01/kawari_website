# Kawari — site web

Landing page statique pour Kawari (HTML/CSS/JS vanilla, sans build step).

## Publication via GitHub Pages

1. Pousser ce dépôt sur GitHub.
2. Aller dans **Settings > Pages**.
3. **Source** : sélectionner la branche principale (`main`), dossier `/ (root)`.
4. **Custom domain** : renseigner `kawari.app` (le fichier `CNAME` à la racine
   du dépôt contient déjà cette valeur).
5. Configurer les enregistrements DNS du domaine `kawari.app` pour pointer
   vers GitHub Pages (voir la documentation GitHub pour les enregistrements
   A/ALIAS/CNAME requis), puis activer **Enforce HTTPS** une fois le
   certificat généré.

## À compléter avant mise en ligne définitive

Deux TODO sont laissés dans `index.html` :

- **Numéro WhatsApp** : remplacer `NUMERO_A_REMPLACER` dans le lien
  `https://wa.me/NUMERO_A_REMPLACER` (bouton "Démarrer sur WhatsApp") par le
  numéro WhatsApp Business réel, au format international sans le `+`
  (ex. `wa.me/33612345678`).
- **Page Facebook** : remplacer l'URL du lien "Page Facebook" dans le footer
  par l'URL réelle de la page Facebook Kawari.
