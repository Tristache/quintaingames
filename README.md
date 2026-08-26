# quintaingames.com

Site du studio Quintain Games (GitHub Pages, domaine personnalisé
`quintaingames.com`, fichier `CNAME`, HTTPS forcé). Dépôt DISTINCT de
`tristache.github.io`, qui reste servi tel quel pour les anciennes
builds (liens profonds, version.json, politiques).

Contenu (étape 1 de docs/migration-domaine-quintaingames.md du dépôt
rami-chinois, 2026-08-26) :

- `index.html` — page d'accueil du studio ;
- `.well-known/assetlinks.json`, `.well-known/apple-app-site-association`
  — copies à l'identique de tristache.github.io (mêmes apps, mêmes
  empreintes) : les apps ne déclarent PAS ENCORE ce domaine, elles le
  feront dans une build dédiée ;
- `rejoindre.html`, `meldfall.html` — pages de repli des liens (mêmes
  chemins que sur l'ancien domaine) ;
- `meldfall/confidentialite.html`, `meldfall/suppression-compte.html`,
  `meldfall/version.json` — pages Meldfall aux chemins définitifs ;
- à venir : `ramio/` (politique, suppression, version.json).

Tant que des builds citent tristache.github.io, on AJOUTE ici, on ne
retire rien là-bas.
