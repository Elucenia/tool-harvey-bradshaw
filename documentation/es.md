<!-- ELUCENIA technical documentation · harvey-bradshaw · es · no clinical/professional/rights approval -->

# Índice de Harvey-Bradshaw

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/harvey-bradshaw)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Bienestar general (día anterior)

`bem`

- `0` — Muy bien
- `1` — Ligeramente por debajo de lo normal
- `2` — Mala
- `3` — Muy malo
- `4` — Muy mala

### Dolor abdominal (día anterior)

`dor`

- `0` — Ninguna
- `1` — Leve
- `2` — Moderada
- `3` — Intensa

### Deposiciones líquidas o muy blandas (día anterior)

`evac`

por día · intervalo: 0–40

### Masa abdominal

`massa`

- `0` — Ausente
- `1` — Dudosa
- `2` — Definida
- `3` — Definida y dolorosa

### Artralgia

`artralgia`

### Uveítis

`uveite`

### Eritema nudoso

`eritema`

### Úlceras aftosas

`aftas`

### Pioderma gangrenoso

`pioderma`

### Fisura anal

`fissura`

### Fístula nueva

`fistula`

### Absceso

`abscesso`

## Edición del método

HBI/Harvey–Bradshaw 1980: 5 dominios, recuento abierto de deposiciones líquidas; no CDAI

## Fórmula documentada

Bienestar (0–4) + dolor abdominal (0–3) + número de deposiciones líquidas del día anterior + masa abdominal (0–3) + 1 punto por complicación presente.

## Límites y población

El Harvey–Bradshaw describe actividad clínica en la enfermedad de Crohn, incluida la cantidad de deposiciones líquidas del día anterior y la evaluación de masa abdominal y complicaciones. No diagnostica Crohn ni sustituye la evaluación de inflamación u otras causas de los síntomas. La relación con CDAI es buena, pero imperfecta: Best 2006 analizó 224 visitas y documentó límites de predicción, por lo que HBI no puede convertirse en un CDAI exacto. Los resultados de respuesta y remisión de los estudios citados corresponden a las poblaciones y períodos de esos ensayos.

## Referencias

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
