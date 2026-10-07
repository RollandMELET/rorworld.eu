# rorworld.eu

> Fichier canonique pour tout agent (Claude Code, Codex, RC1, RC2). `CLAUDE.md` est un symlink vers ce fichier.

## Rôle

Site statique d'une page pour RoRworld SARL (conseil en passeport numérique de produit et en IA), publié sur GitHub Pages au domaine `rorworld.eu`. Il porte le logo, l'activité, le contact et les mentions légales. Le dossier `assets/` contient aussi l'image de signature mail.

## Arborescence

- `index.html` : la page unique, CSS inline, aucune dépendance.
- `assets/` : logos SVG (dont `logo-anime.svg`), favicons, image Open Graph `og.png`, `signature.png` (signature mail).
- `CNAME` : domaine `rorworld.eu`.
- `.nojekyll` : désactive Jekyll sur GitHub Pages.

## Commandes

Aucune : pas de build, pas de dépendance, pas de test.

```bash
open index.html     # aperçu local
git push origin main   # déploiement (GitHub Pages, branche main)
```

## Règles propres au dépôt

- Branche unique `main` : un push publie le site.
- Ne pas supprimer `CNAME` ni `.nojekyll`.
- Page sans cookie ni mesure d'audience : ne pas ajouter de traceur ni de script tiers (la mention légale du pied de page l'affirme).
- Les mentions légales du pied de page (capital, RCS, TVA, siège, hébergement) sont à modifier avec soin, elles ont valeur légale.
- `signature.png` est l'image de signature mail : fond blanc, 1200 px.
