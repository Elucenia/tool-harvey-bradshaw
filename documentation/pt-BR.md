<!-- ELUCENIA technical documentation · harvey-bradshaw · pt-BR · no clinical/professional/rights approval -->

# Índice de Harvey-Bradshaw

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/harvey-bradshaw)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Bem-estar geral (dia anterior)

`bem`

- `0` — Muito bem
- `1` — Levemente abaixo do normal
- `2` — Ruim
- `3` — Muito ruim
- `4` — Péssimo

### Dor abdominal (dia anterior)

`dor`

- `0` — Nenhuma
- `1` — Leve
- `2` — Moderada
- `3` — Intensa

### Evacuações líquidas ou muito moles (dia anterior)

`evac`

por dia · intervalo: 0–40

### Massa abdominal

`massa`

- `0` — Ausente
- `1` — Duvidosa
- `2` — Definida
- `3` — Definida e dolorosa

### Artralgia

`artralgia`

### Uveíte

`uveite`

### Eritema nodoso

`eritema`

### Úlceras aftosas

`aftas`

### Pioderma gangrenoso

`pioderma`

### Fissura anal

`fissura`

### Fístula nova

`fistula`

### Abscesso

`abscesso`

## Edição do método

HBI/Harvey Bradshaw 1980:5 domínios, fezeslíquidascontagem aberta; sem CDAI

## Fórmula documentada

Bem-estar (0 a 4) + dor abdominal (0 a 3) + número de evacuações líquidas no dia anterior + massa abdominal (0 a 3) + 1 ponto por complicação presente.

## Limites e população

O Harvey–Bradshaw descreve atividade clínica da doença de Crohn, incluindo a contagem de evacuações líquidas do dia anterior e a avaliação de massa e complicações. Não diagnostica Crohn nem substitui avaliação de inflamação ou de outras causas dos sintomas. A relação com o CDAI é boa, mas imperfeita: Best 2006 analisou 224 visitas e documentou limites de previsão, portanto um HBI não pode ser convertido em CDAI exato. Os resultados de resposta e remissão dos estudos citados pertencem às populações e períodos desses ensaios.

## Referências

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Remissão clínica (< 5)

| Detalhes do resultado | |
| --- | --- |
| Complicações somadas | 0 |


### 2

Atividade leve (5 a 7)

| Detalhes do resultado | |
| --- | --- |
| Complicações somadas | 0 |


### 3

Atividade moderada (8 a 16)

| Detalhes do resultado | |
| --- | --- |
| Complicações somadas | 2 |


### 4

Atividade grave (> 16)

| Detalhes do resultado | |
| --- | --- |
| Complicações somadas | 2 |

