# BZD-Visualisation

Visualisation comparative de six benzodiazépines courantes (oxazépam, alprazolam, lorazépam, bromazépam, diazépam, clorazépate) à doses orales approximativement équivalentes à 10 mg de diazépam.

**Site en ligne : https://afgto79.github.io/BZD-Visualisation/**

## Pages

| Page | Contenu |
|---|---|
| [Visualisation interactive](https://afgto79.github.io/BZD-Visualisation/) | Radars de profils relatifs, métabolites actifs, demi-vies en échelle logarithmique, tableaux de données et sources. Sélection des molécules à afficher. |
| [Capture](https://afgto79.github.io/BZD-Visualisation/capture.html) | Capture d'écran de la visualisation interactive. |
| [Infographie 1](https://afgto79.github.io/BZD-Visualisation/infographie-1.html) | Deux types d'infographies : comparaisons visuelles et profils cliniquement utiles. |
| [Infographie 2](https://afgto79.github.io/BZD-Visualisation/infographie-2.html) | Comparaison clinique et pharmacocinétique des six molécules. |

## Contenu du dépôt

```
index.html            visualisation interactive (HTML, CSS et JavaScript autonomes)
capture.html          page de la capture
infographie-1.html    page de l'infographie 1
infographie-2.html    page de l'infographie 2
images/               images affichées par les pages ci-dessus
```

Aucune dépendance ni étape de compilation : les pages sont des fichiers HTML statiques servis par GitHub Pages depuis la branche `main`, dossier racine.

## Mettre à jour le site

Modifier ou ajouter des fichiers dans le dossier, puis :

```bash
git add -A && git commit -m "Mise à jour" && git push
```

Le site est republié une ou deux minutes après le push.

## Avertissement

Support pédagogique destiné aux professionnels de santé. Les scores des radars sont des estimations semi-quantitatives non validées cliniquement, et les doses équivalentes sont des ordres de grandeur. Ce contenu ne remplace ni le RCP ni le jugement clinique, et ne doit pas servir de support de décision de substitution au comptoir. Les sources sont détaillées en bas de la visualisation interactive.
