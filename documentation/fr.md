<!-- ELUCENIA technical documentation · harvey-bradshaw · fr · no clinical/professional/rights approval -->

# Indice de Harvey-Bradshaw

[conditions, sources et autorisations](https://elucenia.org/fr/outils/harvey-bradshaw)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Bien-être général (jour précédent)

`bem`

- `0` — Très bien
- `1` — Légèrement inférieur à la normale
- `2` — Mauvaise
- `3` — Très mauvais
- `4` — Très mauvaise

### Douleur abdominale (jour précédent)

`dor`

- `0` — Aucune
- `1` — Léger
- `2` — Modérée
- `3` — Intense

### Selles liquides ou très molles (jour précédent)

`evac`

par jour · intervalle: 0–40

### Masse abdominale

`massa`

- `0` — Absent
- `1` — Douteuse
- `2` — Certaine
- `3` — Certaine et douloureuse

### Arthralgie

`artralgia`

### Uvéite

`uveite`

### Érythème noueux

`eritema`

### Ulcères aphteux

`aftas`

### Pyoderma gangrenosum

`pioderma`

### Fissure anale

`fissura`

### Nouvelle fistule

`fistula`

### Abcès

`abscesso`

## Édition de la méthode

HBI/Harvey–Bradshaw 1980 : 5 domaines, nombre libre de selles liquides ; pas CDAI

## Formule documentée

Bien-être (0–4) + douleur abdominale (0–3) + nombre de selles liquides la veille + masse abdominale (0–3) + 1 point par complication présente.

## Limites et population

Le Harvey–Bradshaw décrit l’activité clinique de la maladie de Crohn, notamment le nombre de selles liquides de la veille et l’évaluation d’une masse abdominale et des complications. Il ne diagnostique pas la maladie de Crohn et ne remplace pas l’évaluation de l’inflammation ou d’autres causes des symptômes. La relation avec le CDAI est bonne, mais imparfaite : Best 2006 a analysé 224 visites et documenté des limites de prédiction ; le HBI ne peut donc pas être converti en un CDAI exact. Les résultats de réponse et de rémission des études citées concernent les populations et périodes de ces essais.

## Références

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
