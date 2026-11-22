# links.prestivocar.com

Page de liens Prestivo Cars (réseaux sociaux + contact WhatsApp direct), publiée avec GitHub Pages.

## Modifier les liens

Ouvrez `index.html` et éditez le bloc **`PROFILE`** (repéré par « ✏️ À MODIFIER ») :

- `whatsapp.number` : numéro international, chiffres uniquement (06 12 34 56 78 → `33612345678`)
- `whatsapp.message` : message déjà écrit à l'ouverture de la conversation
- `whatsapp.label` / `sub` : texte du bouton et petite ligne en dessous
- `links` : un réseau par ligne ; supprimez une ligne pour le masquer

Puis publiez :

```bash
git add -A
git commit -m "Mise à jour des liens"
git push
```

Le site se met à jour en environ une minute (rechargez avec Ctrl + F5).

## Fichiers

- `logo.jpg` : logo affiché en haut de la page
- `og-image.jpg` : image d'aperçu quand le lien est partagé
- `favicon.png`, `apple-touch-icon.png` : icônes d'onglet et d'écran d'accueil
- `CNAME` : déclare le domaine `links.prestivocar.com` pour GitHub Pages (ne pas supprimer)
- `site.json` : configuration d'origine (sert à régénérer la page avec le skill `page-liens`)

## Aperçu local

```bash
python -m http.server 4173
```

puis ouvrez http://localhost:4173
