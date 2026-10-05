<!-- ELUCENIA technical documentation · harvey-bradshaw · de · no clinical/professional/rights approval -->

# Harvey-Bradshaw-Index

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/harvey-bradshaw)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Allgemeines Wohlbefinden (Vortag)

`bem`

- `0` — Sehr gut
- `1` — Leicht unter dem Normalwert
- `2` — Schlecht
- `3` — Sehr schlecht
- `4` — Sehr schlecht

### Bauchschmerzen (Vortag)

`dor`

- `0` — Keine
- `1` — Leicht
- `2` — Mäßig
- `3` — Stark

### Flüssige oder sehr weiche Stühle (Vortag)

`evac`

pro Tag · Bereich: 0–40

### Abdominelle Raumforderung

`massa`

- `0` — Nicht vorhanden
- `1` — Fraglich
- `2` — Gesichert
- `3` — Gesichert und druckschmerzhaft

### Arthralgie

`artralgia`

### Uveitis

`uveite`

### Erythema nodosum

`eritema`

### Aphthöse Ulzera

`aftas`

### Pyoderma gangraenosum

`pioderma`

### Analfissur

`fissura`

### Neue Fistel

`fistula`

### Abszess

`abscesso`

## Fassung der Methode

HBI/Harvey–Bradshaw 1980: 5 Bereiche, offene Flüssigstuhlzählung; kein CDAI

## Dokumentierte Formel

Wohlbefinden (0–4) + Bauchschmerz (0–3) + Anzahl flüssiger Stühle am Vortag + Bauchresistenz (0–3) + 1 Punkt je vorhandener Komplikation.

## Grenzen und Population

Harvey–Bradshaw beschreibt die klinische Aktivität bei Morbus Crohn, einschließlich der Zahl flüssiger Stühle am Vortag sowie der Beurteilung einer abdominellen Raumforderung und von Komplikationen. Er diagnostiziert keinen Morbus Crohn und ersetzt weder die Beurteilung von Entzündung noch anderer Symptomursachen. Die Beziehung zum CDAI ist gut, aber unvollkommen: Best 2006 untersuchte 224 Visiten und dokumentierte Vorhersagegrenzen; ein HBI lässt sich daher nicht in einen exakten CDAI umrechnen. Ansprech- und Remissionsbefunde der zitierten Studien gehören zu den jeweiligen Studienpopulationen und Zeiträumen.

## Referenzen

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
