# Lady H Society — version GitHub Pages

Site statique bilingue FR/EN, sans serveur Node.js.

## Publication
1. Déposez **le contenu de ce dossier** à la racine de la branche `main` du dépôt GitHub.
2. Dans Settings → Pages, sélectionnez **Deploy from a branch**, `main`, `/ (root)`.
3. Dans Settings → Pages, vérifiez le domaine personnalisé `ladyhsociety.com`.
4. Configurez les enregistrements DNS selon la documentation GitHub Pages, puis activez HTTPS.

⚠️ Ne modifiez pas le DNS du site actuel avant d'avoir vérifié la publication.
Les pages utilisent des chemins absolus (`/images`, `/stylesheets`...) : le domaine personnalisé
est nécessaire pour un affichage correct. Pour un aperçu sous `username.github.io/repository`,
il faudra adapter les chemins.

## Remarques
- La page Contact utilise un formulaire externe Framaforms déjà intégré : aucun serveur Node n'est nécessaire.
- Les anciennes routes `/send-contact` et les scripts Node/Express ne sont pas inclus.
- Les traductions sont pré-générées dans les dossiers `/fr/` et `/en/`.
- Vérifiez les liens externes, intégrations et contenus après déploiement.
