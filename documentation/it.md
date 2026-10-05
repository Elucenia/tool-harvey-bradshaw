<!-- ELUCENIA technical documentation · harvey-bradshaw · it · no clinical/professional/rights approval -->

# Indice di Harvey-Bradshaw

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/harvey-bradshaw)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Benessere generale (giorno precedente)

`bem`

- `0` — Molto bene
- `1` — Leggermente al di sotto della norma
- `2` — Scarsa
- `3` — Molto scarso
- `4` — Pessima

### Dolore addominale (giorno precedente)

`dor`

- `0` — Nessuna
- `1` — Lieve
- `2` — Moderata
- `3` — Intensa

### Evacuazioni liquide o molto molli (giorno precedente)

`evac`

al giorno · intervallo: 0–40

### Massa addominale

`massa`

- `0` — Assente
- `1` — Dubbia
- `2` — Certa
- `3` — Certa e dolente

### Artralgia

`artralgia`

### Uveite

`uveite`

### Eritema nodoso

`eritema`

### Ulcere aftose

`aftas`

### Pioderma gangrenoso

`pioderma`

### Ragade anale

`fissura`

### Nuova fistola

`fistula`

### Ascesso

`abscesso`

## Edizione del metodo

HBI/Harvey–Bradshaw 1980: 5 domini, conteggio aperto delle feci liquide; non CDAI

## Formula documentata

Benessere (0–4) + dolore addominale (0–3) + numero di feci liquide il giorno precedente + massa addominale (0–3) + 1 punto per complicanza presente.

## Limiti e popolazione

L’Harvey–Bradshaw descrive l’attività clinica nella malattia di Crohn, comprendendo il numero di evacuazioni liquide del giorno precedente e la valutazione di massa addominale e complicanze. Non diagnostica il Crohn né sostituisce la valutazione dell’infiammazione o di altre cause dei sintomi. Il rapporto con il CDAI è buono ma imperfetto: Best 2006 ha analizzato 224 visite e documentato limiti di previsione, quindi un HBI non può essere convertito in un CDAI esatto. I risultati di risposta e remissione degli studi citati riguardano le popolazioni e i periodi di quegli studi.

## Riferimenti

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
