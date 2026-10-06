<!-- ELUCENIA technical documentation · harvey-bradshaw · en · no clinical/professional/rights approval -->

# Harvey–Bradshaw Index

[conditions, sources and permissions](https://elucenia.org/en/tools/harvey-bradshaw)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### General well-being (previous day)

`bem`

- `0` — Very well
- `1` — Slightly below normal
- `2` — Poor
- `3` — Very poor
- `4` — Very poor

### Abdominal pain (previous day)

`dor`

- `0` — None
- `1` — Mild
- `2` — Moderate
- `3` — Intense

### Liquid or very soft stools (previous day)

`evac`

per day · range: 0–40

### Abdominal mass

`massa`

- `0` — Absent
- `1` — Questionable
- `2` — Definite
- `3` — Definite and tender

### Arthralgia

`artralgia`

### Uveitis

`uveite`

### Erythema nodosum

`eritema`

### Aphthous ulcers

`aftas`

### Pyoderma gangrenosum

`pioderma`

### Anal fissure

`fissura`

### New fistula

`fistula`

### Abscess

`abscesso`

## Method edition

HBI/Harvey–Bradshaw 1980: 5 domains, open liquid-stool count; not CDAI

## Documented formula

Well-being (0–4) + abdominal pain (0–3) + number of liquid stools the previous day + abdominal mass (0–3) + 1 point per present complication.

## Limits and population

Harvey–Bradshaw describes clinical activity in Crohn’s disease, including the number of liquid stools on the previous day and assessment of an abdominal mass and complications. It does not diagnose Crohn’s disease or replace assessment of inflammation or other causes of symptoms. Its relationship with CDAI is good but imperfect: Best 2006 analyzed 224 visits and documented prediction limits, so HBI cannot be converted to an exact CDAI. Response and remission findings from the cited studies belong to those trial populations and periods.

## References

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Clinical remission (< 5)

| Result details | |
| --- | --- |
| Sum of complications | 0 |


### 2

Mild activity (5 to 7)

| Result details | |
| --- | --- |
| Sum of complications | 0 |


### 3

Moderate activity (8 to 16)

| Result details | |
| --- | --- |
| Sum of complications | 2 |


### 4

Severe activity (> 16)

| Result details | |
| --- | --- |
| Sum of complications | 2 |

