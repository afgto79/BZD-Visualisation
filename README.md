# BZD-Visualisation

Visualisations comparatives de médicaments courants, destinées aux professionnels de santé :

- **benzodiazépines** : six molécules (oxazépam, alprazolam, lorazépam, bromazépam, diazépam, clorazépate) à doses orales approximativement équivalentes à 10 mg de diazépam ;
- **antidépresseurs** : neuf molécules en cinq groupes ;
- **bêta-bloquants** : six molécules.

**Site en ligne : https://afgto79.github.io/BZD-Visualisation/**

## Navigation

Un menu principal en haut de page relie les sections :

| Menu | Page | Contenu |
|---|---|---|
| Visualisation interactive BZD | [index.html](https://afgto79.github.io/BZD-Visualisation/) | Page d'accueil. Radars de profils relatifs, métabolites actifs, demi-vies en échelle logarithmique, tableaux de données et sources. |
| Capture BZD | [capture.html](https://afgto79.github.io/BZD-Visualisation/capture.html) | Capture d'écran de la visualisation interactive. |
| Infographies BZD | [infographies.html](https://afgto79.github.io/BZD-Visualisation/infographies.html) | Les deux infographies, l'une sous l'autre. |
| Infographies Antidépresseurs | [ad_synthese_prescripteurs.html](https://afgto79.github.io/BZD-Visualisation/ad_synthese_prescripteurs.html) | Synthèse pour prescripteurs : statut par situation clinique, fiches, comparaison en radar. |
| Visualisations Bêta-bloquants | [bb_synthese_prescripteurs.html](https://afgto79.github.io/BZD-Visualisation/bb_synthese_prescripteurs.html) | Ouvre la section bêta-bloquants (voir ci-dessous). |

Les pages bêta-bloquants ont leur propre sous-menu, avec un lien « Retour » vers l'accueil :

| Sous-menu | Page |
|---|---|
| Synthèse prescripteurs | `bb_synthese_prescripteurs.html` |
| Profils comparés | `bb_1_profils_compares.html` |
| Profils relatifs | `bb_3_profils_relatifs.html` |
| Pharmacocinétique | `bb_2_pharmacocinetique.html` |

## Contenu du dépôt

```
index.html                        visualisation interactive des benzodiazépines
capture.html                      capture de la visualisation
infographies.html                 infographies benzodiazépines
ad_synthese_prescripteurs.html    antidépresseurs : synthèse pour prescripteurs
bb_*.html                         bêta-bloquants : synthèse et trois vues détaillées
images/                           images affichées par capture.html et infographies.html
```

Aucune dépendance ni étape de compilation : les pages sont des fichiers HTML statiques autonomes, servis par GitHub Pages depuis la branche `main`, dossier racine.

Les menus sont insérés dans chaque page entre les commentaires `<!--sitenav-->` et `<!--/sitenav-->`, et leur style entre `<!--sitenav-style-->` et `<!--/sitenav-style-->`. Pour ajouter une page au menu, il faut modifier le menu dans chaque page concernée.

## Mettre à jour le site

Modifier ou ajouter des fichiers dans le dossier, puis :

```bash
git add -A && git commit -m "Mise à jour" && git push
```

Le site est republié une ou deux minutes après le push.

## Avertissement

Support pédagogique destiné aux professionnels de santé. Les scores des radars sont des estimations semi-quantitatives non validées cliniquement ; les doses équivalentes et les autres valeurs sont des ordres de grandeur. Ces contenus ne remplacent ni le RCP ni le jugement clinique, et ne constituent ni une recommandation de prescription ni une aide à la substitution. Les hypothèses, divergences et sources sont détaillées en bas de chaque page.
