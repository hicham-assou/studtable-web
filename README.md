# Stud'Table — pages publiques

Site statique hébergeant les pages légales publiques de l'application **Stud'Table**,
requises par le Google Play Store (et plus tard l'App Store).

## Pages

- `index.html` — page d'accueil (liens vers les pages ci-dessous)
- `privacy-policy.html` — politique de confidentialité
- `delete-account.html` — procédure de suppression de compte

## Hébergement

Déployé sur **Cloudflare Pages** (gratuit). Chaque `git push` sur `main`
redéploie automatiquement le site.

URLs à renseigner dans la Google Play Console :

- Politique de confidentialité : `https://<projet>.pages.dev/privacy-policy.html`
- Suppression de compte : `https://<projet>.pages.dev/delete-account.html`

> La page de redirection des liens de partage (`r.html`) sera ajoutée plus tard,
> en même temps que le retour du bouton « Partager » dans l'app.
